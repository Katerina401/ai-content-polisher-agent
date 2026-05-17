# AI Content Polisher Agent

This is a multi-agent workflow prototype for Chinese content quality optimization.

The project focuses on helping Chinese content creators improve AI-generated drafts by diagnosing and reducing common "AI flavor" issues, such as mechanical structure, repetitive paragraph rhythm, vague expression, over-explaining, and platform style mismatch.

The repository is maintained as a documentation-first prototype for MiMo Token plan application review. It does not include production credentials, private data, API keys, or live service configuration.

## Core Scenarios

- WeChat public account article polishing
- Xiaohongshu copywriting optimization
- Short video script refinement
- Novel prose AI-flavor diagnosis
- Marketing copy naturalization

## Multi-Agent Workflow

1. **Diagnosis Agent**  
   Detects template-like expressions, vague wording, repetitive structure, over-explaining, and unnatural rhythm.

2. **Platform Style Agent**  
   Chooses different optimization strategies for WeChat articles, Xiaohongshu posts, video scripts, novel prose, and marketing copy.

3. **Rewrite Agent**  
   Rewrites the content while preserving the original meaning and improving naturalness.

4. **Self-Check Agent**  
   Checks whether the rewritten content changes the original meaning, adds unsupported facts, or still sounds overly mechanical.

5. **Coordinator Agent**  
   Integrates multi-step outputs and produces the final optimized version.

## Project Structure

```text
docs/
  project-overview.md     Project background, users, pain points, and scenarios
  workflow.md             Multi-agent workflow design
  evaluation-plan.md      Prototype evaluation metrics and test plan
prompts/
  diagnosis-agent.md      Prompt framework for AI-flavor diagnosis
  rewrite-agent.md        Prompt framework for naturalized rewriting
samples/
  sample-input.md         Example Chinese draft with strong AI flavor
  sample-output.md        Example diagnosis and improved version
README.md                 Repository summary
```

## Current Status

The project is currently in the **prototype validation stage / 原型验证阶段**.

Current progress includes:

- Prompt workflow design
- AI-flavor diagnosis criteria
- Multi-agent editing process design
- Sample testing with Chinese articles, Xiaohongshu posts, video scripts, and novel prose
- Planning for future web or WeChat mini-program deployment

## Planned Use of MiMo API

MiMo API will be used to test:

- Long-form Chinese text understanding
- AI-flavor diagnosis
- Multi-step editing workflow
- Platform-specific rewriting
- Batch content polishing
- Quality self-check and evaluation

The goal is to evaluate MiMo's performance in Chinese content editing and build a lightweight AI writing assistant for creators.
