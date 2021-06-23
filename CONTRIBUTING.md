# Contributing

This project, like all lessons from [The Carpentries][c-site] ([Software Carpentry][swc-site], [Data Carpentry][dc-site], and [Library Carpentry][lc-site]), is open source,
and we welcome contributions of all kinds:
fixes to existing material,
bug reports,
and reviews of proposed changes are all welcome.

## Contributor Agreement

By contributing,
you agree that we may redistribute your work under [our license](LICENSE.md).
In exchange,
we will address your issues and/or assess your change proposal as promptly as we can,
and help you become a member of our community.
Everyone involved in [The Carpentries][c-site]
agrees to abide by our [code of conduct](CODE_OF_CONDUCT.md).

## How to Contribute

The easiest way to get started is to file an issue
to tell us about a spelling mistake,
some awkward wording,
or a factual error.
This is a good way to introduce yourself
and to meet some of our community members.

1.  If you have a [GitHub][github] account,
    or are willing to [create one][github-join],
    but do not know how to use Git,
    you can report problems or suggest improvements by [creating an issue][issues].
    This allows us to assign the item to someone
    and to respond to it in a threaded discussion.

3.  If you are comfortable with Git,
    and would like to add or change material,
    you can submit a pull request (PR).
    Instructions for doing this are [included below](#using-github).

## Where to Contribute

1.  If you wish to change this lesson,
    please work in [the lesson's GitHub repository][lesson-repo].

2.  If you wish to change CSS style files, tools,
    or HTML boilerplate for lessons or workshops stored in `_includes` or `_layouts`,
    please work in <https://github.com/carpentries/styles>.

## What to Contribute

There are many ways to contribute,
from writing new exercises and improving existing ones
to providing feedback after teaching or learning from this lesson,
and submitting [bug reports][issues]
about things that don't work, aren't clear, or are missing.
If you are looking for ideas, please see the 'Issues' tab for
a list of issues associated with this repository.

Comments on issues and reviews of pull requests are just as welcome:
we are smarter together than we are on our own.
Reviews from novices and newcomers are particularly valuable:
it's easy for people who have been using these lessons for a while
to forget how impenetrable some of this material can be,
so fresh eyes are always welcome.

## What *Not* to Contribute

The lesson is already quite long,
and we need to think carefully before adding
more concepts or tools to the material.
If you would like to add a new block of content,
i.e. more than 1-2 new sentences,
please open an issue before writing this
so you can discuss the potential addition with the lesson maintainers.

If you want to introduce a new idea,
you should (a) estimate how long it will take to teach
and (b) explain what you would take out to make room for it.
The first encourages contributors to be honest about requirements;
the second, to think hard about priorities.

We are also not looking for exercises or other material that only run on one platform.
Our workshops typically contain a mixture of Windows, macOS, and Linux users;
in order to be usable,
our lessons must run equally well on all three.

## Using GitHub

If you choose to contribute via GitHub, you may want to look at
[How to Contribute to an Open Source Project on GitHub][how-contribute].
To manage changes, we follow [GitHub flow][github-flow].
Each lesson has two maintainers who review issues and pull requests or encourage others to do so.
The maintainers are community volunteers and have final say over what gets merged into the lesson.
To use the web interface for contributing to a lesson:

1.  Fork the originating repository to your GitHub profile.
2.  Within your version of the forked repository, move to the `gh-pages` branch and
create a new branch for each significant change being made.
3.  Navigate to the file(s) you wish to change within the new branches and make revisions as required.
4.  Commit all changed files within the appropriate branches.
5.  Create individual pull requests from each of your changed branches
to the `gh-pages` branch within the originating repository.
6.  If you receive feedback, make changes using your issue-specific branches of the forked
repository and the pull requests will update automatically.
7.  Repeat as needed until all feedback has been addressed.

When starting work, please make sure your clone of the originating `gh-pages` branch is up-to-date
before creating your own revision-specific branch(es) from there.
Additionally, please only work from your newly-created branch(es) and *not*
your clone of the originating `gh-pages` branch.
Lastly, published copies of all the lessons are available in the `gh-pages` branch of the originating
repository for reference while revising.

### Authorship

We would like to credit everyone who has contributed to the lesson,
by including their name in the list of authors for the lesson.
To help us do this, please modify the `AUTHORS` file to add your details
when submitting your first pull request to the lesson repository.
It is not compulsory to include your email address when doing so,
but it may be helpful for us to contact you in future e.g.
to discuss the publication of the lesson.

## Style Guide

### Title Case

We use Title Case for all headings in the lesson, following
[the rules described by the American Psychological Association](https://apastyle.apa.org/style-grammar-guidelines/capitalization/title-case).

### Point of View

Contributions to this lesson should use _we_ instead of _I_
when writing in the first person. For example:

> We recommend writing Markdown links ‘reference-style’.

Alternatively, contributions can use _you_ when directing
or "speaking" to the hypothetical learner. For example:

> Remove the include tag for navigation links from all the pages of your site.

## Get in Touch

Conversations about the development of this lesson take place on
[the `jekyll-pages-lesson` channel in The Carpentries Slack workspace][jekyll-channel].
Before you can join that channel, you will need to
[become a member of the Slack workspace][slack-invitation].

General discussion of [The Carpentries][c-site]
happens on the [discussion mailing list][discuss-list],
which everyone is welcome to join.
You can also [reach The Carpentries Core Team by email][email].

[lesson-repo]: https://github.com/carpentries-incubator/jekyll-pages-novice
[lesson-jekyll]: https://carpentries-incubator.github.io/jekyll-pages-novice/
[email]: mailto:admin@software-carpentry.org
[dc-issues]: https://github.com/issues?q=user%3Adatacarpentry
[dc-lessons]: http://datacarpentry.org/lessons/
[dc-site]: http://datacarpentry.org/
[discuss-list]: http://lists.software-carpentry.org/listinfo/discuss
[github]: https://github.com
[github-flow]: https://guides.github.com/introduction/flow/
[github-join]: https://github.com/join
[how-contribute]: https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github
[issues]: https://guides.github.com/features/issues/
[jekyll-channel]: https://swcarpentry.slack.com/archives/C0186GK56UC
[slack-invitation]: https://swc-slack-invite.herokuapp.com/
[swc-issues]: https://github.com/issues?q=user%3Aswcarpentry
[swc-lessons]: https://software-carpentry.org/lessons/
[swc-site]: https://software-carpentry.org/
[c-site]: https://carpentries.org/
[lc-site]: https://librarycarpentry.org/
[lc-issues]: https://github.com/issues?q=user%3Alibrarycarpentry
