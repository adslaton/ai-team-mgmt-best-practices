# Gemini Configuration

This file provides context for interacting with the Gemini CLI in this project.

## Project Overview

This is an AI Team Management Best Practices repository. It contains visual guides, checklists, and interactive tools to help development teams transition from traditional practices to AI-first methodologies, treating AI agents as specialized team members.

## Architecture & Structure

### Core Components

**Interactive HTML Visualizations (`src/`)**:
- These are self-contained HTML files with embedded CSS and JavaScript.
- They require no build process or external dependencies.
- Each file is a complete educational module (e.g., mental model transformations, assessment tools, interactive checklists).
- They can be opened directly in a web browser.

**Documentation System (`docs/`)**:
- This directory follows an "Information-Dense Keywords (IDK)" methodology.
- It contains a hierarchical command dictionary, research artifacts, and AI instruction files.

### Content Philosophy
- **Spec-driven development**: New features and content are driven by detailed specifications.
- **Agent orchestration**: The focus is on coordinating multiple AI agents rather than individual AI usage.
- **Quality assurance**: QA is integrated throughout all development workflows.

## Working with This Codebase

### Adding New Interactive Tools
- Create a new HTML file in the `src/` directory.
- Follow the existing pattern: a single file with embedded CSS and self-contained JavaScript.
- Ensure the tool is interactive and provides measurable outcomes (e.g., scoring, progress tracking, dynamic recommendations).

### Updating Documentation
- Adhere to the IDK methodology found in the `docs/dictionary/` directory.
- Maintain the consistent structure for commands (Definition → Usage → Expected Output Format).
- If you add a new command, update the index in `docs/information-dense-keywords.md`.

### Content Standards
- All HTML visualizations must be browser-ready without any build steps.
- Documentation should follow spec-driven development principles.
- Interactive tools must provide measurable outcomes and actionable recommendations.
- Maintain a consistent visual design language across all HTML files.

## Information Dense Keywords (IDK) Integration

This repository uses the IDK methodology for AI collaboration. Key commands relevant to this project include:

-   `document this`: Generate comprehensive documentation with examples.
-   `analyze this`: Examine code or architecture for patterns and implementation opportunities.
-   `spec this`: Create detailed technical specifications for new features.
-   `review this`: Perform a thorough assessment of interactive tools and documentation.

**Example Workflow (Command Chaining):**
`analyze this assessment tool then spec this improvement then document this change`

## Project-Specific Considerations

-   **Mental Model Focus**: Emphasize treating AI as specialized team members, not just tools. All content should reflect this perspective.
-   **Measurement-Driven**: All interactive tools must provide quantifiable assessments, progress tracking, and concrete metrics.
-   **Implementation-Ready**: Content should be practical and actionable, including templates, checklists, and frameworks.
-   **Visual Learning**: Use interactive diagrams, progress indicators, and visual metaphors to explain complex concepts.
