# Victoria's Secret

## Description

Victoria is notorious for being forgetful. She encrypted the flag using XOR, but then worried she might lose the key.
So... she encrypted a reminder note to herself **using the exact same key**.

Fortunately for you, we intercepted both encrypted messages — and we already know what her reminder said.

Can you recover the flag she tried to protect?

---

## Provided

- **Ciphertext 1:**
```
2221240f01411f52010001001647002b6b2f5f5758000b
```

- **Ciphertext 2:**
```
12060d531b1e061216261c461119560d291957104e531f08
```

- **Known Plaintext Note:**
```
don'tloseyourkeyvictoria
```

---

## Hint

- *Reusing the same key with XOR is a terrible idea.*
- Try XORing the two ciphertexts together.
- What happens when you XOR that with the known plaintext?

---

## Goal

Recover the hidden flag.