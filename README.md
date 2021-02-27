This is a template for my Latex documents.

I use Latexmk so that I don't have to compile separately the bib file. PDF Viewer and TeXiFy IDEA plugins are used in IntelliJ to make my life easier.

Please note that your source .tex file must be higher in the tree than the out folder, otherwise the bib file won't be compiled due to Latex security measures.

# Set Latexmk as default compiler in IntelliJ
Go to Run/Debug configurations (after you've compiled the project for the first time, using the in-editor compile option), select the existing configuration, and in the compiler dropdown, select Latexmk. Click apply, then Close.
