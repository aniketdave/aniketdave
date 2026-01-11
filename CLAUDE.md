# CLAUDE.md - AI Assistant Guide

This document provides comprehensive guidance for AI assistants (like Claude) working with this repository.

## Repository Overview

**Repository Type:** GitHub Profile Repository
**Purpose:** This is a special GitHub repository (`aniketdave/aniketdave`) that displays its README.md on the user's GitHub profile page.
**Primary Language:** Markdown
**Repository URL:** `aniketdave/aniketdave`

## Repository Structure

```
aniketdave/
├── README.md          # Profile page content (displays on GitHub profile)
├── CLAUDE.md          # This file - AI assistant guide
└── .git/              # Git version control
```

### Key Files

- **README.md**: The main profile content that appears on `github.com/aniketdave`. This is the most important file in the repository and should be carefully curated.
- **CLAUDE.md**: Documentation for AI assistants working with this repository.

## Purpose and Context

This is a **GitHub Profile README** repository, which means:
- The README.md content appears on the user's GitHub profile page
- It serves as a personal introduction, portfolio, or profile card
- Changes to README.md directly impact the user's public GitHub presence
- Quality and accuracy are critical since this is public-facing content

## Development Workflows

### Making Changes to the Profile

1. **Read Before Modifying**: Always read README.md before making changes
2. **Understand Intent**: Clarify what the user wants to showcase or communicate
3. **Maintain Professionalism**: This is a public profile - keep content professional and accurate
4. **Test Markdown**: Ensure markdown renders correctly (use GitHub-flavored markdown)
5. **Commit & Push**: Use clear commit messages describing profile updates

### Typical Tasks

Common requests for profile repositories include:
- Adding professional summary/bio
- Listing skills and technologies
- Showcasing projects and achievements
- Adding contact information
- Including GitHub stats or badges
- Adding visual elements (banners, icons, GIFs)
- Organizing content with sections

## Git Conventions

### Branching Strategy

- **Development Branch**: `claude/add-claude-documentation-Hv159` (current feature branch)
- **Main Branch**: Default branch for production content
- Always develop on feature branches starting with `claude/`
- Branch names should end with matching session ID

### Commit Messages

Use clear, descriptive commit messages:
- ✅ Good: "Add skills section with tech stack"
- ✅ Good: "Update bio with current role and interests"
- ✅ Good: "Add GitHub stats widgets"
- ❌ Bad: "Update README"
- ❌ Bad: "Changes"

### Push Protocol

```bash
# Always use upstream flag with branch name
git push -u origin <branch-name>

# Branch must start with 'claude/' and end with session ID
# Example: claude/add-claude-documentation-Hv159
```

**Retry Logic**: If push fails due to network errors, retry up to 4 times with exponential backoff (2s, 4s, 8s, 16s).

## Best Practices for AI Assistants

### Content Guidelines

1. **Accuracy First**: Only include accurate, verifiable information about the user
2. **Ask Before Assuming**: Don't fabricate skills, projects, or experience
3. **Respect Privacy**: Don't add personal information without explicit permission
4. **Professional Tone**: Maintain a professional, friendly tone
5. **Markdown Quality**: Use proper formatting, headings, and structure

### Technical Considerations

1. **GitHub-Flavored Markdown**: Use GFM syntax (tables, task lists, emoji codes)
2. **Image Hosting**: Use reliable image hosts or GitHub-hosted images
3. **Badge Services**: Use reputable services (shields.io, etc.) for badges
4. **Stats Widgets**: Consider using github-readme-stats or similar tools
5. **Accessibility**: Use alt text for images, proper heading hierarchy
6. **Mobile-Friendly**: Keep content readable on mobile devices

### Common Enhancements

**Profile Sections to Consider:**
- 👋 Introduction/Greeting
- 💼 About Me / Professional Summary
- 🛠️ Skills & Technologies
- 🚀 Featured Projects
- 📊 GitHub Statistics
- 📫 Contact Information
- 🎯 Current Focus/Goals
- 🌱 Learning Journey
- ⚡ Fun Facts

