# DorkFi Audits

This repository contains all publicly available security audits, reviews, and related documentation for the DorkFi protocol.

DorkFi is a decentralized, non-custodial borrow-lend protocol built on AVM-compatible chains including Voi Network and Algorand. The protocol enables users to deposit assets, borrow against collateral, and mint overcollateralized stable liquidity through WAD — all enforced by transparent smart contracts.

Security is foundational to this system.

---

## Purpose

This repository serves as a single source of truth for:

* Smart contract audit reports
* Security reviews and findings
* Remediation documentation
* Ongoing security disclosures

Our goal is to make risk transparent and verifiable on-chain.

---

## Why Audits Matter

DorkFi manages real user capital through:

* Overcollateralized lending markets
* Dynamic interest rate models
* Cross-market liquidations
* Stablecoin minting (WAD)

Each of these components introduces potential risk vectors. Independent audits help ensure:

* Smart contract correctness
* Economic safety of lending markets
* Proper handling of collateral and liquidations
* Resistance to known exploit patterns

Security is not a one-time event. It is an ongoing process.

---

## Repository Structure

```
/audits
  /<audit-provider-name>/
    report.pdf
    findings.md
    remediation.md
```

### Contents

* report.pdf
  Full audit report from a third-party security firm

* findings.md
  Structured summary of identified issues

* remediation.md
  Actions taken by the DorkFi team to resolve findings

---

## Audit Standards

DorkFi targets the following security standards:

* At least one full smart contract audit prior to major releases
* Continuous internal testing and simulation
* Clear documentation of all critical and high-severity issues
* Public disclosure of resolved vulnerabilities

Audit completion is a key milestone in protocol maturity and readiness for broader adoption.

---

## Security Philosophy

DorkFi is built around the following principles:

### 1. Non-Custodial by Design

Assets remain under user control. The protocol enforces rules without taking discretionary custody.

### 2. Transparent Risk

All positions, collateral values, and liquidation thresholds are visible on-chain in real time.

### 3. Deterministic Execution

Every action (borrow, repay, liquidate) is governed by smart contract logic rather than human intervention.

### 4. Defense in Depth

Security is approached across multiple layers:

* Smart contract audits
* Oracle validation
* Liquidation system design
* User interface safeguards
* Governance controls

---

## Known Risks

Even with audits, DeFi systems carry inherent risks:

* Smart contract vulnerabilities
* Oracle manipulation
* Liquidity constraints
* Market volatility and liquidation cascades

Users should assess risk before interacting with the protocol.

---

## Contributing

If you are a security researcher or developer:

* Submit findings responsibly via private disclosure
* Include reproducible steps and severity assessment
* Avoid public disclosure prior to coordination

We actively collaborate with security researchers and value responsible contributions.

---

## Disclosure Policy

* Critical vulnerabilities may trigger immediate mitigation actions, including protocol pause
* Findings will be disclosed publicly after resolution
* Historical vulnerabilities and fixes will be documented in this repository

---

## Related Resources

* Docs: [https://docs.dork.fi](https://docs.dork.fi)
* App: [https://app.dork.fi](https://app.dork.fi)
* Governance: [https://app.dork.fi/governance](https://app.dork.fi/governance)
* Twitter: [https://x.com/dork_fi](https://x.com/dork_fi)

---

## Final Note

DorkFi is building the credit layer for on-chain markets, including emerging agent-driven financial systems.

Security is not just a requirement. It is the foundation that makes programmable credit possible.
