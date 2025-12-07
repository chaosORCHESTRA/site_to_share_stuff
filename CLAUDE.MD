# CLAUDE.MD

## Repository Overview

This is **site_to_share_stuff** - a website project dedicated to sharing scientifically accurate information about astronomical phenomena, currently featuring a comprehensive report on Comet C/2023 A3 (Tsuchinshan-ATLAS), also known as "The Great Comet of 2024."

## Project Purpose

This repository hosts educational content about celestial events, specifically:
- In-depth scientific analysis with peer-reviewed citations
- Fact-checked astronomical data and observations
- Debunking misinformation and fake news about astronomical events
- Making complex astronomical concepts accessible to general audiences

## Repository Structure

```
site_to_share_stuff/
├── LICENSE                          # GNU GPL v3 license
├── CLAUDE.MD                        # This file - AI assistant guide
└── Tsuchinshan-ATLAS/
    └── index.html                   # Main comet report page
```

## Content Guidelines

### Current Content: Comet C/2023 A3 Report

The main page (`Tsuchinshan-ATLAS/index.html`) is a comprehensive scientific report featuring:

- **47 fact-checked claims** with inline citations
- **Peer-reviewed sources**: A&A, MNRAS, arXiv papers
- **Official sources**: NASA, ESA, JPL, CBET
- **Educational sections**: Magnitude scale explanation, orbital mechanics, composition analysis
- **Misinformation debunking**: Addressing viral fake news about the comet

### Writing Style & Standards

When working on this project, maintain:

1. **Scientific Accuracy**
   - All specific claims must have inline citations
   - Link directly to primary sources (peer-reviewed papers, official space agency communications)
   - Use format: `<span class="source-citation">(<a href="URL" target="_blank">Source</a>)</span>`

2. **Accessibility**
   - Explain technical concepts for general audiences
   - Use analogies and comparisons (e.g., "42 full moon diameters")
   - Include callout boxes for key concepts

3. **Visual Design**
   - Modern, gradient-based design with purple theme (#667eea to #764ba2)
   - Responsive layout (mobile-friendly)
   - Semantic callout boxes with emojis (info, tip, warning, danger, etc.)
   - Tables for structured data
   - Timeline format for chronological events

4. **Content Structure**
   - Executive summary at the top
   - Clear section headings with hierarchical organization
   - "Why this matters" explanations for technical details
   - Debunking sections for misinformation
   - Comprehensive references at the end

## HTML Structure & Components

### Callout Box Types

The HTML uses specialized callout boxes:
- `.callout-info` - Blue - General information
- `.callout-summary` - Purple - Executive summaries
- `.callout-tip` - Green - Helpful tips and key concepts
- `.callout-note` - Orange - Important notes
- `.callout-example` - Pink - Examples and illustrations
- `.callout-important` - Light red - Important warnings
- `.callout-danger` - Red - Critical alerts and debunking
- `.callout-check` - Green - Verified facts
- `.callout-warning` - Yellow - Cautionary information
- `.callout-success` - Dark green - Success stories

### Common Components

- `.timeline` - For chronological events
- `.comparison-box` - Side-by-side comparisons
- `.meta-info` - Metadata and source lists
- `table` - Structured data with gradient headers
- `blockquote` - Quotations

## Working with This Repository

### When Adding New Content

1. **Research first**: Gather peer-reviewed sources and official documentation
2. **Fact-check everything**: Every specific claim needs a citation
3. **Maintain inline citations**: Don't just list sources at the end
4. **Use appropriate callouts**: Match the callout type to the content purpose
5. **Test responsiveness**: Check mobile display with the media query

### When Editing Existing Content

1. **Preserve citations**: Never remove or modify citations without verification
2. **Maintain formatting**: Keep the established visual hierarchy
3. **Update metadata**: If making substantial changes, update the "Report compiled" date
4. **Verify links**: Ensure all external links remain active

### When Debunking Misinformation

This project takes a strong stance against astronomical misinformation:
- Use `.callout-danger` for fake news alerts
- Provide factual counterpoints with citations
- Explain WHY the misinformation spread
- Be direct and clear: "This is complete nonsense" when appropriate

## Technical Notes

### Styling Philosophy

- Self-contained HTML file (no external dependencies)
- Embedded CSS for portability
- Gradient design with professional aesthetics
- Print-friendly white background for content area
- Accessible color contrasts

### Browser Compatibility

- Uses modern CSS (flexbox, grid, gradients)
- WebKit prefixes for gradient text effects
- Responsive breakpoint at 768px
- Works on all modern browsers

## Future Expansion

This repository can grow to include:
- Additional astronomical events and phenomena
- Interactive visualizations
- Image galleries with proper attribution
- Comparison articles between different celestial events
- Educational explainers on astronomical concepts

## Key Principles

1. **Scientific Integrity**: Always prioritize accuracy over engagement
2. **Source Transparency**: Every claim must be traceable
3. **Public Education**: Make complex topics accessible
4. **Combat Misinformation**: Actively debunk fake news with evidence
5. **Visual Excellence**: Make science beautiful and engaging

## License

GNU General Public License v3.0 - See LICENSE file for details.

## Contact & Contributions

This is a public educational resource. When making contributions:
- Verify all facts against multiple authoritative sources
- Maintain the citation standard (minimum 40+ inline citations for major articles)
- Follow the established design language
- Keep content accessible to non-specialists while maintaining scientific rigor

---

**Last Updated**: December 2025
**Primary Content**: Comet C/2023 A3 (Tsuchinshan-ATLAS) comprehensive report
**Citation Count**: 47 fact-checked claims with inline sources
