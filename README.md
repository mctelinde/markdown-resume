## Getting Started

### Generate HTML Resume

Use the following command to generate your resume from markdown:

```bash
pandoc --standalone -c ../style.css --from markdown --to html -o output/index.html chris_resume.md
```

### Generate PDF Resume (using ConTeXt)

```bash
pandoc --standalone -c style.css --from markdown --to pdf -o output/chris_resume.pdf chris_resume.md -t context
```

### Dependencies

- [Pandoc](https://pandoc.org/)
- [LaTeX](https://www.latex-project.org/get/) or [ConTeXt](https://wiki.contextgarden.net/Main_Page) for generating the resume in PDF format

### Resources

- [Editing a CV in markdown with pandoc (Ch-M.D)](https://blog.chmd.fr/editing-a-cv-in-markdown-with-pandoc.html)
