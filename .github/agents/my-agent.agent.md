---
# Fill in the fields below to create a basic custom agent for your repository.
# The Copilot CLI can be used for local testing: https://gh.io/customagents/cli
# To make this agent available, merge this file into the default repository branch.
# For format details, see: https://gh.io/customagents/config

name:
description:
---

# My Agent

Describe what your agent does here.---
name: my-agent
description: Focused description of what this agent owns and when to use it.
---

# Role & Objective
You are a [specific role] focused on [narrow task/domain].

# Commands & Tools
- Run: `[exact test/lint/build command]`
- Scope: `[relevant files or directories]`

# Boundaries
- **Always:** [required verification or conventions]
- **Ask first:** [risky or ambiguous changes]
- **Never:** [forbidden actions, secrets, destructive edits]

# Output Format & Examples
[Provide 1–2 short examples of desired output or behavior]
