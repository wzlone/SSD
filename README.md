# SSD

## Naming Conventions

When contributing to this project, please follow these guidelines for descriptive variable and function names:

### Variables

- Use meaningful names that describe the purpose of the variable
- Avoid single-letter names except for loop counters (`i`, `j`, `k`)
- Use camelCase for variable names (e.g., `userCount`, `totalPrice`)
- Boolean variables should indicate their purpose (e.g., `isActive`, `hasPermission`, `canEdit`)

**Examples:**
| Poor Name | Better Name |
|-----------|-------------|
| `x` | `userAge` |
| `temp` | `temporaryFilePath` |
| `data` | `customerOrderDetails` |
| `n` | `numberOfItems` |

### Functions

- Use verbs that describe the action performed
- Be specific about what the function does
- Use camelCase for function names (e.g., `calculateTotalPrice`, `getUserById`)
- Functions returning booleans should start with `is`, `has`, `can`, `should`

**Examples:**
| Poor Name | Better Name |
|-----------|-------------|
| `process()` | `validateUserInput()` |
| `doIt()` | `sendEmailNotification()` |
| `handle()` | `handlePaymentSubmission()` |
| `check()` | `isValidEmail()` |
