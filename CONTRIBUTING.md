# How to Contribute

Open Data! Open Source! Get Involved! We want this tool to be useful for the 
community at large.

Contributions take many forms, from submitting issues, writing docs, 
to making code changes. We welcome it all. Don't forget to sign up for a 
[GitHub account](https://github.com/signup/free), if you haven't already.

## Getting Started

You can clone this repository locally from GitHub using the "Clone in Desktop" 
button from the main project site, or run this command in the Git Shell:

`git clone git@github.com:CityOfSantaMonica/SODA.net.git SODA`

If you want to make contributions to the project, 
[forking the project](https://help.github.com/articles/fork-a-repo) is the easiest 
way to do this. You can then clone down your fork instead:

`git clone git@github.com:MY-USERNAME-HERE/SODA.net.git SODA`

### What needs to be done?

Please check our 
[`issue tracker`](https://github.com/CityofSantaMonica/SODA.net/issues?state=open) 
for tasks which contributors can pick up.

If you've found something you'd like to contribute to, 
leave a comment in the issue so everyone is aware.

Ideally, we'd like SODA.net to support all of the functionality that 
[`soda-java`](https://github.com/socrata/soda-java) supports. 
With that in mind, this will remain a pre-1.0 release until we can incorporate some of the 
more advanced functionality like Workflow and create/update/delete on dataset structure.

## Making Changes

When you're ready to make a change, 
[create a branch](https://help.github.com/articles/fork-a-repo#create-branches) 
off the `master` branch. We use `master` as the default branch for the 
repository, and it holds the most recent contributions, so any changes you make
in master might cause conflicts down the track.

If you make focused commits (instead of one monolithic commit) and have descriptive
commit messages, this will help speed up the review process.

SODA.net also has a suite of tests (built on [NUnit 2.6.3](http://www.nunit.org/)) 
which you can run to ensure existing behavior is unchanged. If you're adding new features, 
please add some tests to keep us all sane!

### Submitting Changes

You can publish your branch from GitHub for Windows, or run this command from
the Git Shell:

`git push origin MY-BRANCH-NAME`

Once your changes are ready to be reviewed, publish the branch to GitHub an
[open a pull request](https://help.github.com/articles/using-pull-requests) 
against it.

A few tips with pull requests:

 - prefix the title with `[WIP]` to indicate this is a work-in-progress. It's
   always good to get feedback early, so don't be afraid to open the PR before it's "done".
 - use [checklists](https://github.com/blog/1375-task-lists-in-gfm-issues-pulls-comments) 
   to indicate the tasks which need to be done, so everyone knows how close you are to done.
 - add comments to the PR about things that are unclear or you would like suggestions on

Don't forget to mention in the pull request description which issue/issues are 
being addressed.

Some things that will increase the chance that your pull request is accepted.

- Follow existing code conventions. Most of what we do follows standard .NET
  conventions except in a few places.
- Include unit tests that would otherwise fail without your code, but pass with 
  it.
- Update the documentation, the surrounding comments/docs, examples elsewhere, guides, 
  whatever is affected by your contribution

# Additional Resources

- [General GitHub documentation](http://help.github.com/)

# Thank you!

Many thanks to the [octokit.net](https://github.com/octokit/octokit.net) team for the
inspiration and foundation behind these contributing guidelines.