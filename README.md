# MIS029 Chocolate Dashboard

<div align="center">

![Chocolate Dashboard banner](https://capsule-render.vercel.app/api?type=waving&color=timeGradient&height=180&section=header&text=Chocolate%20Dashboard&fontSize=48&fontAlignY=38&desc=R%20Flexdashboard%20analysis%20of%20global%20chocolate%20bar%20ratings%2C%20origins%2C%20ingredients%2C%20and%20quality%20patterns&descAlignY=58&descSize=17)

![R](https://img.shields.io/badge/R-Flexdashboard-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Plotly](https://img.shields.io/badge/Charts-Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Data](https://img.shields.io/badge/Data-Chocolate%20Ratings-8B5E3C?style=for-the-badge&logo=datatable&logoColor=white)

</div>

MIS029 Chocolate Dashboard is an R Markdown flexdashboard that explores chocolate bar ratings by company, origin, cocoa percentage, ingredient count, and tasting characteristics. It packages the final analysis as an interactive HTML dashboard.

![Code snapshot](assets/code-snapshot.png)

## Features

- Interactive flexdashboard layout
- Chocolate-themed visual styling
- Value boxes for headline metrics
- Rating, origin, manufacturer, and ingredient analysis
- Data table views for detailed inspection
- Standalone generated HTML output

## Quick Start

```bash
git clone https://github.com/mertefekurt/MIS029-Chocolate-Dashboard.git
cd MIS029-Chocolate-Dashboard
```

Open the rendered dashboard:

```text
docs/index.html
```

To rebuild from R:

```r
rmarkdown::render("MertEfeKurt_2307071061_Final.Rmd")
```

## Project Structure

```text
MertEfeKurt_2307071061_Final.Rmd   Source R Markdown dashboard
MertEfeKurt_2307071061_Final.html  Rendered dashboard artifact
docs/index.html                    Publishable dashboard page
chocolate.csv                      Chocolate bar rating dataset
_site.yml                          Site configuration
```

## Dataset

The dataset includes manufacturer, company location, review date, bean origin, bar name, cocoa percentage, ingredients, memorable characteristics, and rating fields.
