# Contributing code to Enigma's open source projects
Thank you for taking the time to contribute to one of Enigma's open source! 🔥 🦊 ❤️ 🤖! 🎉 👍 For a full list of projects go through the repos marked *hacktoberfest*

Before contributing, please review our [Community Participation Guidelines](https://github.com/partha2000/EnigmaCMS-Backend/blob/main/CONTRIBUTING_guidelines.md).

If you run into trouble at any point, ask for help! Check out our
[preferred communication channels.](./CONTRIBUTING_guidelines.md#communication)

Contents:
- [Beginner's guides](#beginners-guides)
- [Finding issues to work on](#finding-issues-to-work-on)
- [Creating a Pull Request](#creating-a-pull-request)
- [Merging](#merging)
- [Writing tests](#writing-tests)

## Beginner's guides
Unfamiliar with the technology we use? No problem! We were once new to this
too! Here are few guides we've compiled to help you get started:
- [Git guide](www.google.com)
- [django guide](www.google.com)
- [GraphQL guide](www.google.com)
- [MongoDB guide](www.google.com)

If these are confusing or if you have questions, please let us know!

## Finding issues to work on
**New to open source projects?** See issues labeled `good first issue` and/or 'hacktoberfest' in our project's
issues tracker (example: [placeholder](www.google.com)). These are designed to be
easier to implement so you can focus on learning our pull request workflow. *Please only
fix one of these.*

**Looking for more challenging issues?** See issues labeled `help wanted` (example:
[place-holder](www.google.com)). These are issues that are ready to be implemented without
additional product or UX discussion.

**When you find an issue you'd like to work on,** *comment on the issue* saying that
you'd like to work on it. This ensures it is still available for you to work on.

**If you want to work on a new feature**, *always file an issue first* and wait
for our team to discuss it. We want to ensure all teams (product, ui/ux, engineering)
have an opportunity to provide feedback. **Pull requests for unsolicited features
are unlikely to get merged.**

## Creating a Pull Request
Our team follows [the GitHub pull request workflow][gh workflow]: fork, branch, commit,
pull request, automated tests, review, merge. If you're new to GitHub, check out [the official
guides][gh guides] for more information.

An example commit message summary looks like, `For #5: Upgrade gradle to v1.3.0`.

Please follow these guidelines for your pull requests:

- All Pull Requests should address an issue. If your pull request doesn't have an
issue, file it!
  - GitHub search defaults to issues, not PRs, so ensuring there is an issue for your PR
  means it'll be easier to find
- The commit message summary should briefly describe what code changed in the commit, *not
the issue you're fixing.*
  - We encourage you to use the commit message body to elaborate what changed and why
- Include the issue number in your commit messages. This links your PR to the issue it's
intended to fix.
  - If your PR closes an issue, include `Closes #...` in one of your commit messages. This
  will automatically close the linked issue ([more info][auto close]).
  - If your PR has to go through a longer process, for example multiple team meetings, use the 
  `For #...` syntax to allow the linked issue to be closed at a later, more appropriate time.
- Prefer "micro commits".
  - A micro commit is a small commit that generally changes one thing.
  A single Pull Request may comprise of multiple incremental micro commits.
  - A series of micro commits should tell a story. For example, if your goal is to add a new
  icon to the toolbar, you can make a commit to add the icon asset and then make a commit to
  use the icon in the code.
  - Commits should generally not undo the work of previous commits in the same PR.
  - If you're not comfortable making micro commits, it's okay to begin contributing without
  them.
- Add a reviewer to ensure someone sees, and reviews, your pull request so it can be merged
- If the tests fail, please try to fix them! Keeping the tests passing ensures our code isn't
broken and the code is unlikely to get merged without passing tests. If you run into trouble,
ask for help!
- If there are UI changes, include a screenshot so UI/UX team can also do a visual review
- When in doubt, look at the closed PRs in the repository to follow as an example or ask
us online!

If your code is not approved, address the suggested comments, push your changes, and re-request
review from your reviewer again.

## Merging
After your code has been approved and the tests pass, your code will be merged into master
by the core team. When merging, we use GitHub's "Rebase and merge":
- We keep a linear git history for readability
- We prefer incremental commits to remain in the history
  - It's easier to read, helps with bisection, and matches repo state during review.

## Writing tests
If you think you are experienced in writing unit tests then contact someone of the core team. Though unit tests are
considered one of best practices in software development, we have intentionally kept them out to allow beginners to dive in.

### Some useful links
- [good first](https://github.com/mozilla-mobile/focus-android/labels/good%20first%20issue)
- [github workflow](https://guides.github.com/introduction/flow/)
- [github guides](https://guides.github.com/)
- [auto close](https://help.github.com/articles/closing-issues-using-keywords/)