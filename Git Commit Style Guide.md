# GIT Commit Style Guide
Except your init commit message, any other commit should fall into one of these
categories. So, start your commit with one of these and Write your commit message.
Commit message should be no greater than 50 characters, should begin with a capital letter and do not end with a period.

Use an imperative tone to describe what a commit does, rather than what it did. For example, use change; not changed or changes.

- `feat`: a new feature
- `fix`: a bug fix
- `docs`: changes to documentation
- `style`: formatting, missing semi colons, etc; no code change
- `refactor`: refactoring production code
- `test`: adding tests, refactoring test; no production code change
- `chore`: updating build tasks, package manager configs, etc; no production code change

``` sh
git commit -m "feat: Summarize changes in around 50 characters or less"
```