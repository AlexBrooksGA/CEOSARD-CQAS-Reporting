# CEOS-ARD C-QAS Reporting

Interactive C-QAS report views and a CEOS-ARD Product Explorer concept.

[Open the tool](https://alexbrooksga.github.io/CEOSARD-CQAS-Reporting/)

## Views

- **Original report:** the supplied report reproduced in its original layout.
- **Simple view:** scene suitability for basic Earth observation users.
- **Advanced view:** technical checks, accuracy and evidence.
- **Product Explorer:** a concept for presenting C-QAS quality checks in the CEOS-ARD Product Explorer.

The proposed views use illustrative example data.

## Run locally

Download `index.html` and open it in a browser. No installation or server is required. Google Fonts loads the Barlow font when online; otherwise the page uses a system font.

## Update

Edit `index.html` and push to `main`. GitHub Pages publishes the repository root once enabled.

The `DATA` block in the HTML drives the report views. The embedded Product Explorer concept carries its own copy of the example values. See [USAGE.txt](USAGE.txt) for interaction details; the hosted entry file is named `index.html`.
