# beamer-metro-template
[![Compile][compile-badge]][compile-yml]

Latex beamer Metropolis template for presentations.


# Usage
- change the link to the `compile-badge`
- change the link to `compile-yml`
- change the relevant info in `.github/workflows/Compile.yml`
- commands inside the `src` directory:
    - `make`: compile beamer slides
    - `make watch`: incremental compile beamer slides (watches for edits)
- Whenever a git tag is created, a GitHub release will be created and a pdf
  document will be generated in the GitHub release.


[compile-badge]: https://github.com/luiarthur/beamer-metro-template/actions/workflows/Compile.yml/badge.svg
[compile-yml]: https://github.com/luiarthur/beamer-metro-template/actions/workflows/Compile.yml
