# void-cipher-copyeditor

Copyediting framework for prose set in the Void Cipher universe.

World-building and style docs live in the shared [void-cipher-universe](https://github.com/binaryspartan/void-cipher-universe) submodule at `docs/universe/`.

## Structure

```
docs/
  COPY_EDIT_MODES.md   — defined copyediting passes and what each targets
  universe/            — submodule: canonical world_bible.md + style_guide.md
scenes/
  intro.md             — scene files
scripts/
  intro.md             — script files
```

## Setup

```bash
git clone --recurse-submodules https://github.com/binaryspartan/void-cipher-copyeditor.git
```

To sync universe docs after updates:

```bash
git submodule update --remote docs/universe
```
