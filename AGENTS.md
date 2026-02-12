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
- NO GitHub links or references to RooCodeInc/RooVeterinaryInc
- Focus ONLY on how to use Harvi Code
- All support references should point to "службу поддержки Harvi Code" (generic support)

## Content structure rules

- NO duplicate H1 headings in markdown files
- Title comes from frontmatter only
- Content starts immediately after frontmatter (no # Heading)
- Use ## for first heading in content, not #
- Keep content clean and minimal

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
- No excessive separators (---) between sections
- Clean, minimal formatting

## Content boundaries

- Document user-facing features only
- No internal implementation details
- No mentions of upstream/fork/base functionality
- No references to original Roo Code documentation structure
- Keep it simple and focused on Harvi Code usage

## Translation approach

- Translate from upstream docs but completely rewrite
- Make content more friendly and understandable
- Use simpler language than original
- Add practical examples where helpful
- Remove corporate/marketing speak
- Focus on "how to use" not "what it is"

## File organization

Current structure:
```
/
├── index.mdx (main page)
├── getting-started/
│   ├── installing.mdx
│   └── first-task.md
├── basic-usage/
│   ├── chat-interface.md
│   ├── tools.md
│   ├── context-mentions.md
│   ├── modes.md
│   └── writing-requests.md
└── faq.md
```

## What NOT to include

- Provider setup pages (no external providers)
- API key configuration
- Model selection guides
- Pricing information (refer to official site)
- Social media links
- GitHub repository links
- Community links (Discord, Reddit, etc.)
- References to "Roo" anything
- Mentions of being a fork or based on another project

## Common mistakes to avoid

1. Writing "Harvi" instead of "Harvi Code"
2. Adding duplicate H1 headings (# Title) after frontmatter
3. Mentioning Roo Code, roo-cline, or fork relationship
4. Including external provider information
5. Adding social media or GitHub links
6. Using `.rooignore` instead of `.harviignore`
7. Using `showRooIgnoredFiles` instead of `showHarviIgnoredFiles`
8. Referencing `.roorules` instead of `.harvirules`
9. Adding excessive separators (---) between sections
10. Making content too verbose - keep it concise

## Quality checklist

Before finishing any page, verify:
- [ ] No "Harvi" alone (always "Harvi Code")
- [ ] No duplicate H1 headings
- [ ] No Roo/roo-cline mentions
- [ ] No external provider references
- [ ] No social/GitHub links
- [ ] Correct technical names (.harviignore, etc.)
- [ ] Friendly Russian tone ("ты")
- [ ] Clean, minimal formatting
- [ ] Practical and helpful content
- [ ] All links point to existing pages
