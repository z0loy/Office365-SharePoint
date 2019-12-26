# SharePoint Column Formatting

## What is SP Column Formatting (CF)
Column Formatting is a feature in SharePoint which allow you to customize your SP Lists or libraries field view, in another words you can customize how these fields should be displayed. In order to do this and to get benefit from my simple work, you just need to create a JSON object that describes the elements that are displayed when a field is included in a list view, and the styles to be applied to those elements. keep in mind that CF doesn't affect your data in the items or files, it only changes how it's displayed to users, that's all.

## How can you use the Column Formatting in your SP List
To open the CF pane, please follow the next steps: 
  - Go to your column that you want to customize
  - Open the dropdown menu under that column
  - Click on Column Settings
  - Select Formt this column
the following pane will appear to you: 
![screenshot of the sample](https://docs.microsoft.com/en-us/sharepoint/dev/images/sp-columnformatting-panel.png)

inside that box, enter your CF JSON, you can **Preview** the formatting or you can directly commit your changes by selecting **Save**. 

## Sample

|Author(s)
|---------
| Aimen Boulahia



## Additional notes
This sample is also covered in the main documentation around the Column Formatting and the in the official repository of SharePoint:

- [Use column formatting to customize SharePoint](https://docs.microsoft.com/en-us/sharepoint/dev/declarative-customization/column-formatting)
- [SharePoint/sp-dev-column-formatting repository](https://github.com/SharePoint/sp-dev-list-formatting)
