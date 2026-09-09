---
layout: default
title: gcp-goog-connector
permalink: /
---

# gcp-goog-connector

`gcp-goog-connector` is a private Google OAuth application operated by DenIT. It allows the operator's self-hosted n8n instance, running on a private NAS, to connect to the operator's Google Drive account.

## What the application does

The application authorizes n8n workflows configured by the operator to perform Google Drive operations. Depending on the workflow and the permissions granted during OAuth authorization, those operations can include reading file information and content, creating files, updating files, downloading files, and deleting files.

The application is not offered to the public. It has no public registration, subscriptions, advertising, or commercial user-facing service. Access is limited to the operator's own Google account.

## Google user data

Google user data is used only to perform the Drive operations explicitly configured by the operator in the self-hosted n8n instance. OAuth credentials and workflow data are not stored in this public website or its GitHub repository.

For details, read the [Privacy Policy](/privacy/) and [Terms of Service](/terms/).

## Contact

Questions about this application can be sent to [pawel.pastuszka90@gmail.com](mailto:pawel.pastuszka90@gmail.com).
