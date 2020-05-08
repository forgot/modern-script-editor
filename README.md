
# Overview

This is a fork and customization of the `react-script-editor` example. Click [here](https://github.com/pnp/sp-dev-fx-webparts/tree/master/samples/react-script-editor) to view the full `README`. This example was originally created by Mikael Svenson.

# Changes

- Changed the default description to "No Description Set"
- Set `"requiresCustomScript": false` within `ScriptEditorWebPart.manifest.json` to allow it to work in non-script sites
- Removed original creators self attribution from the settings panel
- Add a check for user permissions, and disabled configuration fields for anyone without Site Admin privileges or above
