# Contributing

* External developers should fork the repository and submit a pull request in
  order to make changes to a repository.
* Developers inside the organization should create a new branch inside the
  repo and submit a pull request in order to make changes to the repo. Branches
  should be named in the format `feature/add-lasers-to-sharks`, where the suffix
  is a brief description of the change and the prefix is one of the following:
  * `feature`
  * `bug`
  * `internal` - refactoring, devops, etc.
  * `docs`
* It is highly recommended that substantial changes be discussed in an issue
  ticket before programming begins. This is also a good time to provide
  conceptual designs where applicable.
* Organization members should assign issue tickets to themselves when starting
  work on an issue. (Non-members will not have this option).
* Lines in files should be terminated with Linux-style line endings `\n`.
* Follow the language [style guides](https://github.com/EVEolve/styleguides)
  associated with the organization and its projects. If there is a case where a
  guideline is unclear or does not exist, first try to follow the implicit code
  style of the project, then the organization, then the programming language in
  general. If all else fails, use common sense and err on the side of
  readability.
* Do not push to the `master` branch.
* When creating a pull request (PR) based on an existing issue ticket, the issue
  number should be referenced in the PR by the author of the PR. Ideally this
  would be at the very top or bottom of the body of the PR description. Words 
  like `For` or `Ref` can be used to denote a direct reference, and 
  `Rel`/`Related` can denote a loose relationship to other PR's or issues.

  > For example:

  > ```text
  > For: #1

  > This PR implements a method to display the phrase "Hello World" to the user.
  > ```

  > ```text
  > Ref: #1
  > Rel: #2

  > This PR implements a method to display the phrase "Hello World" to the user.
  > ```
* Pull requests should be reviewed by at least one member of the organization.
  A pull request can be marked ready for review by the author by simply writing
  `Ready for review` in a comment. Approval can be given by replying with a
  comment stating `Approved`, or an emoji of :+1:, :100:, or :shipit:.
    * If the pull request was initiated by an organization member, that member
      should merge his/her own pull request after receiving approval.
    * If the pull request was initiated by an external developer, any
      organization member who approved the pull request can merge it on behalf
      of the external developer.
    * Depending on the complexity of the pull request, discretion can be used to
      wait for multiple approvals before merging a pull request.
* Issue and pull request numbers should only be referenced from within GitHub.
  These issue numbers should not be referenced inside a commit message, as
  it may spam the issue history if certain Git operations are executed.
* An issue ticket should only be closed after its corresponding pull request has
  been merged and tested.
* By contributing to this organization's projects, you as an author implicitly
  consent to transferring ownership of your work, which will become licensed
  under the terms of the respective project. This transfer is to be considered
  effective at the time the work is uploaded to a resource under the
  organization's control (like GitHub).
* By participating in any of the organization's projects, you implicitly warrant
  that any content contributed is either your sole work or otherwise
  unencumbered by copyright issues. As a contributor you implicitly agree to
  take responsibility and accept the consequences for any plagiarized work;
  the organization shall be held harmless.
