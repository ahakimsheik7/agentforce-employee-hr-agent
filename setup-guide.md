# Setup Guide — Agentforce Employee HR Assistant Agent

This guide explains how to set up and configure the **Employee HR Assistant Agent using Salesforce Agentforce**.

Follow the steps below to reproduce the project in a Salesforce Developer Edition environment.

---

# Prerequisites

Before starting, ensure the following requirements are met:

• A Salesforce Developer Edition org with Agentforce access
• A Trailhead account
• System Administrator permissions in Salesforce

This project was developed using **Salesforce Agentforce and Einstein AI features.**

---

# Step 1 — Create Agentforce Developer Edition Org

Sign up for a special Salesforce Developer Edition with Agentforce access.

1. Open the Agentforce Developer Edition signup page.
2. Fill out the registration form.

Required fields include:

Email
Use an active email address.

Username
Choose a username formatted like an email address.
Example:

[example@agentforce.dev](mailto:example@agentforce.dev)

Note: The username must be unique across all Salesforce organizations.

3. Click **Sign Me Up**.

Salesforce will send an activation email.

4. Open the activation email.
5. Click **Verify Account**.
6. Create a password and security question.

After completing the setup, log in to the new Developer Edition org.

---

# Step 2 — Connect Developer Org to Trailhead

To complete Trailhead projects and verify challenges, connect the new org.

1. Log in to your Trailhead account.
2. Navigate to the Trailhead module challenge.
3. Click **Connect Org**.
4. Enter your Developer Edition credentials.
5. Click **Allow Access**.
6. Select **Yes! Save it** when prompted.

The org is now connected to Trailhead.

---

# Step 3 — Enable Einstein AI

Agentforce requires Einstein AI to be enabled.

1. Click the **Setup** icon.
2. Open **Setup**.

Search in the Quick Find box:

Einstein Setup

3. Open **Einstein Setup**.
4. Toggle **Turn On Einstein** to **ON**.

After enabling Einstein, refresh the Setup page.

---

# Step 4 — Enable Agentforce

Agentforce must be activated before creating agents.

1. Go to **Setup**.
2. In Quick Find, search:

Salesforce Go

3. Open **Salesforce Go**.
4. In the search box, type:

Agentforce

5. Select **Agentforce (Default)**.

Click the following buttons:

Get Started
Turn On
Confirm

Agentforce is now enabled in the Salesforce org.

---

# Step 5 — Review Agentforce Assets

Agentforce provides default Topics and Actions.

To review them:

1. Go to **Setup**.
2. Search:

Agentforce Assets

3. Open the **Agentforce Assets Library**.

You will see two tabs:

Topics
Actions

These represent the building blocks of AI agents.

Topics define conversation categories.

Actions define tasks the AI agent can execute.

---

# Step 6 — Create Employee HR Assistant Agent

Create a new AI agent.

1. Go to **Setup**.
2. Search:

Agentforce Agents

3. Click **New Agent**.

Configure the following:

Agent Name
Employee HR Assistant

Description
AI assistant that helps employees access HR policies, benefits information, and internal resources.

Agent Type
Employee Agent

Click **Save**.

---

# Step 7 — Create Topics

Topics help the AI agent classify employee questions.

Create the following topics.

Topic 1
Employee Benefits

Topic 2
PTO Policy

Topic 3
HR Contact

Each topic should include:

Description
Example user questions
Associated actions

---

# Step 8 — Configure Actions

Actions allow the AI agent to retrieve information.

Example actions:

Search HR Knowledge Base
Retrieve employee information
Provide HR contact details

Actions connect the AI agent with Salesforce data.

---

# Step 9 — Create Permission Set

Users must have access to interact with the AI agent.

1. Go to **Setup**.
2. Search:

Permission Sets

3. Click **New Permission Set**.

Name the permission set:

Employee Agent Access

Grant access to the Employee HR Assistant Agent.

Assign this permission set to users who will interact with the agent.

---

# Step 10 — Test the AI Agent

Test the agent by asking example questions.

Example test prompts:

What benefits does the company offer?

How many PTO days do employees receive?

How do I contact HR?

Verify that the AI agent correctly identifies the topic and returns an appropriate response.

---

# Conclusion

You have successfully configured the **Employee HR Assistant Agent using Salesforce Agentforce**.

This setup demonstrates how AI agents can automate internal HR support and improve employee access to company information.
