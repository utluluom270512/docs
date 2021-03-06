---
title: About branch restrictions
intro: 'Branches within repositories that belong to organizations can be configured so that only certain users, teams, or apps can push to the branch.'
product: '{% data reusables.gated-features.branch-restrictions %}'
redirect_from:
  - /articles/about-branch-restrictions
versions:
  free-pro-team: '*'
  enterprise-server: '*'
  github-ae: '*'
---

When you enable branch restrictions, only users, teams, or apps that have been given permission can push to the protected branch. For more information, see "[Enabling branch restrictions](/articles/enabling-branch-restrictions)" and "[About protected branches](/articles/about-protected-branches)." You can view and edit the users, teams, or apps with push access to a protected branch in the protected branch's settings.

You can only give push access to a protected branch to users, teams, or installed {% data variables.product.prodname_github_apps %} with `write` access to a repository.

People and apps with admin permissions to a repository are always able to push to a protected branch.

{% tip %}

**Note:** If "Include administrators" is selected, you've enabled required status checks on the branch, and if any status checks fail, any attempt to push changes to the protected branch will also fail, even for people and apps with admin permissions. For more information, see "[Enabling required status checks](/articles/enabling-required-status-checks)."

{% endtip %}

### Дополнительная литература

- "[About protected branches](/articles/about-protected-branches)"
- "[Configuring protected branches](/articles/configuring-protected-branches)"
- "[About required status checks](/articles/about-required-status-checks)"
- "[Enabling required status checks](/articles/enabling-required-status-checks)"