**Visual Elements:**
- Profile banner/header image
- Skill badges (shields.io)
- Technology icons
- GitHub stats cards
- Contribution graphs
- Custom graphics/animations

### Anti-Patterns to Avoid

❌ **Don't:**
- Add content without reading existing README first
- Include outdated or incorrect information
- Over-engineer simple profile pages
- Add unnecessary complexity
- Use broken image links or badges
- Include sensitive personal information
- Copy templates without customization
- Use excessive emojis (unless user's style)

✅ **Do:**
- Keep content current and relevant
- Use working, reliable external resources
- Test all links and images
- Maintain consistent formatting
- Personalize content to the user
- Keep it concise and scannable
- Update regularly when requested

## Repository-Specific Conventions

### File Organization

- Keep the repository minimal - this is primarily for the profile README
- Additional files (like this CLAUDE.md) are for development guidance
- Avoid cluttering with unnecessary files
- Assets (images) can be stored here or linked externally

### Markdown Style

- Use consistent heading levels (# for title, ## for sections, ### for subsections)
- Prefer emoji codes (`:rocket:`) over Unicode for better compatibility
- Use blank lines for readability
- Align similar elements (badges, links) for visual consistency
- Use HTML sparingly, prefer pure markdown when possible

### Content Updates

When updating the profile:
1. Review current content first
2. Discuss major changes with the user
3. Maintain the user's voice and style
4. Test rendering on GitHub (if possible)
5. Commit with descriptive message
6. Push to feature branch

## Resources and References

### Useful Tools & Services

- **GitHub Stats**: [github-readme-stats](https://github.com/anuraghazra/github-readme-stats)
- **Badges**: [shields.io](https://shields.io)
- **Icons**: [Simple Icons](https://simpleicons.org), [Dev Icons](https://devicon.dev)
- **Markdown Guide**: [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
- **Profile Examples**: [awesome-github-profile-readme](https://github.com/abhisheknaiidu/awesome-github-profile-readme)

### Testing Markdown

- Use GitHub's preview feature when possible
- Check rendering on both light and dark themes
- Verify links are working
- Ensure images load correctly

## Emergency Procedures

### If Something Goes Wrong

1. **Bad Content Pushed**: Immediately revert using `git revert`
2. **Broken Links/Images**: Fix and push update ASAP
3. **Formatting Issues**: Test markdown and correct
4. **Accidental Information**: Remove sensitive data and force push (with permission)

### Recovery Commands

```bash
# Revert last commit
git revert HEAD

# Reset to previous commit (use carefully)
git reset --hard HEAD~1

# Check what will be pushed
git diff origin/main..HEAD
```

## Collaboration Notes

### Working with the User

- **Clarify Intent**: Ask about goals for their profile
- **Show Examples**: Suggest examples of similar profile styles
- **Iterate**: Be prepared to refine and adjust
- **Respect Preferences**: Honor the user's style choices
- **Stay Updated**: Keep content current with user's activities

### Quality Checklist

Before pushing profile updates:
- [ ] Content is accurate and current
- [ ] All links work correctly
- [ ] Images load properly
- [ ] Markdown renders correctly
- [ ] No typos or grammatical errors
- [ ] Formatting is consistent
- [ ] Content aligns with user's intent
- [ ] Professional and appropriate tone

## Version History

- **2026-01-11**: Initial CLAUDE.md created with comprehensive guidance
- Repository currently contains minimal README.md template

## Notes for Future Development

This repository may evolve to include:
- Custom profile page layouts
- Automated profile updates
- Dynamic content (GitHub Actions)
- Asset management (images, badges)
- Multiple profile variations

Always maintain the primary purpose: showcasing the user's GitHub presence professionally and accurately.

---

**Last Updated**: 2026-01-11
**Maintained By**: AI Assistants (Claude) with user oversight
**Questions?**: Refer to GitHub Profile README best practices and ask the user for clarification
