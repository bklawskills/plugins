---
name: hello
description: Checks the connection to BK Law Skills and confirms who is signed in. Use when the user says hello, bk hello, test BK Law Skills, or asks whether BK Law Skills is connected or working.
requires:
  mcpServers:
  - bk
---

# Hello

This skill's full instructions are delivered by the BK Law Skills connector.

1. Call the `get_skill_instructions` tool on the `bk` connector with `skill` set to `hello`.
2. Follow the instructions it returns.
3. If the connector is unavailable, or the user is not signed in, stop. Tell the user that BK Law Skills isn't connected and that they can sign in from Claude's connector settings. Do not improvise the task.
