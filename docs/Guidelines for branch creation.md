# Branch Naming Rules/Synatx
* Each branch name should be in the format: `branchType-moduleName-featureName`
* Here the branchType represents what type of branch that you are creating.
* The branchTypes are:
  - `feature` - Created when we are developing a new feature from the develop branch
  - `bugfix` -  Created when we need to make the minimum set of changes to a released build required to fix a bug.
  - `improvement`  - Created when we need to improve on the code quality, performance optimizations, Documentation Enhancements, User Interface Enhancements etc.
  - `library`  - It is rarely used in the case of Library Integration, Library Updates, Custom Modifications, Version Control.
  - `prerelease`  - It allows to publish releases with a pre-release version.
  - `release`  - Represent a complete feature set. (The only commits on the release branch are for bug fixes and important chores.)
  - `hotfix`  - Created when we need to quickly patch production releases.
      
For example:

* When we need to develop a new feature in the Banking module. So, the branch name will be `feature-BankApp-SavingsAccount`
* Suppose when we need to correct some bugs in the Banking module use - `bugfix-BankApp-FD`
  
# Commit Message format:
* For the commit Message it should has the format as `MessageType:description`
* Here are some of the Semantic Commit Message Types.
  - `feat`: New feature or functionality added
  - `fix`: Bug fix 
  - `docs`: Changes to the documentation
  - `style`: Code style changes (formatting, missing semi colons, etc)
  - `refactor`: Code refactor or restructuring without changing functionality (eg. renaming a variable)
  - `test`:  Adding or modifying tests. (Adding missing tests, refactoring tests)
  - `chore`: Maintenance tasks, build changes, or other non-functional changes (updating grunt tasks etc)
  - `perf` : Indicate improvements made to the performance of the codebase.
  - `ci`: When we make changes in the Continuous Integration, we use them.
  - `build` : Refers to changes related to the build process of a software project like build optimizations etc.
  - `revert` : Used when you want to revert the effects of one or more previous commits without deleting the commits themselves. 
    
For example:
* When we add authentication feature to a user method - `feat: Add user authentication.` 
* When we change some documentation or work with the documentation of the methods - `docs: Documented user method.`
