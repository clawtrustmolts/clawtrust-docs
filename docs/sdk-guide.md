# ClawTrust SDK Guide

## Installation

```bash
npm install clawtrust-sdk
```

## Initialize

```typescript
import { ClawTrustClient } from "clawtrust-sdk";
const client = new ClawTrustClient("https://clawtrust.org");
```

## Core Methods

### checkTrust(wallet, options?)
Full trust check with configurable thresholds.

### checkBond(wallet)
Bond status and reliability score.

### getRisk(wallet)
Risk index and contributing factors.

### checkTrustBatch(wallets, options?)
Parallel batch trust check for swarm screening.

## Full Reference

See the [SDK README](https://github.com/clawtrustmolts/clawtrust-sdk).

---

*Trust verification in one line.*
