<!-- # Präsentation -->

Präsentation

## Preview

```sh
quarto preview index.qmd   # live reload in browser
quarto render index.qmd    # build index.html
```

Speaker view: press `S` in the browser.

## Two versions, two repos

GitHub Pages serves one site per repo, so each version of the talk has its own repo. Both publish `index.html` from the root of `main` (legacy Pages build).

| Version | Local branch | Remote | Slides |
| --- | --- | --- | --- |
| 55 min, D³ Kongress, 11.11.2026 (with exercise 3: breakouts + pad) | `main` | `origin` → CorrelAid/power_der_prompts_d3 | <https://correlaid.github.io/power_der_prompts_d3/> |
| 50 min, Civic Data Lab Online Barcamp, 19.11.2026 (no exercise 3) | `cdl` | `cdl` → CorrelAid/power_der_prompts_cdl | <https://correlaid.github.io/power_der_prompts_cdl/> |

To update a site: check out its branch, `quarto render index.qmd`, commit `index.html` along with the sources, `git push`. Without a fresh render the site keeps showing the old slides. The welcome slide links to its own version's URL, so check that link when you copy changes between branches.

## License

Slides licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.de) (see [LICENSE](LICENSE)). Third-party content (photos, logos, illustrations, cited material) is excluded where marked.
