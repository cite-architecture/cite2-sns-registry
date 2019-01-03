Notes on this directory

`lead-for-pdf.md` is the header, in markdown format, for the publication of  a release of the registry.

`mdforpandoc.sc` is a script you can run from an sbt console in the root directory of this repository to generate the body content in markdown format for a release of the registry, with entries sorted alphabetically.

The PDF version of a release can be generated with pandoc, e.g.,


    pandoc cite2-sns-1-0-0.md --pdf-engine=xelatex -o cite2-sns-1-0-0.pdf
