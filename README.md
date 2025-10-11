This workflow contains a main LaTeX compilation file Book.tex and the chapter files it calls to compile a pdf of the Resonance Continuum Theory.

You will need something capable of compiling LaTeX. I use TeXShop, but there are many.

To compile a PDF from a .tex file, use the command pdflatex yourfile.tex in your terminal or command prompt. Navigate to the directory where your file is saved, run the command, and a yourfile.pdf will be generated. For automated or repeated runs, the latexmk -pdf yourfile.tex command is recommended as it handles multiple passes automatically. 
Using the command line

    Open your terminal or command prompt . 

Navigate to the directory: where your .tex file is saved using the cd command. For example, cd C:\Users\YourName\Documents. 
Run the command: pdflatex yourfile.tex (replace yourfile.tex with your actual filename). 
Repeat if necessary: for cross-references or a table of contents to update correctly. 
Use latexmk for convenience: on more complex documents by running latexmk -pdf yourfile.tex. This command will automatically run the necessary compilation steps to ensure everything is correct. 

Using a LaTeX editor

    Many dedicated LaTeX editors, like TeXworks, TeXnicCenter, or extensions for VS Code, have built-in buttons or commands to compile your document with a single click. 

These editors often provide a side-by-side view of the source code and the generated PDF, with the PDF updating automatically as you save your .tex file. 
