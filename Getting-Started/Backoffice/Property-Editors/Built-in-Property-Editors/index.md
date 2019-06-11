---
versionFrom: 8.0.0
---

# Built-in Umbraco Property Editors

This page contains a list of all the built-in Umbraco property editors and a short description of what they do:

## [Checkbox (True/False)](True-False.md)
`Alias: Umbraco.TrueFalse`

A simple checkbox which saves either 0 or 1, depending on the checkbox being checked or not.

## [Checkbox list](CheckBox-List/index.md)
`Alias: Umbraco.CheckBoxList`

Displays a list of preset values as a list of checkbox controls

## [Color Picker](Color-Picker/index.md)
`Alias: Umbraco.ColorPicker`

Adds a list of approved colours which can be selected by clicking.

## [Content Picker](Content-Picker/index.md)
`Alias: Umbraco.ContentPicker`

The content picker allows the content editor to pick a specific node from the content structure.

## [Date/Time](Date-Time/index.md)
`Alias: Umbraco.DateTime`

Displays a calendar UI for selecting dates and time.

## Decimal
`Alias: Umbraco.Decimal`

A configurable number control allowing only numbers including decimals.

## [Dropdown](DropDown/index.md)
`Alias: Umbraco.DropDown.Flexible`

Introduced in Umbraco v 7.10. Displays a list of preset values. The content editor can select either a single or multiple values.

## Email address
`Alias: Umbraco.EmailAddress`

A single line textbox only allowing valid email addresses.

## File upload
`Alias: Umbraco.UploadField`

Adds an upload field, which allows documents or images to be uploaded to Umbraco

## [Grid Layout](Grid-Layout/index.md)
`Alias: Umbraco.Grid`

New to v7.2, gives editors a grid layout editor which allows them to insert different types of content in a predefined layout.

## [Image Cropper](Image-Cropper.md)
`Alias: Umbraco.ImageCropper`

Used to crop and resize images to predefined sizes. Available from V7.1

## Label
`Alias: Umbraco.Label`

Label is a non-editable control and can only be used to display a pre-set text.

## List View
`Alias: Umbraco.ListView`

This control gives the same functionality as the standard listview, but allows you to add the listview as a control on a tab while controlling the other tabs and properties.

## Markdown editor
`Alias: Umbraco.MarkdownEditor`

[Markdown](https://daringfireball.net/projects/markdown/) is a lightweight markup language with plain text formatting syntax. It is designed so that it can be converted to HTML.  The built-in editor allow the user to use the markdown formatting options.

The markdown editor will be interpreted by the Models Builder. Behind the scenes, Umbraco uses the [Markdown NuGet package](https://www.nuget.org/packages/Markdown/).

## [Media Picker](Media-Picker/index.md)
`Alias: Umbraco.MediaPicker`

The media picker displays the current selected media and provides the option to open the mediaPicker dialog to select existing or upload new media files. There is a setting to enable multiple media items to be selected.

## Member Group Picker
`Alias: Umbraco.MemberGroupPicker`

## [Member Picker](Member-Picker/index.md)
`Alias: Umbraco.MemberPicker`

## [Multi Url Picker](Multi-Url-Picker/index.md)
`Alias: Umbraco.MultiUrlPicker`

New in Umbraco v8, used to be a package called RJP Multi Url Picker. Replaced Related Links in v8.

## [Multinode Treepicker](Multinode-Treepicker/index.md)
`Alias: Umbraco.MultiNodeTreePicker`

The multinode treepicker data type allows content editors to choose multiple nodes in the content or media trees.

## [Nested Content](Nested-Content/index.md)
`Alias: Umbraco.NestedContent`

New to v7.7, the nested content property editor enables you to use Document Types as a schema for list items.

## [Numeric](Numeric/index.md)
`Alias: Umbraco.Integer`

A configurable number control allowing only numbers.

## [Radio button list](RadioButton-List/index.md)
`Alias: Umbraco.RadioButtonList`

Pretty much like the name indicates this property editor enables editors to choose from list of radio buttons.

## [Repeatable textstrings](Multiple-Textbox.md)
`Alias: Umbraco.MultipleTextstring`

The Repeatable textstrings property editor enables a content editor to make a list of text items

## Rich Text Editor
`Alias: Umbraco.TinyMCE`

A [tinymce](https://www.tinymce.com/) based rich text editor which is highly configurable.  Probably one of the most used controls in Umbraco projects.

## Slider
`Alias: Umbraco.Slider`

A slider with a number in a certain range.

## [Tags](Tags/index.md)
`Alias: Umbraco.Tags`

A tag control which can be controlled by a certain group of tags.

## [Textarea](Textarea/index.md)
`Alias: Umbraco.TextArea`

A simple textarea control to input text.

## [Textbox](Textbox/index.md)
`Alias: Umbraco.TextBox`

A normal html input text field.

## User picker
`Alias: Umbraco.UserPicker`

The easiest way to pick a person from user backend users.  See Members for front-end users.