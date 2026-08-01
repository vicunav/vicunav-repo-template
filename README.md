# GitHub Repository Template

This repository is a reusable starting point for new GitHub repositories. Creating a repository from this template copies its files and directory structure into a new, independent repository, without treating it as a fork.

## Creating a repository from this template

1. Open this template repository on GitHub.
2. Select **Use this template** and then **Create a new repository**.
3. Choose the owner, repository name, description, and visibility.
4. Select **Create repository**.
5. Clone the new repository, including its submodules:

   ```bash
   git clone --recurse-submodules https://github.com/OWNER/REPOSITORY.git
   cd REPOSITORY
   ```

If the repository was cloned without submodules, initialize them afterward:

```bash
git submodule update --init --recursive
```

After creating the repository, replace this README with project-specific documentation and set up the tooling, permissions, and branch protections the new project requires.

For more information, see the GitHub guide on [creating a repository from a template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template).
