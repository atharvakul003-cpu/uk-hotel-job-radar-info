---
layout: default
title: Privacy information
---

# Privacy information

UK Hotel Job Radar is operated for its owner's personal job search.

The tool uses Google OpenID email information to verify the authorized sender and Gmail send permission to send job alerts and controlled connection tests. It does not request inbox-reading permission. Alert messages contain public vacancy details and the owner's designated sender and recipient addresses.

OAuth client credentials and the refresh token are stored in encrypted GitHub Actions Secrets. Temporary access tokens are used during workflow execution. Credentials are not written to the source repository or monitoring database.

The private monitoring database stores public job details, first-seen timestamps, source health, and notification outcomes to prevent repeated alerts. Google processes outgoing email; GitHub hosts the workflow, secrets and private monitoring state. Google user data is not sold, used for advertising, or used to train AI models.

The owner can revoke the app's access through their Google Account connections settings, delete the GitHub secrets, disable the workflow, and delete stored monitoring state. Revocation does not delete messages already delivered to mailboxes or copies retained in repository history.

Use of information received from Google APIs follows the Google API Services User Data Policy, including its Limited Use requirements.

[Home](./)
