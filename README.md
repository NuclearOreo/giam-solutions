# A Gentle Introduction to the Art of Mathematics

Worked solutions to problems from *A Gentle Introduction to the Art of Mathematics* (GIAM), authored in [Quarkdown](https://github.com/iamgio/quarkdown).

## Layout

```
solutions/
├── chapter-5/
│   ├── section-1/
│   │   └── problem-2.qd
│   └── section-2/
│       └── problem-5.qd
├── chapter-6/
│   └── section-1/
│       ├── problem-1.qd
│       ├── problem-2.qd
│       ├── problem-3.qd
│       └── problem-4.qd
└── images/
    └── chapter-6/
        └── section-1/
            ├── problem-2-graph.svg
            └── problem-3-graph.svg
references/               # source PDFs (textbook + solutions manual)
references/legacy-pdfs/   # PDFs from the prior LaTeX/Tectonic flow
quarkdown-output/         # compiled PDFs
```

## Compile

```bash
# Compile a single problem
quarkdown compile solutions/chapter-5/section-1/problem-2.qd --pdf

# Live preview + watch
quarkdown compile solutions/chapter-6/section-1/problem-3.qd -p -w
```

## Install

```bash
brew install quarkdown-labs/quarkdown/quarkdown
```
