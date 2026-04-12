# Calculator App Test Scenarios

## Project Overview
This document contains simple, beginner-friendly test scenarios for a calculator app.  
It is designed for a QA portfolio project.

---

## Application Name
Calculator App

## Module
Basic Arithmetic Operations

## Prepared By
[Kenneth Whitfield]

## Date
[4/8/2026]

---

## Test Scenario Table

| Scenario ID | Test Scenario | Test Data | Expected Outcome |
|------------|---------------|-----------|------------------|
| TS001 | Verify addition of two positive numbers | 5 + 3 | Result should display **8** |
| TS002 | Verify subtraction of two positive numbers | 9 - 4 | Result should display **5** |
| TS003 | Verify multiplication of two positive numbers | 6 × 2 | Result should display **12** |
| TS004 | Verify division of two positive numbers | 8 ÷ 2 | Result should display **4** |
| TS005 | Verify addition with zero | 7 + 0 | Result should display **7** |
| TS006 | Verify multiplication by zero | 9 × 0 | Result should display **0** |
| TS007 | Verify subtraction resulting in a negative number | 3 - 7 | Result should display **-4** |
| TS008 | Verify division by one | 6 ÷ 1 | Result should display **6** |
| TS009 | Verify division by zero | 5 ÷ 0 | Calculator should display **error message** or prevent calculation |
| TS010 | Verify decimal number addition | 2.5 + 1.5 | Result should display **4.0** |
| TS011 | Verify pressing equals without completing full input | 5 + = | Calculator should show correct handling or error |
| TS012 | Verify multiple operator clicks | 5 + - 2 | Calculator should ignore invalid operator sequence or show error |
| TS013 | Verify clear button functionality | Enter 8 + 2, then press C | Calculator display should reset to **0** or blank |
| TS014 | Verify large number calculation | 999999 + 1 | Result should display **1000000** |
| TS015 | Verify repeated equals behavior | 2 + 2 = = | Calculator should behave as designed consistently |

---

## Status Tracking Table

| Scenario ID | Actual Outcome | Status | Comments |
|------------|----------------|--------|----------|
| TS001 | 8 | Pass | Works as expected, no issues. | 
| TS002 | 5 | Pass | Works as expected, no issues. |
| TS003 | 12 | Pass | Works as expected, no issues. |
| TS004 | [4] | Pass | [Notes] | Works as expected, no issues. |
| TS005 | [7] | Pass | [Notes] | Works as expected, no issues. |
| TS006 | [0] | Pass | [Notes] | Works as expected, no issues. |
| TS007 | [-4] | Pass | [Notes] | Works as expected, no issues. |
| TS008 | [6] | Pass | [Notes] | Works as expected, no issues. |
| TS009 | [error message] | Pass | [Notes] | Works as expected, no issues. |
| TS010 | [4.0] | Pass | [Notes] | Works as expected, no issues. |
| TS011 | [Nothing appears] | Fail | [Notes] | Outcome was not as expected, nothing was able to show up on the application. |
| TS012 | [Addition sign is erased  for a proper equation  ] | Fail | [Notes] | Outcome was not as expected do to application fail-safe features. | 
| TS013 | [0 Appears] | Pass | [Notes] | Works as expected, no issues. |
| TS014 | [1000000] | Pass | [Notes] | Works as expected, no issues. |
| TS015 | [6] | Pass | [Notes] | Works as expected, no issues. |

---

## Conclusion
These test scenarios cover:
- Basic arithmetic operations
- Zero handling
- Negative result handling
- Decimal calculations
- Error validation
- Clear button behavior
- Edge cases

