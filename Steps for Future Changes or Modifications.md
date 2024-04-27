
### Steps for Future Changes or Modifications:

1. **Pull Latest Changes**: Before starting any work on your project, always pull the latest changes from the remote repository to ensure your local copy is up to date.
   ```bash
   git pull origin main
   ```

2. **Create a New Branch**: When working on a new feature or bug fix, create a new branch from the main branch to isolate your changes.
   ```bash
   git checkout -b feature-branch-name
   ```

3. **Make Changes**: Implement your desired changes or modifications in the project files.

4. **Stage Changes**: Add the modified files to the staging area to prepare them for commit.
   ```bash
   git add <file1> <file2> ...
   ```

5. **Commit Changes**: Commit the staged changes with a descriptive commit message.
   ```bash
   git commit -m "Description of changes"
   ```

6. **Resolve Conflicts (if any)**: If you encounter merge conflicts during a pull or merge operation, resolve them by editing the conflicted files and then commit the resolved changes.

7. **Pull Before Pushing**: Before pushing your changes to the remote repository, always pull any new changes from the remote to ensure you're not overwriting any updates.
   ```bash
   git pull origin main
   ```

8. **Push Changes**: Finally, push your committed changes to the remote repository.
   ```bash
   git push origin feature-branch-name
   ```

9. **Create Pull Request**: If you're working in a collaborative environment, create a pull request from your feature branch to the main branch on the remote repository. This allows others to review and merge your changes.
