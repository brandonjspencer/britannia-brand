# Britannia Custom Builders · Brand kit
Edition 02

Use this kit to create consistent Britannia communications. Start with the brand guidelines, then choose the logo format and file type that suits the application.

## Find the right file
- assets/logos/: scalable SVG logos, including full-color, one-color and editable-text versions.
- assets/png/: transparent PNG logos for presentations and office documents.
- assets/icons/ and assets/patterns/: supporting symbols and repeat patterns.
- assets/palette/: HEX/RGB colors, CSS tokens, JSON and a GPL palette.
- assets/fonts/: Libre Caslon Text and Montserrat, with font licenses.
- assets/guidelines/: the brand manual in Markdown and printable HTML.
- assets/applications/: illustrative application images and an editable A4 letterhead.
- assets/textures/: the parchment texture and notes on its Stone color treatment.
- assets/reference/: visual-direction imagery for materials, mood and composition.

Use outlined SVGs for reliable logo reproduction. Editable-text companions are for controlled design changes; install the supplied font if your application does not support embedded fonts. For fabrication, supply a vector logo and confirm dimensions, finish and a material proof with the fabricator.

The complete kit is britannia-brand-kit-r02.zip. Separate logo and symbol packages carry the same r02 suffix. The SVG files contain vector artwork rather than embedded raster pictures. The circular seal has no tagline; legacy seal-tagline filenames remain as compatibility aliases.

## Use the website
Extract the website ZIP and open index.html. The site uses relative links and locally bundled fonts. To preview with a local server, run `python3 -m http.server 8080` in this folder and open http://localhost:8080.

For static hosting, upload the folder contents and preserve the asset paths. Publish the directory containing index.html. The existing Sites project is recorded in .openai/hosting.json; its deployment package places the site in dist. Use the hosting service's sharing controls to choose who can view it.

## Design archive
The separate review folder records the artwork's development and source provenance. It is retained for project records and is not part of the working asset selection. Use the files in assets/ for new layouts and the brand guidelines for usage instructions.
