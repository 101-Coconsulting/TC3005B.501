# Contribution Guidelines

This is a document to establish the expected contribution workflow for the project. It explains how the project is structured at an organization-wide level.

# Table of Contents

<ul>
    <li>
        <details open>
            <summary>
                <a href=#1-working-with-issues>1. Working with Issues</a>
            </summary>
            <ul>
                <li>
                    <a href=#11-when-to-use-issues>1.1. When to use Issues</a>
                </li>
                <li>
                    <details open>
                        <summary>
                            <a href=#12-issue-types>1.2. Issue Types</a>
                        </summary>
                        <ul>
                            <li>
                                <a href=#121-what-are-issue-types>1.2.1. What are Issue Types?</a>
                            </li>
                            <li>
                                <a href=#122-available-issue-types>1.2.2. Available Issue Types</a>
                            </li>
                            <li>
                                <a href=#123-responsibility-for-issue-types>1.2.3. Responsibility for Issue Types</a>
                            </li>
                        </ul>
                    </details>
                </li>
                <li>
                    <details open>
                        <summary>
                            <a href=#13-sub-issues>1.3. Sub-Issues</a>
                        </summary>
                        <ul>
                            <li>
                                <a href=#131-what-are-sub-issues>1.3.1. What are sub-issues?</a>
                            </li>
                            <li>
                                <a href=#132-using-sub-issues>1.3.2. Using Sub-Issues</a>
                            </li>
                        </ul>
                    </details>
                </li>
                <li>
                    <details open>
                        <summary>
                            <a href=#14-issue-forms>1.4. Issue Forms</a>
                        </summary>
                        <ul>
                            <li>
                                <a href=#141-what-are-issue-forms>1.4.1. What are Issue Forms?</a>
                            </li>
                            <li>
                                <a href=#142-using-issue-forms>1.4.2. Using Issue Forms</a>
                            </li>
                        </ul>
                    </details>
                </li>
            </ul>
        </details>
    </li>
    <li>
        <details open>
            <summary>
                <a href=#2-working-with-prs>2. Working with PRs</a>
            </summary>
            <ul>
                <li>
                    <a href=#21-when-to-use-prs>2.1. When to use PRs?</a>
                </li>
                <li>
                    <a href=#22-create-pr>2.2. Create PR</a>
                </li>
                <li>
                    <a href=#23-reviewing-prs>2.3. Reviewing PRs</a>
                </li>
                <li>
                    <a href=#24-merging-prs>2.4. Merging PRs</a>
                </li>
            </ul>
        </details>
    </li>
    <li>
        <details open>
            <summary>
                <a href=#3-feature-workflow>3. Feature Workflow</a>
            </summary>
            <ul>
                <li>
                    <a href=#31-creating-a-feature-branch>3.1. Creating a feature branch</a>
                </li>
                <li>
                    <a href=#32-commiting-changes>3.2. Commiting changes</a>
                </li>
                <li>
                    <a href=#33-pushing-changes>3.3. Pushing changes</a>
                </li>
                <li>
                    <a href=#34-pulling-changes>3.4. Pulling changes</a>
                </li>
                <li>
                    <a href=#35-test-locally>3.5. Test locally</a>
                </li>
                <li>
                    <a href=#36-PR-to-development>3.6. PR to `development`</a>
                </li>
            </ul>
        </details>
    </li>
    <li>
        <details open>
            <summary>
                <a href=#4-release-workflow>4. Release Workflow</a>
            </summary>
            <ul>
                <li>
                    <a href=#41-testing-development>4.1. Testing `development`</a>
                </li>
                <li>
                    <details open>
                        <summary>
                            <a href=#42-planning-a-release>4.2. Planning a Release</a>
                        </summary>
                        <ul>
                            <li>
                                <a href=#421-milestones>4.2.1. Milestones</a>
                            </li>
                            <li>
                                <a href=#422-git-tags-as-releases>4.2.2. Git Tags as Releases</a>
                            </li>
                            <li>
                                <a href=#423-semantic-versioning>4.2.3. Semantic Versioning</a>
                            </li>
                        </ul>
                    </details>
                </li>
                <li>
                    <details open>
                        <summary>
                            <a href=#43-publishing-a-release>4.3. Publishing a Release</a>
                        </summary>
                        <ul>
                            <li>
                                <a href=#431-creating-a-pr>4.3.1. Creating a PR</a>
                            </li>
                            <li>
                                <a href=#432-merging-a-release>4.3.2. Merging a Release</a>
                            </li>
                            <li>
                                <a href=#433-tagging-a-release>4.3.3. Tagging a Release</a>
                            </li>
                        </ul>
                    </details>
                </li>
            </ul>
        </details>
    </li>
    <li>
        <details open>
            <summary>
                <a href=#5-bug-reporting>5. Bug Reporting</a>
            </summary>
            <ul>
                <li>
                    <a href=#51-when-to-bug-report>5.1. When to Bug Report?</a>
                </li>
                <li>
                    <a href=#52-bug-report-or-reopen-issue>5.2. Bug Report or Reopen Issue?</a>
                </li>
                <li>
                    <a href=#53-creating-a-bug-report>5.3. Creating a Bug Report</a>
                </li>
            </ul>
        </details>
    </li>
