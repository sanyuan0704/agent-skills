# Agent Skills

A collection of agent skills for Claude Code and other AI agents.

## Available Skills

### nano-banana-pro

AI image generation using Google Gemini's `gemini-3-pro-image-preview` model.

**Install:**
```bash
npx skills add sanyuan0704/agent-skills
```

**Usage:**
```bash
python ${SKILL_DIR}/scripts/generate_image.py --prompt "A serene mountain landscape" --output "output.png"
```

## Requirements

- Python 3.8+
- Google API key with Gemini access (`GOOGLE_API_KEY`)

## License

MIT
