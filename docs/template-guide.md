# Guide: Using the OKR Template with LLM Tools

This guide explains how to use the OKR (Objectives and Key Results) template with Large Language Model (LLM) tools like Anthropic's Console or OpenAI's Playground. The template is designed to help generate well-structured OKRs based on specific inputs.

## Table of Contents

1. [Template Overview](#template-overview)
2. [Using the Template](#using-the-template)
3. [Example: Anthropic Console](#example-anthropic-console)
4. [Example: OpenAI Playground](#example-openai-playground)
5. [Tips for Best Results](#tips-for-best-results)
6. [Contributing](#contributing)

## Template Overview

The template is designed to generate OKRs based on the following inputs:

- `{{NAME}}`: The name of the entity (company, team, individual) for which OKRs are being created.
- `{{LEVEL}}`: The scope of the OKRs (e.g., company, product, team, or individual).
- `{{CONTEXT}}`: Background information about the entity.
- `{{RELATED_OKRS}}`: OKRs from peer teams or individuals for alignment.
- `{{ROUGH_IDEAS}}`: Initial thoughts or concepts for objectives and key results.
- `{{ADDITIONAL_DETAILS}}`: Extra information, timelines, or constraints to consider.

## Using the Template

1. Copy the entire template from the [`templates/okr.md`](../templates/okr.md) file. Make sure to copy the raw file content, not the rendered markdown.
2. Paste it into your chosen LLM tool (e.g., Anthropic Console, OpenAI Playground).
3. Replace the placeholder variables (e.g., `{{NAME}}`, `{{LEVEL}}`) with your specific information.
4. Submit the prompt to the LLM tool.
5. Review and refine the generated OKRs as needed.

## Example: Anthropic Console

Here's how you might use the template with Anthropic's Console:

1. Open Anthropic Console and start a new conversation.
2. Paste the entire template into the input box.
3. Replace the variables with your specific information. For example:

```
<name>ZipThought Engineering Team</name>
<level>Team</level>
<context>ZipThought is a SaaS company developing a collaborative project management tool. The engineering team is responsible for backend infrastructure and API development.</context>
<related>Product Team OKR: Increase user engagement by 25% this quarter</related>
<rough_ideas>Improve API performance, enhance scalability, implement new features</rough_ideas>
<additional_details>We have a major product release planned for the end of the quarter. The team consists of 5 backend engineers.</additional_details>
```

4. Submit the prompt and review the generated OKRs.
5. If needed, ask for refinements or clarifications.

## Example: OpenAI Playground

The process for OpenAI Playground is similar:

1. Go to OpenAI Playground.
2. Paste the entire template into the input area.
3. Replace the variables as in the Anthropic Console example.
4. Set the model (e.g., GPT-4) and adjust parameters if desired.
5. Click "Submit" to generate the OKRs.
6. Review the output and iterate if necessary.

## Tips for Best Results

1. Be as specific as possible in your inputs, especially in the `{{CONTEXT}}` and `{{ROUGH_IDEAS}}` sections.
2. Ensure that `{{RELATED_OKRS}}` align with the level you're creating OKRs for.
3. Use the `{{ADDITIONAL_DETAILS}}` section to provide any constraints or important information that should be considered.
4. After generating OKRs, review them critically. Ensure they are ambitious yet achievable, and that key results are specific and measurable.
5. Don't hesitate to ask the LLM for revisions or explanations if the initial output isn't quite what you need.

Remember, while LLM tools can provide a great starting point, the final OKRs should always be reviewed and adjusted by human stakeholders to ensure they truly align with your organization's goals and capabilities.
