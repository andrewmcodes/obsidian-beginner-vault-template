# Obsidian Beginner Vault Template

A minimal template for your first [Obsidian vault](https://obsidian.md) aimed at setting good defaults.

This template is intended for first time users of Obsidian.

## Getting Started

- [Download and install Obsidian](https://obsidian.md/download)
- [Use this template](https://github.com/andrewmcodes/obsidian-beginner-vault-template/generate) and clone the repo
- Open Obsidian
- Click "Open" next to the "Open folder as vault" label
- Select the folder you cloned the repo to
- open `_START HERE.md` and follow the instructions

## Folder Structure

- `_assets`: project specific files and folders
  - `attachments`: this is where [attachment files](https://help.obsidian.md/How+to/Manage+attachments), like images, are stored
  - `templates`: this is where [template files](https://help.obsidian.md/Plugins/Templates) are stored
- `daily`: [Daily Note](https://help.obsidian.md/Plugins/Daily+notes) storage

## Settings

These are the settings that have been modified from the defaults.

### Editor

| Setting          | Value   |
| ---------------- | ------- |
| Show frontmatter | Enabled |
| Fold heading     | Enabled |
| Fold indent      | Enabled |
| Use tabs         | Enabled |
| Tab size         | 2       |

### Files & Links

| Setting                              | Value                         |
| ------------------------------------ | ----------------------------- |
| Confirm file deletion                | Enabled (Asks first time)                     |
| Automatically update internal links  | Enabled                       |
| Detect all file extensions           | Enabled                       |
| Default location for new attachments | In the folder specified below |
| Attachment folder path               | `_assets/attachments`         |

### Appearance

| Setting            | Value   |
| ------------------ | ------- |
| Translucent window | Enabled |
| Font size          | 15      |

### Hotkeys

I have modified some of the important hotkeys to better match VS Code's defaults since that is the text editor that I am most familiar with. Click the `Restore default` icon if you'd like to revert a specific hotkey to Obsidian's default hotkeys.

| Description                           | Shortcut    |
| ------------------------------------- | ----------- |
| Add internal link                     | ⌘K          |
| Command palette: Open command palette | ⌘⇧P         |
| Delete current file                   | ⌘⇧Backspace |
| Delete paragraph                      | ⌥Backspace  |
| Edit file title                       | ⌘⌥T         |
| Focus on editor                       | ⌘1          |
| Quick switcher: Open quick switcher   | ⌘P          |
| Split horizontally                    | ⌘\          |
| Split vertically                      | ⌘⇧\         |
| Swap line down                        | ⇧⌥↓         |
| Swap line up                          | ⇧⌥↑         |
| Add Markdown link                     | ⌘⌥K         |
| Open in default app                   | ⌘⌥D         |
| Show in system explorer               | ⌘⌥R         |
| Toggle Left Sidebar                   | ⌘⇧E         |
|                                       |             |

### Core plugins

| Plugin                                                                                 | Value    |
| -------------------------------------------------------------------------------------- | -------- |
| [Outgoing Links](https://help.obsidian.md/Plugins/Outgoing+links)                      | Enabled  |
| [Tag pane](https://help.obsidian.md/Plugins/Tag+pane)                                  | Enabled  |
| [Daily notes](https://help.obsidian.md/Plugins/Daily+notes)                            | Enabled  |
| [Templates](https://help.obsidian.md/Plugins/Templates)                                | Enabled  |
| Slash commands                                                                         | Enabled  |
| [Starred](https://help.obsidian.md/Plugins/Starred+notes)                              | Enabled  |
| [Markdown format importer](https://help.obsidian.md/Plugins/Markdown+format+converter) | Disabled |
| [Outline](https://help.obsidian.md/Plugins/Outline)                                    | Enabled  |
| [Audio recorder](https://help.obsidian.md/Plugins/Audio+recorder)                      | Enabled  |

### Community Plugins

This vault does not come with any community plugins by default.

| Setting   | Value    |
| --------- | -------- |
| Safe mode | Disabled |

## Core Plugin Options

### [Templates](https://help.obsidian.md/Plugins/Templates)

| Setting                  | Value               |
| ------------------------ | ------------------- |
| Template folder location | `_assets/templates` |

### [Daily notes](https://help.obsidian.md/Plugins/Daily+notes)

| Setting                    | Value                       |
| -------------------------- | --------------------------- |
| New file location          | daily                       |
| Template file location     | `_assets/templates/t_daily` |
| Open daily note on startup | Enabled                     |

#### Hotkeys

| Description                | Shortcut |
| -------------------------- | -------- |
| Templates: Insert template | ⌘⌥I      |
