## v2.0 - 2026-03-22
### Added
- Full Scope awareness (only scans in-scope URLs)
- Numbered Evidence list in issue details for better traceability
- Proper AuditIssue construction with remediationBackground
- Body size limit + better error handling + memory leak avoidance

### Fixed
- Scope checking (no more scanning out-of-scope traffic)
- AuditIssue API compatibility for Montoya 2026
- Minor performance and logging improvements
