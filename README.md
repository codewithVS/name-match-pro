# @vspro/name-match-pro

A robust name matching library for Node.js and TypeScript that combines multiple strategies — initials handling, token swapping, fuzzy similarity, and prefix normalization — for accurate name matching in fintech, insurance, CRM, and other applications.

[![npm version](https://img.shields.io/npm/v/@vspro/name-match-pro)](https://www.npmjs.com/package/@vspro/name-match-pro)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

---

## Features

- **Multi-strategy Matching**: Combines exact match, initials handling, swapped tokens, and fuzzy Levenshtein similarity.
- **Prefix Normalization**: Removes common prefixes like Mr, Mrs, Dr, Shri, Smt, etc.
- **Initials Expansion & Merge**: Converts `K.S.` → `KS`, `KS` → `K S`, or merges initials intelligently.
- **Swapped Tokens Handling**: Recognizes names in different order (e.g., "K S Gowri" → "Gowri K S").
- **Scoring System**: Returns percentage similarity and descriptive remarks: Exact Match, High Similarity, Possible Match, Low Match.
- **Fuzzy Matching**: Handles typos and variations using Levenshtein distance.
- **Node.js & TypeScript Ready**: Works in JS, TS, and frameworks like Next.js.

---

## Installation

Install via npm:

```bash
npm install @vspro/name-match-pro# name-match-pro
