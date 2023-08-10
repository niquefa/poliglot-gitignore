# Contributing Guidelines for polyglot-gitignore

Thanks for your interest in contributing to `polyglot-gitignore`! This project aims to maintain a `.gitignore` file that's suitable for folders with multiple languages at the same time.

## Guidelines

1. **Check Existing Entries**: Before adding a new entry, ensure it doesn't already exist. Duplicates will clutter the file.

2. **Language Specificity**: When adding new entries, make sure they are universally applicable to the programming language or framework. Avoid entries that are specific to certain tools or editors unless widely used by the community.

3. **Organization**: Keep entries grouped by the programming language or technology. For example, group all Python-related entries together.

4. **Commenting**: Precede each section (or programming language) with a comment explaining which language or tool it relates to. This makes it easier for others to find and modify related rules.

   ```gitignore
   # --- PYTHON --- 
   *.pyc

## How to Contribute

1. **Fork the Repository**: If you're unfamiliar with this, GitHub has a guide on [how to fork a repository](https://docs.github.com/en/get-started/quickstart/fork-a-repo).

2. **Clone Your Fork**: Once forked, clone it to your local machine.

   ```bash
   git clone https://github.com/YOUR-USERNAME/polyglot-gitignore.git

## How to Contribute

1. **Fork the Repository**: If you're unfamiliar with this, GitHub has a guide on [how to fork a repository](https://docs.github.com/en/get-started/quickstart/fork-a-repo).

2. **Clone Your Fork**: Once forked, clone it to your local machine.

   ```bash
   git clone https://github.com/YOUR-USERNAME/polyglot-gitignore.git
    ```

3. **Make Your Changes**: Navigate to the .gitignore file and input your additions or modifications. Ensure your changes are clear and meaningful.

3. **Commit Your Updates**: After finalizing your edits, commit them with a descriptive commit message that encapsulates your changes.

```
git add .
git commit -m "Add/Update [LANGUAGE] rules"
```

4. **Push to Your Fork**: Once your changes are committed, push your branch to your forked repository on GitHub.

```
git push origin feature/my-new-feature
```
5. **Initiate a Pull Request (PR)**: Go to the polyglot-gitignore repository and click "New Pull Request". Make sure you're comparing the main branch of the original repository with the branch you've pushed to your fork. Fill in the necessary details about your changes and then submit your PR.

6. **Wait for Feedback**: After submitting, the maintainers or other contributors will review your PR. They may provide feedback or ask for changes. Ensure you monitor your PR and respond to any comments or suggestions.

7. **Implementing Feedback**: If there are requested changes, make them on your branch and then commit and push them. The PR will automatically update.

8. **Final Steps**: Once your PR is approved, it will be merged into the main repository. Congratulations on your contribution!