# Limbo Language Support for VSCode

Adds syntax highlighting for **Limbo Project Configuration** (`.lmproj`) files in Visual Studio Code.

![preview](https://user-images.githubusercontent.com/yourusername/your-preview-image.png) <!-- Optional screenshot -->

## 📦 Features

- Syntax highlighting for `.lmproj` files
- Support for:
  - Keys like `name`, `version`, `output`, `tags`, `predicates`, etc.
  - Strings, numbers, and inline functions
  - YAML-like structure with Limbo-specific keywords

## 🔧 File Association

This extension automatically activates for files ending in `.lmproj`.

## 🚀 Getting Started

### 1. Install

You can install this extension by:

- Searching **"Limbo Language Support"** in the Extensions view in VSCode *(if published)*  
**OR**
- Installing manually:
  1. Download the `.vsix` file
  2. In VSCode, open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`)
  3. Run `Extensions: Install from VSIX...`
  4. Select the `.vsix` file

### 2. Open a `.lmproj` file  
Enjoy automatic highlighting!

## 🧠 Example Syntax

```yaml
name: "test-project"
version: "1.0.0"
minecraft_version: "1.20.2"

output:
  namespace: "test_project"
  pack_format: 15
  target_path: "./output"

tags:
  blocks:
    - "custom_block_tag"
  functions:
    - "load"
    - "tick"
