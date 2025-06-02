---
title: "Github Copilot Export JSON to Markdown Converter "
date: 2025-06-02
---

Github Copilot Export JSON to Markdown Converter is a toolset for converting JSON files (such as those exported from Copilot) into clean, readable Markdown documents. The project includes both a standalone Python script and a dedicated Obsidian plugin, making it easy to integrate into different workflows.

## Key Features
- **JSON to Markdown Conversion:** Converts JSON files in a specified input directory to Markdown files in an output directory.
- **Automatic Directory Handling:** Creates output directories if they do not exist.
- **Flexible Formatting:** Extracts and formats relevant fields, preserving code blocks and structure.
- **Obsidian Plugin:** Seamless integration with Obsidian, allowing conversion with a single click or command palette action.
- **Customizable:** Input/output folders and formatting can be configured or modified.
- **Cross-Platform:** Works as a Python script or as a plugin within Obsidian.

## Usage
- For the Python script: Place JSON files in the `jsons/` directory and run `python3 json_to_md.py`. Output will be saved in `markdowns/`.
- For the Obsidian plugin: Copy the plugin folder to your vault, enable it, and use the ribbon icon or command palette to convert files.

## Example
- Input: JSON file with Copilot conversation data
- Output: Markdown file with formatted requests, responses, and code blocks

## License
This project is licensed under the GNU GPL v3.0 license.

For more details, visit the [Github Copilot Export JSON to Markdown Converter repository](https://github.com/FPGArtktic/copilot-export-json-to-markdown).
