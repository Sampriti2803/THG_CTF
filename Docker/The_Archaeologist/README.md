# The Archaeologist

## Description

Welcome, Archaeologist!

We've unearthed a digital artifact — a mysterious container image. Our records suggest a valuable flag once existed inside it, but the creator attempted to erase all traces before publishing.

We suspect remnants of the flag still exist, buried deep within the layers of the image.
Your mission: **excavate the past and recover what was lost.**

---

## Category
- **Docker**

## Difficulty
- **Easy**

---

## Provided Files
- `ctf-archaeologist.tar`

---

## Instructions

You have been given a `ctf-archaeologist.tar` file.
First, load the image into your local Docker daemon:

```bash
docker load < ctf-archaeologist.tar
```

Once loaded, the image will appear locally.

🔎 **Your task: Find the flag hidden somewhere in the image's history.**

---

## Hint

> The final container might look clean… but an image’s past is permanent.

---

## Goal
Recover the hidden flag.
