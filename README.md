# Vibe Note-Taking Example

A small, fictional Markdown knowledge base that shows a low-friction capture workflow:

1. Capture a rough thought, typed or dictated.
2. Route it through maps, not a hard-coded path list.
3. Read the destination note before updating it.
4. Keep the map current when the structure changes.

The goal is not a perfect taxonomy. The goal is to make a thought easy to save now and useful later.

## Start here

- Browse the [root map](knowledge-base/personal-brain._map.md).
- Use the generic [`take-note` skill](.github/skills/take-note/SKILL.md) with an agent that supports skills.

## Repository layout

```text
knowledge-base/
├── 00-inbox/       # temporary captures when no stable home is clear
├── 20-projects/    # active efforts with an outcome
├── 40-areas/       # ongoing responsibilities and interests
└── 50-resources/   # reference material
```

Every content directory has a `dirname._map.md` file. Maps are the navigable index of the knowledge base. They let folders evolve without forcing a person or an agent to memorize paths.

## Make it yours

Copy this repository, rename the folders to fit your life, and start with only a few notes.

## License

MIT. See [LICENSE](LICENSE).
