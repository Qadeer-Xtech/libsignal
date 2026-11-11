# How this package differs from upstream

`@qadeer-xtech/libsignal` 1.0.0 is a **faithful republish** of the
official **libsignal 6.0.0** (npm package `libsignal`), renamed so the
StableBail dependency tree carries a single publisher scope.

## Changed
- `package.json` — package name, version (1.0.0) and branding fields.
- `README.md` — title and install instructions.

## NOT changed — verified
Every code file is **byte-identical** to the official `libsignal@6.0.0`
npm tarball: all of `src/`, plus `index.js` and `index.d.ts`.
Verified with a full recursive diff and per-file `cmp` against the
official tarball on 2026-11-11. There are no code modifications of
any kind in this republish.

If a future version of this package ever modifies code, the change
will be listed here file by file.
