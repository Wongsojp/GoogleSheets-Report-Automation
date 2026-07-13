# Backup System

## Overview

This module creates a backup of the active spreadsheet before important processes such as monthly closing.

The backup helps preserve data in case changes need to be reviewed later.

---

## Process

1. Get the active spreadsheet.
2. Create a copy.
3. Save the backup to a Google Drive folder.
4. Rename the backup file.

---

## Example Code

```javascript
const backup = file.makeCopy(backupName, backupFolder);
```

---

## Result

- Automatic backup
- Data preservation
- Simple recovery process
