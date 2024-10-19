# Contributing to the project

Thank you for your interest in contributing to this project! We welcome contributions from everyone. By participating in this project, you agree to abide by the [code of conduct](CODE_OF_CONDUCT.md).

Please take a moment to review this document in order to make the contribution process easy and effective for everyone involved.

## Pull Requests

Adhering to the following process is the best way to get your work included in the project:

1. [Fork](https://help.github.com/articles/fork-a-repo/) the project, clone your fork, and configure the remotes:

  ```bash
  # Clone your fork of the repo into the current directory
  git clone https://github.com/<your-username>/my-first-contribution.git
  # Navigate to the newly cloned directory
  cd my-first-contribution
  # Assign the original repo to a remote called "upstream"
  git remote add upstream https://github.com/Open-reSource/my-first-contribution.git
  ```

2. If you cloned a while ago, get the latest changes from upstream:

  ```bash
  git checkout main
  git pull upstream main
  ```

3. Create a new topic branch off the `main` branch to contain your change:

  ```bash
  git checkout -b <topic-branch-name>
  ```

4. Commit your changes **with the following commit message**: 

  ```bash
  git commit -am "Add my GitHub username to the CONTRIBUTORS.md file"
  ```

5. Locally merge (or rebase) the upstream development branch into your topic branch:

  ```bash
  git pull [--rebase] upstream main
  ```

6. Push your topic branch up to your fork:

  ```bash
  git push origin <topic-branch-name>
  ```

7. [Open a Pull Request](https://help.github.com/articles/about-pull-requests/) **with the following title "Add my GitHub username to the CONTRIBUTORS.md file"** against the `main` branch. The description is optional.

## License

By contributing your code, you agree to license your contribution under the [MIT License](LICENSE).
