# Foster Rx Systems

**Certified assessments for life-sciences IP and capital decisions — signed by a named reviewer, checkable by anyone, free to verify, permanently.**

Every Foster Rx certificate is Ed25519-signed under a published trust anchor and verifies at a public URL with no account, no fee, and no Foster Rx server in the path. Trust derives from the mathematics, not from us.

## Verify a certificate

- **In your browser:** [fosterrx.com/verify](https://fosterrx.com/verify)
- **Trust anchor (Ed25519 public key):** [`/.well-known/angis-signing-key-v1.pub`](https://fosterrx.com/.well-known/angis-signing-key-v1.pub) — fingerprint is SHA-256 over the DER SubjectPublicKeyInfo
- **Machine index of all verification paths:** [`/.well-known/fosterrx-verify.json`](https://fosterrx.com/.well-known/fosterrx-verify.json)
- **For AI assistants:** an open Model Context Protocol connector lets any agent verify a certificate cryptographically and read its signed record

Anything a Foster Rx page claims can be re-derived from the signed bytes. Nothing needs to be believed — it can be checked.

## What lives in this organization

- **[fosterrx-prediction-register](https://github.com/Foster-Rx/fosterrx-prediction-register)** — our public, hash-chained, OpenTimestamps-anchored prediction register: forward forecasts on clinical, regulatory, and coverage outcomes with probabilities stated and resolution criteria fixed at entry, scored as outcomes land — including the misses. A track record cannot be backdated, so we started ours in public.

> *A research calibration record. Forecasts about clinical, regulatory, and coverage events, made to be scored. Not investment advice; not a solicitation.*

## Contact

[fosterrx.com](https://fosterrx.com) · [LinkedIn](https://www.linkedin.com/company/foster-rx-systems) · gabrielle@fosterrx.com

---

Foster Rx Systems Inc. · Non-confidential · Patent Pending No. 19/459,855