</ul>

# 1. Working with Issues

[Back to top &#x21e7;](#contribution-guidelines)

## 1.1. When to use Issues

For any sort of technical, development, and software related work that is required for the project, consider utilizing issues. Issues provide a way to track work via feature development branches, issue discussions, labels, assignees, eventually Pull Requests (PR)s, and can be linked to a GitHub Project, which allows for better Project Management.

[Back to top &#x21e7;](#contribution-guidelines)

## 1.2. Issue Types

[Back to top &#x21e7;](#contribution-guidelines)

### 1.2.1. What are Issue Types?

Issue Types allow an organization to better manage the different nature of the various issues accross multiple repositories. They provide a clear distinction between issues and are ordered according to the level of specificity they have related to the project. [Learn more](https://docs.github.com/en/issues/tracking-your-work-with-issues/configuring-issues/managing-issue-types-in-an-organization)

[Back to top &#x21e7;](#contribution-guidelines)

### 1.2.2. Available Issue Types

1. Epic: Collection of User Stories for an overarching project requirement.
2. Sub-Epic: Specialized collection of User Stories for related project requirements.
3. User Story: A feature, request, idea or new functionality.
4. Task: A specific piece of work.
5. Sub-Task: A highly specific piece of work that builds towards a task.
6. Bug: An unexpected problem or behaviour.

[Back to top &#x21e7;](#contribution-guidelines)

### 1.2.3. Responsibility for Issue Types

- Project Managers (PM)s and Lead Architects (LA)s.
    - Epics
    - Sub-Epics
- Team-Leads and Repo Maintainers
    - User Stories
- Anyone
    - Tasks
    - Sub-Tasks
    - Bugs

[Back to top &#x21e7;](#contribution-guidelines)

## 1.3. Sub-Issues

[Back to top &#x21e7;](#contribution-guidelines)

### 1.3.1. What are Sub-Issues?

Sub-Issues allow for parent-child relationships for issue management, and allow for the sub-division of bigger and more complex issues into smaller, and simpler issues that can be more easily discussed, managed and developed. [Learn more](https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/adding-sub-issues)

[Back to top &#x21e7;](#contribution-guidelines)

### 1.3.2. Using Sub-Issues

The way that the various Issue Types are structured, it is expected that smaller and more specific issue types are always created as sub-issues of larger issue types.

There are 3 main ways to work with sub-issuse:

1. Create a brand new issue as a sub-issue from an existing issue.
2. Add an existing issue as a sub-issue of an existing issue.
3. Add an existing issue as a parent of an existing issue.

The parent-child relationship can span separate repositories, so it's okay to create an issue in a submodule and then declare an issue in the main repository as its parent. For Tasks and Sub-Tasks, it is best to create the issues on their corresponding repositories and then declare the appropriate User Story or Task as its parent issue.

Rather than creating them as sub-issues in the main repository and later transfering the issue to its corresponding repository. This latter workflow should be reserved for PMs and LAs only.

[Back to top &#x21e7;](#contribution-guidelines)

## 1.4. Issue Forms

### 1.4.1. What are Issue Forms?

Issue forms are an improved version of issue templates which allowed for much more structure when creating an issue. In exchange for flexibility, issue forms provide a more consistent and reliable syntax for any issues created in a repository. [Learn more](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/configuring-issue-templates-for-your-repository#creating-issue-forms)

[Back to top &#x21e7;](#contribution-guidelines)

### 1.4.2. Using Issue Forms

There are currently 5 different issue forms, all correlating to the various issue types according to the levels of granularity normally encountered in the project. To use issue forms, simply

1. Create a new issue.
2. Choose the corresponding issue form for it.
3. Fill out all of the required fields.
4. Add any missing details not pre-determined by the issue form.
    - Assignees
    - Labels
    - Milestones

[Back to top &#x21e7;](#contribution-guidelines)

# 2. Working with PRs

[Back to top &#x21e7;](#contribution-guidelines)

## 2.1. When to use PRs

TL;DR: Always. Any sort of change that has finished initial development should utilize a Pull Request to *request* (suggest) that the contents developed in some branch can be *pulled* (merged) into the `development` branch for testing and eventual inclusion in a release.

[Back to top &#x21e7;](#contribution-guidelines)

## 2.2. Create PR

Create a PR to the `development` branch, add the appropriate labels, assign the people responsible for merging the PR, and assign the people responsible for reviewing the changes proposed. In the description, explain what the changes you made add to the project, how they change the behaviour of the software, the rationale behind it, and what Task or Sub-Task it aims to resolve. It is very important that the Task or Sub-Task is also linked to the PR using GitHub, but should be done automatically if the branch was created from a particular issue in the first place. [Learn more](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/getting-started/helping-others-review-your-changes)

[Back to top &#x21e7;](#contribution-guidelines)

## 2.3. Reviewing PRs

Once the PR is created, the QA team will review the changes proposed, ensure that they do indeed build towards the intended feature, approve the changes and add a comment explaining that the changes provided do indeed contribute towards the development of the project. If, on the other hand, there are any comments to be made, which would usually be questions the reviewer has on the changes that require clarification, they can add comments both to the PR as a whole, and to individual lines or files. Comments are intended to mark that something needs attention. So they mustn't be used to say that something works as intended. Additionally, reviewers can even suggest changes while adding comments to individual lines. These suggested changes can even be applied directly on GitHub by the PR owner with a new commit, and added to modify the PR. [Learn more](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/about-pull-request-reviews)

[Back to top &#x21e7;](#contribution-guidelines)

## 2.4. Merging PRs

Once a feature has the required approving reviews, it can be merged to the `development` branch using the merge option. This will mean the related issue is marked as complete, and the feature branch is deleted. [Learn more](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/incorporating-changes-from-a-pull-request/merging-a-pull-request)

[Back to top &#x21e7;](#contribution-guidelines)

# 3. Feature Workflow

The project will follow GitHub Flow for its feature development. [Learn more](https://docs.github.com/en/get-started/using-github/github-flow)

[Back to top &#x21e7;](#contribution-guidelines)

## 3.1. Creating a feature branch

In order to start working on an issue, first a feature branch must be created from `development`, and be linked to said issue. These should be created using GitHub (or `gh` CLI) for the default name to be used: `[ issue number ]-[ issue title ]`. This automatically links the branch to said issue and it makes it clear that that issue is actively being worked on.

[Back to top &#x21e7;](#contribution-guidelines)

## 3.2. Commiting changes

Once a development branch has been created an is linked to the issue that it's developing, make and commit changes in that feature branch. The commits should follow the conventional commits standard for the commit message structure. It has 3 main parts:

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

The `<type>` cant be one of:

- `fix`
- `feat`
- `build`
- `chore`
- `ci`
- `docs`
- `style`
- `refactor`
- `perf`
- `test`

And the `<description>` must be short and start with lowercase. [Learn more](https://www.conventionalcommits.org/en/v1.0.0/)

The nature of a commit should be atomic. That is, that each commit should only encompass a single change to the code. This means that a single commit should have a clear and identifiable purpose, and not cover multiple changes simultaneously. In the future, this will make it easier to understand the commit history, more easily review proposed changes, and also revert any faulty commits and identify problems more easily. [Learn more](https://github.blog/developer-skills/github/write-better-commits-build-better-projects/)

[Back to top &#x21e7;](#contribution-guidelines)

## 3.3. Pushing changes

Once a set of commits are ready to be worked on by someone else, or can be considered a complete piece of work, they can be pushed to the remote repository. There is no need to be pushing every single commit to the remote if the commits are considered to be work in progress (WIP). Pushed commits **must** have the correct conventional commit format, and be organized in such a manner that later review process, integration, and possible revertion and bug fixing can be easily done by looking at the commit history.

[Back to top &#x21e7;](#contribution-guidelines)

## 3.4. Pulling changes

Feature branches should always have a single owner. This means that only a single person should be working in a determined feature at any point. This prevents any sort of conflicts from emerging between the local and remote feature branches. And feature branches should always be developed independently from the `development` branch. And only pull changes from it if they directly affect the development of said feature. There is no need to be constantly updating the branch to be in sync with `development`. Only when required to make development adjustments or once the development is finished and there are any conflicts that need to be fixed. [Learn more](https://git-scm.com/docs/gitworkflows#_topic_branches)

[Back to top &#x21e7;](#contribution-guidelines)

## 3.5. Test locally

Before requesting to pull any changes worked on for the feature into the `development` branch, ensure to add needed unitary and integration tests as required to identify any bugs or malfuctions in the code on its own without having to test the entire application as a whole as part of the QA workflow.

[Back to top &#x21e7;](#contribution-guidelines)

## 3.6. PR to `development`

Once a feature has been thoroughly tested locally, a PR can be created into the `development` branch to integrate the feature to the current batch of features in testing.

[Back to top &#x21e7;](#contribution-guidelines)

# 4. Release Workflow

This Workflow is intended to integrate the `development` branches into the `main` branch of a repository.

[Back to top &#x21e7;](#contribution-guidelines)

## 4.1. Testing `development`

Before considering any sort of new release, the `development` branch is intended to serve as a testing ground. Here, the QA team should conduct integration tests to ensure that any features merged into `development` and not yet released to `main` work as intended and no unforseen bugs appear once the whole system is tested.

[Back to top &#x21e7;](#contribution-guidelines)

## 4.2. Planning a Release

[Back to top &#x21e7;](#contribution-guidelines)

### 4.2.1. Milestones

GitHub allows the control and planning of new releases utilizing milestones, which outline the description of the new release, the deadline for its release, and the scope of the release by linking related issues for its completion. They allow for better project management by setting progress markers for the project, and tracking progress towards any given milestones by comparing the number of finished and unfinished issues the milestone has, by assuming that all issues are the same size. Adding or removing issues is allowed, and a milestone can be considered complete once 100% of the issues assigned to said milestone have been completed. [Learn more](https://docs.github.com/en/issues/using-labels-and-milestones-to-track-work/about-milestones)

[Back to top &#x21e7;](#contribution-guidelines)

### 4.2.2. Git Tags as Releases

GitHub consideres releases to be a specific version of the repository marked by a `git` tag. These should only exist on the `main` branch of the repository and contain the software version related to that specific release. [Learn more](https://docs.github.com/en/repositories/releasing-projects-on-github/about-releases)

[Back to top &#x21e7;](#contribution-guidelines)

### 4.2.3. Semantic Versioning

Any release implies a new software version, and it **must** utilize semantic versioning (semver), which has the format `MAJOR.MINOR.PATCH`. And the new version of any release is determined by the highest order of change introduced. So a release that introduces `MINOR` and `PATCH` changes, should be considered a new `MINOR` version. And the `MAJOR`, `MINOR` and `PATCH` are determined by the types of commits the release introduces.

- `MAJOR` to any commit type with `!` and `BREAKING CHANGES` footer.
- `MINOR` to any `feat` commit type.
- `PATCH` to any `fix` commit type.

Due to the project's development being comprised as mostly it being in a pre-release state, with the final project objective being a `1.0.0` version, all versions prior to the finish of the project should be considered `0.x.z`, starting with `0.1.0`. This means that `MINOR` and `PATCH` versions are the only types of versions that should be considered. Since `MAJOR` or `BREAKING CHANGES` apply once a stable release has been established. Hence any sort of Pre-Release `MAJOR` change should instead be treated as a `MINOR` change for semantic versioning. [Learn more](https://semver.org/)

[Back to top &#x21e7;](#contribution-guidelines)

## 4.3. Publishing a Release

[Back to top &#x21e7;](#contribution-guidelines)

### 4.3.1. Creating a PR

Once a new release is complete and tested in the `development` branch, a PR can be created to the `main` branch. This PR should include the `CHANGELOG` the new release introduces compared to the latest available release. It should also include an update to a `CHANGELOG` file [Learn more](https://keepachangelog.com/en/1.0.0/)

[Back to top &#x21e7;](#contribution-guidelines)

### 4.3.2. Merging a Release

Once the release has been apropriately reviewed and approved, it should be merged into the `main` branch utilizing the squash and rebase merge method, with the message of the commit containing the descriptions of all the commits which are being incorporated into the project for the new release. This means that the commit history for the `main` branch should only contain specific release squash commits with all the changes introduced by each release.

[Back to top &#x21e7;](#contribution-guidelines)

### 4.3.3. Tagging a Release

Each release merged to the `main` branch should include a `git` tag with the release version in the format `vMAJOR.MINOR.PATCH` and a message indicating `Release vMAJOR.MINOR.PATCH`. These types of tags **must** exist **only** in the `main` branch, but alternate tags are allowed to track progress in the `development` and feature branches.

[Back to top &#x21e7;](#contribution-guidelines)

# 5. Bug Reporting

[Back to top &#x21e7;](#contribution-guidelines)

## 5.1. When to Bug Report?

Bug reporting should only occur once a release has been made, and an error or unexpected behaviour is found to occurr in the release, a new bug report should be created to communicate that something is not working as intended when considering all modules of the software.

[Back to top &#x21e7;](#contribution-guidelines)

## 5.2. Bug Report or Reopen Issue?

If something is still in `development` and doesn't work properly, that specific feature which is not working properly should be addressed by:

1. Reverting the merge commit made to `development`.
2. Reopening the issue with a description of what was found to be malfunctioning.
3. Fixing the issue.
4. Reintegrating the issue into `development`.

[Back to top &#x21e7;](#contribution-guidelines)

## 5.3. Creating a Bug Report

The most important thing a bug report should have are:

- The intended behaviour
- The current behaviour
- The steps to reproduce such bug

Beyond this, any sort of appreciated information could perhaps be:

- Console logging information
- Error messages

And any sorf of information that would aid the developers error guessing what is wrong.

[Back to top &#x21e7;](#contribution-guidelines)
