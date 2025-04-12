<!--
###################################################################################
                               READ BEFORE SUBMITTING
###################################################################################

This is a PR template which comprehends 3 different types of PR: 

1. Chore PR
2. Feature PR
3. Release PR

Check the _Before Submitting_ checklist if you feel unsure which your PR type is.

===================================================================================
                               CHOOSE A PR TYPE
===================================================================================

1. Determine the PR type you are creating.
2. Delete the other PR templates which don't correspond to your PR type.
3. Ensure you comply with the _Before Submitting_ checklist and mark it as done.
   (E.g. Change "- [ ]" to "- [x]" for completed items.)
4. Submit your PR.
5. You can also delete this comment if you prefer.
-->

<!--
<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<
                              CHORE PR TEMPLATE START
<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<
-->
# Chore PR

## Before Submitting

- [ ] This is a required activity that does not directly relate to any User Stories.
- [ ] PR is linked to a standalone `chore` Task Issue: _Specify the issue here_.
- [ ] PR is from a feature branch from `development`.
- [ ] PR is being made to the `development` branch.
- [ ] Use **only** `git` conventional commits of type `style`, `docs`, `refactor`, or `chore`.

## Description

_Outline what the Pull Request achieves, and the effect it will have upon being merged to the `development` branch._

## Dependent Issues

_List dependent issues which could start to be worked on once this PR is merged._

## Affected Issues

_List affected issues which would require merging from `development` once this PR is merged._
<!--
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
                              CHORE PR TEMPLATE END
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
-->

<!--
<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<
                            FEATURE PR TEMPLATE START
<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<
-->
# Feature PR

## Before Submitting

- [ ] PR is linked to an issue: _Specify the issue here_
- [ ] PR is from feature branch created from the `development` branch.
- [ ] PR is to the `development` branch.
- [ ] `git` conventional commits.

## Description

_Outline what the Pull Request achieves, and the effect it will have upon being merged to the development branch._

## Dependent issues

_List dependent issues which could start to be worked on once this PR is merged._

## Affected Issues

_List affected issues which would require merging from `development` once this PR is merged._
<!--
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
                              FEATURE PR TEMPLATE END
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
-->

<!--
<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<
                            RELEASE PR TEMPLATE START
<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<
-->
# Release PR

## Before Submitting

- [ ] Milestone exists for release.
- [ ] Includes `docs` commits for documentation updates in new release.
- [ ] Include `CHANGELOG` changes with what the new version will introduce.
- [ ] PR is from the `development` branch.
- [ ] PR is to the `main` branch.

## New Version

_What version will this next one be?_

## Description

_Outline what this new version will introduce and the changes it will make._

## Related features

_List the related User Stories, Sub-Epics, and Epics that the Release advances or deals with._
<!--
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
                              RELEASE PR TEMPLATE END
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
-->
