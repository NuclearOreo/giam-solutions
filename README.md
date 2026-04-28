# math-solutions

Worked solutions to problems from *Gateway to Abstract Mathematics* (GIAM), authored in [Quarkdown](https://github.com/iamgio/quarkdown).

## Layout

```
solutions/*.qd            # one file per problem
references/               # source PDFs (textbook + solutions manual)
references/legacy-pdfs/   # PDFs from the prior LaTeX/Tectonic flow
```

## Compile

```bash
quarkdown compile solutions/giam-5-2-problem-5.qd --pdf
quarkdown compile solutions/giam-5-2-problem-5.qd -p -w   # live preview + watch
```

## Install

```bash
brew install quarkdown-labs/quarkdown/quarkdown
```
