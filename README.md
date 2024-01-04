![2023-03-22T1722-Obsidian@2x](https://user-images.githubusercontent.com/18423853/227069885-83a9a90a-36a9-47c0-86fe-a7a124030f4b.png)

# Obsidian Beginner Vault Template

A template for a minimal [Obsidian vault](https://obsidian.md/), focused on setting good defaults and VS Code-like hotkeys. If you want to try Obsidian for the first time or just get a barebones template, you're in the right place.

## Getting Started

To use this template, follow these steps:

1. Download and install Obsidian from [obsidian.md/download](https://obsidian.md/download).
2. Use this template by clicking the ["Use this template"](https://github.com/andrewmcodes/obsidian-beginner-vault-template/generate) button on this page and cloning the repo.
3. Open Obsidian.
4. Click "Open" next to the "Open folder as vault" label.
5. Select the folder you cloned the repo to.
6. Open `GETTING STARTED.md` and follow the instructions.

## Folder Structure

The template vault has the following folder structure:

- `_assets`: this folder contains project-specific files and folders.
  - `attachments`: this is where attachment files like images are stored.
  - `templates`: this is where template files are stored.
- `daily`: this folder is used for storing daily notes.

## Settings

This section describes the settings that have been modified from the default Obsidian settings.

### Editor

The following table lists the editor settings that have been modified:

| Setting          | Value |
| ---------------- | ----- |
| Show frontmatter | true  |
| Use tabs         | false |

### Files & Links

> **Warning**
> If you are following along instead of using the template, make sure you have created the default folders listed above.

The following table lists the files and links settings that have been modified:

| Setting                              | Value                         |
| ------------------------------------ | ----------------------------- |
| Automatically update internal links  | true                          |
| Detect all file extensions           | true                          |
| Default location for new attachments | In the folder specified below |
| Attachment folder path               | `_assets/attachments`         |

### Appearance

The following table lists the appearance settings that have been modified:

| Setting            | Value   |
| ------------------ | ------- |
| Accent color       | #6e56cf |
| Font size          | 15      |
| Translucent window | true    |

### Hotkeys

The following table lists the modified hotkeys:

| Description                           | Shortcut    |
| ------------------------------------- | ----------- |
| Add internal link                     | ⌘K          |
| Command palette: Open command palette | ⌘⇧P         |
| Delete current file                   | ⌘⇧Backspace |
| Templates: Insert Template            | ⌘⌥I         |
| Quick switcher: Open quick switcher   | ⌘P          |
| Split right                           | ⌘\          |
| Split down                            | ⌘⇧\         |
| Move line down                        | ⌥↓          |
| Move line up                          | ⌥↑          |
| Add Markdown link                     | ⌘⌥K         |
| Open in default app                   | ⌃D          |
| Reveal in Finder                      | ⌃R          |
| Toggle Left Sidebar                   | ⌘E          |
| Toggle Right Sidebar                  | ⌘⇧E         |
| Toggle Reading View                   | ⌃V          |

### Core Plugins

The following core plugins are toggled by default in this template:

| Plugin           | Value |
| ---------------- | ----- |
| Format converter | false |
| Page preview     | false |
| Slash commands   | true  |
| Bookmarks        | true  |
| Properties       | true  |

### Community Plugins

This vault does not come with any community plugins by default. You will have to disable safe mode in order to use them when you open the plugins settings menu.

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
| Open daily note on startup | true                        |

I hope this template helps you get started with Obsidian and provides a good base for customizing your own Obsidian vault.
