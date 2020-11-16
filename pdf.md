# PDF Command Line Tools

## PDFjam
* in Latex Enthalten

`pdfjam OPTIONEN DATEI1 SEITENAUSWAHLDATEI1 DATEI2 SEITENAUSWAHLDATEI2 `

### Mehrere Seiten auf eine Seite
`pdfjam --nup 1x2 datei.pdf --outfile Dokument.pdf`
* Weitere Optionen:
| Option | Beschreibung |
| ------ | ------------ |
| --landscape/--no-landscape | Querformat |
| --scale | Skaliert Eingabeseiten |
