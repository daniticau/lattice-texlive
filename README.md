# lattice-texlive

TeX Live 2026 and the BusyTeX engine, compiled to WebAssembly, split into 20 MB parts for static hosting. The Lattice web app at lattice.daniticau.com loads them from this repo's GitHub Pages site. Its service worker joins the parts back into whole files, as `parts.json` lists them.

The files come unchanged from the `assets-v1.4.1` release of [TeXlyre/texlyre-busytex](https://github.com/TeXlyre/texlyre-busytex), which is licensed AGPL-3.0. Its source, and the TeX Live and BusyTeX sources it builds on, are at that link. TeX Live's own packages keep their own licenses.
