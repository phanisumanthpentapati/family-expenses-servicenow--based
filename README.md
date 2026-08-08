# Family Expenses Management System

## Description
A ServiceNow application for managing daily family expenses
and automatically maintaining daily expense summaries.

## ServiceNow Features Used
- Custom Tables
- Number Maintenance
- Business Rules
- Auto populating Fields
- GlideRecord
- Table Relationships
- Related Lists
- Update Sets

## Tables
- Daily Expenses
- Family Expenses

## Automation
Daily expenses are automatically aggregated into the
corresponding Family Expenses record based on date.

## Business Rule logic

The Business Rule automatically maintains the Family Expenses
summary based on the Daily Expenses entered for each date.

### Functionality

- Checks whether a Family Expenses record exists for the selected date.
- If it exists, adds the new expense amount to the existing total.
- Updates the expense details.
- If no record exists, creates a new Family Expenses record.
