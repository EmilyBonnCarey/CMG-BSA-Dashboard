# CMG BSA Dashboard

A centralized dashboard for CMG Financial Business Systems Analysts (BSAs) providing quick access to essential tools, resources, and environments.

## Features

### Environment Access
Quick-access buttons in the top banner for Clear environments:
- **PROD** - Production environment
- **UAT** - User Acceptance Testing
- **QA** - Quality Assurance
- **DEV** - Development environment
- **Clear Cache** - Direct link to browser cache settings

### AI Agents
Five specialized Claude AI agents for common BSA tasks:
- Email Agent
- Meeting Overview Agent
- Requirement Builder
- BRD Builder
- Ticket Builder

### Forms & Requests
- XD Intake Form
- LOS Intake / Change Management Request

### Development Tools
- Azure DevOps (ADO)
- ChatGPT

### Resources
- ADO Ticket Templates
- Regression Testing Sheets

## Design

### Color Scheme
The dashboard uses CMG Financial's brand colors:
- **Azure** (#33878f) - Header and primary accents
- **Green** (#99c34d) - PROD button and highlights
- **Dark Grey** (#3e3d40) - Text and secondary buttons
- **Light Grey** (#f0efee) - Background
- **Orange Grey** (#b1a7a2) - Subtle accents

### Layout
- Clean, card-based interface
- Responsive design that adapts to different screen sizes
- Hover effects for better interactivity
- All external links open in new tabs

## Team Customization

The dashboard is designed to be team-specific. Currently configured for the **Clear Team**, it displays:
- Clear environment buttons (PROD, UAT, QA, DEV)
- Clear-specific resources

Future versions can include login functionality to dynamically show team-specific tools based on user authentication.

## Deployment

### GitHub Pages
1. Create a new repository on GitHub
2. Upload `index.html` to the repository
3. Go to repository Settings → Pages
4. Select the branch (usually `main`) and root folder
5. Save and wait for deployment
6. Access at: `https://yourusername.github.io/repo-name/`

### Local Development
Simply open `index.html` in any modern web browser. No server or build process required.

## Browser Compatibility
- Chrome/Edge (recommended)
- Firefox
- Safari

## Maintenance

### Adding New Links
1. Open `index.html` in a text editor
2. Find the appropriate section (AI Agents, Forms, Tools, or Resources)
3. Copy an existing card structure
4. Update the href, icon class, title, and URL text
5. Save and test

### Changing Colors
All colors are defined in the `<style>` section at the top of the file. Search for hex codes like `#33878f` to update colors globally.

### Adding New Teams
To add support for additional teams:
1. Duplicate the environment button structure
2. Update links to point to the new team's environments
3. Add team-specific resources in new categories

## Technical Details
- Single HTML file with embedded CSS
- Uses Font Awesome 6.4.0 for icons via CDN
- No JavaScript required
- No external dependencies except Font Awesome
- Fully self-contained and portable

## Support
For questions or issues, contact the BSA team or submit an issue in the repository.

---

Built with Claude Code for CMG Financial BSA Team
