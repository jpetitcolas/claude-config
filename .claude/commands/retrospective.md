Analyze recent work and conversations to identify improvements for CLAUDE.md guidelines.

## Process

1. **Scan CLAUDE.md files**
   - Check all CLAUDE.md files throughout the project directory tree
   - Note the hierarchy of guidelines (project root vs subdirectory levels)

2. **Analyze current discussion context**
   - Review recent interactions and corrections
   - Identify patterns where the user had to clarify or correct behavior
   - Note repeated instructions or preferences

3. **Extract improvements**
   - Group findings by: behavioral patterns, technical preferences, workflow patterns, quality standards
   - Categorize by frequency (how often it appeared) and impact (how significant)
   - Determine appropriate scope (project-specific vs universal)

4. **Present findings interactively**
   Format each finding as:
   ```
   **[Category]: [Specific Finding]**
   - Current: [What happens now]
   - Desired: [What should happen]  
   - Proposed guideline: "[Exact text to add]"
   - Suggested level: [Current project / Parent / Global]
   ```

5. **For each improvement**
   - Ask: "Add this guideline to [suggested level] CLAUDE.md? (yes/no/modify)"
   - If modify: ask for the preferred wording
   - If yes: note for implementation
   - Default to most logical placement based on scope

6. **Apply approved changes**
   - Update the appropriate CLAUDE.md files
   - Maintain consistent formatting
   - Preserve valuable existing guidelines
   - Report what was added/modified

## Output Format

Start with 3-5 highest priority improvements, then group remaining by category. Include concrete examples from the conversation that led to each finding.

## Guidelines for Good Improvements

- Must be specific and actionable (not vague like "be better at X")
- Should not conflict with existing guidelines
- Should be testable/verifiable in practice
- Consolidate similar patterns into single guidelines when possible

## Common Patterns to Watch For

- Testing preferences (frameworks, patterns, file naming)
- Code style (formatting, naming conventions, organization)
- Workflow preferences (when to ask for approval, level of detail)
- Communication style (technical depth, format, examples)
- Tool preferences (specific commands, packages, approaches)