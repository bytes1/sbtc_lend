# sBTC Lending Protocol

## Project Description

A decentralized lending and borrowing system for sBTC on the Stacks blockchain, allowing users to lend, borrow, deposit, and withdraw sBTC.

### Project Structure:

```
/contracts
├── lagoon.clar
/src
├── app
│   ├── borrow
│   │   └── page.js
│   ├── deposit
│   │   └── page.js
│   ├── lend
│   │   └── page.js
│   └── withdraw
│       └── page.js
└── ...
README.md
```

## Technical Requirements & Features:

### Smart Contract Development:

- **Clarity Smart Contracts**: The core logic is defined in `lagoon.clar`, which includes functions for depositing, borrowing, repaying, and claiming yield.
- **Error Handling & Security**: The contract includes basic assertions to ensure valid transaction conditions.

### Additional Features I Want:

- **Interest Rate Calculation**: A private function `calculate-accrued-interest` is included to calculate interest based on elapsed blocks.
- **sBTC Bridge Integration**: The frontend includes components for depositing BTC to mint sBTC (`DepositForm.js`) and withdrawing sBTC to BTC (`WithdrawForm.js`).
