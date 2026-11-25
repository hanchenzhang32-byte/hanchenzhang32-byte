# Hi, I'm Hanchen 👋

Computer Science student at the University of Birmingham (BSc, 2025 to 2028). I like building software end to end: getting messy real data into a clean database, writing the code and tests around it, and putting a simple web app on top so people can actually use it.

## Featured projects

### [SME Review](https://github.com/hanchenzhang32-byte/sme-review-app)
A web app where analysts confirm or correct uncertain LLM tag mappings and see early warning alerts for 9,588 UK companies. Built with the Next.js App Router (server components and Server Actions), a PostgreSQL schema with constraints and transactions, and an audit log where rows are only ever added. 26 Vitest tests, including the review flow against a real Postgres database in memory.

`TypeScript` `Next.js` `React` `PostgreSQL` `Vitest`

### [UK SME Financial Health](https://github.com/hanchenzhang32-byte/uk-sme-financial-health)
Parses 84,151 real Companies House accounts (iXBRL) in Python, loads 2.3 million figures into PostgreSQL and maps 929 tags to 13 balance sheet items with SQL rules. Compares the rules with an LLM (Claude Haiku) on accuracy and how easy each is to audit, and adds a one year ahead distress prediction model.

`Python` `PostgreSQL` `SQL` `pytest` `Claude API` `scikit-learn`

### [Bankruptcy Prediction](https://github.com/hanchenzhang32-byte/polish-bankruptcy)
Tests whether gradient boosting beats the classic Altman Z' score on 43,405 Polish company records, with checks for duplicates, leakage from missing values and ratios that may use future data.

`Python` `scikit-learn` `pandas` `pytest`

### Earlier work
- [Java text adventure](https://github.com/hanchenzhang32-byte/java-text-adventure): command line game with a 5x5 map, inventory, keycard puzzles and JUnit tests.
- [Java coffee shop simulation](https://github.com/hanchenzhang32-byte/java-coffee-shop-simulation): object oriented resource simulation from coursework.
- [LSTM French to English translation](https://github.com/hanchenzhang32-byte/lstm-seq2seq-fr-en): PyTorch encoder and decoder built from scratch.
- [MNIST: MLP vs CNN](https://github.com/hanchenzhang32-byte/mnist-digit-classification): 99.04% vs 97.82% test accuracy on the same split.

## Tools

TypeScript · JavaScript · Python · Java · SQL · React · Next.js · PostgreSQL · Git · Vitest · pytest · JUnit
