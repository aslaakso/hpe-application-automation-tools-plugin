# What's new in earlier versions


This page shows a history of the enhancements made to the Micro Focus Application Automation Tools Jenkins plugin.

See the [Changelog ](https://wiki.jenkins.io/display/JENKINS/Changelog)for information about beta versions and recent patches.

[What's New in version 6.5](#what's-new-in-version-6.5)

[What's New in version 6.4](#what's-new-in-version-6.4)

[What's New in version 6.3](#what's-new-in-version-6.3)

[What's New in version 6.0](#what's-new-in-version-6.0)

[What's New in version 5.9](#what's-new-in-version-5.9)

## What&#39;s New in version 6.5

Version 6.5 introduced the following enhancements:

**General**

- “github-branch-source” dependency was removed.
- Certified for Jenkins version 2.263.1.

**ALM Octane**

- New option to cache the job list for pipeline creation in ALM Octane
- Caching of Octane pipeline roots, to avoid sending non-relevant events/tasks/logs to ALM Octane
- Added ability to execute UFT tests with parameters from ALM Octane
- Bug fix: UFT test descriptions are properly formatted in ALM Octane

## What&#39;s New in version 6.4

Version 6.4 introduced the following enhancements:

**General**

- Multiple dependencies updated. You can verify your Jenkins plugins compatibility with the [plugin dependencies](https://plugins.jenkins.io/hp-application-automation-tools-plugin/#dependencies).
- Certified for Jenkins version 2.249.1.

**ALM Octane**

- Ability to configure folder for UFT Test Runner creation
- Ability to create auto-generated UFT jobs with SSH credentials
- Reduced name length of UFT auto-generated Test Runner jobs
- Added support for Configuration-as-code plugin to ALM Octane configuration
- collectPullRequestsToAlmOctane pipeline step – now supports environment parameters for all fields (including credentialsId)

**UFT One**

- Migration of ALM credentials from the Task configuration page to global configuration

## What&#39;s New in version 6.3

Version 6.3 introduced the following enhancements:

**ALM Octane**

- Ability to disable configuration

- Ability to configure jenkinsUser per ALM Octane workspace and to restrict job visibility during new pipeline creation

- Ability to configure ALM Octane allowed storage for logs

- Support for base64 encoding for jobIds (relevant for ALM Octane behind an Apache server)

- New icons indicating the connected workspaces

- Bug fix: The UFT Discovery job now populates the description of UFT API tests.

- Bug fix: Connectivity issue where ALM indicated that Jenkins was not connected, was resolved.

- Bug fix: CI pipeline jobs are automatically updated when you rename or move jobs.

**UFT One**

- Support for defining the number of iterations for UFT tests

## What&#39;s New in version 6.0

Version 6.0 introduced the following enhancements:

**ALM Octane**

- You can now SET/GET milestones on ALM Octane Pipeline configurations.


## What&#39;s New in version 5.9

Version 5.9 introduced the following enhancements:

**ALM Octane**

- Support for custom converters to test frameworks

- Improvements in logs

- Support for additional versions of the Sonarqube scanner plugin (2.6.1, 2.8.1, 2.9)

- Bug fixes

**UFT Mobile (Mobile Center)**

- Rebrand from &quot;Mobile Center&quot; to &quot;UFT Mobile&quot;

**ALM**

- Improvements in the logic of parsing test case status.

https://issues.jenkins-ci.org/browse/JENKINS-58134 

**UFT**

- Support for ALM 15.0 with SSO 

- Refactoring of HpToolsLauncher

- Bug fixes



