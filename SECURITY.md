# Security Policy

[![Security Status](https://github.com/International-GNSS-Service/igs-tools/workflows/security/badge.svg)](https://github.com/International-GNSS-Service/igs-tools/actions/workflows/security.yml)

Only the latest version of the igs-tools [![PyPI version](https://badge.fury.io/py/igs-tools.svg)](https://pypi.python.org/pypi/igs-tools/) is supported on the versions of Python [![PyPI pyversions](https://img.shields.io/pypi/pyversions/igs-tools.svg)](https://pypi.python.org/pypi/igs-tools/) our continuous integrations are currently running on.

## Monitoring Dependencies

The igs-tools depends on upstream software. Before inclusion as a dependency, upstream software is carefully reviewed for stability, ongoing support and trust. We rely on [Safety](https://safetycli.com/) for monitoring upstream vulnerabilities. When a new vulnerability is discovered the security badge on this page will indicate a failure against [our policy](https://github.com/International-GNSS-Service/igs-tools/blob/master/.safety-policy.yml). We will triage the vulnerability and make one of three decisions:

1. Replace the dependency
2. Upgrade the dependency
3. Exempt the vulnerability in our policy.

If we exempt the vulnerability the reason will be noted in the [policy file](https://github.com/International-GNSS-Service/igs-tools/blob/master/.safety-policy.yml).


## Reporting a Vulnerability

If you think you have found a vulnerability, and even if you are not sure, please email cb@igs.org We will review it and get back to you. Please refrain from public discussions of the issue.
