# Contributing to QGIS Plugin Privacy Statements

Thank you for your interest in contributing to this repository! This guide will help you add or update privacy statements for QGIS plugins.

## Who Can Contribute?

- **Plugin Developers**: Add or update privacy statements for your own plugins
- **Community Members**: Help improve existing privacy statements or add missing ones
- **Users**: Report inaccuracies or request privacy statements for plugins

## How to Add a New Privacy Statement

### 1. Check if a Privacy Statement Already Exists

Before adding a new privacy statement, check the `plugins/` directory to see if one already exists for the plugin.

### 2. Use the Template

Copy the [PRIVACY_TEMPLATE.md](PRIVACY_TEMPLATE.md) file and fill it out with accurate information about the plugin.

### 3. File Naming Convention

- Use the plugin name in PascalCase (e.g., `QuickMapServices.md`, `QGIS2Web.md`)
- Save the file in the `plugins/` directory
- Use `.md` (Markdown) file extension

### 4. Required Information

Your privacy statement must include:

- **Overview**: Brief description of the plugin and its purpose
- **Data Collection**: What data (if any) is collected
- **Data Usage**: How collected data is used
- **Data Storage**: Where and how long data is stored
- **Data Sharing**: Whether data is shared with third parties
- **User Rights**: What rights users have regarding their data
- **Contact Information**: How to reach the developer/maintainer
- **Changes to This Privacy Statement**: When the statement was last updated
- **Compliance**: Relevant privacy regulations the plugin complies with

### 5. Writing Guidelines

- **Be Clear and Concise**: Use simple language that non-technical users can understand
- **Be Honest**: Accurately describe all data collection and sharing practices
- **Be Specific**: Provide concrete details rather than vague statements
- **Be Complete**: Cover all aspects of data handling, even if minimal
- **Date Your Statement**: Include the date when the statement was created or last updated

### 6. Examples of Good Privacy Statements

If no data is collected:
```markdown
## Data Collection
[Plugin Name] does not collect any user data:
- No usage statistics
- No telemetry
- No personal information
```

If data is collected:
```markdown
## Data Collection
[Plugin Name] collects the following types of data:
- Geographic coordinates when processing queries
- API keys (stored locally only)
- Error logs (only if user opts in)
```

### 7. Submit a Pull Request

1. Fork this repository
2. Create a new branch for your privacy statement
3. Add your privacy statement file to the `plugins/` directory
4. Update the README.md to include your plugin in the list
5. Submit a pull request with a clear description

## How to Update an Existing Privacy Statement

If you need to update an existing privacy statement:

1. Fork the repository
2. Make the necessary changes to the relevant file in `plugins/`
3. Update the date in the "Changes to This Privacy Statement" section
4. Submit a pull request explaining what changed and why

## Reporting Issues

If you notice an inaccuracy in a privacy statement:

1. Open an issue on GitHub
2. Clearly describe the problem
3. Provide evidence or references if possible
4. Tag the issue with `accuracy` or `correction`

## Requesting Privacy Statements

If you want a privacy statement for a plugin that isn't listed:

1. Open an issue on GitHub
2. Provide the plugin name and link to its repository
3. Tag the issue with `request`
4. Consider contacting the plugin developer directly

## Code of Conduct

- Be respectful and constructive
- Focus on accuracy and user privacy
- Do not submit false or misleading information
- Respect intellectual property and licensing

## Review Process

All contributions will be reviewed for:

1. **Accuracy**: Information should be factually correct
2. **Completeness**: All required sections should be filled out
3. **Clarity**: Language should be clear and understandable
4. **Format**: Proper Markdown formatting and file naming

## Questions?

If you have questions about contributing:

- Open an issue on GitHub
- Check existing issues for similar questions
- Review the template and examples for guidance

## Licensing

By contributing to this repository, you agree that your contributions will be licensed under the GNU General Public License v2.0.

Thank you for helping make QGIS plugins more transparent and privacy-friendly!
