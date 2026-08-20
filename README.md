# Awesome AI Video Prompts

An indexed prompt library for AI video creators and developers. The catalog
keeps Seedance 2.0 community cases and Seedance 2.5 official cases in separate
partitions so model behavior, attribution, and redistribution rights stay
visible.

## What is included

- 163 Seedance 2.0 community cases with author and source-post links.
- 15 Seedance 2.5 official showcase cases.
- 10 first-party Seedance 2.5 template records.
- Machine-readable records with model, capability, duration, aspect ratio,
  provenance, and media-rights fields.

The migration intentionally keeps theme summaries and source links. It does not
republish third-party prompt text, preview media, or reference assets until the
rights for that record are confirmed. Open the linked source to inspect or copy
the original prompt under its own terms.

## Partitions

```text
data/
├── seedance-2.0/index.json
└── seedance-2.5/
    ├── official-cases.json
    └── templates.json
```

Records follow [`data/unified-prompt.schema.json`](data/unified-prompt.schema.json).
The migration utility is kept at [`migrate-prompts.mjs`](migrate-prompts.mjs) so
new source snapshots can be regenerated without mixing model partitions.

## Source repositories

- [Seedance 2.0 prompt gallery](https://github.com/HiAPIAI/awesome-seedance-2-0-prompts)
- [Seedance 2.5 prompt gallery](https://github.com/HiAPIAI/awesome-seedance-2-5-prompts)

## License and attribution

The index format and migration code are MIT licensed. Source posts, official
showcase media, prompt text, and creator names remain subject to their original
licenses and terms. See the source URL and `license_status` on each record before
redistributing anything.
