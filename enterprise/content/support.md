---

title: 'Camunda Enterprise Support Guide'
weight: 30

menu:
  main:
    name: "Support"
    identifier: "enterprise-support"

---

This guide is intended to help you get the support you need quickly and conveniently. This document includes information about contacting technical support, description of response times, and online resources.


# How to Create a Support Issue

Based on the agreed SLA (Service Level Agreement), you can contact our support service with your questions, wishes and problems.
To create a new support issue, follow the instructions below. To shorten the processing time, please provide us with as much information as possible.

{{< img src="../img/jira-create-support-issue.png" title="Create Support Issue" >}}

* Go to our [JIRA support system](https://jira.camunda.com/projects/SUPPORT/queues)
* Select `Create Issue`
* Select `Support` as **project** and choose the desired [issue type]({{< relref "#issue-types" >}}).
* Give the ticket a meaningful **summary**
* You can give your ticket a [**priority**]({{< relref "#priority-level" >}}) depending on how urgent the issue is for you.
* Provide us with a date in case of important **deadlines** that need to be reached.
* Enter a detailed **description** of your issue. Make use of the provided template in the description filed (Reproduce steps, Problem, Expected behavior, etc.). In order to represent code snippets in a more readable way use the [JIRA text formatting]({{< relref "#text-formatting" >}}).
* **Attachments** like screenshots, log files, stack traces or BPMN files help us to find and reproduce your bug faster. If possible provide log files and stack traces as plain text file.
* For bug reports and help requests, it is important to know which **environment** you use. Inform us about the used Camunda Platform version, application server, database and everything else that seems to be important for your issue.


## Issue Types

We distinguish three types of issues:

<table class="table table-bordered">
  <thead>
  <tr class="success">
    <th>Issue Type</th>
    <th>Description</th>
    <th>Important Notes</th>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td>Bug Report<img class="img-responsive" src="../img/jira-bug-report.png"/></td>
    <td>File a Bug Report if a feature of the system doesn't work properly.</td>
    <td>Do not file Feature Requests as Bug Reports, even if you think that it is a really vital feature without which the product seems unusable.</td>
  </tr>
  <tr>
    <td>Feature Request<img class="img-responsive" src="../img/jira-feature-request.png"/></td>
    <td>Any missing features can be filed here.</td>
    <td>A Feature Request might be declined with an explanation about why it will not be part of the product. Otherwise, it is usually placed on the road-map and we inform you about status changes. Please add some information about your use case and why the feature is important to you.</td>
  </tr>
  <tr>
    <td>Help Request<img class="img-responsive" src="../img/jira-help-request.png"/></td>
    <td>File any questions you have that are unrelated to Bug Reports or Feature Requests as Help Requests.</td>
    <td></td>
  </tr>
  </tbody>
</table>

## Self-Service Help Request

Apart from general help requests, we have four types of self-service help requests. The following self-service requests allow you to receive and change information faster. Select the `Help Request Type` and allow the `Description` to autopopulate then submit the ticket.

{{< img src="../img/jira-self-service-request.png" title="Self Service Issue" >}}

<table class="table table-bordered">
  <thead>
  <tr class="success">
    <th>Help Request Type</th>
    <th>Description</th>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td>I need the Camunda Hotline information</td>
    <td>This will provide you the Camunda Hotline number.</td>
  </tr>
  <tr>
    <td>I need my Camunda license key</td>
    <td>This will provide your organization's Camunda license key.</td>
  </tr>
  <tr>
    <td>I need the credentials for downloading Camunda</td>
    <td>This will provide your account credentials for downloading Camunda.</td>
  </tr>
    <tr>
    <td>I want to reset the company account password (Camunda download credentials)</td>
    <td>This will guide you through the process of changing the password for your company account.</td>
  </tr>
  </tbody>
</table>

## Priority Level

You can prioritize issues depending on the impact of an issue on your system. Feature Requests and Help Requests are always prioritized as L3 - Default.

<table class="table table-bordered">
  <thead>
  <tr class="success">
    <th>Priority Level</th>
    <th>Description</th>
    <th>Important Notes</th>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td>L1 <img class="img-responsive" src="../img/jira-blocker.png"/>Blocker</td>
    <td>Total failure of the core components of the contract software (specifically process engine) or occurrence of errors that make useability in the current productive operation impossible.</td>
    <td><b>Production mode only!</b><br>Bug Reports, Help Requests
	</td>
  </tr>
  <tr>
    <td>L2 <img class="img-responsive" src="../img/jira-major.png"/>Critical</td>
    <td>Use of the contractual software greatly restricted, troubleshooting urgently needed.</td>
    <td>Bug Reports, Help Requests</td>
  </tr>
  <tr>
    <td>L3 <img class="img-responsive" src="../img/jira-minor.png"/>Default</td>
    <td>Less critical errors, help requests, feature requests.</td>
    <td>Bug Reports, Feature Requests, Help Requests</td>
  </tr>
  </tbody>
</table>


## Text Formatting

JIRA offers the possibility to format text fields and comments using the Wiki Style Renderer. This offers a variety of formatting options, among which the option of adding preformatted code to your issues. To display a preview of your text in formatted form, hit the preview button at the bottom left of text fields.
You can click the help icon or go to the JIRA [Text Formatting Notation Help](https://jira.atlassian.com/secure/WikiRendererHelpAction.jspa?section=all) to find additional information.


## Visibility of JIRA Tickets

JIRA tickets will be shared with all your support contacts automatically.

{{< img src="../img/jira-watcher.png" title="JIRA Watcher" >}}

By clicking the watcher bubble you can see who is following the ticket. Here you can add or remove watchers. Please note that you can only add users who are entitled Camunda enterprise support contacts, otherwise you will get an error message stating that the user with that email address is not found.

# Phone Support

Based on your support contract (Service Level Agreement), you could also reach out to Camunda technical support via phone. You can find the support hotline number in your contract. 

You can reach Technical Support by calling our Toll-Free support hotline phone number if calling from USA. Please note that the German number can be used from all other countries, but in this case, the call may not be free of charge.  

## How does support hotline work?
Support hotline helps you to connect to Camunda technical support for an immediate assistance with your case. Your call is received directly to our in-house technical support team (no external call center). 

Please find below the instructions on how to make use of support hotline.

* Dial in phone number provided in the contract
* The IVR would prompt you to enter service pin. The service pin is a 5-digit number provided with the contract. This helps us in authenticating you to your account.
* If service pin is handy, then please enter it.  
* If you do not have service pin handy, just press the hash key (#) instead.
* You will now be connected to Camunda technical support


