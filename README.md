# Graph Umbraco Components - Footer

## Installation steps:
1. Make sure [https://github.com/AndyButland/UmbracoMapper](Zone.UmbracoMapper) and [https://github.com/nicbell/ucreate](UCreate) are installed in your project
2. Copy the folder 'Footer' to 'Components' (for manual installation only, otherwise use Stamp tool)
3. Remove fields from FooterSettings.cs if it's needed
4. Use it: @Html.Action("Index", "FooterSurface")

## Settings
The only mandatory field in settings is "SettingsNodeId" - id of the Settings node with all needed fields

## Fields
You can set only needed:
* AddressFieldAlias
* PhoneFieldAlias
* EmailFieldAlias
* FaxFieldAlias
* FacebookFieldAlias
* TwitterFieldAlias
* InstagramFieldAlias
* LinkedInFieldAlias
* YouTubeFieldAlias
* CopyrightTextFieldAlias
