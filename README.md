# Frictionless

> A fast, local-first workbench for cleaning, formatting, converting, and working with messy copied text.

**Live Demo:** https://copyandpaste2.vercel.app/
**Source Code:** https://github.com/jinjintt89-cmyk/Friction-less-copy-and-paste

---

## What is Frictionless?

Frictionless started as a simple tool for cleaning up messy copied text.

It has since grown into a complete text and data workbench designed for situations where copied content needs to be cleaned, transformed, checked, or converted before being used somewhere else.

Instead of using a different website for every small task, Frictionless puts these tools together in one place.

Everything runs locally in the browser. Your text and recent pastes stay on your device rather than being sent to a server.

---

## Why I Built It

Copying and pasting text can introduce annoying problems:

* Invisible characters
* Non-breaking spaces
* Unwanted whitespace
* Curly quotation marks
* Em dashes and en dashes
* Duplicate lines
* Inconsistent capitalization
* Incorrect formatting
* Data that needs to be converted between formats

These problems are usually small, but fixing them manually can take time.

Frictionless is designed to make those jobs quick.

---

## Features

### Clean Text

Clean copied text with options for:

* Curly quotes → straight quotes
* Em/en dash → hyphen
* Non-breaking spaces
* Invisible characters
* Trailing whitespace
* Collapsing blank lines

You can preview the result and copy the cleaned output when you're finished.

### Text Tools

Additional tools for working with text:

* Find & Replace
* Duplicate line detection/removal
* Sort lines

  * A–Z
  * Z–A
  * Numerical
  * Reverse order
* Case Converter

  * UPPERCASE
  * lowercase
  * Title Case
  * Sentence case

These tools work directly with the main paste area so you can combine multiple transformations.

### Data Tools

Work with structured data without leaving the app:

#### JSON

* Validate JSON
* Format JSON
* Convert results to CSV
* Copy formatted results

#### CSV

* Parse CSV
* Filter rows
* Convert CSV to JSON

#### Markdown

* Format Markdown
* Preview Markdown
* Convert Markdown to plain text
* Convert plain text to Markdown

#### Diff / Compare

Compare two versions of text side-by-side to see what changed.

### Output Formats

Cleaned content can be viewed as:

* Clean text
* Markdown table
* CSV
* JSON
* Marks

This makes it easier to take messy copied information and turn it into a format that can actually be used.

### Saved Presets

Create custom cleanup presets containing the operations you use most often.

For example, you could create a preset for cleaning copied text that automatically removes invisible characters, fixes quotation marks, removes unwanted whitespace, and collapses blank lines.

Once saved, the preset can be run on new text with one click.

### History

Frictionless can keep recent cleaned pastes locally so you can find previous work again.

You can search your recent pastes and choose how long they should be kept.

### Toolkit

The app also includes small utilities for working while processing text:

* Date & time inserter
* Calendar
* Countdown timer
* Stopwatch
* Quick timer presets

Dates and times can be inserted directly into the paste area.

### Undo & Redo

Changes to the main paste area can be undone and redone, making it easier to experiment with different transformations without losing your original text.

---

## Privacy

Frictionless is designed to work locally.

Your text processing happens in the browser, and recent pastes are stored in your own local storage rather than being shared with other users.

There is no account required to use the web version.

---

## Example Use Cases

Frictionless can be useful when:

* Cleaning text copied from a website
* Removing invisible whitespace
* Preparing text before pasting it into another application
* Removing duplicate lines
* Sorting a list
* Changing capitalization
* Finding and replacing repeated text
* Formatting JSON
* Inspecting CSV data
* Converting between CSV and JSON
* Formatting Markdown
* Comparing two versions of text
* Creating repeatable cleanup workflows with presets
* Quickly inserting dates and times

It is especially useful for small jobs where opening a large editor or writing a script would be unnecessary.

---

## Web Version

The easiest way to use Frictionless is through the web app:

**https://copyandpaste2.vercel.app/**

No installation is required.

---

## Desktop Version

Frictionless also has a macOS desktop version built with Electron.

The desktop version packages the same workbench into a standalone application, allowing it to be used as a dedicated local tool instead of keeping it open in a browser tab.

The current desktop build targets Apple Silicon Macs.

---

## Tech Stack

* HTML
* CSS
* JavaScript
* Vercel
* Electron
* Electron Forge

The web application is client-side focused, while Electron is used to package the application for macOS.

---

## Running Locally

Clone the repository:

```bash
git clone https://github.com/jinjintt89-cmyk/Friction-less-copy-and-paste.git
cd Friction-less-copy-and-paste
```

Install dependencies:

```bash
npm install
```

Run the desktop version:

```bash
npm start
```

To package the application:

```bash
npm run make
```

---

## Project Structure

```text
Friction-less-copy-and-paste/
├── assets/
├── copyandpaste.html
├── main.js
├── forge.config.js
├── package.json
├── package-lock.json
├── README.md
└── .gitignore
```

---

## Development

Frictionless has evolved from a small copy-and-paste cleanup tool into a much larger workbench.

The development process has focused on adding useful tools while keeping everything connected to the same workflow:

**Paste → Clean → Transform → Review → Copy**

The project has also been tested as both a web application and a macOS desktop application.

---

## Future Improvements

Some areas I would like to continue improving include:

* Further UI simplification
* More keyboard shortcuts
* Additional text transformations
* More data-format conversions
* Better desktop integration
* More customization
* Continued performance and usability improvements

---

## License

This project is open source. See the repository for the current license and source code.

---

## Links

Live Demo:
https://copyandpaste2.vercel.app/

GitHub:
https://github.com/jinjintt89-cmyk/Friction-less-copy-and-paste



<img width="1430" height="786" alt="Screenshot 2026-09-09 at 5 12 27 am" src="https://github.com/user-attachments/assets/2a352b4e-aa88-453b-bfdc-3c134850792c" />

