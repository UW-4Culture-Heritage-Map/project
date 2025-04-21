# 4Culture Heritage Mapping Project

This digital collection site was created using [CollectionBuilder-GH](https://collectionbuilder.github.io/collectionbuilder-gh/), a lightweight, open-source template for publishing digital heritage materials via [GitHub Pages](https://pages.github.com/).

The site visualizes collections care and heritage stewardship efforts supported by 4Culture across King County. Each mapped record highlights organizations, collections, and individuals who preserve the region’s diverse cultural history, using data drawn from program applications and public archives.

## How This Project Works

The project is powered by:

- A CSV of metadata documenting participating organizations and their collections
- A folder of JPEG images and PDF files related to each heritage record
- A GitHub-hosted site structured via Jekyll and the CollectionBuilder-GH template

This prototype supports community visibility and exploratory research into King County's living archives, organizations, and collections stewards.

> **Note:** GitHub Pages is best suited for lightweight, public-facing exhibits. Collections with high-resolution assets or complex access control should use the [CollectionBuilder-CSV](https://github.com/CollectionBuilder/collectionbuilder-csv) template or other infrastructure.

## Customization & Workflow

We have customized the following files for this project:

- `metadata.csv`: Core record data, including organization name, subject area, location, contact, and access methods
- `config-map.csv`: Controls display of popup content and map behavior
- `collection-banner.html`: Custom branding for 4Culture, including logos and titles
- `objects/`: Contains associated media files for mapped organizations

## Teaching and Research Value

This site demonstrates a minimal computing approach to cultural heritage mapping and is used as part of an academic internship supported by the University of Washington’s iSchool and 4Culture.

Skills developed and demonstrated through this project include:

- Git and GitHub version control
- Metadata creation using CSV
- Web publishing with Markdown and HTML
- Static site generation using [Jekyll](https://jekyllrb.com/)
- Open data and digital preservation best practices
- Map-based visualization using [Leaflet](http://leafletjs.com/)
- "Collections as Data" and minimal computing principles

## Credits

Project supported by:

- [4Culture Heritage Department](https://www.4culture.org/)
- University of Washington, Information School
- Community-based heritage organizations throughout King County

Built with [CollectionBuilder](https://collectionbuilder.github.io/) developed by the University of Idaho Library’s [Digital Initiatives](https://www.lib.uidaho.edu/digital/) and [CDIL](https://cdil.lib.uidaho.edu/).

## License

This project uses CollectionBuilder’s open source components:

- **Code** is licensed [MIT](https://github.com/CollectionBuilder/collectionbuilder-csv/blob/master/LICENSE)
- **Documentation** is licensed [Creative Commons BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/)

All media and content in this site are provided by the contributing organizations and may have their own rights statements. Refer to the `rights` field in each metadata entry for usage details.

