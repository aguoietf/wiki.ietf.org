---
title: MGB Sandbox
description: federated entity
published: false
date: 2023-03-24T09:00:09.531Z
tags: string
editor: markdown
dateCreated: 2023-03-24T09:00:09.530Z
---

- [content-sprin[ImplementationReports](/group/anima/ImplementationReports)ts](/content-sprints)![ietf-logo-reversed-square-300dpi-transparent-background.png](/ietf-logo-reversed-square-300dpi-transparent-background.png){.align-center}# This is a sandbox page for testing only.


## Table<iframe class="embed-iframe" src="//cdn.loc.gov/loader/embed//embed-with-loader.php?uuid=958B6C7AC55F0062E0538C93F1160062&size=mediumWide&name=&type=V&image=//stream-media.loc.gov/copyright/Copyright_on_the_Internet_bg.jpg" width="512" height="450" frameborder="0" scrolling="no"></iframe>

| test |      |     |      |
| ---- | ---- | --- | ---- |
|      | test |     |      |
|      |      | tes |      |
|      | test |     | test |

> is-info test
{.is-info}

> is-warning test
{.is-warning}


```
                 +----------+
                 | List of  |+
                 | valid    ||
                 | PSAP ids ||
                 +----------+|
                  +----------+
                      *
                      * whitelist
                      *
                      V
   Incoming      +----------+    Normal
   SIP Msg       | SIP      |+   Treatment
  -------------->| Entity   ||=============>
   + Identity    |          ||(if not in whitelist)
                 +----------+|
                 +----------+
                      ||
                      ||
                      || Preferential
                      || Treatment
                      ++=============>
                        (in whitelist)

```




