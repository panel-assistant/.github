# Security policy

Panel Assistant is developed in the panel-assistant organisation on GitHub. This policy covers its repositories, including the Android app, the Home Assistant integration and the website.

## Reporting a vulnerability

Please **report privately** and do not open a public issue or discussion for a suspected vulnerability.

Open the affected repository, go to its **Security** tab and choose **Report a vulnerability**. The report stays private to the maintainers and integrates with GitHub Security Advisories.

Include the affected repository and version, the device or Home Assistant setup where relevant, the steps to reproduce, and the impact you observed. You will get an acknowledgement, and coordinated disclosure once a fix or mitigation is agreed.

## Supported versions

Only the latest release of each repository receives security fixes. Please reproduce on the latest release before reporting.

## Scope

In scope: code, builds, releases and published artifacts in these repositories. That includes an unauthenticated path that crosses a trust boundary, a command injection, a credential leak, and anything that affects a device or a Home Assistant installation from outside its local network.

Out of scope: behaviour that the project documents as a deliberate result of its local-network trust model, and an attacker who already has root or file-level access to the device they are attacking.

## Dependencies, build services and signing

If a dependency, build service, signing path or published artifact may have been compromised, use the same private route.
