# Multi-Agent Workflow

The workflow separates diagnosis, style adaptation, rewriting, and verification into focused agent roles. The project is in the **prototype validation stage / 原型验证阶段**.

## 1. Diagnosis Agent

The Diagnosis Agent reviews the input draft and identifies quality issues that make the text sound overly AI-generated. It checks mechanical structure, repetitive paragraph rhythm, vague expression, over-explaining, preachy tone, lack of concrete detail, and platform mismatch.

Output:

- Issue summary
- Severity level
- Representative examples
- Rewrite priorities

## 2. Platform Style Agent

The Platform Style Agent selects the target content style. It adapts editing criteria for WeChat public account articles, Xiaohongshu posts, short video scripts, novel prose, and marketing copy.

Output:

- Target platform profile
- Tone and rhythm guidance
- Structure suggestions
- Constraints to avoid over-editing

## 3. Rewrite Agent

The Rewrite Agent produces an improved version while preserving the original meaning. It reduces AI-like tone, strengthens natural expression, and adds concrete details only when they are supported by the source or clearly marked as optional.

Output:

- Rewritten version
- Notes on major edits
- Unchanged core meaning summary

## 4. Self-Check Agent

The Self-Check Agent compares the rewritten text against the original. It checks meaning preservation, factual consistency, unsupported additions, remaining mechanical phrasing, and target-platform fit.

Output:

- Pass/fail checklist
- Potential meaning drift
- Remaining risks
- Suggested final adjustments

## 5. Coordinator Agent

The Coordinator Agent integrates all intermediate results and produces the final optimized version. It resolves conflicts between naturalness, platform adaptation, and factual consistency.

Output:

- Final polished text
- Concise quality report
- Optional revision notes for the creator
