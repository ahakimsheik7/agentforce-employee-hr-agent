# Topics Configuration — Agentforce Employee HR Assistant Agent

## Overview

Topics define the **conversation domains** that the AI agent understands.
Each topic represents a specific category of employee questions and determines how the Agentforce AI agent classifies user requests.

When an employee asks a question, the Agentforce system analyzes the message and maps it to the most relevant topic.

Once the correct topic is identified, the agent executes associated actions to retrieve the appropriate information.

This project includes three core topics designed to support common HR-related inquiries.

---

# Topic Architecture

The topics in this project are designed around common HR support requests.

Employee Question
↓
Agentforce Topic Classification
↓
Trigger Topic Action
↓
Retrieve Information from Salesforce

---

# Topic 1 — Employee Benefits

## Description

The **Employee Benefits** topic helps employees understand the benefits offered by the organization. This includes healthcare plans, insurance coverage, and employee wellness programs.

## Scope

This topic covers questions related to:

• Health insurance plans
• Dental and vision coverage
• Retirement plans
• Employee wellness programs
• Additional company benefits

## Example Employee Questions

• What health insurance benefits are available?
• Does the company offer dental coverage?
• What retirement plans are offered?
• Are wellness programs available for employees?

## Topic Classification Instructions

If the employee question relates to company benefits, insurance, healthcare plans, or retirement programs, classify the request under **Employee Benefits**.

## Associated Actions

Search HR Knowledge Base
Retrieve Benefits Documentation

---

# Topic 2 — PTO Policy

## Description

The **PTO Policy** topic provides employees with information about vacation policies, leave guidelines, and time-off rules.

## Scope

This topic handles questions about:

• Paid time off (PTO)
• Vacation days
• Sick leave policies
• Holiday schedules
• Leave request procedures

## Example Employee Questions

• How many PTO days do employees receive?
• What is the vacation policy?
• Can I take unpaid leave?
• How do I request time off?

## Topic Classification Instructions

If the employee question refers to vacation, leave, PTO, holidays, or absence policies, classify the request under **PTO Policy**.

## Associated Actions

Retrieve PTO policy documentation
Provide leave request instructions

---

# Topic 3 — HR Contact

## Description

The **HR Contact** topic helps employees find the appropriate HR department contact for assistance.

## Scope

This topic covers questions related to contacting HR for:

• Payroll issues
• Benefits questions
• Workplace concerns
• HR policy clarification

## Example Employee Questions

• How can I contact HR?
• Who handles payroll issues?
• Who should I speak to about benefits?
• How do I report a workplace concern?

## Topic Classification Instructions

If the employee asks about contacting HR, HR support channels, or HR department responsibilities, classify the request under **HR Contact**.

## Associated Actions

Provide HR contact information
Direct employee to HR support channels

---

# Topic Design Best Practices

Designing effective topics is critical for building accurate AI agents.

Best practices include:

• Keep topics focused on a single domain
• Avoid overlapping topic scopes
• Provide clear classification instructions
• Include multiple example questions
• Ensure topics trigger relevant actions

Well-designed topics improve the agent’s ability to correctly interpret user requests.

---

# Future Topic Enhancements

Additional topics can be added to expand the AI agent’s capabilities.

Possible future topics include:

• Payroll Questions
• Employee Onboarding
• Workplace Policies
• Training and Development

These topics would allow the agent to support a wider range of employee requests.

---

# Conclusion

Topics form the **intelligence layer of the Agentforce AI agent**.
They allow the system to understand employee requests and route them to the appropriate actions.

By organizing HR support requests into structured topics, organizations can deliver faster and more accurate responses to employees.
