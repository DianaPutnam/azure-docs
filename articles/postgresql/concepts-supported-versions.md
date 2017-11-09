---
title: Supported versions in Azure Database for PostgreSQL | Microsoft Docs
description: Describes the supported versions in Azure Database for PostgreSQL.
services: postgresql
author: kamathsun
ms.author: sukamat
manager: jhubbard
editor: jasonwhowell
ms.service: postgresql
ms.topic: article
ms.date: 11/09/2017
---
# Supported PostgreSQL Database Versions
There are three types of PostgreSQL Database updates that Microsoft supports:

•	Major version (e.g. PostgreSQL 9.5 to 9.6) - Microsoft will support within 90 days of release.

•	Minor version (e.g. PostgreSQL 9.6.x to 9.6.y) – Microsoft will support within 60 days of release. 

•	Hotfixes & security patches – Microsoft will support as soon as possible.

## Major versions
Microsoft aims to support n-2 major versions of the PostgreSQL engine in the Azure Database for PostgreSQL service, meaning the currently released major version (n) and the two prior major versions (-2).  When a new major version is released, for example PostgreSQL Version 10, Microsoft aims to support the new version within 90 days of the communitity release.  Refer to the [PostgreSQL documentation](https://www.postgresql.org/docs/10/static/index.html) to learn more about improvements and fixes in PostgreSQL 10.1.

Azure Database for PostgreSQL currently supports the following major versions:

## PostgreSQL Version

## PostgreSQL Version 9.6.2
Refer to the [PostgreSQL documentation](https://www.postgresql.org/docs/9.6/static/release-9-6-2.html) to learn more about improvements and fixes in PostgreSQL 9.6.2.

## PostgreSQL Version 9.5.7
Refer to the [PostgreSQL documentation](https://www.postgresql.org/docs/9.5/static/release-9-5-7.html) to learn about improvements and fixes in PostgreSQL 9.5.7.

## Managing updates and upgrades
Azure Database for PostgreSQL automatically manages patching for minor version updates. Currently, in public preview, major version upgrade is not supported. For example, upgrading from PostgreSQL 9.5 to PostgreSQL 9.6 is not supported.

## Next steps
For information about the support of different PostgreSQL extensions, see [PostgreSQL Extensions](concepts-extensions.md)
