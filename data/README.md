### [data](./data)
* [ecology_statistical_ecology_classification_v01.csv](./data/ecology_statistical_ecology_classification_v01.csv) File with data from literature view

| Variable name | Meaning |
|---------------|---------|
| authors | Author list of paper |
| title | Title of paper |
| year | Year of publication |
| volume | Volume of publication |
| issue | Issue of publication |
| start_page | Starting page number of publication |
| end_page | Ending page number of publication |
| citations | Number of citations the paper has |
| q75_citations | The 75th percentile of number-of-publications for the journal for the given year |
| prop_rank | Proportional rank citations, calculated as rank(citations) / max(rank(citations)) |
| omit | Each paper is coded as omit (e.g., erratum) or keep (research article) |
| statistical | Yes/no, does the paper have a focus on statistical ecology |
| individual | 1/0 Is the paper focused on models for individuals (only for statistical ecology papers with citations > q75_citations) |
| population | 1/0 Is the paper focused on models for populations (only for statistical ecology papers with citations > q75_citations) |
| community | 1/0 Is the paper focused on models for communities (only for statistical ecology papers with citations > q75_citations) | 
| ecosystem | 1/0 Is the paper focused on models for ecosystems (only for statistical ecology papers with citations > q75_citations) |
| spatial | 1/0 Is the paper focused on models for space (only for statistical ecology papers with citations > q75_citations) |
| validation_selection | 1/0 Is the paper focused on model validation or selection (only for statistical ecology papers with citations > q75_citations) |
| tools_practices | 1/0 Is the paper focused on general modeling tools or best practices (only for statistical ecology papers with citations > q75_citations) |
