# Foster Rx Systems

Evidence assessments for drug assets, built from public sources by methods registered in advance, and issued as signed records.

Foster Rx builds [Thesis Rx](https://thesisrx.ai), a platform that assembles the evidence on a drug asset into one record with the same sections every time. Each section states what was found, what was looked for and not found, and which sources it rests on. Every record is signed, so a reader can confirm that the file in front of them is the file that was issued.

## Check a record

- **In a browser:** [fosterrx.com/verify](https://fosterrx.com/verify). No account is needed.
- **Public signing key (Ed25519):** [`/.well-known/angis-signing-key-v1.pub`](https://fosterrx.com/.well-known/angis-signing-key-v1.pub)
- **Index of the ways to check a record:** [`/.well-known/fosterrx-verify.json`](https://fosterrx.com/.well-known/fosterrx-verify.json)

## Public repositories

| Repository | What it is |
|---|---|
| [fosterrx-prediction-register](https://github.com/Foster-Rx/fosterrx-prediction-register) | Forecasts on clinical, regulatory and coverage events. Each is entered with a probability and a resolution rule before the outcome is known, hash-chained and timestamped, then scored when the outcome lands, misses included. A research calibration record. Not investment advice. |
| [fosterrx-verify-mcp](https://github.com/Foster-Rx/fosterrx-verify-mcp) | A read-only connector that lets an AI assistant check a signed record against the public key and read exactly what was signed. It uses public material only and holds no credential. |

## Contact

- General: info@fosterrx.com
- Security reports: security@fosterrx.com
- Data requests: data@fosterrx.com
- [fosterrx.com](https://fosterrx.com) · [thesisrx.ai](https://thesisrx.ai) · [LinkedIn](https://www.linkedin.com/company/foster-rx-systems)

---

Foster Rx Systems Inc.
