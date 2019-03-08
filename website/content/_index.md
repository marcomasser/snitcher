---
title: "Little Snitch Rule Groups"
---

This is a list of [rule groups](https://help.obdev.at/littlesnitch/lsc-rule-group-subscriptions) of blacklisted hosts you can subscribe to from [Little Snitch](https://www.obdev.at/products/littlesnitch/index.html) version 4.1 onwards.

These groups are generated from the raw host files on Steven Black's [unified hosts project](https://github.com/StevenBlack/hosts).

## The rule groups

- Unified (adware + malware) [subscribe][subscribe-unified], [rule group file](/rules/unified.lsrules)
- Unified + fake news [subscribe][subscribe-unified-fakenews] [rule group file](/rules/fakenews.lsrules)
- Unified + gambling [subscribe][subscribe-unified-gambling] [rule group file](/rules/gambling.lsrules)
- Unified + porn [subscribe][subscribe-unified-porn] [rule group file](/rules/porn.lsrules)
- Everything [subscribe][subscribe-everything] [rule group file](/rules/everything.lsrules)

The scripts for the rule group generator and the source for this website are at https://github.com/tastapod/snitcher.

The site was built using [Hugo](https://gohugo.io/) and uses the [vanilla-bootstrap](https://themes.gohugo.io/vanilla-bootstrap-hugo-theme/) theme.

&copy; 2019 Dan North, [all rights reserved](https://raw.githubusercontent.com/tastapod/snitcher/master/LICENSE)


[subscribe-unified]: x-littlesnitch:subscribe-rules?url=https%3A%2F%2Fsnitcher%2Edannorth%2Enet%2Frules%2Funified%2Elsrules
[subscribe-unified-fakenews]: x-littlesnitch:subscribe-rules?url=https%3A%2F%2Fsnitcher%2Edannorth%2Enet%2Frules%2Ffakenews%2Elsrules
[subscribe-unified-gambling]: x-littlesnitch:subscribe-rules?url=https%3A%2F%2Fsnitcher%2Edannorth%2Enet%2Frules%2Fgambling%2Elsrules
[subscribe-unified-porn]: x-littlesnitch:subscribe-rules?url=https%3A%2F%2Fsnitcher%2Edannorth%2Enet%2Frules%2Fporn%2Elsrules
[subscribe-everything]: x-littlesnitch:subscribe-rules?url=https%3A%2F%2Fsnitcher%2Edannorth%2Enet%2Frules%2Feverything%2Elsrules
