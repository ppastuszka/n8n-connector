---
layout: default
title: Privacy Policy
permalink: /privacy/
---

# Privacy Policy

**Last updated:** September 9, 2026

This Privacy Policy describes how `gcp-goog-connector` (the **Application**), operated by DenIT (the **Operator**), accesses and uses Google user data.

## Purpose and users

The Application is a private OAuth connection used solely by the Operator. It allows a self-hosted n8n instance running on the Operator's private NAS to access the Operator's Google Drive account. The Application is not offered to the public and does not provide user registration.

## Data accessed

Depending on the permissions shown and granted during Google's OAuth consent flow, the Application may access:

- Google account identification needed to establish the authorized connection;
- Google Drive file and folder metadata;
- Google Drive file content; and
- permissions needed to create, download, update, organize, or delete Drive files.

The Application requests access only for Google Drive operations used by the Operator's n8n workflows.

## How data is used

Google user data is used only to execute Google Drive actions explicitly configured by the Operator in the self-hosted n8n instance. It is not used for advertising, profiling, resale, or training artificial intelligence models.

The Application's use and transfer of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

## Storage and retention

OAuth tokens are stored by the Operator's self-hosted n8n instance on the private NAS. They are not stored on this website or in its public GitHub repository. Tokens are retained until the connection is removed, access is revoked, or Google invalidates them.

Google Drive data may be processed temporarily by n8n or stored on the Operator's NAS when a configured workflow requires it. Any such data is retained only for the workflow's private operational purpose and is deleted by the Operator when it is no longer required.

## Sharing and disclosure

The Application does not sell Google user data or share it with third parties. Data is processed only within the Operator-controlled n8n and NAS environment, except for communication with Google APIs required to perform the requested Drive operations.

## Security

Access to the Application, n8n instance, NAS, and OAuth credentials is restricted to the Operator. The Operator is responsible for maintaining the security of those systems and credentials.

## Revoking access and deleting data

The Operator can revoke the Application's access at any time from the [Google Account third-party connections page](https://myaccount.google.com/connections) and can delete locally retained workflow data from the self-hosted n8n and NAS environment.

## Changes to this policy

This policy may be updated if the Application's operation or data practices change. The date at the top of this page identifies the latest revision.

## Contact

Privacy questions can be sent to [pawel.pastuszka90@gmail.com](mailto:pawel.pastuszka90@gmail.com).

[Return to the application homepage](/)
