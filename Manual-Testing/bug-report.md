## Bug Report Format

```
Bug ID:
Title:
Module:
Severity:
Priority:
Environment:
Preconditions:
Steps to Reproduce:
Expected Result:
Actual Result:
Status:
```

---

## 🐞 BUG-001

```
Bug ID: BUG-001
Title: Strike rate displays NaN instead of N/A for player with zero balls faced
Module: Players
Severity: Medium
Priority: Medium
Environment: Chrome / Windows 10
Preconditions:
- User logged in
- Players page loaded

Steps to Reproduce:
1. Navigate to Players page
2. Locate player "Aiden Markram"
3. Observe Strike Rate column

Expected Result:
Strike rate should display "N/A" when balls faced is zero

Actual Result:
Strike rate displays "NaN" and is highlighted in red

Status: Open
```

---

## 🐞 BUG-002 (OPTIONAL – UI)

```
Bug ID: BUG-002
Title: No tooltip available for disabled pagination button
Module: Pagination
Severity: Low
Priority: Low
Environment: Chrome / Windows 10
Preconditions:
- User on last page of matches

Steps to Reproduce:
1. Navigate to last page
2. Hover over disabled Next button

Expected Result:
Tooltip explaining disabled state should appear

Actual Result:
No tooltip is displayed

Status: Open
```

---

## 🐞 BUG-003 (OPTIONAL – UX)

```
Bug ID: BUG-003
Title: Empty state reload button does not reset filters
Module: Matches
Severity: Low
Priority: Medium
Environment: Chrome / Windows 10
Preconditions:
- Empty state enabled
- Filters applied

Steps to Reproduce:
1. Apply a filter
2. Enable empty state
3. Click Reload button

Expected Result:
Filters should reset and data reload

Actual Result:
Filters remain applied

Status: Open
```
