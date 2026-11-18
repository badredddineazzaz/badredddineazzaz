# Portfolio review — 18 November 2026

## Positioning

The strongest evidence is the combination of web application development and visual interaction: a Python/FastAPI + React/TypeScript job dashboard, Python/OpenGL marker-based AR, and C++/OpenCV interface experiments. Java, PHP and frontend coursework show earlier foundations. This is a project-based portfolio; no seniority, employment, performance or user-adoption claims are inferred.

## Scope and verification

Reviewed the 12 pre-existing public repositories through repository trees, README files, manifests and selected source files. Private repositories were not used as portfolio evidence. Repository trees were not truncated. This is a presentation/documentation review, not a comprehensive code or security audit.

Published a profile README and a self-hosted SVG banner, added the public display name and bio, and updated descriptions and topics for all 12 repositories. Reworked the README files for JobScraper Dashboard, ArUco AR, IHM Projects and the Java recipe explorer. Preserved project authorship credits.

Six pinned repositories, in display order:

1. `jobScrapingDashboard`
2. `ARUCO-AR-3d`
3. `IHM-Projects`
4. `functionnal-java`
5. `Java-projects`
6. `7segmentscpp`

The first four also form the featured project grid in the profile README. No external statistics service is required for the profile. The technology badges are static Shields.io images.

## Repository inventory

| Repository | Evidence and presentation decision | Next useful work |
| --- | --- | --- |
| [jobScrapingDashboard](https://github.com/badredddineazzaz/jobScrapingDashboard) | Strongest public application: FastAPI routes, React/TypeScript frontend, SQLAlchemy/Alembic, CLI, searches and application tracking. Featured first. | Capture a real dashboard demo, validate a clean installation and publish measured test results. Review inherited project URLs in `pyproject.toml` with appropriate code-change approval. |
| [ARUCO-AR-3d](https://github.com/badredddineazzaz/ARUCO-AR-3d) | Distinctive AR prototype with marker pose estimation and OpenGL transformations. Featured with explicit legacy setup limits. | Reconcile OpenCV packages, add missing imports to dependency declarations and make calibration/device selection configurable. Requires code-change approval. |
| [IHM-Projects](https://github.com/badredddineazzaz/IHM-Projects) | Four C++/OpenCV coursework solutions. Corrected the description of `Calibrate` to reflect its image-viewer implementation. | Reproducible build instructions, configurable local paths, supplied cascade asset and a recorded hardware demo. Source changes require approval. |
| [functionnal-java](https://github.com/badredddineazzaz/functionnal-java) | Collaborative JavaFX/XML coursework. Maven entry point and two unfinished UI queries are now documented. | Complete the unfinished queries and validate XML parsing on representative inputs, with code-change approval. |
| [Java-projects](https://github.com/badredddineazzaz/Java-projects) | Collaborative ESTCOURS console and JavaFX/MySQL project. Pinned as supporting Java/database work. | Expand setup around the SQL dump, JDBC configuration and UI module; preserve all co-author credits. |
| [7segmentscpp](https://github.com/badredddineazzaz/7segmentscpp) | Small C++ Boolean-logic exercise with terminal output and an existing demonstration link. Pinned as a compact foundations example. | Add a compiler-specific build example and verify all 16 hexadecimal inputs before claiming correctness. |
| [articles_website](https://github.com/badredddineazzaz/articles_website) | PHP/MySQL publishing prototype; original README contains only a title. Supporting learning project. | Document MySQL 8 dump requirements and local setup; distinguish database-backed cards from static placeholders and unfinished navigation. |
| [Html-Css-JavaScript](https://github.com/badredddineazzaz/Html-Css-JavaScript) | Weather interface and digital clock. Root README is minimal. Linked under foundations. | Add per-project launch instructions and check external APIs before publishing a live demo. Review client-side API credential handling with code-change approval. |
| [WEB-Projects](https://github.com/badredddineazzaz/WEB-Projects) | Collaborative PHP/MySQL MyGym coursework. Linked under foundations. | Document database import, connection settings and actual features; verify the historical hosted preview before promoting it. |
| [c-project](https://github.com/badredddineazzaz/c-project) | HTML-tag removal exercise implemented in C++, despite its repository name. Keep as coursework. | Add source/build navigation and a small input/output example after checking the parser; keep co-author credits. |
| [candidature-stage-codelab360](https://github.com/badredddineazzaz/candidature-stage-codelab360) | Static frontend exercise with jQuery slider/navigation and client-side form validation; no README. | Add a README and actual preview. Do not claim form delivery or persistence: the reviewed handler prevents submission and shows a toast. |
| [nmeacontroller](https://github.com/badredddineazzaz/nmeacontroller) | Contains only a README. Description explicitly identifies it as a documentation-only concept. Not featured as an implemented Android application. | Add source and build instructions if an implementation exists; otherwise describe the intended functionality as a concept. |

No duplicate repositories were established. Similar technologies or generic names do not prove duplication. Older coursework is historical work, not evidence that a project has been abandoned. None of these repositories was archived, renamed, deleted or made more public.

## Naming convention — recommendations only

Use short lowercase kebab-case names describing the project. Existing names remain unchanged. Renaming requires owner approval and a review of clone URLs, links and integrations.

| Current name | Suggested name if a rename is approved |
| --- | --- |
| `jobScrapingDashboard` | `job-scraper-dashboard` |
| `ARUCO-AR-3d` | `aruco-lung-ar` |
| `IHM-Projects` | `opencv-interaction-lab` |
| `functionnal-java` | `java-recipe-explorer` |
| `Java-projects` | `estcours-java` |
| `7segmentscpp` | `hex-seven-segment` |
| `articles_website` | `php-articles` |
| `Html-Css-JavaScript` | `frontend-experiments` |
| `WEB-Projects` | `mygym-php` |
| `c-project` | `html-tag-remover-cpp` |
| `candidature-stage-codelab360` | Keep historical exercise name unless its original brief supports a clearer title |
| `nmeacontroller` | Keep until the intended project identity and implementation are clarified |

## Verification boundaries

The revised setup guidance was checked against manifests, source imports, CLI definitions, API routes, Maven configuration, Vite proxy settings and Docker configuration. Installations, builds, camera tests, scraping requests and automated tests were not run. No screenshots of the applications, performance results or test-pass claims were fabricated.

Documentation commits and metadata updates are reversible. Application source code, dependency manifests, repository history and visibility were left unchanged.
