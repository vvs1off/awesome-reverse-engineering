# Contributing

Thanks for helping make this list better. Quality matters more than quantity, so please read this before opening a pull request.

## What belongs here

- Legitimate, publicly available resources for reverse engineering and binary analysis: tools, learning material, CTF platforms, books, blogs, research and communities.
- Malware **analysis** resources (sandboxes, YARA, unpacking tutorials) are welcome.

## What does not belong here

- Malware samples or "how to build malware" guides.
- Tools whose primary purpose is attacking third-party systems.
- Pirated material, cracked software, license bypasses or keygens.
- Low-quality blogspam, thin aggregators and dead or abandoned projects.
- Self-promotion without clear community value. If you maintain the project, say so in the pull request and let maintainers judge it on merit.

## Entry format

One entry per line, in this exact format:

```markdown
- [Name](https://official.example/) - Short, one-line description ending with a period.
```

Rules:

1. Link to the **official** project page or primary source, not a mirror or a third-party article about it.
2. Keep the description to one line, start with a capital letter, end with a period, and do not repeat the name.
3. Keep entries **alphabetical** within a section (case-insensitive).
4. Add the entry to the single most fitting section. Tools that clearly belong in several sections may be listed in each, but keep the description specific to that section.
5. Books: use the form `[Title](publisher-or-official-link) - Author. Description.` Link only to the publisher or the author's site, never to pirated copies.
6. Use HTTPS links. Every link must return HTTP 200; no dead links.
7. No trailing whitespace and no duplicated entries within a section.

## Proposing a new section

Open an issue first and explain why the existing sections do not fit. New sections should hold at least five good entries.

## Submitting a pull request

1. Fork the repository and create a branch.
2. Edit `README.md` following the rules above.
3. Open a pull request with a short title such as `Add <Name>` and one sentence on why it belongs.
4. The link checker runs automatically on every pull request. Fix any failure it reports.

By contributing, you agree to release your contribution under [CC0 1.0](LICENSE).
