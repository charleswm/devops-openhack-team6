---
title: Build Failed
assignees: {{ payload.sender.login }}
labels: bug
---
Your build failed. Build pushed by {{ payload.sender.login }}.
{{tools.context.pullRequest}}