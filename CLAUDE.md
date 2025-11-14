# CLAUDE.md - AI Assistant Guide

## Repository Overview

This is a **GitHub profile repository** (`richardkern/richardkern`), a special repository type whose `README.md` appears on the GitHub profile page. It serves as a personal introduction and portfolio showcase.

### Repository Purpose
- Display professional introduction on GitHub profile
- Showcase learning journey and interests
- Connect with potential collaborators
- Document technical skills and projects

### Current Owner Context
- Learning to code through:
  - [The Odin Project](https://www.theodinproject.com/)
  - [freeCodeCamp](https://www.freecodecamp.org/)
- Early in coding journey, building foundational skills

---

## Repository Structure

```
richardkern/
├── README.md          # Profile page content (displays on GitHub profile)
├── CLAUDE.md          # This file - AI assistant guidelines
└── .git/              # Git repository metadata
```

### File Descriptions

#### README.md
- **Purpose**: Main profile page visible to GitHub visitors
- **Location**: Root directory
- **Visibility**: Public, appears on https://github.com/richardkern
- **Format**: GitHub Flavored Markdown
- **Current Content**: Personal introduction, learning status, interests

---

## Development Workflows

### Working with Profile Content

#### Making Changes to README.md
1. **Read current content** to understand existing structure
2. **Edit incrementally** - preserve user's personal voice
3. **Preview locally** if possible (GitHub markdown preview)
4. **Commit with descriptive messages** explaining changes
5. **Push to current branch** for review before merging to main

#### Content Guidelines for README.md
- Keep it personal and authentic
- Use emojis sparingly (only if they match user's style)
- Include sections like:
  - Introduction/greeting
  - Current learning focus
  - Skills and technologies
  - Projects (as they develop)
  - Contact information
  - Collaboration interests

### Git Workflow

#### Branch Strategy
- **Main branch**: Production content (displays on profile)
- **Feature branches**: Use `claude/*` prefix for AI-assisted changes
- **Current branch**: `claude/claude-md-mhydr0pfoms8bvky-01NCfJixxfc4nCyAtWoh3kUD`

#### Commit Messages
Format: `<type>: <description>`

Types:
- `feat`: New content or sections
- `update`: Modify existing content
- `fix`: Correct errors or typos
- `docs`: Meta-documentation (like this file)
- `style`: Formatting changes

Examples:
```
feat: add skills section with web development technologies
update: reflect completion of JavaScript fundamentals
fix: correct typo in introduction
docs: add CLAUDE.md for AI assistant guidance
```

#### Push/Pull Guidelines
- Always use: `git push -u origin <branch-name>`
- Branch must follow pattern: `claude/*-<session-id>`
- Retry on network failures: 4 times with exponential backoff (2s, 4s, 8s, 16s)
- Fetch specific branches: `git fetch origin <branch-name>`

---

## Key Conventions for AI Assistants

### General Principles

1. **Preserve User Voice**
   - This is a personal profile - maintain authenticity
   - Don't overwrite the user's personality with corporate/formal language
   - Keep the casual, friendly tone if that's the user's style

2. **Learning Journey Focus**
   - User is actively learning to code
   - Reference to learning resources (Odin Project, freeCodeCamp) is important context
   - As skills develop, help document progress authentically

3. **Incremental Improvements**
   - Don't completely rewrite the README unless explicitly requested
   - Suggest additions rather than replacements
   - Ask before making major structural changes

### Content Best Practices

#### Profile README Sections to Consider
As the user progresses, consider suggesting these sections:

```markdown
## About Me
- Brief introduction
- Current learning focus
- Career goals

## Skills & Technologies
- Languages (JavaScript, HTML, CSS, etc.)
- Frameworks and libraries
- Tools and platforms

## Current Projects
- Link to repositories
- Brief descriptions
- Technologies used

## Learning Path
- Completed courses/modules
- Currently studying
- Next steps

## GitHub Stats (Optional)
- Can use GitHub stats widgets
- Keep minimal and tasteful

## Connect With Me
- Professional email
- LinkedIn
- Twitter/X
- Portfolio website (when available)
```

#### Markdown Formatting Tips
- Use headers (##, ###) for clear hierarchy
- Bullet points for lists
- Badge shields for technologies (shields.io)
- Proper link formatting: `[text](url)`
- Code blocks with language syntax highlighting
- Line breaks for readability

### Things to Avoid

❌ **Don't Do This:**
- Remove personal touches or humor
- Add excessive emojis unless user's style includes them
- Use overly formal or corporate language
- Include fake/placeholder project information
- Add stats or achievements that aren't real
- Create walls of text without structure

✅ **Do This Instead:**
- Enhance existing content thoughtfully
- Suggest additions based on actual learning progress
- Maintain authentic, conversational tone
- Keep it concise and scannable
- Use real information only
- Structure content with headers and whitespace

### Working with a Learning Developer

**Important Context:**
- User is early in their coding journey
- May not have many projects to showcase yet - that's okay!
- The README should reflect current status honestly
- As skills grow, incrementally add to the profile
- Focus on learning journey and potential, not just accomplishments

**Helpful Approach:**
- Suggest documenting completed tutorials/courses
- Help articulate learning goals
- Format code examples from learning materials
- Create space for future project additions
- Encourage growth mindset language

---

## Technical Considerations

### File Editing
- Always read README.md before editing
- Use Edit tool for modifications (preserve formatting)
- Validate markdown syntax
- Check for broken links
- Ensure emoji rendering (if used)

### Character Limits
- GitHub README has no strict limit, but keep it scannable
- Profile page viewers typically skim, not read deeply
- Aim for content readable in 30-60 seconds

### Images and Media
- Store images in repository or use external hosting (imgur, etc.)
- Use relative paths for repository images: `![alt text](./images/photo.jpg)`
- Optimize image sizes for web
- Provide alt text for accessibility

### GitHub Features to Leverage
- Markdown support (GFM - GitHub Flavored Markdown)
- Automatic link previews
- Syntax highlighting in code blocks
- Task lists: `- [ ]` and `- [x]`
- Tables for structured data
- Collapsible sections with `<details>` tags

---

## Example Profile Enhancement Workflow

When asked to improve the profile:

1. **Assess Current State**
   ```bash
   # Read current README
   cat README.md
   ```

2. **Identify Gaps**
   - Missing sections that would add value
   - Outdated information
   - Formatting improvements
   - Link additions

3. **Propose Changes**
   - Present options to user
   - Explain benefits of each addition
   - Get approval before major changes

4. **Implement Incrementally**
   - Make one logical change at a time
   - Test markdown rendering
   - Commit with clear messages

5. **Review and Refine**
   - Check overall flow
   - Ensure consistency
   - Validate all links work

---

## Maintenance Notes

### Regular Updates to Consider
- Skills learned/technologies mastered
- Completed courses or certifications
- New projects added to GitHub
- Changed learning focus
- Updated contact information

### Seasonal/Event-Based Updates
- Hackathon participation
- Open source contributions
- Learning milestones (e.g., "Completed JavaScript module")
- Career transitions (student → developer)

---

## Resources for AI Assistants

### Markdown References
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
- [Markdown Guide](https://www.markdownguide.org/)
- [Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet)

### Profile README Inspiration
- [Awesome GitHub Profile README](https://github.com/abhisheknaiidu/awesome-github-profile-readme)
- [GitHub Profile README Examples](https://github.com/durgeshsamariya/awesome-github-profile-readme-templates)

### Badge Generators
- [Shields.io](https://shields.io/) - Custom badges
- [Simple Icons](https://simpleicons.org/) - Technology icons

### Stats Widgets
- [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats)
- [GitHub Profile Trophy](https://github.com/ryo-ma/github-profile-trophy)

---

## Quick Reference Commands

### Git Operations
```bash
# Check current status
git status

# Create and switch to feature branch
git checkout -b claude/feature-description-sessionid

# Stage changes
git add README.md

# Commit with message
git commit -m "update: add skills section"

# Push to remote (first time)
git push -u origin claude/feature-description-sessionid

# Push subsequent changes
git push
```

### File Operations
```bash
# View README
cat README.md

# Check line count
wc -l README.md

# Search for content
grep -i "keyword" README.md
```

---

## Version History

- **v1.0** (2025-11-14): Initial CLAUDE.md creation
  - Documented repository structure
  - Established AI assistant guidelines
  - Defined development workflows
  - Added best practices for profile README management

---

## Questions or Improvements?

If you're an AI assistant working with this repository and encounter:
- Unclear guidelines
- Missing information
- Outdated conventions
- New use cases

Consider updating this file to help future AI assistants work more effectively with this repository. Always commit documentation improvements alongside feature work.

---

**Last Updated**: 2025-11-14
**Repository Type**: GitHub Profile Repository
**Primary File**: README.md
**Audience**: Public (GitHub visitors)
**Maintenance**: Active (learning journey in progress)
