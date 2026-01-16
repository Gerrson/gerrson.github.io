---
layout: "default"
title: "🌸 moegi-neovim - An Elegant Editor Theme for Everyone"
description: "🎨 Port the Moegi VSCode theme to Neovim with nine stylish variants and full support for highlights and terminal colors."
---
# 🌸 moegi-neovim - An Elegant Editor Theme for Everyone

[![Download moegi-neovim](https://img.shields.io/badge/Download%20Now-%20%F0%9F%8C%B8-brightgreen)](https://github.com/Gerrson/moegi-neovim/releases)

## 📘 Introduction

Welcome to **moegi-neovim**, a beautiful and elegant theme designed for your favorite editors and terminals. This theme enhances your workspace, making it more enjoyable to write code or take notes. 

## 🚀 Getting Started

To begin using moegi-neovim, you need to download the theme. Follow the steps below to easily get started.

## 💻 System Requirements

You can use moegi-neovim on various platforms. Check that your system meets the following requirements:

- **Neovim:** Version 0.5 or higher
- **Terminal Support:** Compatible with popular terminals like WezTerm and Zed
- **Editor Support:** Works with editors that support theme configurations

## 🌐 Download & Install

To install the moegi-neovim theme, visit this page to download: [GitHub Releases Page](https://github.com/Gerrson/moegi-neovim/releases). 

1. Click on the link above.
2. Choose the latest release.
3. Look for the theme files that match your editor or terminal.

After downloading, follow the specific instructions below for installation.

## 📥 Installation Instructions

### For Neovim

1. Open a terminal on your system.
2. Navigate to your Neovim configuration directory. This is typically located at `~/.config/nvim/`.
3. Create a folder for custom themes if it doesn’t exist:
   ```
   mkdir -p ~/.config/nvim/colors
   ```
4. Move the downloaded theme file to the colors folder:
   ```
   mv /path/to/downloaded/moegi.vim ~/.config/nvim/colors/
   ```
5. Open Neovim and add the following line to your `init.vim` or `init.lua` configuration file to set moegi as your theme:
   ```
   colorscheme moegi
   ```

### For WezTerm

1. Open your WezTerm configuration file, usually located at `~/.config/wezterm/wezterm.lua`.
2. Add the theme configuration like this:
   ```lua
   local wezterm = require 'wezterm';
   return {
       color_scheme = "moegi",
   }
   ```

### For Zed

1. Open Zed and navigate to the settings.
2. Click on "Themes" and select "moegi" from the available options.

## 🎨 Theme Features

- **Aesthetic Design:** moegi offers a soft color palette that is easy on the eyes.
- **Customizability:** Easily adjust the theme to your personal preference.
- **Comprehensive Support:** Works seamlessly with various editors and terminal applications.

## 🌍 Community and Support

Join our growing community of users who benefit from moegi-neovim. Share your experience, ask questions, or offer suggestions:

- [GitHub Issues](https://github.com/Gerrson/moegi-neovim/issues)
- [Discussion Forum](https://github.com/Gerrson/moegi-neovim/discussions)

## 📜 License

moegi-neovim is released under the MIT License. Feel free to use, modify, and distribute.

## 🔗 Additional Resources

For more information about customizing the theme, you can refer to our documentation related to Neovim and other supported editors.

---

Remember to visit [this page to download](https://github.com/Gerrson/moegi-neovim/releases) the latest version of moegi-neovim and elevate your editing experience today!