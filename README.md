# The Just-Bound
## A Structural Theory of Normative Legitimacy and Domination
### by Neron Dakos

> **That which permits no domination cannot be undone.**

This repository contains the original and signed versions of the manifesto *The Just-Bound*.
It proposes a structural framework for understanding normativity, legitimacy, and domination — where rationality, universality, and coherence are the only defenses against tyranny.

The author, **Neron Dakos**, has cryptographically signed each release using GPG to prove authorship and date of creation. All versions remain archived and verifiable.

---

## Current Version

- **Version**: `v2` (2025-03-30)
- **File**: [`the-just-bound-manifesto.md`](the-just-bound-manifesto.md)
- **Signature**: [`the-just-bound-manifesto.md.asc`](v2/the-just-bound-manifesto.md.asc)

To verify:
```bash
gpg --import neron-dakos-public.asc
gpg --verify v2/the-just-bound-manifesto.md.asc
```

---

## Version History

All versions are preserved and cryptographically signed:

- [Version History (VERSIONS.md)](VERSIONS.md)
- Previous version: [`v1/the-just-bound-manifesto.md`](v1/the-just-bound-manifesto.md)
- [Signature (asc)](v1/the-just-bound-manifesto.md.asc)

---

## Public Key

The author’s GPG key is available for signature verification:

- [`neron-dakos-public.asc`](neron-dakos-public.asc)

---

## Optional Detached Verification

If you prefer to verify the `.sig` files instead of the inline `.asc`, you can use:

### v2 Verification

```bash
gpg --import neron-dakos-public.asc
gpg --verify v2/the-just-bound-manifesto.sig v2/the-just-bound-manifesto.md
```

### v1 Verification

```bash
gpg --import neron-dakos-public.asc
gpg --verify v1/the-just-bound-manifesto.sig v1/the-just-bound-manifesto.md
```

If the signature is valid you will see:

```
Good signature from "Neron Dakos"
```

---

## Directory Layout Reference (for clarity)

```plaintext
/v1/
  ├── the-just-bound-manifesto.md
  ├── the-just-bound-manifesto.md.asc
  └── the-just-bound-manifesto.sig

/v2/
  ├── the-just-bound-manifesto.md
  ├── the-just-bound-manifesto.md.asc
  └── the-just-bound-manifesto.sig
