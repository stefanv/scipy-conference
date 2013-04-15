Conference proceedings : Process outline
========================================

Background
----------
The aim of the SciPy conference proceedings is threefold: to provide a peer-reviewed platform for giving an overview of the conference, to give academic legitimacy to the event, and to assist academics in receiving funding for attending.  In the past, papers were due *after* the conference via a pull request on GitHub.  The papers are written in restructured text, and are compiled to PDF using provided tools.  All PRs are checked for validity and merged into the repository, after which open reviews are solicited.  Based on this feedback, authors are allowed to amend their papers, before they are published.

The system had successes and failings:

- Since the proceeding tools were provided, all papers had consistent layout and format.  Very few problems were experienced by users in compiling their papers, or in mastering the text-based format.
- The proceedings publication process had been almost entirely automated--including the building of the proceedings website.

- The proceedings coordinators were too busy to efficiently drive the review solicitation and feedback process, and were a single point of failure.
- In addition, some reviewers and paper authors responded slowly to requests, further delaying progress.  Proceeding coordinators did not follow up in a timely fashion.

For the 2013 conference, after due consideration of the above failings, we propose a new light-weight process.

A lightweight, online review process
------------------------------------
Most of the failings above can be attributed to two factors:

1. The proceedings editors were lacking the time to drive reviews from day-to-day.
2. Reviewing and editing papers becomes a chore.
3. A single review round is unsatisfactory: some papers may still not be ready, whereas others are already suitable for publication.  The editors now have to make a call, or work with the authors further.

To address these issues, we propose the following light-weight process:

1. Authors who wish to participate in the proceedings submit a paper 4 weeks before the conference.
2. To each pull request, one or more reviewers are assigned.
3. During the next 3 weeks, reviewers comment on papers.  In response, authors update their pull request to address the comments.
4. Once a reviewer is satisfied that a paper can be published, he signs off on it (via a comment on the PR).
5. The paper is merged by the editors into the proceedings.
6. Just before the conference, an electronic copy of the proceedings is generated, containing all papers that were signed off.

Publication
-----------
After the conference, the best papers are selected by the programme committee for possible inclusion in a published journal.  The journal editors work with these authors to get their content accepted.
