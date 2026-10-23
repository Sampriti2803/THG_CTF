# Operation: Pixel Stream

## Description

Our agents intercepted a **burst transmission** from a suspected spy. The data is a mess, but intel suggests the spy was exfiltrating secret files by **hiding them in plain sight**.

They were heard muttering about *"a picture being worth a thousand words."*

We've captured the network stream. Can you find the secret?

---

## Category
- **Forensics / Networking / Steganography**

## Difficulty
- **Medium**

---

## Provided Files
- `challenge.pcap`

---

## Objective

Analyze the captured network stream, recover the files the spy sent, and uncover the secret hidden inside them.

Flag format: `THG{...}`

---

## Hints

- Files sent over the network can be pulled straight out of a capture. Wireshark can export them for you.
- Once you have the pictures, don't just look at them. Look **inside** them.

---

## Goal

Extract the exfiltrated images from the traffic and recover the hidden flag.
