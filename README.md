# Welcome to `cisagov` #

[![GitHub Build Status](https://github.com/cisagov/cisagov/workflows/build/badge.svg)](https://github.com/cisagov/cisagov/actions)

Welcome to `cisagov`, the GitHub home for the Cybersecurity and Infrastructure
Security Agency (CISA)!

This repository aims to make it easier to get working with GitHub and Free
and Open Source Software (FOSS) for people who work at or with CISA.

For developer-focused documentation and guides, please visit our
[development-guide repository](https://github.com/cisagov/development-guide/).

## Common questions ##

### Getting started with GitHub ###

- How do I make a GitHub account?
  - Please see the [FISMA-Ready GitHub Guide](https://github.com/fisma-ready/github)
- Why do I add my work email instead of making a separate work-only GitHub
account?
  - GitHub's terms of service say to use one account per person.
  Any commits made will be associated with the user who created them, and
  GitHub allows for granular, role-based access that can also be revoked
  when someone departs CISA.
- How do I use GitHub? Where do I start?
  - [18F Intro to GitHub](https://handbook.tts.gsa.gov/intro-to-github/)
  - [Digital.gov intro to GitHub](https://digital.gov/resources/an-introduction-github/)
  - Always remember that GitHub is a version control system, so all changes
  are saved and there is nothing we can't fix or undo.

### GitHub access ###

- How do I get access to the `cisagov` organization?
  - For federal employees, send your GitHub username to
    [github@cisa.gov](mailto:github@cisa.gov)
  - For contractors, ask your fed lead to send in your username
- How do I get put on a team within the `cisagov` organization?
  - See [Github's organizations and teams documentation](https://docs.github.com/en/organizations)
  - You'll need to contact a team member or a `cisagov` administrator
- How do I get access to a specific repository?
  - Most repositories are associated with the
  [teams](https://docs.github.com/en/organizations/organizing-members-into-teams)
  that use them, so to get access you can contact
  [github@cisa.gov](mailto:github@cisa.gov), a team member, or a
  `cisagov` administrator to get access
- How do I make a new repository?
  - [GitHub's documentation on creating a repository](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-new-repository)
  - [`cisagov`'s Project Setup guide](https://github.com/cisagov/development-guide/tree/develop/project_setup)

## Policies and content guides ##

- What belongs in `cisagov` versus another GitHub organization?
  - Here are some questions to ask when considering posting a project:
    - Does CISA use or develop the software? Is it developed by or for one of
    the groups or divisions within CISA?
      - If not, we recommend the authors create their own GitHub organization
      and post their work there
    - What source control system is in place currently?
      - Many source control systems, such as Mercurial and GitLab, can export
      the entire development history for import into GitHub - this is by far
      the preferred method
    - Is the project still under active development or is it in maintenance?
      - If the project no longer has a team performing maintenance, we
      recommend the repository be archived to make that clear to people who
      may want to use it
- What belongs on [cisa.gov](https://www.cisa.gov) versus on `cisagov`?
  - The [cisa.gov](https://www.cisa.gov) site is primarily focused at an
  audience outside of CISA, such as Critical Infrastructure partners or the
  public
  - `cisagov` is for both internal and external users, as well as partners. It exists
  specifically to share projects with the public as well as internal users.
- Working in public (dos and don'ts, best practices)
  - As a best practice, use the `cisagov` organization issue templates and
  pull request templates. These templates are available by default in
  all repositories created in the `cisagov` organization.
  - As a best practice, we require code reviews before merging pull requests.
  This is done using [branch protection](https://docs.github.com/en/github/administering-a-repository/about-protected-branches).
- When should I talk to CISA External Affairs (EA)?
  - Early and often!
- What is CISA's open source policy?
  - See [CISA's open source policy here](https://github.com/cisagov/development-guide/blob/develop/open-source-policy/policy.md)

## Feedback and contact ##

Have an idea about how to make these pages better? [File an issue!](https://github.com/cisagov/cisagov/issues/new/choose)

For any repository-specific questions or feedback, please make an issue in
that repository so the appropriate team will see it.

For more about CISA as an agency or any of its subcomponents, please visit the
[About CISA page on cisa.gov](https://www.cisa.gov/about-cisa).

For other GitHub-related questions, feel free to [email us](mailto:github@cisa.dhs.gov).

## Developer resources ##

We have a [cisagov development-guide](www.github.com/cisagov/development-guide)
repository, which contains coding standards, steps for setting up a development
environment, and other information.

## Contributing ##

We welcome contributions!  Please see [`CONTRIBUTING.md`](CONTRIBUTING.md) for
details.

## Thanks ##

We would like to thank the General Services Administration and 18F, the
Consumer Financial Protection Bureau, Department of Defense, and Office
of Management and Budget for their work in blazing the path for the use
of FOSS in the U.S. federal government.

## License ##

This project is in the worldwide [public domain](LICENSE).

This project is in the public domain within the United States, and
copyright and related rights in the work worldwide are waived through
the [CC0 1.0 Universal public domain
dedication](https://creativecommons.org/publicdomain/zero/1.0/).

All contributions to this project will be released under the CC0
dedication. By submitting a pull request, you are agreeing to comply
with this waiver of copyright interest.
