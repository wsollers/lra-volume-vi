# lra-volume-vi

**Volume VI: Algebra** — Overleaf-ready standalone repository.

## Structure

```text
volume-vi.tex          — full-volume root (Overleaf main document)
volume-vi-<book>.tex   — individual book roots
common/               — shared LaTeX infrastructure supplied by lra-common; ignored here
bibliography/         — per-book bibliography shards
volume-vi/             — all LaTeX content for this volume
```

## Overleaf

Upload or checkout `common/` beside this repository's TeX roots, then set the main document to `volume-vi.tex` for the full volume or to one of the book roots:

```text
volume-vi-algebra.tex, volume-vi-lattice-and-order-theory.tex, volume-vi-linear-algebra.tex
```

`common/` is ignored by git in this volume repo; edit shared infrastructure in `lra-common`.

## Building locally

```powershell
python F:\repos\lra-governance\tools\governance\build_volume_docker.py --root F:\repos\lra-volume-vi --common-root F:\repos\lra-common
```
