* Always prefer simple solutions
* Avoid duplication of code whenever possible
    * When writing new code always check for other areas of the codebase that might already have similar code and functionality.
    * Centralize similar or duplicate functionality into appropriately named libraries for system wide use.
* Write code that takes into account the different environments: dev, test, and prod
* Be careful to only make changes that are requested and that you are confident are well understood and related to the change being requested
* When fixing an issue or bug:
    * Do not introduce a new pattern or technology without first exhausting all options for the existing implementation
    * If a new pattern or technology must be used make sure to remove the old implementation afterwards so there is no duplicate logic.
* Keep the codebase very clean and organized
* Avoid writing scripts in files if possible, especially if the script is likely only to be run once
* Avoid having files over 200*300 lines of code. Refactor at that point.
* Mocking data should never be in the primary code base.
    * Seed data, for example initial records in a database to test functionality is acceptable as it is not in the code base.
    * Never add stubbing or fake data patterns to code, that can affect testing and lead to false positive/negative results
* Never overwrite the `.env` file without first asking and confirming
