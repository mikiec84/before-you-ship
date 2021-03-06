---
title: ATOs
---

An Authority to Operate (ATO) is a complex security review process that is required before you can deploy anything on the public web. See also: [the more formal definition](https://github.com/fisma-ready/introduction#introduction).

Before a system is made publicly accessible on the Internet, it must go through either the full ATO process or a 90-Day [Limited Authority to Operate](types/). Systems can be made available for use in an extremely limited capacity if they meet the [pre-authorization criteria](types/#pre-authorization).

While the ATO is the final compliance step that's required before launching an application, you will want to **start the process as soon as possible** after your project gets off the ground.

### Starting the ATO process

To start the ATO process, follow the [walkthrough](walkthrough/).

### Re-authorization

If a system substantively changes, it'll need a new ATO. Examples for triggers for a new ATO include changes to:

* Encryption methodologies
* Administrative functionality within the application
* The kinds of information you store (e.g. [personally identifiable information](../security/pii/))

The 18F Infrastructure team will make this determination – please [open a new issue](https://github.com/18F/Infrastructure/issues/new?title=ATO+re-authorization+for+%3Cproject%3E?) if you think you have made a change that may require a new ATO.
