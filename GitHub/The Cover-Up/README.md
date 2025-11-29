# The Cover-Up

## Description

This repository looks clean. Almost too clean. A developer mentioned a **'small security fix'** in a panic this morning, but now their tracks seem to be covered. I can't find any secrets in the current code, but I have a feeling they're still in here... somewhere.

---

## Category
- **GitHub / OSINT**

## Difficulty
- **Easy / Medium**

---

## Provided Links
👉 https://github.com/thehackersgauntlet/blog-website

---

## Scenario

The repository appears clean:

- No .env

- No API keys

- No hard-coded tokens

- No suspicious files

At first glance, it's a normal blog website with nothing unusual.

But Git remembers everything.

Your mission is to **catch the secret the developer tried to hide**.

Somewhere in that history lies the flag.

---

## Goal

Dig through the Git history, uncover the mistakenly committed secret, and retrieve the flag.

Flag Format: `THG{flag}`

