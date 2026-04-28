# math-solutions

Worked solutions to problems from *Gateway to Abstract Mathematics* (GIAM), authored in [Quarkdown](https://github.com/iamgio/quarkdown).

## Layout

```
main.qd               # landing page
solutions/*.qd        # one file per problem
image/                # shared assets
references/           # source PDFs (textbook + solutions manual)
references/legacy-pdfs/   # PDFs from the prior LaTeX/Tectonic flow
```

## Compile

```bash
quarkdown compile main.qd                       # → quarkdown-output/<name>/index.html
quarkdown compile solutions/giam-5-2-problem-5.qd --pdf
quarkdown compile main.qd -p -w                 # live preview + watch
```

## Install

```bash
brew install quarkdown-labs/quarkdown/quarkdown
```
