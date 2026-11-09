# Security Policy

This is the default security policy for DevPrax projects. A repository's own security policy takes precedence.

## Supported versions

Refer to the affected project's security policy and release documentation for supported versions. DevPrax does not currently have an organization-wide support window or a blanket commitment to backport fixes. If a project has no support matrix, include the affected version in your report and maintainers will assess it individually.

## Report a vulnerability privately

Do not disclose suspected vulnerabilities in public issues, discussions, or pull requests.

1. Open the affected repository's **Security and quality** (or **Security**) tab and look for **Report a vulnerability** on its security overview or **Advisories** page.
2. If available, use that option to send a private report to the repository's maintainers.
3. If the option is unavailable, follow any private reporting instructions in that repository's security policy. DevPrax has not yet designated a security email address. If no private route is listed, open an issue containing only a request for a private security reporting channel. Do not include the vulnerability type, affected component, reproduction steps, logs, or other sensitive details. Wait for maintainers to arrange a private channel before sharing the report.

Private vulnerability reporting must be enabled for the affected repository; this policy does not enable it. See [GitHub's private reporting instructions](https://docs.github.com/en/code-security/how-tos/report-and-fix-vulnerabilities/report-privately) for the reporting workflow.

## What to include in a private report

- The affected repository, version or commit, and relevant environment.
- A description of the vulnerability and its potential impact.
- Minimal reproduction steps or a proof of concept using synthetic data.
- Any prerequisites, affected configurations, and known mitigations.
- Your preferred way to follow up and whether you would like public credit.

Remove credentials, tokens, personal data, and unrelated confidential information. Test only in environments you own or have permission to assess, and avoid accessing other people's data or disrupting services.

## Triage and coordinated disclosure

Maintainers will assess reports as availability permits, request clarification when needed, and discuss remediation and disclosure with the reporter through the private channel. DevPrax does not currently guarantee response or resolution times.

For a confirmed vulnerability, maintainers will work to determine affected versions, prepare a fix or mitigation, and coordinate release and publication of an advisory when appropriate. The advisory should explain impact, affected versions, and how users can protect themselves. Reporter credit will be included with the reporter's consent.

Please coordinate public disclosure with maintainers so users have an opportunity to update or apply mitigations. Discuss a disclosure timeline privately rather than assuming a fixed deadline or an indefinite embargo. If you have not heard back, follow up through the same private channel without posting vulnerability details publicly.
