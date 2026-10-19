# test-webhooks-demo
Staging Resolve webhook integration demo: Goal-based typo review

This public repository exercises GitHub App push delivery to the single staging
Resolve webhook endpoint. Its configured Goal reviews Python text for spelling
errors and returns its findings and corrected code as downloadable artifacts.

The initial test change deliberately contains a spelling error in `demo.py`.
