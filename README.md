# Kompilera ett dokument

  $ pandoc -S --reference-odt=reference.odt --filter pandoc-citeproc -o output.odt input.md

# Krav

  * brew install pandoc pandoc-citeproc
  * LibreOffice (eller kanske något annat som fattar .odt bra)
  * Zotero för enklare referenshantering

# TODO

  * [ ] Ordna Makefile/fabfile för kompilering. Kanske fabfile som även kan användas för att mejla iväg en fil osv?
  * [ ] Undersök möjligheterna att göra en titelsida enligt högskolans specifikationer.
  * [ ] Skriv en vettig README :-)
