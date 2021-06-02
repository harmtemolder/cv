# Harm te Molder's CV

A curriculum vitae maintained in plain text and rendered to HTML and PDF using CSS.

## How-to

### Where is what?

- `_config.yml` contains the global settings, like the name of the style to be used. (In my case `harmtemolder`.)
- `_layouts/cv.html` contains the HTML of the page, including Google Tag Manager.
- `styles/harmtemolder.scss` contains my CSS
- `index.md` contains the actual CV

### How to build

- To serve locally, use `jekyll serve`_*_ and navigate to the printed URL (probably [localhost:4000](http://localhost:4000/))
- Pushing changes to GitHub will publish the CV to [harmtemolder.github.io/cv/](https://harmtemolder.github.io/cv/)
- To generate a PDF, just print from your browser. The CSS contains an `@media print` section that takes care of print formatting

### _*_ Installing Jekyll

1. `gem install --user-install bundler jekyll` Source: <https://jekyllrb.com/docs/installation/macos/>

## Credits

- Original Markdown CV by [Eliseo Papa](https://elipapa.github.io/markdown-cv/)
- Icons by [Tikhon Reztcov](https://thenounproject.com/peter1153/collection/pixel-icon/)
- The colours I use come from [Google Analytics](https://analytics.google.com/analytics/web/)

  - <span style="color: #058DC7">#058DC7</span>

  - <span style="color: #9bd1e9">#9bd1e9</span>

  - <span style="color: rgb(205, 232, 244)">rgb(205, 232, 244)</span>

  - <span style="color: #ED7E17">#ED7E17</span>

  - <span style="color: #f8cba2">#f8cba2</span>

  - <span style="color: rgb(251, 229, 209)">rgb(251, 229, 209)</span>

  - <span style="color: #50B432">#50B432</span>

  - <span style="color: #b9e1ad">#b9e1ad</span>

  - <span style="color: rgb(220, 240, 214)">rgb(220, 240, 214)</span>

  - <span style="color: #AF49C5">#AF49C5</span>

  - <span style="color: #dfb6e8">#dfb6e8</span>

  - <span style="color: rgb(239, 219, 243)">rgb(239, 219, 243)</span>

## License

[GNU GPLv3](https://raw.githubusercontent.com/harmtemolder/cv/master/LICENSE)
