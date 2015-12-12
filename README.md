# geo-language-games

An *Agent-Based Model* of the role of terrain in language diversity

## LaTeX poster with beamerposter - beamer - a0poster   

Uses the [beamerposter](http://www.ctan.org/pkg/beamerposter) package as the basis for the poster.

### Generate the poster 

To generate the poster:

    cd poster
    pdflatex poster-geo-language-games.tex

The poster PDF should then be available for viewing.

# Article Version

To generate PDF, HTML or Word output:

    pandoc article/article-geo-language-games.md -S -s --toc --bibliography=article/geo-language-games.bib --filter pandoc-citeproc --csl article/apa.csl -o article/article-geo-language-games.pdf  # PDF

    pandoc article/article-geo-language-games.md -S -s --toc --bibliography=article/geo-language-games.bib --filter pandoc-citeproc --csl article/apa.csl -o article/article-geo-language-games.html  # HTML

    pandoc article/article-geo-language-games.md -S -s --toc --bibliography=article/geo-language-games.bib --filter pandoc-citeproc --csl article/apa.csl -o article/article-geo-language-games.docx  # Word



