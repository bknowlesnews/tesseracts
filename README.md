# Tesseracts 

**Tesseracts is a tool for managing well defined package archetypes within a monorepo.**

You have a **monorepo**. It's used by many teams for many projects. 
It has already solved a lot of problems by capturing the unique working state of all your code at any snapshot in time.
**But it's far from perfect...**

* Keeping external package **dependencies up to date** is **hard**
* Installing dependencies and **bootstrapping takes longer** and longer the more the repo grows because of the increasing amount of unique files to download
* **Hoisting dependencies** to a root level is **not an option** because some package dependencies **genuinely need to vary**
* Different teams manage different packages and need to **upgrade dependencies at their own pace** where breaking changes are concerned
* Keeping the monorepo in a state which can be **built from a single command** at the top level becomes **increasingly complex** as each new package introduces the opportunity to add **scripts which break convention**
* Specific tests will need to be run to confirm an upgrade doesn't have **unexpected side effects**, but where should these be defined and when should they be run?
* Creating a **new package** often takes some **work** and **configuration** to get it integrated into the build

#### Tesseracts aims to solve all these problems and more in a transparent and flexible way...

