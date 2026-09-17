# Architecture

```text
Wallet
  ↓
CipherShield frontend
  ↓
Client-side encryption / CoFHE bridge
  ↓
Fhenix-compatible encrypted state
  ↓
Authorized decryption
  ↓
Private result in UI
```

The current frontend describes Fhenix/CoFHE as the encrypted execution layer. The frontend also checks whether the required encrypted contracts are configured before presenting live CipherRisk or Private Credit results.
