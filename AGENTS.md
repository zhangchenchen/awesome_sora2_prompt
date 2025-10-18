# Repository Guidelines

## Project Structure & Module Organization
This repository is Markdown-first with prompts and guides stored by topic.
- `README.md` summarizes the catalog; `CONTRIBUTING.md` holds the submission template and review checklist.
- Prompt collections in `prompts/` stay grouped by theme—append rows under the existing heading and mirror the table layout.
- Deep-dive explainers belong in `guides/`; keep filenames lowercase and hyphenated.

## Build, Test, and Development Commands
- `git clone https://github.com/zhangchenchen/awesome-sora2-prompt.git` to start a local workspace.
- `markdownlint "**/*.md"` (after `npm install -g markdownlint-cli`) enforces formatting.
- `npx markdown-link-check README.md` is optional but catches broken outbound links.

## Coding Style & Naming Conventions
Write in clear, instructional English with compact paragraphs. Use sentence case for prompt headings (e.g., `### Neon rain market`). Follow the template in `CONTRIBUTING.md`, adding the Five Pillars table when it clarifies intent. Keep filenames descriptive, lowercase, and hyphen-separated, and use descriptive link text instead of raw URLs.

## Testing Guidelines
Preview Markdown locally so tables render and code fences close properly. Verify every video, image, and social link before submitting. For new prompts, confirm the Five Pillars breakdown matches the narrative and mark attribution or engagement fields as unavailable when needed. Only attach assets you are licensed to share.

## Commit & Pull Request Guidelines
Adopt Conventional Commit prefixes—recent history uses `feat:`, `docs:`, and `refactor:`. Keep commits focused on one prompt or guide change. Pull requests should restate the prompt or guide name, summarize key additions, link related issues, and supply video proofs when possible. Tag reviewers if timing is critical or multiple files are touched.

## MCP Tooling for Agents
Preferred MCP servers:
- `search` (e.g., web-search or brave-search) for sourcing public references during curation.
- `fetch`/`http` for API calls or metadata checks when validating links.
- `playwright` for rendering dynamic pages or capturing scripted walkthroughs.
Use them only when sandbox and policy settings permit network access, and document findings in the relevant prompt entry.

## Attribution & Responsible Use
Always credit original prompt authors and cite the platform where the content surfaced. Flag sensitive themes and avoid disallowed content per the quality standards. When uncertain, open a draft PR or discussion so maintainers can advise before publishing.
