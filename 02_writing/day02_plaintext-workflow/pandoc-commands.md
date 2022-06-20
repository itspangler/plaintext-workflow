# Handy pandoc commands

### To export .md as .docx

    pandoc main.md --citeproc -o main.docx

### To export .md as .pdf

    pandoc main.md --citeproc -o main.pdf

### To export .md with references

    pandoc main.md --citeproc -o main.docx

### To export .md with references and custom formatting

    pandoc main.md --citeproc --reference-doc=custom-reference.docx -o main.docx

### To export .md with references, custom formatting, and numbered sections

    pandoc main.md --citeproc --reference-doc=custom-reference.docx --number-sections -o main.docx
