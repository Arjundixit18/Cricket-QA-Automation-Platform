## 📌 TEST CASE FORMAT (STANDARD)

```
Test Case ID:
Test Scenario:
Preconditions:
Test Steps:
Expected Result:
Actual Result:
Status:
```

---

## 🔐 LOGIN MODULE TEST CASES

### TC-LOGIN-01

```
Test Case ID: TC-LOGIN-01
Test Scenario: Login with valid credentials
Preconditions: User is on login page
Test Steps:
1. Enter valid username
2. Enter valid password
3. Click Login
Expected Result: User should be redirected to Matches page
Actual Result: As expected
Status: Pass
```

### TC-LOGIN-02

```
Test Case ID: TC-LOGIN-02
Test Scenario: Login with invalid password
Preconditions: User is on login page
Test Steps:
1. Enter valid username
2. Enter invalid password
3. Click Login
Expected Result: Error message should be displayed
Actual Result: As expected
Status: Pass
```

### TC-LOGIN-03

```
Test Case ID: TC-LOGIN-03
Test Scenario: Login with empty fields
Preconditions: User is on login page
Test Steps:
1. Leave username empty
2. Leave password empty
3. Click Login
Expected Result: Validation message should appear
Actual Result: As expected
Status: Pass
```

---

## 🚪 LOGOUT & SESSION TESTING

### TC-LOGOUT-01

```
Test Case ID: TC-LOGOUT-01
Test Scenario: Logout from application
Preconditions: User is logged in
Test Steps:
1. Click Logout
Expected Result: User redirected to login page
Actual Result: As expected
Status: Pass
```

### TC-LOGOUT-02

```
Test Case ID: TC-LOGOUT-02
Test Scenario: Browser back button after logout
Preconditions: User has logged out
Test Steps:
1. Click browser back button
Expected Result: User should not access protected pages
Actual Result: As expected
Status: Pass
```

---

## 🏏 MATCHES PAGE TEST CASES

### TC-MATCH-01

```
Test Case ID: TC-MATCH-01
Test Scenario: View all matches
Preconditions: User logged in
Test Steps:
1. Click Matches tab
Expected Result: All matches should be displayed
Actual Result: As expected
Status: Pass
```

### TC-MATCH-02

```
Test Case ID: TC-MATCH-02
Test Scenario: Filter Live matches
Preconditions: User logged in
Test Steps:
1. Click Live filter
Expected Result: Only live matches should be displayed
Actual Result: As expected
Status: Pass
```

### TC-MATCH-03

```
Test Case ID: TC-MATCH-03
Test Scenario: Filter Upcoming matches
Preconditions: User logged in
Test Steps:
1. Click Upcoming filter
Expected Result: Only upcoming matches displayed
Actual Result: As expected
Status: Pass
```

### TC-MATCH-04

```
Test Case ID: TC-MATCH-04
Test Scenario: Search match by team name
Preconditions: User logged in
Test Steps:
1. Enter "India" in search box
Expected Result: Matches involving India should be displayed
Actual Result: As expected
Status: Pass
```

### TC-MATCH-05

```
Test Case ID: TC-MATCH-05
Test Scenario: Case-insensitive search
Preconditions: User logged in
Test Steps:
1. Enter "india" in search box
Expected Result: Matches involving India displayed
Actual Result: As expected
Status: Pass
```

---

## 📄 PAGINATION TEST CASES

### TC-PAGE-01

```
Test Case ID: TC-PAGE-01
Test Scenario: Navigate to next page
Preconditions: More than 5 records exist
Test Steps:
1. Click Next button
Expected Result: Next page records displayed
Actual Result: As expected
Status: Pass
```

### TC-PAGE-02

```
Test Case ID: TC-PAGE-02
Test Scenario: Next button disabled on last page
Preconditions: User on last page
Test Steps:
1. Observe Next button
Expected Result: Next button should be disabled
Actual Result: As expected
Status: Pass
```

---

## 👤 PLAYERS PAGE TEST CASES

### TC-PLAYER-01

```
Test Case ID: TC-PLAYER-01
Test Scenario: Display player statistics
Preconditions: User logged in
Test Steps:
1. Click Players tab
Expected Result: Player table should be displayed
Actual Result: As expected
Status: Pass
```

### TC-PLAYER-02

```
Test Case ID: TC-PLAYER-02
Test Scenario: Player with zero stats
Preconditions: Players page open
Test Steps:
1. Locate Aiden Markram
Expected Result: Runs and wickets displayed as 0
Actual Result: As expected
Status: Pass
```

### TC-PLAYER-03 (INTENTIONAL BUG)

```
Test Case ID: TC-PLAYER-03
Test Scenario: Strike rate for zero stat player
Preconditions: Players page open
Test Steps:
1. Locate Aiden Markram
Expected Result: Strike rate should display "N/A"
Actual Result: Displays "NaN"
Status: Fail
```

---

## 🏆 RANKINGS PAGE TEST CASES

### TC-RANK-01

```
Test Case ID: TC-RANK-01
Test Scenario: View team rankings
Preconditions: User logged in
Test Steps:
1. Click Rankings tab
Expected Result: Rankings table should load
Actual Result: As expected
Status: Pass
```

### TC-RANK-02

```
Test Case ID: TC-RANK-02
Test Scenario: Sort by points
Preconditions: Rankings page open
Test Steps:
1. Click Points column header
Expected Result: Table sorted by points
Actual Result: As expected
Status: Pass
```

---

## 🚫 EMPTY / NO DATA STATE TEST CASES

### TC-EMPTY-01

```
Test Case ID: TC-EMPTY-01
Test Scenario: No matches available
Preconditions: Empty state enabled
Test Steps:
1. Enable empty state
Expected Result: "No matches found" message displayed
Actual Result: As expected
Status: Pass
```
