# Contribution guide

Thank you for helping people find tools for useful work without an internet connection.

## Scope

Suggest maintained desktop applications that complete a clearly described task locally after setup. Tools can be open source or proprietary; describe that accurately. Server administration platforms, generic web links and cloud-only products belong in other lists.

## Before submitting

1. Check that the tool is not already listed and that its category fits.
2. Read the official documentation and check whether the source repository is archived, if one exists. Do not infer inactivity from a mirror alone.
3. State the exact offline task, supported desktop platforms, required downloads and optional network services.
4. Give an official source for the offline claim. If you tested it, record the version, OS, steps and result. Otherwise say documentation review only.
5. Explain why it adds a useful option rather than another near-identical product.

## Entry format

Follow this format in the relevant category:

```markdown
- [Name](https://example.com/) - A specific, neutral description. `Windows, macOS, Linux`.
```

Replace the sample name and URL with the real resource. Keep the description concise, start it with a capital letter and end the entry with a period. Link to the official site or canonical repository. Do not use affiliate links, unverifiable superlatives or star counts in descriptions.

Update both language readmes and add the evidence to [docs/source-review.md](docs/source-review.md) and [docs/catalog.json](docs/catalog.json). If you cannot translate, mention that in your pull request so the maintainer can help. Keep the category order and existing readme layout.

## Corrections and removals

Open a correction issue when a link breaks, a product becomes cloud-dependent or an offline claim is too broad. Include the affected entry and a primary source. Prefer removing or narrowing an unsupported claim rather than adding an explanation that contradicts it.

## AI assistance

AI assistance is allowed when disclosed. Verify factual claims against primary sources and distinguish actual tests from proposed instructions. Do not represent generated content as personal testing or as acceptance by the upstream Awesome index.

## Review checklist

- Both readmes contain the same resources and categories.
- Relative links, images and Contents anchors resolve.
- Required assets and optional online features are clear.
- The source review states what was checked and what was not.
- Contributions contain only original or appropriately licensed text.

By contributing original list content, you agree to release that contribution under this repository's CC0 dedication. Software linked here retains its own license.
