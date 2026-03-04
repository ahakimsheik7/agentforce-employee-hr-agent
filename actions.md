# Actions Configuration — Agentforce Employee HR Assistant Agent

## Overview

Actions define the **tasks the Agentforce AI agent can execute** after identifying a user's request and mapping it to a topic.

While Topics help the agent understand **what the employee is asking**, Actions determine **how the system responds and retrieves information**.

In this project, actions are designed to help employees quickly access HR-related information stored in Salesforce knowledge resources or internal documentation.

---

# Action Architecture

Employee Request
↓
Agentforce Topic Classification
↓
Associated Action Triggered
↓
Retrieve Information from Salesforce
↓
Return Response to Employee

---

# Action 1 — Search HR Knowledge Base

## Description

This action allows the AI agent to search the organization's HR knowledge base to retrieve relevant policy information.

It helps employees quickly find answers to HR-related questions without manually searching internal documentation.

## Use Cases

Employees may ask questions such as:

• What benefits does the company offer?
• What is the company PTO policy?
• What health insurance options are available?

## Action Behavior

When triggered, the action:

1. Searches HR-related knowledge articles
2. Identifies relevant documentation
3. Returns the most appropriate policy information

## Data Source

Salesforce Knowledge Articles

## Associated Topics

Employee Benefits
PTO Policy

---

# Action 2 — Retrieve Employee HR Information

## Description

This action retrieves general HR-related information that employees may need.

It can provide details about internal processes or guide employees to appropriate HR resources.

## Use Cases

Employees may ask:

• How do I update my benefits information?
• Where can I find HR documents?
• How do I request PTO?

## Action Behavior

When executed, the action:

1. Identifies the relevant HR process
2. Retrieves internal guidance or documentation
3. Provides instructions to the employee

## Data Source

Internal HR documentation and Salesforce records

## Associated Topics

Employee Benefits
PTO Policy

---

# Action 3 — Provide HR Contact Information

## Description

This action helps employees contact the appropriate HR department when additional assistance is required.

Some issues require direct HR support rather than automated responses.

## Use Cases

Employees may ask:

• How can I contact HR?
• Who handles payroll questions?
• Who should I speak to about benefits?

## Action Behavior

When triggered, the action:

1. Identifies the correct HR contact or department
2. Returns contact details
3. Provides instructions on how to reach HR support

## Data Source

Internal HR contact directory

## Associated Topics

HR Contact

---

# Action Design Best Practices

Designing effective actions ensures the AI agent provides useful and accurate responses.

Recommended best practices include:

• Ensure actions retrieve reliable data sources
• Limit each action to a specific task
• Connect actions to the appropriate topics
• Avoid redundant actions
• Validate responses before returning them to users

Properly designed actions improve the reliability and usefulness of AI agents.

---

# Future Action Enhancements

Additional actions could expand the capabilities of the HR assistant agent.

Examples include:

• Submit PTO requests automatically
• Create HR support tickets
• Update employee profile information
• Trigger HR workflow automations

These improvements would allow the AI agent to perform more advanced tasks beyond answering questions.

---

# Conclusion

Actions form the **execution layer of the Agentforce AI agent**.

After a topic is identified, the corresponding action retrieves the necessary information and returns a response to the employee.

By connecting Topics and Actions, organizations can build intelligent AI agents that automate internal support processes and improve employee productivity.
