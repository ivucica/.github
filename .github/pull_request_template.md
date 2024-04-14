touched/section: One line summary under 80 characters.

This pull request addresses XYZ. The longer description is written in
multiple paragraphs, preferably broken into max 80 characters per
line.

The above is an example of a good pull request summary. Please, treat the
pull request as _possibly_ the only commit message that will survive the
squash; it is possible that multiple commits on your pull request will all
be used, so use the same suggestions as below for each commit message; but,
pull request message itself should also be a valid single commit's message.

Reference an issue using syntax such as #123456. Or if closing a bug, state
in a separate paragraph near the bottom:

```
Closes #123456
```

If other people contributed, add near bottom of your pull request message:

```
Signed-off-by: Other Person <their@email.com>
```

Other semantic tags / "trailers" at the bottom of the commit message are also
welcome -- they should be in the same paragraph on separate lines. Examples
include [On-behalf-of] or [Co-authored-by]:

```
On-behalf-of: @some-org <contact@email.com>
Co-authored-by: Other Person <their@email.com>
```

[On-behalf-of]: https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/creating-a-commit-on-behalf-of-an-organization

Prefer squashable pull request, unless each commit in the chain is semantically
separate from others (i.e. there is a reason to keep them separate in history).
Do not send merge commits as part of the pull request; they will be rejected.
Where possible, prefer executing rebase yourself; pull requests that are not
cleanly rebaseable (i.e. have to be merged carefully) will likely be rejected.

Most of the [Udacity style guide](https://udacity.github.io/git-styleguide/)
for Git is a good idea, but it is not a gospel (and specifying what is changed
is, for my work, slightly preferable over the type).

Fixes: #1
