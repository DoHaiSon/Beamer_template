# LaTeX Beamer Theme - Custom Madrid Template

This is a custom LaTeX Beamer theme based on the popular Madrid theme. It provides a clean, professional layout with a polished design suitable for academic and research presentations.

## Features
- **Primary Color:** Custom blue (`#1a3f7a`) for a sleek, professional look.
- **Foot/Head Customization:** White text on a blue background for consistency and clarity.
- **No Navigation Buttons:** Simplified presentation view without navigation symbols.
- **No Shadow:** Clean, flat design with no shadow effects for a modern look.
- **Citation Style:** Numeric citations with footnotes in a compact style, perfect for research papers and academic talks.
- **Manual Citation Command:** New command `\manualcite{index}{key}` to generate citations with customized footnotes, allowing you to specify the citation number manually, without following a sequential order.
- **Dynamic Section/Subsection Titles:** Automatically generates title slides for each section and subsection, with distinct formatting.
- **Customized Lists:** Unique bullet points and enumeration styles for a more structured presentation.
- **Clean Footnote Design:** Footnotes are compact and aligned with the content for minimal distraction.

## Usage
This theme is compatible with **TeXstudio**, other offline LaTeX compilers, and **[Overleaf](https://www.overleaf.com/)** (strongly recommended). To use this theme:

1. **On [Overleaf](https://www.overleaf.com/) (strongly recommended):**
   - Create a new project and upload the theme file, or directly copy-paste the code into your project.
   - Compile using the pdfLaTeX version 2020 or newer. 
   
2. **In Offline Compilers (e.g., TeXstudio):**
   - Download or clone this repository.
   - Compile and run the `main.tex` file using the LaTeX engine.
   - If any libraries are missing, you may need to install them manually via the MiKTeX console (for Windows users) or through your LaTeX distribution's package manager.
   - **Note: This template uses TikZ for an advanced figure. You can comment out or remove unused libraries to speed up compilation.**

## License
This theme is released under the [**GNU General Public License v3.0**](LICENSE). You are free to modify and distribute the code, provided you adhere to the terms of the license.
