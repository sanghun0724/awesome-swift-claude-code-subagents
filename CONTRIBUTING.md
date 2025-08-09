# Contributing to Awesome Swift Claude Code Subagents

Thank you for your interest in contributing to the Awesome Swift Claude Code Subagents project! This guide will help you get started with contributing new subagents or improving existing ones.

## How to Contribute

### 1. Submitting a New Subagent

To add a new Swift/Apple platform subagent:

1. **Choose the appropriate category** based on your subagent's primary function
2. **Create a new .md file** in the relevant category folder
3. **Follow the standard template** (see below)
4. **Test your subagent** with real Swift/Apple platform projects
5. **Submit a pull request** with a clear description

### 2. Subagent Template

Each subagent file should follow this structure:

```markdown
---
name: your-subagent-name
description: Brief description focusing on Swift/Apple platform capabilities
tools: Read, Write, MultiEdit, Bash, swift, swiftc, xcodebuild, instruments, swiftlint
---

You are a [role description] specializing in [specific Swift/Apple platform area].

When invoked:
1. [First action]
2. [Second action]
3. [Third action]

[Platform]-specific checklist:
- [ ] Item 1
- [ ] Item 2
- [ ] Item 3

[Continue with sections as needed...]
```

### 3. Naming Conventions

- Use lowercase with hyphens (e.g., `swiftui-developer`, `coredata-expert`)
- Be specific about the Swift/Apple technology focus
- Keep names concise but descriptive

### 4. Quality Standards

All subagents must:

- **Support multiple Apple platforms** (iOS, macOS, watchOS, visionOS)
- **Use modern Swift** (5.9+ features, async/await, actors)
- **Follow Apple guidelines** (HIG, API design guidelines)
- **Include platform-specific considerations**
- **Provide clear examples** with Swift code
- **Be thoroughly tested** on real projects

### 5. Testing Your Subagent

Before submitting:

1. Test with Claude Code on actual Swift projects
2. Verify compatibility across different Apple platforms
3. Ensure Xcode integration works properly
4. Check SwiftLint compliance
5. Validate performance with Instruments

### 6. Pull Request Guidelines

When submitting a PR:

- **Title**: `Add [subagent-name] for [specific use case]`
- **Description**: Include:
  - What the subagent does
  - Which Apple platforms it supports
  - Swift version requirements
  - Example use cases
  - Testing performed

### 7. Improving Existing Subagents

To improve an existing subagent:

1. **Identify the issue** or enhancement
2. **Test your changes** thoroughly
3. **Document the improvements** in your PR
4. **Maintain backward compatibility** when possible

## Code of Conduct

We follow the Swift Community's values:

- **Be welcoming and inclusive**
- **Be respectful and constructive**
- **Focus on what is best for the community**
- **Show empathy towards other community members**

## Platform-Specific Guidelines

### iOS/iPadOS
- Consider iPhone and iPad form factors
- Support latest iOS versions (iOS 17+)
- Include accessibility features

### macOS
- Support macOS 14+ features
- Consider menu bar and window management
- Include keyboard shortcuts

### watchOS
- Optimize for small screens
- Consider battery efficiency
- Support complications

### visionOS
- Include spatial computing concepts
- Support hand tracking and eye tracking
- Consider immersive experiences

## Questions?

If you have questions about contributing:

1. Check existing subagents for examples
2. Open an issue for discussion
3. Join Swift community forums

## Recognition

Contributors will be acknowledged in:
- The project README
- Release notes
- Individual subagent files (as co-authors)

Thank you for helping make Claude Code better for Swift developers! 🚀