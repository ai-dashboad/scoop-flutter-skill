# Scoop Bucket for Flutter Skill

This is a [Scoop](https://scoop.sh) bucket for [Flutter Skill](https://github.com/ai-dashboad/flutter-skill).

## Installation

```powershell
# Add this bucket
scoop bucket add flutter-skill https://github.com/ai-dashboad/scoop-flutter-skill

# Install Flutter Skill
scoop install flutter-skill
```

## What is Flutter Skill?

Flutter Skill is a bridge that connects AI agents (Claude, Cursor, Windsurf) to running Flutter applications via the Dart VM Service Protocol.

## MCP Configuration

Add to your AI agent's config:

```json
{
  "mcpServers": {
    "flutter-skill": {
      "command": "flutter-skill",
      "args": ["server"]
    }
  }
}
```

## Links

- [GitHub](https://github.com/ai-dashboad/flutter-skill)
- [Documentation](https://github.com/ai-dashboad/flutter-skill#readme)
