---
linkTitle: Plugins
title: Creating and Using Plugins in Spinnaker
weight: 25
no_list: true
description: >
  Resources for extending Spinnaker functionality with plugins.
aliases:
  - /spinnaker-user-guides/plugin-creators/
  - /docs/spinnaker-user-guides/plugin-creators/
  - /spinnaker-user-guides/plugin-users/
  - /docs/spinnaker-user-guides/plugin-users/
---

## Spinnaker<sup>TM</sup> plugin guides:

* [Plugin Users Guide](https://spinnaker.io/guides/user/plugins)
  * Explains important concepts and files, such as `plugins.json` and `repositories.json`, that you need to deploy a plugin
  * Specifies what types of plugins you can deploy to Spinnaker
  * Shows how to deploy a plugin using Halyard


* pf4jStagePlugin deployment [walkthrough](https://spinnaker.io/guides/user/plugins/deploy-example/) using Halyard
* pf4jStagePlugin deployment [walkthrough]({{< ref "pf4j-deploy-example" >}}) using the Armory Operator


* Halyard Command Reference

  * [`hal` commands](https://spinnaker.io/reference/halyard/commands/#hal-plugins-repository) to add, update, enable, list, and delete plugin repositories
  * [`hal` commands](https://spinnaker.io/reference/halyard/commands/#hal-plugins) to add, update, enable, list, and delete plugins


* Plugin Creators Guide

  * [Overview](https://spinnaker.io/guides/developer/plugin-creators/overview/) covers taxonomy and types of plugins
  * [Test a Pipeline Stage Plugin](https://spinnaker.io/guides/developer/plugin-creators/deck-plugin/) explains how to set up a local Spinnaker environment for testing a plugin


## Plugin repositories

* [Spinnaker Plugin Examples](https://github.com/spinnaker-plugin-examples)
* [Armory Plugins](https://github.com/armory-plugins)
