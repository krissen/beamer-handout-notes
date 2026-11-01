# beamer-handout-notes

Give every beamer slide exactly one notes page in handouts, even when the
slide has no `\note`. With `pgfpages` layouts such as `2 on 1` this keeps
each slide above its own notes instead of letting the pairs drift apart.

## Usage

```tex
\usepackage{beamerhandoutnotes}
```

The package does nothing unless `\setbeameroption{show notes}` is active
and the notes are not shown on a second screen.

`krissen_handoutnotes` is a deprecated compatibility wrapper.

## Build and test

```sh
make check
make install
```

## Licence

LPPL 1.3c, see `LICENSE`.
