# Protected Branches

* Protected branches ensure that collaborators on your repository cannot make irrevocable (final) changes to branches.
* Enabling protected branches also allows you to enable other optional checks and requirements, like required status checks and required reviews.

* Repository owners and people with admin permissions for a repository can enforce certain workflows or requirements, before a collaborator can merge a branch in your repository by creating protected branch rules.

# Branch protection settings
_`When you create a protected branch rule in a repository, collaborators cannot force push to the protected branch or delete the branch by default`. You can enable other branch protection settings, so that collaborators:_

* Can't merge changes into the protected branch unless required status checks pass.
* Can't merge changes into the protected branch until required reviews are approved.
* Can't edit the protected branch or upload files to it from the web
* Can't merge changes into the protected branch until changes to files that have a designated code owner have been approved by that owner.
* Can't push commits to the protected branch that are not signed and verified.

_If your repository is owned by an organization, you can restrict users or teams from pushing to a protected branch._

# About branch restrictions
* Branches within repositories that belong to organizations can be configured so that only certain users or teams can push to the branch.

_Note: Organization owners and users with admin permissions for a repository are always able to push to a protected branch._

* When you enable branch restrictions, only people or teams that have been given permission can push to the protected branch. You can view and edit the users or teams with push access to a protected branch in the protected branch's settings.

_Note: If the "Include administrators" is checked and you've enabled required status checks on the branch and they fail, any attempt to push changes to the base branch will also fail, regardless of a user or team's permission status._
