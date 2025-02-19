---
title: Update passbolt on Red Hat
date: 2021-11-26 00:00:00 Z
description: How to update your server on Red Hat.
card_teaser: Guide for instances installed using Red Hat package.
card_title: Update for Red Hat
card_position: 10
icon: fa-redhat
categories: [hosting, update]
sidebar: hosting
layout: default
slug: redhat
permalink: /:categories/:slug.html
---

{% assign distribution = 'redhat' %}
{% assign distributionLabel = 'Red Hat' %}
{% assign distributionPackage = 'dnf' %}
{% assign webServerUser = 'nginx' %}

{% include layout/row_start.html %}
{% include layout/col_start.html column="7" %}

{% include hosting/update/package-update.md %}

{% include hosting/update/in-case-of-issues.md %}

{% include date/updated.html %}

{% include layout/col_end.html %}
{% include layout/col_start.html column="4 last push1" %}

{% include aside/message.html
    class="tldr notice"
    content="Are you experiencing issues when updating passbolt?"
    link="https://community.passbolt.com/c/installation-issues"
    ask="Ask the community!"
    button="primary"
%}
{% include aside/message.html %}
{% include layout/row_end.html %}
