# Resume

A professional resume built with LaTeX, featuring a clean and modern design.

## Project Structure

```
.
├── resume.tex              # Main resume document
├── custom-commands.tex     # Custom LaTeX commands and styling
├── src/                    # Section content files
│   ├── heading.tex         # Name, contact info, and header
│   ├── experience.tex      # Work experience section
│   ├── education.tex       # Education section
│   ├── skills.tex          # Skills section
│   └── projects.tex        # Projects section
└── README.md              # This file
```

## Prerequisites

- LaTeX distribution (e.g., TeX Live, MiKTeX, or MacTeX)
- A LaTeX editor or command-line tools (pdflatex, xelatex)

## Building the Resume

### Using pdflatex

```bash
pdflatex resume.tex
```

### Using xelatex (for better font support)

```bash
xelatex resume.tex
```

The compiled PDF will be generated as `resume.pdf`.

## Customization

The resume is organized into modular sections:

- **Heading**: Edit `src/heading.tex` to update your name, contact information, and personal links
- **Experience**: Modify `src/experience.tex` to add or update work history
- **Education**: Update `src/education.tex` with your educational background
- **Skills**: Edit `src/skills.tex` to list your technical and professional skills
- **Projects**: Update `src/projects.tex` to showcase your projects and contributions

### Custom Commands

Custom LaTeX commands for formatting are defined in `custom-commands.tex`. Modify this file to adjust styling, colors, or add new formatting commands.

## Features

- Clean, ATS-friendly design
- Modular section structure for easy maintenance
- Custom LaTeX styling for professional appearance
- FontAwesome 5 integration for icons
- Responsive layout with adjustable margins
- Support for hyperlinks

## License

MIT License - Feel free to use and modify this template for your own resume.

## Credits

Based on the resume template by Audric Serador, inspired by: https://github.com/sb2nov/resume
