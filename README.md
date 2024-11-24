# LaTeX Snippets Repository

This repository contains a curated collection of **LaTeX snippets** designed to streamline your LaTeX workflow. These snippets are ideal for users who frequently write LaTeX documents and want to enhance their productivity in text editors like **VS Code**, **Sublime Text**, or others that support custom snippets.

## Contents

- **[LaTeX-snippets.code-snippets](LaTeX-snippets.code-snippets):**  
  A JSON file containing snippet definitions for:
  - Common LaTeX commands.
  - Frequently used Greek letters.
  - Formatting shortcuts.
  - Environment templates (e.g., `itemize`, `enumerate`, `frames`, etc.).

## Features

- **Greek Letters:** Quickly insert common Greek letters with short prefixes (e.g., `lam` for `\lambda`).
- **Formatting Shortcuts:** Bold, italics, and colored text made easy.
- **Math Mode Support:** Insert math bold, calligraphic symbols, fractions, and integrals.
- **Environment Templates:** Predefined structures for LaTeX environments like `enumerate`, `itemize`, `proof`, `align*`, and more.
- **Custom Commands:** Handy shortcuts for specific LaTeX functions, tailored for rapid document creation.

## Installation

### For VS Code
1. Open **Command Palette** (`Ctrl+Shift+P` or `Cmd+Shift+P`).
2. Search for `Preferences: Configure User Snippets`.
3. Choose `latex.json` or create a new global snippet file.
4. Copy the content of `LaTeX-snippets.code-snippets` into the snippet file.
5. Save the file and restart VS Code.

### For Sublime Text
1. Navigate to `Preferences > Browse Packages`.
2. Open the `User` folder.
3. Copy the `LaTeX-snippets.code-snippets` file here and rename it to `latex.sublime-snippet`.
4. Save and restart Sublime Text.

## Usage

### Snippets in Action
1. Open your LaTeX file in the editor.
2. Start typing the **prefix** (e.g., `alph` for `\alpha` or `bf` for bold text).
3. Press `Tab` or your editor’s expand shortcut to insert the snippet.

### Example
| Prefix    | Output               |
|-----------|----------------------|
| `alph`    | `\alpha`             |
| `bf`      | `\textbf{}`          |
| `enum`    | Creates an `enumerate` environment. |
| `lam`     | `\lambda`            |

## Customization

Feel free to modify the snippets to suit your needs:
- Add custom LaTeX commands you frequently use.
- Change prefixes or descriptions to align with your workflow.

To edit the file:
1. Open `LaTeX-snippets.code-snippets` in any text editor.
2. Add, remove, or adjust snippets following the JSON structure.

## Contributing

Contributions are welcome! If you:
- Encounter issues with existing snippets.
- Want to add new snippets.
- Have ideas for improvements.

Please open an issue or submit a pull request.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

