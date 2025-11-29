# 100% Off Coupon

## Description

Acme Corporation has just launched their highly-anticipated **Acme Rocket Skates** — retail price: **$1000.00**.

Their store claims to use cutting-edge security, and all coupon functionality has been disabled to prevent exploits.

Your task: prove them wrong.

Somewhere in the checkout flow, a **client-side weakness** exists.  
If you can abuse it, you’ll unlock a 100% discount — and the flag.

---

## Category
- **Web / Client-Side Exploitation**

## Difficulty
- **Easy / Medium**

---

## Challenge URL

👉 https://100-off.vercel.app/

---

## Scenario

You’ll find:

- A disabled **coupon field**
- A greyed-out **Redeem** button
- A normal **Complete Purchase** button

Nothing appears editable — but the browser isn’t as secure as it pretends.

---

## Objective

Manipulate the client-side logic and purchase the Rocket Skates for **$0.00**.

Doing so will reveal the flag.

Flag format: `THG{...}`

---

## Hints

- **Hint 1:** If you can see it in the browser, you can change it.
- **Hint 2:** Disable doesn’t mean immutable.
- **Hint 3:** View → Developer Tools → Inspect Element.
- **Hint 4:** Hidden values aren’t secure values.

---

## Goal

Exploit the client-side logic and complete the purchase with a **100% discount** to recover the flag.
