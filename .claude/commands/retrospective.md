Analyze recent work and conversations to identify improvements for CLAUDE.md guidelines.

## Process

1. **Scan CLAUDE.md files**
   - Check all CLAUDE.md files throughout the project directory tree
   - Note the hierarchy of guidelines (project root vs subdirectory levels)

2. **Analyze current discussion context**
   - Review recent interactions and corrections
   - Identify patterns where the user had to clarify or correct behavior
   - Note repeated instructions or preferences

3. **Extract and validate improvements individually**
   - Identify patterns where the user had to clarify or correct behavior
   - For each pattern found, immediately present it to the user for validation
   - Format each finding as:
     ```
     **[Category]: [Specific Finding]**
     - Current: [What happens now]
     - Desired: [What should happen]  
     - Proposed guideline: "[Exact text to add]"
     - Suggested level: [Current project / Parent / Global]
     ```
   - Ask: "Add this guideline to [suggested level] CLAUDE.md? (yes/no/modify)"
   - If modify: ask for the preferred wording and apply immediately
   - If yes: apply the change immediately to the appropriate CLAUDE.md file
   - If no: move on to the next pattern

4. **Process improvements as discovered**
   - Work through patterns in order of importance/frequency
   - Apply each approved change immediately before moving to the next
   - Maintain consistent formatting with existing guidelines
   - Report what was added after each successful addition

5. **Completion summary**
   - Provide a brief summary of all changes made
   - Note any patterns that were identified but not implemented

## Output Format

Process improvements one at a time in order of importance/frequency. For each improvement, include concrete examples from the conversation that led to the finding, then immediately validate and apply if approved before moving to the next.

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