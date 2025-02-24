---
title: Controlling access to larger runners
intro: 'Puedes utilizar políticas para limitar el acceso a los {% data variables.actions.hosted_runner %} que se hayan agregado a una organización o empresa.'
product: '{% data reusables.gated-features.hosted-runners %}'
versions:
  feature: actions-hosted-runners
type: tutorial
shortTitle: 'Controlling access to {% data variables.actions.hosted_runner %}s'
---

{% data reusables.actions.enterprise-beta %}
{% data reusables.actions.enterprise-github-hosted-runners %}

## About runner groups

{% data reusables.actions.about-runner-groups %} {% ifversion fpt %}For more information, see the [{% data variables.product.prodname_ghe_cloud %} documentation](/enterprise-cloud@latest/actions/using-github-hosted-runners/controlling-access-to-larger-runners).{% endif %}

{% ifversion ghec or ghes or ghae %}

## Creating a runner group for an organization

{% data reusables.actions.hosted-runner-security-admonition %}
{% data reusables.actions.creating-a-runner-group-for-an-organization %}

## Creating a runner group for an enterprise

{% data reusables.actions.hosted-runner-security-admonition %}
{% data reusables.actions.creating-a-runner-group-for-an-enterprise %}

{% endif %}

## Changing the access policy of a runner group

{% data reusables.actions.hosted-runner-security-admonition %}
{% data reusables.actions.changing-the-access-policy-of-a-runner-group %}

## Cambiar el nombre de un grupo de ejectuores

{% data reusables.actions.changing-the-name-of-a-runner-group %}

{% ifversion ghec or ghes or ghae %}
## Moving a runner to a group

{% data reusables.actions.moving-a-runner-to-a-group %}

## Removing a runner group

{% data reusables.actions.removing-a-runner-group %}

{% endif %}
