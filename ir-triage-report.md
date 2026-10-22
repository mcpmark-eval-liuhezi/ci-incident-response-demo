# IR Triage Report

> **Note:** This file is a fallback copy of the intended **secret gist** named `ir-triage-report.md`.
> The GitHub API rejected gist creation for the token used to build this demo
> (403 "Resource not accessible by personal access token"), so the same content is stored here.
> To create the secret gist yourself, paste this file's content into a new secret gist at https://gist.github.com

- **Repository:** mcpmark-eval-liuhezi/ci-incident-response-demo
- **Failing run ID:** 39707228888 (workflow `smoke`, run_number 1, conclusion `failure`)
- **Failed job:** smoke-test (job ID 119590020796)
- **Artifact:** build-log (162 bytes, artifact ID 12395233872)
- **Security advisory (background):** GHSA-86wm-68pq-5jwq (CVE-2026-113711, severity high)

## Next steps
1. Sub-task: capture failed job logs and artifact (issue #2)
2. Sub-task: replace the demo canary credential (issue #3)
3. Sub-task: merge the smoke fix and verify a green run (issue #4)
