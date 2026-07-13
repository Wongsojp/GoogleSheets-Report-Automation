# Archive Management

## Overview

This module organizes generated reports into monthly archive folders in Google Drive.

The archive structure makes historical reports easier to find and manage.

---

## Process

1. Generate report.
2. Check archive folder.
3. Create the folder if it does not exist.
4. Save the report to the archive.

---

## Example Code

```javascript
const folder = DriveApp.getFolderById(folderId);

// Save report
```

---

## Result

- Organized report storage
- Easier file management
- Historical reports remain available
