# Bolt (Grav theme)
A simple theme for GRAV that utilizes css grids and variables.

## Features

- Pure HTML and CSS
- Different layouts:
    - Default
    - Columns
    - Gallery
    - Chapter
    - Docs
- Dropdown menus
- A configurable sidebar (can be customized in the page layout settings from the admin panel).
- A breakpoint at 800px that enables the mobile layout.


**Demo**: [re-volt.io](https://re-volt.io)

[![screenshot](bolt/thumbnail.jpg)](bolt/screenshot.jpg)


## Documentation

### Page Templates

All page templates contain a sidebar. Its position can be set in the Layout Settings (see further below).

#### Default
The default layout displays page contents normally.

#### Columns
Divides the page content at horizontal lines `---` and displays it in columns. Their width can be set in the Layout Settings.

#### Gallery
Similarly to the Columns template, it divides the page content at horizontal lines and displays the segments as gallery entries.

#### Chapter
Insipred by the Learn2 Chapter layout. It displays a large heading and a table of child pages.

#### Docs
Also inspired by Learn2. Displays the site title as a large heading with a horizontal line. Otherwise similar to Default.

### Layout Settings

The layout settings can be set per-page in the Grav admin panel. Look out for the new _Layout Settings_ tab in the page editor.

#### Sidebar Layout
Select the sidebar location. The options including the showcase will enable a box with a ranom picture from the page folder.

#### Sidebar Content
In addition to the child pages of the current site, you can also display another page's contents in the sidebar.
Provide the path to the page, e.g. `/downloads/more/`.

#### Showcase
Enable or disable the showcase.

#### Table of Contents
Show or hide the table of child pages in the sidebar.

#### Horizontal Table of Contents
Display the table horizontally rather than as a list. This is useful for the horizontal sidebar layouts.


### Customization

The `custom.css` file in `user/themes/bolt/css/` is enabled by default and can be used to alter the style of the theme.  
`variables.css` contains link and text colors as well as some dimensions for the grid layout.  
`style.css` contains most of the style.

The sidebar layouts can be customized in the `user/themes/bolt/css/layouts` folder.

The favicon and the page background reside in `user/themes/bolt/images`.