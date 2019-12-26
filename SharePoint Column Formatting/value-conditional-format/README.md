# Conditional formatting based on the value of a status column

## Summary
Here we applied conditional formatting to a choice fields that contain a fixed set of values. The following example applies different classes depending on whether the value of the field is:
  - Actif (Active), 
  - Annulé (Canceled),
  - Basculé (Toggled or Swtiched),
  - Clôturé (Closed),
  - Gelé (Frozen),
  - Résolu (Resolved),
  - Traitement (In progress).

**NOTE: in my case, I was working on a French version (the words between brackets are the equivalent words in english)**

This example uses a CSS class (`sp-css-backgroundColor-XXXXX`) to the  `<div />` based on the field's value. This is what determines the element's background color. Then, it outputs a `<span />` element with an `iconName` attribute. This attribute applies another CSS class to that `<span />` that shows an [Office UI Fabric](https://dev.office.com/fabric#/) icon inside that element.

This pattern is useful when you want different values to map to different levels of severity, issue status, page status ...etc. 

![screenshot of the sample](./screenshot.PNG)

## View requirements
- This format can be applied to choice column and expects the following values:
  - Actif (Active), 
  - Annulé (Canceled),
  - Basculé (Toggled or Swtiched),
  - Clôturé (Closed),
  - Gelé (Frozen),
  - Résolu (Resolved),
  - Traitement (In progress).

## Sample

Solution|Author(s)
--------|---------
Statut.json | Aimen Boulahia



## Additional notes
This sample is also covered in the main documentation around the Column Formatting

- [Use column formatting to customize SharePoint](https://docs.microsoft.com/en-us/sharepoint/dev/declarative-customization/column-formatting)

