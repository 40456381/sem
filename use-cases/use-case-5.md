# USE CASE: 5 Allow new employee's details to be added as a HR advisor

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want to add a new employee's details so that I can ensure the new employee is paid.

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the employee details. Database available to INSERT into.

### Success End Condition

New employee is added to the database

### Failed End Condition

No employee is saved

### Primary Actor

HR Advisor.

### Trigger

New enterant to the the company.

## MAIN SUCCESS SCENARIO

1. New staff member joins the company
2. HR advisor captures employee details
3. HR advisor uploads the information to the database
4. System returns success message

## EXTENSIONS

2. **not all details are available**:
    1. HR advisor waits on information

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0