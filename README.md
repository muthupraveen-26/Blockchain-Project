# 🗳️ Blockchain-based Voting System (Python)

This project is a **basic blockchain implementation in Python** that simulates a voting system.  
Each vote is stored as a block in the blockchain, ensuring immutability and transparency.


## 🚀 Features
- Simple blockchain structure (`Block` + `Blockchain` classes).
- Votes are stored securely using SHA-256 hashing.
- Each block contains:
  - Index
  - Previous Hash
  - Timestamp
  - Vote Data (`VoterID → Candidate`)
- Validation method to check blockchain integrity.
- Demonstrates tamper-proof vote recording.

