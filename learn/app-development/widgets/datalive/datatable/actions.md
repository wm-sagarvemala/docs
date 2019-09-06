---
title: "Data Table - Actions"
id: ""
---

Data Table is capable of performing CRUD operations on the underlying Database Source. This functionality can be achieved through the table and record level actions like adding, editing and deleting records. In addition, custom actions can also be defined as per the requirements.

Data Table actions include actions at the table-level and the row-level. These options are available from the **Actions** tab of the **Advanced Settings** property of the Data Table.

### Table-Specific Actions

- _New_ action which creates a new row when executed. This is provided with the Data Table by default and is programmed to insert the record into the underlying database table.
- You can add a new custom action for the Table to add a custom action method that has been created by you. The Action will be a JS function.
- These actions can be displayed either as a _Button_ or an _Anchor_.
- Actions can be made accessible using _Shortcut Keys._ Each of these Table Actions can be assigned a key from the Shortcut Key property. These keys, when used in conjunction with the key code (Alt in Windows & Linux; Alt+Shift in Firefox; Control+Alt in Mac; etc.), will activate or focus the Action.

### Row Specific Actions

- By default two actions are available on Table Rows each programmed to perform the respective action on the underlying database entity:
    - updateRow() - to save changes made to the row fields
    - deleteRow() - to delete the selected row
- You can add a custom row action to add a custom method that has been created by you.

### Actions Visibility

Visibility can be set based upon a column value within the row, for example, to show the  New button only if the Id value is 1, then bind the show property from Use Expression to _row.id === 1_

### Actions Layout

You can configure the layout of the action column in terms of title for the column - set by default to Actions; the position of the column in the table - set to last by default; width of the column; width Unit for the above-mentioned width; class for custom column styles.

[![](../../../../assets/AS_actions.png?ver=20)](../../../../assets/AS_actions.png?ver=20)

< Field Configuration

Events & Methods >

[1\. Live & Data Widgets](/learn/app-development/widgets/widget-library/#data-live)

- [1.1 Cards](/learn/app-development/widgets/datalive/cards/)
- [1.2 Data Table](/learn/app-development/widgets/datalive/data-table/)
    - [i. Data Source](/learn/app-development/widgets/datalive/datatable/data-source/)
        - [○ Variable Source](/learn/app-development/widgets/datalive/datatable/data-source/#variable-source)
        - [○ Widget Source](/learn/app-development/widgets/datalive/datatable/data-source/#widget-source)
    - [ii. Layouts](/learn/app-development/widgets/datalive/datatable/layouts/)
        - [○ Editable with Form as Dialog](/learn/app-development/widgets/datalive/datatable/layouts/#efd)
        - [○ Editable with Form given below the Table](/learn/app-development/widgets/datalive/datatable/layouts/#efb)
        - [○ Inline Editable](/learn/app-development/widgets/datalive/datatable/layouts/#edi)
        - [○ Quick Edit](/learn/app-development/widgets/datalive/datatable/layouts/#edq)
        - [○ Read-Only with details given below](/learn/app-development/widgets/datalive/datatable/layouts/#rof)
        - [○ Read-only Simple View](/learn/app-development/widgets/datalive/datatable/layouts/#ros)
    - [iii. Table Configuration](/learn/app-development/widgets/datalive/datatable/table-configuration/)
        - [○ Search & Filter](/learn/app-development/widgets/datalive/datatable/table-configuration/#search-n-filter)
        - [○ Sorting](/learn/app-development/widgets/datalive/datatable/table-configuration/#sorting)
        - [○ Selection](/learn/app-development/widgets/datalive/datatable/table-configuration/#selection)
        - [○ Pagination](/learn/app-development/widgets/datalive/datatable/table-configuration/#pagin)
        - [○ Export Data](/learn/app-development/widgets/datalive/datatable/table-configuration/#export-data)
        - [○ Message](/learn/app-development/widgets/datalive/datatable/table-configuration/#message)
        - [○ Row Styling](/learn/app-development/widgets/datalive/datatable/table-configuration/#row-style)
    - [iv. Field Configuration](/learn/app-development/widgets/datalive/datatable/field-configuration/)
        - [○ Column Grouping](/learn/app-development/widgets/datalive/datatable/field-configuration/#grouping)
        - [○ View Mode](/learn/app-development/widgets/datalive/datatable/field-configuration/#view-mode)
        - [○ Edit Mode](/learn/app-development/widgets/datalive/datatable/field-configuration/#edit-mode)
    - [v. Actions](/learn/app-development/widgets/datalive/datatable/actions/)
        - [○ Table Specific Actions](#table-actions)
        - [○ Row Specific Actions](#row-actions)
        - [○ Actions Visibility](#actions-visibility)
        - [○ Actions Layout](#actions-layout)
    - [vi. Events & Methods](/learn/app-development/widgets/datalive/datatable/datatable-events-methods/)
        - [○ Events](/learn/app-development/widgets/datalive/datatable/datatable-events-methods/#events)
        - [○ Methods](/learn/app-development/widgets/datalive/datatable/datatable-events-methods/#methods)
    - [vii.Use Cases](/learn/app-development/widgets/datalive/datatable/data-table-use-cases/)
- [1.3 Form](/learn/app-development/widgets/datalive/form/)
- [1.4 List](/learn/app-development/widgets/datalive/list/)
- [1.5 Live Form](/learn/app-development/widgets/datalive/live-form/)
- [1.6 Live Filter](/learn/app-development/widgets/datalive/live-filter/)