# AGENTS.md

Single source of instructions for all AI agents working in this repository.

## Project summary

SediksiDAO - Decentralized Voices is a **documentation-only proposal** for turning
[Sediksi](https://sediksi.com) into a community-governed media platform (DAO).
It was written in August 2024 as a submission to the Movement Web3 builder program.

Status: **concept / proposal**. There is no implementation, and the chain,
storage, and framework have **not been decided**.

## Stack

- Markdown documents only. No code, no build, no dependencies.
- Nothing to install. There are no dev, build, lint, or test commands.
- Preview by reading the Markdown on GitHub or in any Markdown viewer.

## Structure

```
README.md                 Overview, context, next steps, open questions, contact
LICENSE                   CC BY 4.0 notice (full legal code linked)
docs/
  introduction/           Mission and long-term vision
  governance/             Governance model, voting, proposals
  content_management/     Content flow, storage options, curation
  incentivization/        Token reward ideas
  transformation/         Steps from WordPress media to a DAO
  roadmap/                Phased milestones
  glossaries.md           Terms (Web3, DAO, governance)
  unforeseen_challenges_and_opportunities.md
```

## Writing conventions

- Language: English, plain and concise.
- Keep the README "Guidelines and Resources" links in sync when adding,
  moving, or renaming files in `docs/`.
- Use relative links between documents.
- Files use LF in the repository (Git may check them out as CRLF on Windows).
- Mark ideas as proposals or options, not as decisions. Specific networks
  (Ethereum, Polygon, Movement) or IPFS may appear only as examples.
- Commit messages follow Conventional Commits (`docs: ...`, `chore: ...`).

## License

Documentation is licensed under CC BY 4.0. The Sediksi name and logo are
trademarks of Sediksi and are not covered by the license.

## Do not

- Do not add code, packages, config, or scaffolding unless the maintainer
  explicitly asks for an implementation.
- Do not claim a tech stack, chain, token, or timeline that has not been decided.
- Do not write personal data (names of contributors, emails, phone numbers,
  ID numbers) or internal Sediksi data into any file.
- Do not commit secrets, `.env` files, or wallet keys.
- Do not change the license or remove the trademark notice.
