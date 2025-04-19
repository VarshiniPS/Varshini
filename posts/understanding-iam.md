---
layout: post
title: "Understanding IAM"
---

AWS IAM (Identity and Access Management) is how AWS controls who can access what. It helps you define users, groups, roles, and policies.

### Key Concepts
- **Users**: Individual accounts with credentials.
- **Groups**: Collections of users.
- **Roles**: Temporary access with permissions.
- **Policies**: Rules written in JSON to allow/deny access.

```json
{
  "Effect": "Allow",
  "Action": "s3:*",
  "Resource": "*"
}
