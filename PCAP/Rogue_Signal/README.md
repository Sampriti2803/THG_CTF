# Rogue Signal

## Description

One of our junior analysts — **Bob** — was recently terminated for… questionable behavior  
(mainly insisting that **nano is better than vim**).

Before leaving, we suspect he exfiltrated sensitive data. His workstation logs are spotless,  
but we managed to capture **DNS traffic** from his last day.

The rest of the team insists it looks normal — *just standard DNS requests* — but something feels off.  
Bob was clever… maybe **too clever**.

Somewhere in that traffic, the stolen data is hidden.

Your job: **extract it.**

---

## Category
- **Forensics / Networking / Steganography**

## Difficulty
- **Medium**

---

## Provided Files
- `signal.pcap`

---

## Objective

Analyze the captured DNS traffic and recover the stolen data.

Flag format: `THG{...}`

---

## Hints

- DNS isn't always just domain lookups — sometimes **the domain *is* the payload.**
- Look for patterns rather than destinations.

---

## Goal

Recover the hidden flag from the DNS exfiltration data.
