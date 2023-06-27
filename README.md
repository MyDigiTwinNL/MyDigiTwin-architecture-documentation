# MyDigiTwin

## Overview

This repository contains the architecture documentation for the MyDigiTwin project, based on arc42, a lightweight template for documenting software architectures. The documentation is written in Markdown format, with each section contained in its own file. The documentation can be built and viewed using MkDocs, a static site generator.

## Table of Contents

1. [Introduction and Goals](docs/01.Introduction%20and%20Goals.md)
2. [Architecture Constraints](docs/02.Architecture%20Constraints.md)
3. [Context and Scope](docs/03.Context%20and%20scope.md)
4. [Solution Strategy](docs/04.Solution%20Strategy.md)
5. [Building Block View](docs/05.Building%20Block%20View.md)
6. [Runtime View](docs/06.Runtime%20View.md)
7. [Deployment View](docs/07.Deployment%20View.md)
8. [Cross-cutting Concepts](docs/08.Crosscutting%20Concepts.md)
9. [Architecture Decisions](docs/09.Architecture%20Decisions.md)
10. [Quality Requirements](docs/10.Quality%20Requirements.md)
11. [Risks and Technical Debt](docs/11.Risks%20and%20Technical%20Debt.md)
12. [Glossary](docs/12.Glossary.md)
13. [About arc42](docs/Aboutarc42.md)
14. [Appendix](docs/Appendix.md)
15. [Images](docs/images)


## Automated documentation building

This repository includes a GitHub action script that builds the documentation as an HTML website and publishes it in GitHub pages. However, as this repository is currently private, the project's GitHub page won't be available.

## Manual documentation building

To build and view the documentation locally, follow these steps:

1. Ensure you have Python and `mkdocs` installed on your system.
2. Clone this repository to your local machine.
3. Open a command prompt or terminal and navigate to the project directory.
4. Build the documentation by running the following command:
   ```
   mkdocs build
   ```
   This command generates a static HTML site in the `site` directory.
6. To view the documentation, run the following command:
   ```
   mkdocs serve
   ```
   This will start a local development server and provide a URL where you can access the documentation in your web browser.
