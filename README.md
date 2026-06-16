Resume

This repository contains the source code for my resume written in LaTeX.

The document is based on the excellent Jake's Resume template and has been customized to better reflect my professional experience and preferred layout.

Repository Structure
.
├── Anton_Tenytskyi_CV.tex
├── Anton_Tenytskyi_CV.pdf
└── .github/
    └── workflows/
        └── build-pdf.yml
Build Locally

Compile the document using pdflatex:

pdflatex Anton_Tenytskyi_CV.tex

or

latexmk -pdf Anton_Tenytskyi_CV.tex
Continuous Integration

GitHub Actions automatically compiles the PDF on every push to the main branch.

Acknowledgements

This resume is based on the open-source Jake's Resume template and has been extensively customized.

License

The resume content is © Anton Tenytskyi.

The original template is distributed under its own license.
