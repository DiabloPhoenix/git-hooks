#Repository for git hooks

#Installation
Using commit-msg hook as an example

Copy commit-msg into `.git/hooks/` of your project
Remove the sample hook and give permissions to the new hook
```
rm .git/hooks/commit-msg.sample
chmod +x .git/hooks/commit-msg
```

## commit-msg
Formatted:
```
action(subject): Short description under 50 characters

Long description over 50 characters

JIRA [ticket number | none ]
```
Where appropriate actions are `fix`, `refactor`, and `add` (for now)
