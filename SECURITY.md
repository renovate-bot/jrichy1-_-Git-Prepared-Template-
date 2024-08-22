
---

### Supported Version Policy for Security Violations

**Effective Date:** [Insert Date]

#### 1. **Introduction**
This policy outlines the approach and responsibilities for addressing security vulnerabilities in the codebase of the [Git-Prepared-Template](https://github.com/jrichy1/Git-Prepared-Template-) repository. The goal is to ensure that all supported versions of the software are secure and that any identified security issues are promptly resolved.

#### 2. **Supported Versions**
- **Active Versions:** All versions of the repository that have been released within the last 12 months are considered actively supported. These versions will receive security updates and patches as needed.
- **Maintenance Versions:** Versions released between 12 and 24 months ago will be maintained for critical security updates only. Non-security-related issues in these versions will not be addressed.
- **End of Life (EOL):** Versions older than 24 months will no longer receive any updates, including security patches. Users are encouraged to upgrade to a supported version as soon as possible.

#### 3. **Security Violation Response**
- **Detection:** Any security vulnerability reported via the issue tracker, security advisories, or discovered during routine audits will be assessed based on severity.
- **Classification:** Vulnerabilities will be classified as:
  - **Critical:** Requires immediate attention and patching.
  - **High:** Should be addressed within 7 days.
  - **Medium:** Should be addressed within 30 days.
  - **Low:** Addressed in the next scheduled release cycle.
  
- **Patching and Releases:** 
  - **Critical/High Severity:** Patches will be released as soon as possible. Affected versions in the "Active" and "Maintenance" phases will receive updates.
  - **Medium/Low Severity:** Updates will be included in the next scheduled release for active versions. Maintenance versions will receive updates if deemed necessary.

#### 4. **Communication**
- **Advisories:** Security advisories will be published on the repository’s security page to inform users of the vulnerability, affected versions, and the availability of patches.
- **Notification:** Users of affected versions will be notified via release notes, issue trackers, and other communication channels provided by GitHub.

#### 5. **User Responsibilities**
- **Updating:** Users are responsible for regularly updating to the latest versions to benefit from security patches.
- **Reporting:** Users are encouraged to report any suspected security issues directly via the repository's issue tracker or through a designated security contact.

#### 6. **Review and Updates**
This policy will be reviewed annually and updated as necessary to reflect changes in best practices, repository activity, or emerging security threats.

---

This policy can be customized further based on specific needs or requirements for your project. It’s recommended to incorporate this into the repository's `SECURITY.md` file or a similar section to ensure it's easily accessible to all contributors and users.
| Version | Supported          |
| ------- | ------------------ |
| 5.1.x   | :white_check_mark: |
| 5.0.x   | :x:                |
| 4.0.x   | :white_check_mark: |
| < 4.0   | :x:                |

## Reporting a Vulnerability
 
 - Please Report all issues to g.dev/jrichy1
