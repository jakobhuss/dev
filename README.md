# Developer guidelines

## Code
  * Everything to build your project should be in the repository.
  * Have your infrastructure as code in the repository.
  * Have system variables defined in *one* location.
  
## Testing
  * Prefer integrationtests to mocking.

## Servers
  * Do not restart a Linux server to "fix" a problem, it won't.
  * Use a provision utility. Restrain from editing anything manually.
  * Use the lowest possible privileges. Using *root* is dangerous.
  
## Security
  * Use a password manager.
