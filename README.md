# Typst Resume Template

A clean, one-page resume template built with [Typst](https://typst.app/).

## Usage

Clone this repository or use it as a template for your own resume repository.

The public starter file is `resume.sample.typ`. To create your own resume, copy and rename it first so the sample stays unchanged.

```powershell
Copy-Item resume.sample.typ resume.typ
```

You can also rename it to any filename you prefer:

```powershell
Copy-Item resume.sample.typ your-name-resume.typ
```

Then edit the copied `.typ` file with your own name, contact details, education, skills, experience, and projects.

## Generate PDF

First, make sure Typst is installed:

```powershell
typst --version
```

Compile your copied Typst file into a PDF:

```powershell
typst compile resume.typ resume.pdf
```

If you used a custom filename, compile that file instead:

```powershell
typst compile your-name-resume.typ your-name-resume.pdf
```

After editing your `.typ` file, run the compile command again to update the PDF.

## Credits

This project is based on [Jiahao's Typst resume template](https://github.com/woojiahao/resume-template) and is released under the MIT License.
