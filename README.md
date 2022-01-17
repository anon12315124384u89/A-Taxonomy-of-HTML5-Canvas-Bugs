This repository contains data used in the paper `A Taxonomy of HTML5 Canvas Bugs`.

Our methodology for data collection is detailed in the paper.

**Data description:**

| file name                      | description                                                         | fields        |
| -                              | -                                                                   | -             |
| extracted_projects.csv         | 180 open source \<canvas\> projects (extracted from GitHub)         | nameWithOwner |
| extracted_bug_reports.csv      | 2403 \<canvas\> bug reports (extracted from the 180 GitHub projects)| url           |
| classified_bug_reports.csv     | 332 classified bug reports (sampled from extracted_bugs.csv)        | url, type     |
| encoding.json                  | encoding of labels for bug type classification                      |               |
