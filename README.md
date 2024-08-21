### Pull Request Workflow

1. **Creating a Pull Request:**
   - A pull request (PR) is created when you want to merge changes from one branch into another. This allows team members to review and discuss changes before they are merged into the main branch.

2. **Reviewing a Pull Request:**
   - A reviewer is someone who checks the code changes in the PR, suggests improvements, and ensures the code meets the project's standards. They may approve, request changes, or reject the PR based on their review.

3. **Co-Authored Commits:**
   - Co-authored commits occur when multiple contributors work together on a single commit. To acknowledge all contributors, you can add a `Co-authored-by` trailer in the commit message:
     ```plaintext
     Co-authored-by: Name <email@example.com>
     ```

4. **Merging a Pull Request:**
   - Once the PR is approved, it can be merged into the main branch. Merging can be done using different strategies like **merge commit**, **squash and merge**, or **rebase and merge**:
     - **Merge Commit:** Combines all commits into a single merge commit.
     - **Squash and Merge:** Squashes all commits into a single commit before merging.
     - **Rebase and Merge:** Reapplies commits from the PR onto the base branch.

5. **Closing a Pull Request:**
   - If the changes in the PR are no longer needed or are implemented in another PR, it can be closed without merging.

### Additional Concepts

- **Pull Request Template:**
  - A markdown file that outlines a template for PRs, ensuring consistency in the information provided.

- **Issue References:**
  - PRs can reference issues to automatically close them when the PR is merged. Example:
    ```plaintext
    Closes #123
    ```

- **Draft Pull Requests:**
  - These are used for work-in-progress changes that are not yet ready for review. They can be converted to regular PRs when ready.
