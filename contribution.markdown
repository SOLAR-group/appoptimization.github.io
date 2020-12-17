---
layout: page
title: Contribution
description: How to contribute to the survey.
---

Contributions of new publications are welcome! To contribute, please read the following instructions and open a pull request.

### Add a publication

To add a publication, create a new file in the `_publications` folder.
The name of the file should follow the structure `XYZYear.markdown`
where `XYZ` are the first letters of the last names (surnames) of the first three authors (in case the paper has three or more authors)
and `Year` the year of the publication.
If a paper has two authors, use the first two letters, e.g., `XYYear.markdown`.
In case a paper has only one author, just use the first one letter, e.g., `XYear.markdown`.
Within each file, follow the structure shown in the already existing files found in the `_publications` folder.
Once the file is added, the paper will appear in the "All Papers" section.
<pre>
---
layout: publication
title: The title of the Publication
authors: F. M. LastName, F. M. LastName, ...
conference: AbbreviatedNameOfConference
year: YEAR
bibkey: XYZYear or XYYear or XYear
additional_links:
   - {name: "ArXiV", url: "http://arxiv.org/abs/XXXX.YYYY"}
   - {name: "website", url: "http://paperwebsite.com"}
   - {name: "code", url: "https://github.com/path-to/code"}
---
Text of abstract goes here.
</pre>

The `additional_links` and the `abstract` are optional.

### Commit a publication

Please open a pull request [here](https://github.com/SOLAR-group/appoptimization.github.io) to commit your changes. Thank you!
