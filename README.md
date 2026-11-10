# web-application-table

# HTML Table Design Using HTML and CSS

## Project Description
This project demonstrates how to create a table using HTML and CSS. It represents a table with five column headings and four rows, including different cell merging and styling techniques.

## Technologies Used
- HTML5
- CSS3

## Features
- Five column headings
- Table rows and columns
- Rowspan attribute
- Colspan attribute
- Yellow background highlighted cell
- Blue background highlighted cell
- Bold and italic text formatting
- Table borders and cell spacing

## HTML Concepts Used
1. `<table>` - Creates a table.
2. `<tr>` - Creates a table row.
3. `<th>` - Defines table headings.
4. `<td>` - Defines table data.
5. `rowspan` - Merges cells vertically.
6. `colspan` - Merges cells horizontally.
7. CSS - Adds colors, borders and styling.

##CODE

<!DOCTYPE html>
<html>
<head>
    <title>HTML Table</title>
    <style>
        table {
            border-collapse: collapse;
            width: 100%;
        }

        th, td {
            border: 1px solid black;
            padding: 6px;
            text-align: left;
        }

        .yellow {
            background-color: yellow;
        }

        .blue {
            background-color: deepskyblue;
        }

        .italic {
            font-style: italic;
        }

        .bold {
            font-weight: bold;
        }
    </style>
</head>

<body>

<table>
    <tr>
        <th>Col Head1</th>
        <th>Col Head2</th>
        <th>Col Head3</th>
        <th>Col Head4</th>
        <th>Col Head5</th>
    </tr>

    <tr>
        <td>Row1 Cell1</td>
        <td class="yellow">Row1 Cell2</td>
        <td>Row1 Cell3</td>
        <td>Row1 Cell4</td>
        <td>Row1 Cell5</td>
    </tr>

    <tr>
        <td>Row2 Cell1</td>
        <td colspan="2">Row2 Cell2</td>
        <td>Row2 Cell3</td>
        <td rowspan="2" class="italic">Row2 Cell4</td>
    </tr>

    <tr>
        <td>Row3 Cell1</td>
        <td rowspan="2">Row1 Cell2</td>
        <td>Row3 Cell3</td>
        <td class="bold">Row3 Cell4</td>
    </tr>

    <tr>
        <td>Row4 Cell1</td>
        <td>Row4 Cell2</td>
        <td class="blue">Row4 Cell3</td>
        <td>Row4 Cell4</td>
    </tr>

</table>

</body>
</html>
```

## Project Output:
<img width="873" height="192" alt="image" src="https://github.com/user-attachments/assets/25cefac3-5e58-4ae4-aa20-33565c348671" />

The output displays a five-column HTML table with merged cells and different text styles, matching the given assignment design.

## Conclusion
This project helps to understand the basic concepts of HTML tables and CSS styling.

---
**Created for:** Fundamentals of Web Application Development
