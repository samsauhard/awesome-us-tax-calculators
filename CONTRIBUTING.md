# Contributing to Awesome US Tax Calculators

Thank you for helping keep this resource accurate and useful! This list serves real people trying to understand and calculate their US taxes — your contributions directly improve their financial literacy.

---

## What We Welcome

### High-Value Contributions

- **Rate table updates** — IRS releases updated tax brackets, standard deductions, FICA wage bases each October/November. Contributions updating these for the new tax year are always welcome.
- **New open-source libraries** — If you find or build an open-source tax calculation tool that solves a real problem (e.g., self-employment tax, state-specific calculations), please add it.
- **Formula corrections** — If you find a mathematical error in any formula, please open an issue immediately with the correct formula and the official IRS source.
- **Code snippet improvements** — Better implementations of existing formulas (more accurate, more efficient, more readable) are welcome.
- **State tax resources** — Official state tax authority links, rate tables, and notable deductions.
- **New official IRS publications** — If the IRS releases relevant guidance not currently listed, please add it.

### What We Don't Accept

- Commercial product promotions without genuine educational value
- Broken or unmaintained links (check before submitting)
- Resources that duplicate existing entries without adding new value
- "Estimated" rate tables — all rates must be sourced from IRS official publications or Tax Foundation
- Content that could be construed as specific tax advice for individual situations

---

## How to Contribute

### Step 1: Check Existing Content

Before adding a resource, search the README to ensure it isn't already listed.

### Step 2: Open an Issue First (for major additions)

For adding entire new sections or resources you're uncertain about, open an issue to discuss before submitting a PR.

### Step 3: Submit a Pull Request

1. Fork the repository
2. Create a branch: `git checkout -b update/2027-tax-brackets`
3. Make your changes following the style guide below
4. Verify all links work
5. Submit PR with a clear description of what you changed and why

---

## Style Guide

### Adding a Resource

```markdown
- [Resource Name](https://url.com) — One-sentence description of what it contains and why it's useful.
```

- Keep descriptions factual, not promotional
- Use em dash (—) to separate name from description
- Link text should be the official resource name

### Adding a Code Snippet

- Include a comment citing the official source (IRS publication, year)
- Include at least one concrete example with expected output
- Use clear variable names (no single-letter variables except math formulas)
- Test your code before submitting

### Updating Rate Tables

When updating for a new tax year:
1. Update the table values
2. Update the `Source:` citation link to the new IRS Rev. Proc.
3. Update the **Last Updated** date in the README header
4. Verify the standard deductions, brackets, and FICA wage base are all consistent

---

## Accuracy Standards

All numerical data must be sourced from:
- IRS official publications (IRS.gov)
- Tax Foundation (taxfoundation.org)
- Congressional Budget Office (cbo.gov)
- State tax authority official websites

If a rate is disputed or in transition (e.g., TCJA provisions expiring), note this clearly.

---

## Code of Conduct

- Be respectful and constructive in all interactions
- Focus discussions on the technical and factual accuracy of content
- No tax advice to individuals — if someone asks for their specific tax situation, redirect them to a CPA

---

## Questions?

Open an issue with the `question` label.
