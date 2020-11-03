---
id: 02-organizations
title: Setting up an Organization
sidebar_label: Setting up an Organization
slug: organizations
---


When you sign-up for the very first time, the Platformer Console automatically creates a **Personal Workspace** for you.

!!! note ""
    Your Personal Workspace is ideal for your own projects that are NOT shared across a team or an organization. If you wish to continue with the Personal Workspace you can skip this section and [start configuring a Project](./projects) in your personal workspace.

## Before you begin

Before you begin, it's important to understand the resource hierarchies and relationships with key resources involved in deploying applications on Kubernets using the Platformer Console.
[Read about these concepts](./resource-hierachies)


## Creating your Organization

=== "Console"

  1. Open <a href="https://beta.console.platformer.com/" target="_"> Platformer Console :material-open-in-new:</a>

  2. From the Admin Panel select **+ CREATE ORGANIZATION**

  3. Fill in the following mandatory* values
    - Organization Name*
    - Organization Address
    - Country*
    - Organization Domain Name* (note you will need to verify this domain in a later step)

    !!! note ""
        You can optionally use a **custom domain** if you do not own an domain and skip the domain verification steps below.

    - Support Email* (an email where Platformer staff can contact you if required)

  4. Click Continue

  5. At this stage you need to verify that you own the domain name.
    - Copy the TXT record data and verify that you or your Organization owns the domain
    - If you decide to verify it later, please copy the TXT record.

  6. Click Finish - Your organization will be created and set up on the Platformer Console.*


!!! info "Verify your Domain"
    Please note that **unless you have verified the domain name, you will not be able to create projects under this Organization**. This is a security measure to ensure that no 3rd-party or unauthorized user can create an Organization under your domain.