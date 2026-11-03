pdf.js 6.2.108 (Apache-2.0), from the pdfjs-dist npm package. Licence: LICENSE-pdfjs.txt

pdf.min.mjs        renderer, unchanged.
pdf.worker.min.mjs worker, unchanged except that raw control bytes (0x01-0x1F, apart from tab,
                   LF and CR) inside its string literals and regex literals were written as
                   \xNN escapes. Same values at run time; the artifact publisher refuses raw
                   control bytes. Original kept outside the project.
