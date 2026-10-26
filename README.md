# Promise & Practice

An original ACT skills course for Waukegan High School, taught through U.S. History from the Civil War (1861) forward. Prepared for Thomas Stonis / Shadow Dog Studios.

## Open the course

Open `index.html` in a current browser, or serve this folder as a static website. JavaScript is required. There is no build step, installation, API key, external library, or learner account requirement.

For the easiest single-file use, open the separately supplied `Waukegan_ACT_History_Tutorial.html`. It embeds the complete course and archival photographs.

## Deploy to GitHub Pages

1. Unzip the package and upload **its contents** to your repository. `index.html`, `.nojekyll`, this README, and the `assets` folder belong at the repository root. Upload the contents, not only the ZIP.
2. In the repository, open **Settings → Pages**.
3. Select **Deploy from a branch**, then **main** and **/(root)**. Save.
4. Open the Pages address GitHub provides and check the course before sharing the address in Google Classroom.

All application paths are relative and work beneath a GitHub project URL. No GitHub Actions workflow is needed for branch deployment. Organization policies may affect Pages availability.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## What is included

- 36 sequenced core lessons across six historical eras; suitable as a starting framework for one lesson per week.
- 12 optional extension labs in advanced mathematics, reading, science reasoning, English, and writing.
- 384 original items: 48 guided questions, 288 independent questions, and 48 separate review questions.
- Explicit strategies, worked examples, historical readings, labeled practice data, explanations, and error reflections.
- Eight opportunities for a developed writing response, with perspectives and self-review in the four ACT writing domains.
- Untimed and paced checks, question flags, browser progress saving, separate local learner workspaces, and JSON backup/restore.
- Per-lesson PDF and HTML completion certificates with evidence; a core-course certificate after 36 completed lessons.
- Spanish procedural support, larger reading text, paragraph evidence marks, keyboard controls, and browser-dependent read-aloud.
- An in-course teacher guide, current official ACT/Illinois resource links, and historical sources with archival image credits.

## Weekly use

Open **Teacher guide** in the footer for the full routine. A suggested 47-minute meeting includes retrieval, direct teaching, a worked example, guided practice, independent work, feedback, and reflection. Writing may continue into a later session. Adjust the pace to students' prerequisites; do not equate finishing a page with mastering a subject.

Use a separate new official practice form for baseline and later readiness checks, with the correct form-specific scoring key. This history-centered course also needs transfer practice in other ACT Reading genres. Local six-question results are not ACT scaled scores and do not predict a guaranteed score gain.

## Certificates and Google Classroom

Create a Classroom assignment for each assigned lesson. Students finish the lesson requirements, select **Download certificate → Download PDF**, attach the PDF to the assignment, and select **Turn in**. The PDF includes the certificate and pages with their results, reflection, and any writing. Printable HTML and plain-text evidence are also available.

Completion requires the instructional steps, submission, error-cause review for missed/skipped questions, and a reflection. Writing tasks add a minimum word count, which checks participation only. There is no minimum check score for completion. Teachers assess the reasoning and writing quality.

Records are generated on the learner's device. The record ID is not a digital signature. A certificate is evidence submitted for teacher review, not an official ACT credential or a secure assessment result.

## Saving and student information

Progress stays in the browser on the current device. It does **not** synchronize among devices, browsers, a hosted copy, and the standalone edition. Export a progress backup regularly and before changing devices. Clearing browser data can remove saved work. Some browsers restrict saving for locally opened HTML; export if the application shows a saving warning.

Workspaces on a shared browser separate records for convenience; they are not authenticated accounts. Anyone using that browser may open them. This static application has no central student database, gradebook, or secure login. It does not transmit learner work to a service. External links and optional browser speech features may use connectivity or device services.

**Keep student backups, certificates, essays, and identifying information out of the public GitHub repository.** Upload only the course files. Teachers collect evidence through their approved classroom system.

## Edit the course

- `index.html`: entry document.
- `assets/styles.css`: responsive layout, colors, typography, and print rules.
- `assets/app.js`: navigation, learning workflow, saving, checks, certificates, and backup handling.
- `assets/course.js`: structured original curriculum and institutional references, assigned to `window.WHS_COURSE`.
- `assets/*.jpg`: credited archival photographs; image records and rights notes appear in the course.

The files contain all practice keys because this is static learning software. Do not use it as a secure examination platform. Review modified content and test the completion/download workflow before assigning an edited version. The existing progress key is `whs-act-history-v1`; a future incompatible content revision should use a new key or an explicit migration.

Requirements were checked against ACT and ISBE resources for spring 2027 on October 21, 2026. Recheck official requirements before later administrations. Course version: 1.0.0.

ACT® is a registered trademark of ACT Education Corp. This independent classroom course is not endorsed by ACT. Historical readings, instructional datasets, and practice items are original; institutional references support the historical context. Images retain the credits and rights notes listed in the course.
