# Risk register

## Assets
Photos, signatures, protocol PDFs, user accounts, login tokens.

## Risks
| # | Threat | Asset | What I would do about it |
|---|--------|-------|--------------------------|
| 1 | Stolen or lost tablet | all local data | idle lock screen, short-lived tokens, sign-out wipes local data |
| 2 | Someone fakes a signature | signatures, protocols | one-time code at signing, store name, time and hash, lock the protocol after signing |
| 3 | A role gets permissions it should not have (e.g. photo-only user signs off) | protocols | server checks the permission on every write, plus a test that a photo-only user gets rejected when trying to sign |