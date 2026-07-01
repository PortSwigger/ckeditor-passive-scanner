## V3.0 - 2026-07-01
Key improvements:
• Early Content-Type guard before bodyToString() to skip binary files
• Switched to ConcurrentSkipListSet for full thread-safety
• Proper HTML escaping to prevent injection in Audit Issue panel
• Body size limits and better memory management
• Improved plugin extraction and path calculation

## v2.0 - 2026-03-22
### Added
- Full Scope awareness (only scans in-scope URLs)
- Numbered Evidence list in issue details for better traceability
- Proper AuditIssue construction with remediationBackground
- Body size limit + better error handling + memory leak avoidance

### Fixed
- Scope checking (no more scanning out-of-scope traffic)
- Removed Custom UI tab
- AuditIssue API compatibility for Montoya 2026
- Minor performance and logging improvements
