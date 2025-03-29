# The Just-Bound
## A Structural Theory of Normative Legitimacy and Domination
### by Neron Dakos

> **That which permits no domination cannot be undone.**

This repository contains the original, signed version of the manifesto *The Just-Bound*.
It proposes a structural framework for understanding normativity, legitimacy, and domination — where rationality, universality, and coherence are the only defenses against tyranny.

The author, **Neron Dakos**, has cryptographically signed the text using GPG to prove authorship and date of creation. The public key is included below.

---

## Authorship Verification

This manifesto was signed on **2025-03-29** using the GPG key of **Neron Dakos**.

You may verify authorship using either the inline-signed file or the detached signature.

### Files

- `the-just-bound-manifesto.md` — Plaintext Markdown
- `the-just-bound-manifesto.md.asc` — Inline GPG-signed version
- `the-just-bound-manifesto.sig` — Detached signature
- `neron-dakos-public.asc` — Author's GPG public key

---

### To verify the inline-signed version:

```bash
gpg --import neron-dakos-public.asc
gpg --verify the-just-bound-manifesto.md.asc
```

### To verify the detached signature:

```bash
gpg --import neron-dakos-public.asc
gpg --verify the-just-bound-manifesto.sig the-just-bound-manifesto.md
```

If the signature is valid you will see

```
Good signature from "Neron Dakos"
```

This confirms that the text was authored and signed by the original keyholder.
