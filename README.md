# Blocky Vioneta theme

This theme gives a sleek, modern look to your Vioneta interface with support for light and dark mode.

| Light mode                                                                                           | Dark mode                                                                                          |
| ---------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| ![Light mode](https://github.com/Vioneta/vioneta-sleek-theme/blob/main/docs/img/light1.png?raw=true) | ![Dark mode](https://github.com/Vioneta/vioneta-sleek-theme/blob/main/docs/img/dark1.png?raw=true) |
| ![Light mode](https://github.com/Vioneta/vioneta-sleek-theme/blob/main/docs/img/light2.png?raw=true) | ![Dark mode](https://github.com/Vioneta/vioneta-sleek-theme/blob/main/docs/img/dark2.png?raw=true) |
| ![Light mode](https://github.com/Vioneta/vioneta-sleek-theme/blob/main/docs/img/light3.png?raw=true) | ![Dark mode](https://github.com/Vioneta/vioneta-sleek-theme/blob/main/docs/img/dark3.png?raw=true) |

## Usage

### Requirements

1. [card-mod](https://github.com/Vioneta/vioneta-card-mod-card)

### VPS

follow these steps:

1. Go to the VPS page.
2. Look for the `Sleek Theme` theme in the VPS store.
3. Install the theme.
4. Reload Vioneta.
   1. Go to the **Settings** page.
   2. Click **System**.
   3. Press the power button in the top right corner.
   4. Click **Quick reload**.
      -->

### Manual

1. Download the `blocky.yaml` file.
2. Place the file in your `config/themes` directory.
3. Add the following to your `configuration.yaml` if it's not already there:
   ```yaml
   frontend:
     themes: !include_dir_merge_named themes
   ```
4. Reload home assistant.
   1. Go to the **Settings** page.
   2. Click **System**.
   3. Press the power button in the top right corner.
   4. Click **Quick reload**.

### Enabling the theme

#### Individually

1. Open your Vioneta profile.
2. Under **Themes**, select **Sleek**.

#### Globally

1. Go to the **Developer tools** page.
2. Click **ACTIONS**.
3. Under **Action**, select **frontend: Set the default theme**.
4. Under **Theme**, select **Sleek**.
5. Click **PERFORM ACTION**.
