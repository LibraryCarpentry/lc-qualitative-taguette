---
title: 'Saving and Sharing Qualitative Data'
teaching: 30
exercises: 30
---

::: questions

-   How can Taguette projects be shared or archived in common data formats?
-   What are the advantages of sharing qualitative data?
-   What can I do to continue learning?

:::

::: objectives

-   Recognize reasons to consider archiving or sharing qualitative data
-   Practice import/export of various parts of Taguette projects

:::

Many qualitative researchers prefer not to share or archive their data and analysis. In large part, this is because of the amount of interpretive labor they invest, along with frequent direct trusted connections with groups and individuals being studied. This trust can take time to develop before and during data collection, whether as participants or observers.

There are important advantages to archiving and sharing data, however, even for qualitative data. Each researcher ultimately must make their own decisions, but this final section will outline potential values and risks of archiving or sharing data, as well as how to go about doing so in Taguette.

::: callout

Data sharing and interchangeable data formats have only recently become someone widespread in qualitative research. Be aware that information in this section may rapidly become out of date, and if in doubt, consult with a human subjects protection board, archivist, or librarian at your institution or the [Qualitative Data Repository][qdr] before sharing data.

## Import and export in Taguette

Taguette projects are automatically saved either to the cloud or your local computer, depending on whether you use the local `Single-user mode` or sign into [Taguette Cloud][taguette_cloud].

Projects and codebooks can both be exported and imported in Taguette. Projects exported from the `Project info` tab are saved as `sqlite3` databases. They're designed primarily for personal archiving and sharing or moving between cloud and local versions of Taguette, but can also be imported into [QualCoder](https://qualcoder.wordpress.com/how-to-use/) (version 3.8+).

To import a previously-exported project in Taguette, click `Home` at the top to exit to the projects list. From there, click `Import a project file`, find the file you saved, and import. All documents, highlights, and tags should be intact.

::: callout

### Other qualitative data formats

Each major CAQDAS package has its own proprietary data format, specialized to its features. In most cases, projects cannot be moved between software in these formats, Taguette's included. Data files in some software may also be restricted to specific platforms (Windows or Mac) or software versions.

The [REFI-QDA standard](https://www.qdasoftware.org/) offers an alternative, the `QDPX` format. `QDPX` was developed in collaboration between researchers and major package developers, that provides the ability to move projects in a standard format between every major package. It is an open standard which anyone can use and adapt. Because packages structure data differently and have distinct advanced feature sets, some data may fail to import into the target tool.

Taguette currently only implements the codebook portion of the `QDPX` standard, and only for export. To export a codebook that can be imported in other software, choose `Export codebook` from the `Project info` tab and select `QDC (XML)`.

:::

## Data sharing for collaboration

Working with collaborators is one of the most common reasons for sharing qualitative projects. The most direct option for sharing Taguette projects with collaborators is to use [Taguette Cloud][taguette_cloud]. From the `Project info` tab, `Manage collaborators` allows you to add other users (they need to sign up first) and select the level of permissions they have to view, change, or even delete the project.

Sometimes, however, you only want to share a specific portion of the project with collaborators. The document or highlight view can be exported with the dropdown at the top right in `HTML` (webpage), `DOCX` (Word), or `PDF` (Adobe) format. Unlike sharing the original document, exporting this view, will show highlights and add tags in brackets so collaborators can see what codes have been applied.

Highlight view behaves similarly, with the addition of a `CSV` format that can be opened in Excel or other spreadsheet or data analysis software.

Finally, a codebook can be automatically generated from the `Project info` tab that lists code labels, the number of highlights they have been applied to, and any description added to the codes. Formats include all those listed above, as well as `QDC` XML format (see "Other qualitative data formats" above).

## Transparency and reuse

Certain scientific disciplines have called for research transparency, including sharing data and analytic procedures, with momentum growing in many social sciences. Until recently, that effort was primarily applied to quantitative data, such as surveys, experiments, and "big data" gathered from the internet.

A small number of projects are working to change that perception and promote the thoughtful, informed, careful sharing of qualitative and mixed methods data as well, led in part by the [Qualitative Data Repository][qdr] and enabled by improvements in sharing like the `REFI-QDA` standard.

## Helping future you

If the arguments above don't convince you that it's good and worth the effort to archive qualitative data securely, there is one more important case to be made.

Archiving your data in an open and interchangeable format that is backed up in multiple locations can help future you. If your only copy of your project is on your laptop and it is lost or destroyed before analysis and review are complete, or if you decide you want to do additional analysis later, there isn't much that can be done short of repeating a large amount of work.

Taguette's single-user mode only stores data on your computer, and Taguette Cloud only saves it to the Taguette servers, which could go down at any time. Whether or not you plan to share or reuse your data, consider exporting your project from Taguette at key points, such as after you've completed initial or axial coding.

## Next steps

This lesson has covered basic principles of qualitative research, as well as how to use Taguette for qualitative coding and data analysis. With that foundation, the next step is to find or collect your own data and try it for yourself.

In addition to the Qualitative Data Repository (used and discussed here), some other social science data archives such as ICPSR have qualitative sections. For qualitative content analysis, there are thousands of open-access archives of documents, research, education resources, and even entire books.

:::

::: keypoints

- Archiving and sharing qualitative data can help you, your collaborators, and other researchers
- Taguette's import and export options can help you share key components of your work
- There are many resources available to continue learning about qualitative research and finding, reusing and sharing qualitative data

:::
