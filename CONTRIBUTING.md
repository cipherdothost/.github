# General contribution guidelines

Thank you for your interest in improving Cipher Host! We are a WordPress
hosting company built in the open, and we rely on the help of people
like you to make it even better.

While each repository may have its own specific contributing guidelines,
this document outlines how you can help shape the future of our company
and services in a broader sense.

## Code of conduct

[Our code of conduct](CODE_OF_CONDUCT.md) governs all interactions
within our community and repositories. Please read and understand it
before contributing. We are committed to providing a welcoming and
inclusive environment for all contributors.

## Background

First of all, it is important to state: **We appreciate your support**
in every way you choose to contribute. Cipher Host is a large project
that will only work with your help, and we are grateful for the time and
effort you are willing to invest in helping us make it better.

### Understanding how we work

There are a number of things to understand when thinking about
contributing to Cipher Host.

- **Small core team** The core development team for Cipher Host is
  small, with only three people at the moment. The team's top priorities
  right now are building the core blocks of the platform, as well as
  guiding the project's overall direction.
- **Prioritized contributions** To help us to manage our limited
  resources, we encourage starting by checking the relevant repository
  labels for issues that are marked as `help welcome`.
- **Project tooling** We use GitHub for development and most of our
  communication, but some of our team's discussions happen in other
  tools, and not all of those are publicly available.

### Project-specific considerations

- **Limitations** Some repositories will not accept many direct outside
  contributions due to their complexity, dependencies, or use case. We
  appreciate your ideas, but probably will not take many pull requests
  externally. If that is the case, you will see that reflected in the
  project's _CONTRIBUTING.md_ file.
- **Design consistency** UI and visual design elements are overseen by
  our professional designer to ensure a cohesive brand and user
  experience across the company. We work with that professional on
  visual and brand updates, so please do not submit pull requests for
  visual changes.

### Decision-making process

There is a team working on Cipher Host, not a single individual. This
core team discusses implementation choices, and maintains the final say
on which changes make it into the platform and our services.

We aim to make decisions transparently, considering community feedback
and the overall project needs. We are always open to considering future
improvements to our workflow and decision-making process.

Cipher Host is an open source company, but it is not always possible to
accept every contribution. We appreciate your understanding and patience
if your contributions are not accepted.

## Contributing

There are many ways to get involved. Here are some other ideas:

- **Documentation** Improve existing documentation or help to identify
  areas that need improvement.
- **Issue triage** Assist with categorizing new issues, reproduce
  reported bugs, test fixes, and find duplicates. A high-quality,
  validated issue list helps the core team stay on top of things.
- **Testing** Expand the test suites in our projects by writing new test
  cases and improving existing ones.
- **Code** Fix bugs, implement new features (see the sections below),
  and improve code quality. Take a look at the `good first issue` and
  `help welcome` labels in the project's issue tracker.

### Issues

Sensitive security-related issues should be reported to
[security@cipher.host](mailto:security@cipher.host). See [our security
policy](SECURITY.md) for details.

Bug reports and feature suggestions must use descriptive and concise
titles and be submitted via GitHub Issues.

Please use the search function to make sure that you are not submitting
duplicates, and that a similar report or request has not already been
resolved or rejected.

### Submitting code changes

- **Features** Please do not work on major features and ideas without
  first creating an issue for discussion. We are a small team, and are
  unlikely to be able to pick these up as quickly as you might prefer.
- **Smaller fixes** If you are fixing a bug, please open a pull request.
  Ensure that your changes include passing tests, adhere to our coding
  style, and that the PR references the issue it resolves.
- **Testing** New features should also come with additional tests to
  ensure they work as expected, and don't break existing code.

### Pull requests

Adhere to the following rules when submitting your PR:

- **Keep it small**: Avoid changing too many things at once.
- **Individual PRs**: One PR per issue, please.
- **Commit messages**: Take a moment to write meaningful commit
  messages. [Drew DeVault's post on
  this](https://drewdevault.com/2019/02/25/Using-git-with-discipline.html#the-basics-writing-good-commit-messages)
  is a good read.
- **Quality assurance**: [Review your spelling and
  grammar](https://languagetool.org/).
- **Testing**: Write tests and ensure your changes do not break any
  existing functionality.
- **Documentation**: Update or write documentation as needed.
- **Coding style**: Maintain the style of the codebase in your
  contributions.

Remember to sign-off on your commits by running `git commit --signoff`
before pushing. To understand what this means, read [the Linux Kernel
Developer's Certificate of
Origin](https://www.kernel.org/doc/html/latest/process/submitting-patches.html#sign-your-work-the-developer-s-certificate-of-origin).

## License

Unless otherwise noted, by contributing to a Cipher Host project you
agree to license your contributions under the current license of the
repository in question, which is usually located at `/LICENSE.md`.

## Attribution

These contribution guidelines are based on the [Mastodon contributing
guidelines](https://github.com/mastodon/.github/blob/main/CONTRIBUTING.md).
