When creating a pull request, follow these steps to generate a comprehensive PR description:

## 1. Screenshots Section

**For any UI/visual changes:**
- Use the Playwright MCP to capture screenshots of all modified or new screens
- Upload the screenshots directly to the PR description
- Organize screenshots with clear labels (e.g., "Before" and "After" for modifications, or "New Feature: [Feature Name]" for additions)
- Include captions explaining what each screenshot demonstrates

## 2. High-Level Summary

**Provide a concise overview that includes:**
- **What changed:** Brief description of the modifications (2-3 sentences)
- **Why it changed:** The problem being solved or feature being added
- **Impact:** Who/what is affected by these changes

## 3. PR Description Structure

```markdown
## 🖼️ Preview
[Screenshots with captions go here]

## 📋 Summary
### What's Changed
- [Brief description of main changes]

### Why These Changes
- [Problem being solved or feature rationale]

### Impact
- [Who/what is affected]

### Key Changes
- [List major code changes/additions]
- [New dependencies if any]
- [Configuration changes if any]
```

## Instructions for Claude:
1. Always check if there are UI changes that need screenshots
2. If UI changes exist, use Playwright MCP to capture and upload screenshots before writing the description
3. Keep the summary concise but informative
4. Use clear formatting with headers and bullet points
5. Include checkboxes for testing confirmation
6. Link related issues when applicable
7. Highlight any breaking changes or important considerations for reviewers