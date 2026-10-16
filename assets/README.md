# Profile artwork and design notes

The research banner, project cards, education cards, and experience cards are original, repository-local SVG artwork. Each has a light and dark version, chosen by README `picture` elements. Edit both variants when updating project, education, or experience information. Education cards use red and blue backgrounds with the original CMU red PNG and the Nottingham PNG supplied by the profile owner, embedded on white panels for contrast. They link to the universities’ official websites; the degree card identifies the University of Nottingham, UK, while the Research Assistant role remains at UNNC. Company cards embed the official logos from `assets/logos` as self-contained artwork; the music association card embeds the original logo supplied by the profile owner. The Selected Projects cards link directly to project repositories for detailed methods and results. Education, work experience, and honors have separate sections; skills and languages remain under Technical Toolkit.

Education cards are full-width horizontal strips, with CMU above Nottingham. Project and work cards are ordered by start date, newest first, read left to right and then top to bottom. The UNNC Research Assistant card intentionally has no responsibility text until details are supplied.

The contribution snake is generated daily by `.github/workflows/profile-snake.yml`, using the repository's built-in GitHub token. Generated light and dark SVGs are published to the `output` branch. Animated tool icons, decorative wings, separators, and statistics widgets remain in the README. The old top typing animation, coding GIF, and section-navigation row have been removed.

## Layout references

- [sun0225SUN](https://github.com/sun0225SUN/sun0225SUN/blob/main/README.md): existing animated decorations and contribution snake.
- [DenverCoder1](https://github.com/DenverCoder1/DenverCoder1/blob/main/README.md): project highlights and expandable sections.
- [anuraghazra](https://github.com/anuraghazra/anuraghazra/blob/master/README.md): local header artwork and aligned statistics.
- [rasbt](https://github.com/rasbt/rasbt/blob/master/README.md): concise research identity and direct project links.

The layout uses GitHub-supported Markdown, HTML pictures, and details elements. It does not depend on custom page CSS or JavaScript. [Organization logo sources](logos/README.md) are documented separately.
