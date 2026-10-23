# Reader's Guide — javascript-algorithms

## What this project is

**JavaScript Algorithms and Data Structures** is a study collection of the
classic algorithms and data structures, each implemented in JavaScript with
explanations, complexity notes and a full test suite — built for learning and
interview preparation rather than for production use. Every entry can be read
on its own, and most link out to further reading and videos.

## How the content is organised

- `src/data-structures/` — one folder per structure, each with its own README
  and tests: `bloom-filter`, `deque`, `disjoint-set`, `doubly-linked-list`,
  `graph`, `hash-table`, `heap`, `linked-list`, `lru-cache`,
  `priority-queue`, `queue`, `stack`, `tree`, `trie`.
- `src/algorithms/` — one folder per problem family: `cryptography`,
  `graph`, `image-processing`, `linked-list`, `math`, `ml`, `search`,
  `sets`, `sorting`, `stack`, `statistics`, `string`, `tree`,
  `uncategorized` — each family holding the individual algorithms, their
  READMEs and their `__test__` suites.
- `src/playground/` — a scratch file (`playground.js` plus its test) for
  experimenting with the structures and algorithms yourself.
- `src/utils/` — shared helper code used across implementations.
- [`README.md`](README.md) — the master index: **Data Structures** and
  **Algorithms** sections linking every entry, **How to use this repository**,
  and **Useful Information** (references and big-O notes). The index is
  translated into 18 more languages (`README.ko-KR.md`, `README.zh-CN.md`,
  `README.ru-RU.md`, …) alongside the English original.

## How to use it

1. Browse the README index (or the `src/` folders) to the structure or
   algorithm you want; read its folder README for the explanation.
2. `npm install`, then run the tests to watch behaviour: `npm test`, or a
   single suite with `npm test -- 'LinkedList'`. Lint with `npm run lint`.
3. Try variations in `src/playground/playground.js` and test them with
   `npm test -- 'playground'`.

## About this standalone edition

This repository is a standalone edition of
[trekhleb/javascript-algorithms](https://github.com/trekhleb/javascript-algorithms),
converted from a fork into its own repository and enhanced in place. See
[`ENHANCEMENTS.md`](ENHANCEMENTS.md) for what this edition adds and
[`CHANGELOG.md`](CHANGELOG.md) for its version history (v1.0.0 upstream
baseline, v1.1.0 enhancements). All original work belongs to Oleksii Trekhleb
and the upstream contributors; licence MIT (see `LICENSE`).
