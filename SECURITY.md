# Security Policy

We're extremely grateful for security researchers and users that report vulnerabilities to the AccuKnox Security team. All reports are thoroughly investigated by a set of security professionals.

AccuKnox has adopted the security disclosures and response policy below to respond to security issues.

Please do not report security vulnerabilities through public GitHub issues.

> Note: All the points stated herewith are also applicable to onprem AccuKnox deployments, unless explicitly stated otherwise.

## Supported Versions

The following AccuKnox release are currently being supported with security updates.

| [AccuKnox Release](https://help.accuknox.com/getting-started/3.2-release/) | Supported |
| ------- | ------------------ |
| >= 3.0   | :white_check_mark: |
| < 3.0   | ❌ |

## Reporting a Vulnerability

### When should you?
- You think you discovered a potential security vulnerability in AccuKnox Control Plane or in Agents or on the portal.
- You are unsure how a vulnerability affects AccuKnox.
- You think you discovered a vulnerability in a dependency of AccuKnox. For those projects, please leverage their reporting policy.

### When you should not?
- You need assistance in configuring AccuKnox for security - please discuss this at support@accuknox.com.
- You need help applying security-related updates.
- Your issue is not security-related.

### Please use the process below to report a vulnerability to the project:
1. Email the **AccuKnox Security Group at security@accuknox.com**

    * Please include the information listed below (as much as you can provide) to help us better understand the nature and scope of the possible issue:
        * Type of issue (e.g. buffer overflow, SQL injection, cross-site scripting, etc.)
        * Full paths of the source file(s) related to the manifestation of the issue
        * Location of the affected source code (tag/branch/commit or direct URL) 
        * Any special configuration required to reproduce the issue
        * Step-by-step instructions to reproduce the issue
        * Proof-of-concept or exploit code (if possible)
        * Impact of the issue, including how an attacker might exploit the issue

    * This information will help us triage your report more quickly.

2. The organization security team will send an initial response to the disclosure. Once the vulnerability and fix are confirmed, the team will plan to release the fix based on the severity and complexity.

3. You may be contacted by a organization maintainer to further discuss the reported item. Please bear with us as we seek to understand the breadth and scope of the reported problem, recreate it, and confirm if there is a vulnerability present.

## Security bulletins
For information regarding the security of the AccuKnox, please join our [discussions channel](https://github.com/orgs/accuknox/discussions).

## Public Disclosure Timing
A public disclosure date is negotiated by the AccuKnox Security Response team and the bug submitter. We prefer to fully disclose the bug as soon as possible once a user mitigation is available. It is reasonable to delay disclosure when the bug or the fix is not yet fully understood, the solution is not well-tested, or for vendor coordination. The timeframe for disclosure is from immediate (especially if it's already publicly known) to a few weeks. For a vulnerability with a straightforward mitigation, we expect report date to disclosure date to be on the order of 7 days. The AccuKnox Security Response team holds the final say when setting a disclosure date.


