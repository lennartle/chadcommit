# chadCommit

Generate git commit messages with a single click by using GPT-4o to analyze your staged changes.

## In action

![Preview](https://raw.githubusercontent.com/lennartle/chadcommit/main/preview.gif)

## Customizing messages

You can edit the GPT prompt in the extension settings to fit your preferred style of messages.

### Prompt example:

```
Analyze a git diff and make a short conventional commit message, follow this template: 🚀feat(scope) [message]\n🛠️refactor(scope) [message]\n⚙️chore(scope) [message]; Response example: 🚀feat(player) add captions\n🛠️refactor(player) support new formats\n⚙️chore(dependencies) upgrade terser to 5.16.6
```

## Requirements

- You should obtain an OpenAI API key here:
  https://platform.openai.com/account/api-keys

- It is recommended to keep your commits small. Unstage unrelated, large, and auto-generated files (such as package-lock) before clicking the "Suggest" button to avoid context length errors.
