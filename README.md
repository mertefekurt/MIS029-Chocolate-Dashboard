# MIS029 Chocolate Dashboard

![Chocolate dashboard cover](assets/readme-cover.svg)

An R Markdown flexdashboard exploring chocolate bar ratings by origin, manufacturer, cocoa percentage, ingredient count, and tasting notes.

## Dashboard

Open the rendered version from `docs/index.html`, or rebuild the source file in RStudio.

```r
rmarkdown::render("MertEfeKurt_2307071061_Final.Rmd")
```

## What it covers

- Rating distributions and top performers
- Company and bean-origin comparisons
- Cocoa percentage and ingredient patterns
- Interactive tables for detailed inspection
- Standalone HTML output for sharing

## Files

```text
MertEfeKurt_2307071061_Final.Rmd   source dashboard
MertEfeKurt_2307071061_Final.html  rendered dashboard
docs/index.html                    publishable page
chocolate.csv                      source dataset
_site.yml                          site configuration
```
