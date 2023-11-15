# Discourse Theme
A Godot styled theme for discourse.


## Development

You can use the discourse theme CLI to automatically push changes to a live website.
Please follow the instructions in the [official CLI documentation](https://meta.discourse.org/t/install-the-discourse-theme-cli-console-app-to-help-you-build-themes/82950).

> ⚠️ **Note:** Please only use this to sync to the theme creator website, not to the public Godot forum. See [Usage](#usage) for instructions on updating the live website.

Once the CLI is installed, follow these steps as a one time setup:
1. Make sure you have an account on [meta.discourse.org](https://meta.discourse.org/) and are logged in
2. Go to [discourse.theme-creator.io/my/themes](https://discourse.theme-creator.io/my/themes)
3. Select "Install" > "From a git repository" and enter `https://github.com/godotengine/discourse-theme`
4. Reload the website, select the "Godot Theme" again
5. Scroll down, select "Advanced" and change the "Color Palette" to "Godot"
6. Click "Edit Locally" and generate and copy an API key (store it somewhere!)

You can now see a live preview every time you want to work on the theme:
1. On your local machine: open a terminal, navigate to the repository root directory and enter `discourse_theme watch .`
  - if asked, enter the root url: `https://discourse.theme-creator.io/`
  - if asked, enter the API key you retrieved in the one time setup
  - you may answer `y` to store these, so that you don't need to enter them again
  - select the theme "Godot" for synchronisation
2. Go to [discourse.theme-creator.io/my/themes](https://discourse.theme-creator.io/my/themes) and select the theme you are editing
3. Click on the "Preview" button


## Usage

### Installation
1. In discourse, go to Admin > Customize > Themes
2. click the Install button and choose "From a git repository"
3. Enter the URL of this repo: `https://github.com/godotengine/discourse-theme`

### Updates
1. In discourse, go to Admin > Customize > Themes
2. Select the "Godot Theme"
3. Click "Check for Updates"
