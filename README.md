# ES 335 · Machine Learning (August 2024)

Course website for ES 335 Machine Learning at IIT Gandhinagar, Semester I 2024–25:
<https://nipunbatra.github.io/ml2024-fall/>

The site is a [Quarto](https://quarto.org) website in the same design as
[ES 667 Deep Learning](https://nipunbatra.github.io/dl-2026/). On every push to `main`, GitHub Actions
(`.github/workflows/publish.yml`) renders it and publishes it to the `gh-pages` branch with `quarto publish`.

| File | Contents |
|---|---|
| `index.qmd` | Home: course facts, course record, module overview, questions, references, teaching assistants |
| `schedule.qmd` | Lectures: one row per lecture with slides, notebooks and reading |
| `assessment.qmd`, `_dates.qmd` | Grading, attendance, every dated event, quizzes and assignments |
| `faq.qmd` | All questions |
| `exams/prereq.qmd` | Prerequisite test |
| `grading.qmd`, `tentative.qmd`, `quizzes.qmd` | Redirects from old URLs to Assessment |
| `apps/` | Streamlit demo code |
| `styles.scss`, `course.scss` | Shared theme (`styles.scss` is identical to dl-2026) and small additions |
| `rail.html`, `course-theme.html`, `course-tools.html` | Side rail, light and dark switch, footer, copy-link buttons and date handling |

Preview locally with `quarto preview`.
