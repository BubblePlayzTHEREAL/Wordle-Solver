# Wordle-Solver

A fully HTML-based Wordle solver that helps you find possible words based on your Wordle clues.

## Features

- 🟩 **Green Letters**: Enter letters that are in the correct position
- 🟨 **Yellow Letters**: Enter letters that are in the word but wrong position  
- ⬜ **Gray Letters**: Enter letters that are NOT in the word
- 🎯 **Smart Filtering**: Uses the complete Wordle word list (2315 words)
- 💻 **Client-Side**: Everything runs in your browser, no server needed
- 📱 **Responsive**: Works on desktop, tablet, and mobile devices

## How to Use

1. **Green Letters**: Fill in any letters you know are in the correct position (1-5)
2. **Yellow Letters**: Enter yellow letters with their positions (e.g., "A1 B2" means A is yellow at position 1, B is yellow at position 2)
3. **Gray Letters**: Enter all letters that are not in the word (e.g., "QWERTY")
4. **Click "Find Possible Words"** to see all matching words

## Live Demo

Visit the live demo at: [GitHub Pages URL will be here]

## Local Usage

Simply open `index.html` in your web browser. No installation or build step required!

## Word List

The solver uses the official Wordle word list from [zulkarnine/WordleSolver](https://github.com/zulkarnine/WordleSolver).

## Technologies

- Pure HTML, CSS, and JavaScript
- No external dependencies
- Works offline after first load