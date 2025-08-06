# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is an AI Team Management Best Practices repository containing visual guides, checklists, and interactive tools for implementing AI-augmented development teams. The project helps development teams transition from traditional practices to AI-first methodologies by treating AI agents as specialized team members.

## Architecture & Structure

### Core Components

**Interactive HTML Visualizations** (`src/`):
- Self-contained HTML files with embedded CSS and JavaScript
- No build process or dependencies required
- Open directly in browsers for interactive experiences
- Each file represents a complete educational module:
  - Mental model transformations (traditional dev → AI agents)
  - Assessment tools with scoring algorithms
  - Interactive checklists with progress tracking
  - Visual guides with animated diagrams

**Documentation System** (`docs/`):
- Follows information-dense keywords (IDK) methodology
- Hierarchical command dictionary organized by function
- Research artifacts and consensus findings
- AI instruction files for consistent assistant behavior

**Content Philosophy**:
- Spec-driven development approach
- Agent orchestration over individual AI usage  
- Cost management as resource allocation
- Quality assurance integration throughout workflows

### Key Architectural Patterns

**Information Dense Keywords System**:
- Commands organized in `docs/dictionary/` by category (core, development, documentation, quality-assurance, workflow, git)
- Each command file follows consistent structure: Definition → Usage → Expected Output Format
- Supports command chaining for complex workflows
- Reference `docs/information-dense-keywords.md` for the complete index

**Self-Contained Interactive Tools**:
- All HTML files in `src/` are complete applications
- No external dependencies or build systems
- Embedded styling uses CSS custom properties for theming
- JavaScript implements scoring, progress tracking, and dynamic content generation

## Working with This Codebase

### Adding New Interactive Tools
```bash
# Create new HTML file in src/
# Follow existing pattern: embedded CSS, self-contained JavaScript
# Include interactive elements (scoring, progress bars, dynamic recommendations)
```

### Updating Documentation
```bash
# Follow IDK methodology in docs/dictionary/
# Maintain consistent command structure
# Update docs/information-dense-keywords.md index when adding commands
```

### Content Standards
- All HTML visualizations must be browser-ready without build steps
- Documentation follows spec-driven development principles
- Interactive tools should provide measurable outcomes and actionable recommendations
- Maintain consistent visual design language across all HTML files

## Information Dense Keywords Integration

This repository implements the IDK methodology for AI collaboration. Reference `docs/AI.md` for complete assistant instructions. Key commands applicable to this project:

- `document this` - Generate comprehensive documentation with examples  
- `analyze this` - Examine code/architecture for patterns and implementation opportunities
- `spec this` - Create detailed technical specifications for new features
- `review this` - Perform thorough assessment of interactive tools and documentation

### Command Chaining Examples
```bash
# Sequential development workflow
analyze this assessment tool then spec this improvement then document this change

# Parallel quality assurance  
test this interactive HTML and review this documentation
```

## Project-Specific Considerations

**Mental Model Focus**: The project emphasizes treating AI as specialized team members rather than tools. When adding content, maintain this perspective throughout all materials.

**Measurement-Driven**: All interactive tools should provide quantifiable assessments, progress tracking, and concrete metrics. Avoid vague qualitative measures.

**Implementation-Ready**: Content should bridge the gap between concept and practice. Include specific templates, checklists, and actionable frameworks rather than theoretical discussions.

**Visual Learning**: Leverage interactive diagrams, progress indicators, and visual metaphors to communicate complex orchestration concepts effectively.