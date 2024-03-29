# l

Link shortener running on GitHub Actions and GitHub Pages.

Uses shell script to generate a static site which redirects to an external URL.

Each file in the `links/` directory is treated as a link to an external site. For example [chrismytton.uk/l/self](https://www.chrismytton.uk/l/self) is a self-referential link back to this repo.

## Architecture

Have a look at the [GitHub Actions workflow file](.github/workflows/main.yml) to see how it works.

## Inspiration

Inspired by [this Tweet from @mikeal](https://twitter.com/mikeal/status/1284230110678155267) and [the corresponding GitHub repo](https://www.chrismytton.uk/l/mikeal-shortlink), which does something similar, but using JavaScript.
