1. Install Extension: [Custom CSS and JS Loader](https://marketplace.visualstudio.com/itemdetails?itemName=be5invis.vscode-custom-css)
2. Add to `settings.json`:

   ```json
       "vscode_custom_css.imports": [""]
   ```

   **VERY IMPORTANT**: Items in `vscode_custom_css.imports` must be **URL**s. Plain file paths are **NOT URLs**.
   - Create a new file with extensions CSS.
   - Copy my custom VSCode to your custom VSCode file.
   - **Windows File URL Example**: `file:///C:/Users/MyUserName/Documents/custom.css`
   - **MacOS and Linux File URL Example**: `file:///Users/MyUserName/Documents/custom.css`
   - [See here](https://en.wikipedia.org/wiki/File_URI_scheme) for more details.

4. Restart Visual Studio Code with proper permission to modify itself:

   1. **Windows**: Restart with Administrator Permission.

   2. **MacOS and Linux**: See instructions below.

5. Activate command "Reload Custom CSS and JS".

6. Restart.
