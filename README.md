# LaTeX APA Thesis Template

This repository provides a beginner-friendly LaTeX template for students to create APA-style theses using Overleaf. The template includes all necessary settings and structures to help you get started with academic writing in APA format.

## Features

- Pre-configured for APA style.
- Clear and modular structure for adding your content.
- Example content provided to guide you.

## Getting Started

### 1. Clone or Download the Repository

- Option 1: **Clone the repository**
  
  ```bash
  git clone https://github.com/MRI-Lab-Graz/master-thesis-latex.git
  ```

- Option 2: **Download as ZIP**
  - Click the green "Code" button at the top of the repository page.
  - Select "Download ZIP" and extract the files.

### 2. Open the Template in Overleaf

1. Go to [Overleaf](https://www.overleaf.com).
2. Create a new project by selecting **Upload Project**.
3. Upload all the files from this repository to your project.

### 3. Start Writing Your Thesis

- Open `apa_thesis_content.tex` and replace the example content with your own.
- Use `apa_template_settings.tex` to configure settings (if needed). Most users won’t need to modify this file.

## File Structure

- **`apa_template_settings.tex`**: Contains all formatting and style settings for APA compliance.
- **`apa_thesis_content.tex`**: The main file where you write your thesis content.
- **BibTeX File (Optional)**: You can add a `.bib` file for managing references.

## How to Compile

1. Set the compiler in Overleaf to **PDFLaTeX**.
2. Click **Recompile** to generate the PDF.

## Example Usage

Here’s a quick example of how to add content:

```latex
\section{Introduction}
This is where you write your introduction. Make sure to use APA citations, like \cite{example2025}.

\subsection{Background}
Provide necessary background information here.
```

## Adding References

1. Create a `.bib` file for your references (e.g., `references.bib`).
2. Add your references in BibTeX format:
   ```bibtex
   @article{example2025,
     author  = {John Doe},
     title   = {An Example Article},
     journal = {Journal of Examples},
     year    = {2025},
     volume  = {42},
     pages   = {1--10}
   }
   ```
3. Include the `.bib` file in your main document:
   ```latex
   \bibliography{references}
   ```

## Troubleshooting

- **Overleaf Errors:** Double-check your file structure and ensure all necessary files are uploaded.
- **Reference Errors:** Make sure your `.bib` file is correctly formatted.
- **Customization:** Adjustments can be made in `apa_template_settings.tex`.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve this template.

## License

This project is licensed under the [MIT License](LICENSE).
