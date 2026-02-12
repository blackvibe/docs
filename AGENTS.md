# Documentation project instructions

## About this project

- This is documentation for Harvi Code - an independent AI coding assistant
- Harvi Code is a proprietary product with built-in AI models (no external providers)
- Documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- Use "Harvi Code" when referring to the product (NOT "Harvi" alone)
- Use "workspace" not "project"
- Use "agent" for AI assistant references
- Technical file names: `.harviignore` (NOT `.rooignore`), `.harvirules` (NOT `.roorules`)
- Technical settings: `showHarviIgnoredFiles` (NOT `showRooIgnoredFiles`)

## Important rules

- NO mentions of Roo Code, roo-cline, or being a fork
- NO external AI providers (Anthropic, OpenAI, OpenRouter, etc.)
- NO social media links (Discord, GitHub, Reddit)
- NO API keys or provider setup instructions
- Focus ONLY on how to use Harvi Code

## Harvi Code tools

The actual tools available in Harvi Code:
- `ask_user` - Ask user questions for additional information
- `harvi_cmd` - Execute terminal commands
- `list_files` - List files and directories
- `new_task` - Create new task in selected mode
- `read_file` - Read file contents
- `skill` - Load and execute specialized skills
- `str_replace` - Replace text in files
- `grep_search` - Fast text search with ripgrep
- `file_search` - Search files by fuzzy name matching
- `search_google` - Perform Google searches
- `fetch_url` - Fetch web page contents
- `switch_mode` - Switch between modes
- `create_file` - Create new files or overwrite existing

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Friendly tone in Russian ("ты" not "вы")

## Content boundaries

- Document user-facing features only
- No internal implementation details
- No mentions of upstream/fork/base functionality
