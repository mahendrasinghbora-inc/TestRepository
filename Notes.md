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

# Enabling branch restrictions
_`Repository administrators for organizations can enforce branch restrictions so that only certain users or teams are able to push to a protected branch.`_

# Limiting interactions in your repository
_`People with owner or admin access can temporarily restrict certain users from commenting, opening issues, or creating pull requests in your public repository to enforce a period of limited activity.`_
__Note: After 24 hours, users can resume normal activity in your repository.__
* __Limit to existing users:__ Limits activity for users with accounts that are less than 24 hours old who do not have prior contributions and are not collaborators.
* __Limit to prior contributors:__ Limits activity for users who have not previously contributed and are not collaborators.
* __Limit to repository collaborators:__ Limits activity for users who are not collaborators.

# Repository permission levels for an organization
`People with owner or team maintainer roles can manage repository access with teams. Each team can have different repository access permissions.`

_There are `three types of repository permissions` available for people or teams collaborating on repositories that belong to an organization:_
* Read
* Write
* Admin

# Branch protection rules
`Define branch protection rules to disable force pushing, prevent branches from being deleted, and optionally require status checks before merging.`