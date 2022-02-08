---
title: R data package from Monduli, Tanzania
description: This is the first release of my field data from Tanzania
date: "2020-08-08T19:47:09+02:00"
jobDate: 2020
work: [fieldwork, data, R package]
techs: [R]
thumbnail: tanzania-dataset/monduli-photo.jpg
projectUrl: https://github.com/alightner/monduliDataset
---

This data package is linked to the publication, [Acculturation and market integration are associated with greater trust among Tanzanian Maasai pastoralists](https://www.cambridge.org/core/journals/evolutionary-human-sciences/article/acculturation-and-market-integration-are-associated-with-greater-trust-among-tanzanian-maasai-pastoralists/521EC67618FD163A67D8FAC0D5B56B86). All data are anonymized and a low risk of identifiability was tested for an confirmed using [`sdcMicro`](https://cran.r-project.org/web/packages/sdcMicro/index.html).  

To ensure that certain participants were not identifiable, we made two key transformations: (1) ages > 80 years were truncated at 80, and (2) participants with > 40 children were truncated at 40.

The confirmatory results in the research article that's linked to this package should remain unaffected by this change, because neither of these variables are included in our main tests. They are, however, included in our exploratory results, so this transformation may slightly alter a replication of those results.
