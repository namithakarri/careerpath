# Contributing to CareerPath

Thank you for your interest in contributing to CareerPath!

## Development Guidelines

1. **Commit Message Format**:
   - `feat: add qualification explorer`
   - `feat: add job matching engine`
   - `feat: add skill gap analyzer`
   - `feat: add application tracker`
   - `fix: authentication validation`

2. **Branching Strategy**:
   - `main`: Production-ready release branch
   - `develop`: Ongoing feature integration
   - `feature/<name>`: New feature branches

3. **Data Quality Standards**:
   - Real-world company information must be verified with sources (`VERIFIED`).
   - Demo data must be explicitly labeled `DEMO DATA`.
   - Never fabricate hiring claims or guaranteed salary figures.

4. **Code Quality**:
   - Parameterized SQL queries for all database transactions.
   - Strictly avoid plaintext passwords (bcrypt hashing required).
   - Maintain accessibility standards (ARIA, high contrast, responsive UI).
