# Contributing to SelfPass

This is an open source project, so feel free to contribute. How?

As the creators, and maintainers of this project, we're glad to share our projects and invite contributors to help us stay up to date. Please take a moment to review this document in order to make the contribution process easy and effective for everyone involved.


# Getting started

Not sure where to start? If you haven't already, take a look at the Installation Steps in the README file to get a better sense of the project. Clone the repos you're interested in, and make sure you can build and run the Project. If you can't, open an issue, and someone will try to help. Once you're up and running, there are a number of ways to participate:

# Requirements

For your contribution to be accepted:

- The changes must be approved by code review.
- Commits should be atomic and messages must be descriptive. Related issues should be mentioned by Issue number.

If the contribution doesn't meet the above criteria, you may fail our automated checks or a maintainer will discuss it with you. You can continue to improve a Pull Request by adding commits to the Seperate branch from which the you are created.

## Bug reports :bug:

A bug is a demonstrable problem that is caused by the code in the repository. Good bug reports are extremely helpful - thank you!

A good bug report shouldn't leave others needing to chase you up for more information.

Guidelines for bug reports:

* If you find a bug, please search for it in the Issues, and if it isn't already tracked, create a new issue. Fill out the "Bug Report" section of the issue template. Even if an Issue is closed, feel free to comment and add details, it will still be reviewed.
* Issues that have already been identified as a bug (note: able to reproduce) will be labelled 🐞 Bug.
* If you'd like to submit a fix for a bug, send a Pull Request and mention the Issue number.

## New Features 💡

Feature requests are welcome. But take a moment to find out whether your idea fits with the scope and aims of the project. It's up to you to make a strong case to convince the project's developers of the merits of this feature. Please provide as much detail and context as possible.

Do check if the feature request already exists. If it does, give it a thumbs-up emoji or even comment. We'd like to avoid duplicate requests.

## Creating a Pull Request 📥
Good pull requests - patches, improvements, new features - are a fantastic
help. They should remain focused in scope and avoid containing unrelated
commits.

**Please ask first** before embarking on any significant pull request (e.g.
implementing features, refactoring code, porting to a different language),
otherwise you risk spending a lot of time working on something that the
project's developers might not want to merge into the project. As far as _where_ to ask,
the feature request or bug report is the best place to go.

Please adhere to the coding conventions used throughout a project (indentation,
accurate comments, etc.) and any other requirements (such as test coverage).

Follow this process if you'd like your work considered for inclusion in the
project:

1. Fork the project, clone your fork,
   and configure the remotes:

   ```bash
   # Clone your fork of the repo into the current directory
   git clone https://Vinitha-Skeintech@bitbucket.org/umaitero/opensource_ios_selfpass.git
   # Navigate to the newly cloned directory
   cd SelfPass
   # Assign the original repo to a remote called "upstream"
   ```

2. If you cloned a while ago, get the latest changes from upstream:

   ```bash
   git checkout <dev-branch>
   git pull upstream <dev-branch>
   ```

3. Create a new topic branch (off the main project development branch) to
   contain your feature, change, or fix:

   ```bash
   git checkout -b <topic-branch-name>
   ```

4. Commit your changes in logical chunks.

5. Locally merge (or rebase) the upstream development branch into your topic branch:

   ```bash
   git pull [--rebase] upstream <dev-branch>
   ```

6. Push your topic branch up to your fork:

   ```bash
   git push origin <topic-branch-name>
   ```

7. [Open a Pull Request](https://bitbucket.org/umaitero/opensource_ios_selfpass/pull-requests/)
    with a clear title and description.

## Conventions of commit messages ✨

Adding features on repo

```bash
git commit -m "feat: message about this feature"
```

Fixing features on repo

```bash
git commit -m "fix: message about this update"
```

Removing features on repo

```bash
git commit -m "refactor: message about this" -m "BREAKING CHANGE: message about the breaking change"
```

### Our expectations on you as a contributor 🏃

We want contributors to provide ideas, keep the ship shipping and to take some of the load from others. It is non-obligatory; we’re here to get things done in an enjoyable way. 🎉

The fact that you'll have push access will allow you to:

- Avoid having to fork the project if you want to submit other pull requests as you'll be able to create branches directly on the project.
- Help triage issues, merge pull requests.
- Pick up the project if other maintainers move their focus elsewhere.

