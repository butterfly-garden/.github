# Contributing to Butterfly

When contributing to Butterfly, make sure that the changes you wish to make are in line with the project direction. If you are not sure about this, open an issue first, so we can discuss it.

Everyone is welcome to work on the project.

## Communication

Join [Wimpy's World Discord server](https://discord.butterfly-garden.org) where we have a 🦋`#Butterfly` channel for project collaboration.

## Issue policy

Please file any bugs you find, keeping the following in mind:

- One issue per bug. Putting multiple things in the same issue makes both discussion and completion unnecessarily complicated.
- No build issues (or other support requests). If the GitHub Actions CI build succeeds, the build problem is most likely on your side. Work it out locally, or ask on Discord.
- For bare metal issues, please include a detailed report and what you tried to do to solve the issue before opening the issue. Don't forget to add the hardware model of your machine and relevant details about it, to help us diagnose what the problem is.

## Human language policy

The following applies to all user-facing strings, code, comments, and commit messages:

- The official project language is American English with ISO 8601 dates and metric units.
- Use proper spelling, grammar, and punctuation.
- Write in an authoritative and technical tone.

Everyone is encouraged to make use of tooling (spell checkers, etc) to make this easier.

## Code submission policy

Nobody is perfect, and sometimes we mess things up. That said, here are some good dos & dont's to try and stick to:

### DO: ✅

- Conform to the Flutter coding style found here: <https://docs.flutter.dev/development/tools/formatting>.
- Choose expressive variable, function and class names. Make it as obvious as possible what the code is doing.
- Split your changes into separate, atomic commits (i.e. A commit per feature or fix, where the build, tests and the system are all functioning).
- Make sure your commits are rebased on the main branch.
- Wrap your commit messages at 72 characters.
- Write the commit message subject line in the imperative mood ("Foo: Change the way dates work", not "Foo: Changed the way dates work").
- Write your commit messages in proper English, with care and punctuation.
- Squash your commits when making revisions after a patch review.
- Add your personal copyright line to files when making substantive changes. (Optional but encouraged!)
- Check the spelling of your code, comments and commit messages.
- If you have images that go along with your code, run `optipng -strip all` on them to optimize and strip away useless metadata - this can reduce file size from multiple kilobytes to a couple hundred bytes.

### DO NOT: ❌

- Submit code that's incompatible with the project licence, typically MPL-2.0.
- Touch anything outside the stated scope of the PR.
- Iterate excessively on your design across multiple commits.
- Use weasel-words like "refactor" or "fix" to avoid explaining what's being changed.
- End commit message subject lines with a period.
- Include commented-out code.
- Attempt large architectural changes until you are familiar with the system and have worked on it for a while.
- Engage in excessive "feng shui programming" by moving code around without quantifiable benefit.
- Add jokes or other "funny" things to user-facing parts of the system.

## Pull Request Q&A

### I've submitted a PR and it passes CI. When can I expect to get some review feedback?

While unadvertised pull requests may get randomly merged by curious maintainers, you will have a much smoother time if you engage with the community on Discord.

### If my PR isn't getting attention, how long should I wait before pinging one of the project maintainers?

Ping them right away if it's something urgent! If it's less urgent, advertise your pull request on Discord and ask if someone could review it.

### Who are the project maintainers?

Maintainership is by invitation. The project maintainers at this time are:

 - [@flexiondotorg](https://github.com/flexiondotorg) (Martin Wimpress)
 - [@ymauray](https://github.com/ymauray) (Yannick Mauray)
 - [@diddledani](https://github.com/diddledani) (Dani Llewellyn)

### Is there a policy for branches/PRs that haven't been touched in X days? Should they be closed?

Not yet, we need to implement a "stalebot" at some point.

### Are there specific people to reach out to for different components?

In theory, the best person to speak with is whoever wrote most code adjacent to what you're working on. In practice, asking on Discord is usually easier/better, since that allows many people to join the discussion.

### Is Discord the place to ask for review help, or is Github preferred?

It's definitely better to ask on Discord. Due to the volume of GitHub notifications, some of us turn them off and rely on Discord for learning about review requests.

## On abandoned pull requests

Sometimes good pull requests get abandoned by the author for one reason or another. If the pull request is fundamentally good, but the author is not responding to requests, the pull request may be manually integrated with minor changes to code and commit messages.

To make this easier, we do appreciate it if contributors enable the "Allow edits from maintainers" flag on their pull requests.

## On ideologically motivated changes

This is a purely technical project. As such, it is not an appropriate arena to advertise your personal politics or religious beliefs. Any changes that appear ideologically motivated will be rejected.
