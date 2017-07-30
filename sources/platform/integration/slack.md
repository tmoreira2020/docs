page_main_title: Slack
main_section: Platform
sub_section: Integrations
page_title: Slack integration

# Slack integration
Available under the Integration Family: **Notifications**

`Slack` Integration is used to connect Shippable DevOps Assembly Lines platform so that you can send notifications to channels or rooms. 

You can create this from the integrations page. This is the information you would require to create this integration

* **Name** -- friendly name for the integration
* **WebhookUrl** -- Webhook URL to your slack channel. This can be overriden when creating a Resource. This looks like this `https://hooks.slack.com/services/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`

## Resources that use this Integration
Resources are the bulding blocks of assembly lines and some types of resource refer to Integrations by their name. The following Resources Types can created with `Slack` Integration 

* [notification]()
* [ciRepo]()

## Default Environment Variables
When you create a Resource with this integration, and use it as an `IN` or `OUT` into a Job that can execute user defined scripts, a set of environment variables are configured by the platform that may be useful to set the context before user defined scripts execute as part of the Job. These are variables available when this Resource is used

`<NAME>` is the the friendly name of the Resource

| Environment variable						| Description                         |
| ------------- 								|------------------------------------ |
| `<NAME>`\_INTEGRATION\_WEBHOOKURL		| Webhook URL of the Integration|

## Further Reading
* GKE integration
* AWS integration
* runSH job
* runCLI job
* runCI job
* How to setup CI for my git repo

## TODO
| Tasks   |      Status    |
|----------|-------------|
| Hotlinking |  Open |
| Further Reading needs thinking|  Open |