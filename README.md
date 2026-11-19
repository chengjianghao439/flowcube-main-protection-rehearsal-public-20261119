# Merge gate rehearsal

Synthetic fixtures for testing GitHub branch rules. This repository has no application code, real deployment jobs, or credentials.

The workflow named Tests reads `fixtures/tests.txt`. The workflow named Security Scan reads `fixtures/security-scan.txt`. The two PR gate jobs accept only successful prerequisite jobs. The web and Android workflow files are manual-trigger markers.
