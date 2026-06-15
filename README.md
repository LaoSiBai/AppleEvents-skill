<!-- language-selector:start -->
**English** | [中文](./README.zh.md)
<!-- language-selector:end -->

# 🍎 Apple Events Skill

Transform your ordinary product announcements into cinematic, "Apple-flavored" keynote scripts.

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Skill](https://img.shields.io/badge/Agent-Skill-purple.svg)]()

## About

Generic AI-generated copy sounds robotic and uses clichés. This skill forces agents to use the exact rhythmic pacing, vocabulary, and transitions of actual Apple executives. It solves the problem of boring product launches by bringing Apple's legendary "Show, Don't Tell" philosophy and mastery of emotional resonance directly into your AI workflows.

## Features

- **Apple's 7 Core Narrative Philosophies**: Built-in adherence to Apple's presentation secrets, including punchy syntax, relentless positivity, and the "Holistic Synergy" claim.
- **Contextual Grounding**: Powered by a meticulously parsed corpus of authentic Apple Events transcripts (2020-2026).
- **Diverse Executive Personas**: Tell the agent to embody specific executives for tailored styles. Go beyond the defaults:
  - **Tim Cook**: Grand vision, calmness, and humanity-centric openings.
  - **Craig Federighi**: Energetic, geeky humor, and buttery-smooth software demos.
  - **Johny Srouji**: Intense, deeply technical dives into silicon and performance.
  - **Sumbul Ahmad Desai**: Empathetic, scientifically-backed health and wellness.
  - **John Ternus**: Passionate hardware engineering and manufacturing details.
  - **Greg "Joz" Joswiak**: Hard-hitting marketing superlatives and industry dominance.
- **Multi-Speaker Orchestration**: Automatically generates buttery-smooth stage transitions and Markdown headers for multiple speakers.

## Installation

This skill is designed for agents supporting the standard `.gemini/skills` or `.agents/skills` directory structure.

```bash
git clone https://github.com/YOUR_USERNAME/apple-events-skill.git ~/.agents/skills/apple-events-skill
```

### Requirements

- A compatible Agentic CLI or IDE (e.g., antigravity-cli, opencode).

## Usage

Once installed, simply chat with your agent. Trigger the skill by providing a rough draft or bullet points.

```markdown
Here is the draft for our new SaaS platform update. Please use the **apple-events-skill** to rewrite it. Make the opening sound like Tim Cook, and the feature walkthrough sound like Craig Federighi.
```

### More Examples

```markdown
Help me write a product launch script for a new smart coffee maker using the **apple-events-skill**. Focus on 'Holistic Synergy' and 'Relentless Positivity'.
```

## Contributing

Contributions are welcome! If you want to add new personas, update the corpus with the latest Apple Events, or refine the 7 Core Philosophies, please submit a Pull Request.

### Development Setup

To test changes locally:
1. Clone the repo into your local workspace.
2. Ensure you have the `resources/` directory intact.
3. Test your prompts with your agent locally before submitting.

## Acknowledgments

- Transcripts and corpus data derived from real Apple Events spanning 2020 to 2026.
- Inspired by the legendary presentation styles of Steve Jobs, Tim Cook, and the Apple executive team.

## License

Apple Events Skill is licensed under the MIT license.
