---
layout: post
title: "Test Resources"
date: 2024-09-12
---

这里是你的文章内容。

# Cloud

# VM

# Database

## backup policy
backup prosteSQL every week. full dump
backup every days, increment.

#!/bin/bash
TIMESTAMP=$(date +"%F")
BACKUP_DIR="/path/to/backup/directory"
DATABASE_NAME="your_database_name"
USER="your_database_user"
PGPASSWORD="your_database_password"

export PGPASSWORD
mkdir -p $BACKUP_DIR
pg_dump -U $USER $DATABASE_NAME > $BACKUP_DIR/$DATABASE_NAME-$TIMESTAMP.sql
unset PGPASSWORD



# Storage
  Cloudfare R2 OBS upload speed 200KB/s

# test links
https://lobechatdb.serpentleap.com
backup:
https://lobechat.serpentleap.com
