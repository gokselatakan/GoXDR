# Security Policy

## Overview

GoXDR is a static, open source project that provides a collection of KQL queries for detection and threat hunting. The site is served from GitHub Pages at https://goxdr.fyi.

The project does not collect accounts or credentials. All content is intentionally public.

## Supported Versions

Only the latest version in the `main` branch is supported.

## Reporting a Vulnerability

Please use GitHub private vulnerability reporting:

1. Open the Security tab of this repository.
2. Select "Report a vulnerability".
3. Describe the finding, its impact and the steps to reproduce.

Please do not open a public issue for a security finding. If private reporting is not available, open an issue that asks for a private contact and leave the details out.

## Scope

Out of scope:

* Public availability of the HTML, CSS and JavaScript files, which is expected
* Downloading or cloning repository content
* Reuse or redistribution of KQL queries under the project license

## Security Considerations

* No secrets, API keys or credentials should be committed to this repository
* Contributions are reviewed before they are merged
* This repository is the single source of truth for GoXDR

## Disclaimer

This project is provided "as is", without warranty of any kind. Test every query in your own environment before you use it in production. Hunting queries are not alerts and can produce false positives.
