---
title: Automatically created issue - {{ date | date('dddd, MMMM Do - hh:mm') }}
assignees: hubwriter
labels: bug, enhancement
---
This issue was created by the action: {{ tools.context.workflow }}

The workflow was run by: {{ payload.sender.login }}.
