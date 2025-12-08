# ReqExpert Expert System for Software Requirements Engineering (SPA)

A fully functional Single Page Application (SPA) for managing software requirements using expert system rules and ontology-based approach.

## 🌟 Features

### Core Modules

- **📊 Dashboard** - Project overview with statistics and quick actions
- **🏗️ Entities Management** - CRUD operations for requirements, stakeholders, and business rules
- **⚙️ Processes Support** - Quality checks, prioritization, impact analysis, and ambiguity detection
- **📁 Artifacts** - Traceability matrix, document generation, and change history
- **📈 Analytics** - Requirement quality metrics, problematic requirement detection, and system recommendations
- **⚙️ Administration** - Data management, system settings, and rule configuration

### Key Capabilities

- **✅ Full Ontology Support** - Implements the complete requirements engineering ontology
- **🧠 Expert Rules Integration** - 90+ expert system rules for requirements validation
- **📱 Responsive Design** - Works on desktop, tablet, and mobile devices
- **🔧 No Backend Required** - Pure frontend implementation with local data storage
- **📤 Export/Import** - JSON export and import capabilities
- **📊 Visual Analytics** - Interactive charts and quality metrics

## 🚀 Quick Start

### Option 1: Direct Usage
Simply open the `index.html` file in any modern web browser.

### Option 2: Host Online
Upload the single `index.html` file to any web hosting service or GitHub Pages.

## 🛠️ Technology Stack

- **Alpine.js 3.x** - Lightweight reactive framework
- **Bootstrap 5.3** - Responsive CSS framework (compact `sm` size)
- **Font Awesome 6.4** - Icon library
- **Google Fonts** - Inter and Source Code Pro fonts
- **Pure HTML/CSS/JS** - No build process required

## 📁 Project Structure

```
Expert-System-SPA/
├── index.html                    # Complete SPA (all code in one file)
├── requirements_export.json      # Sample export format
└── README.md                     # This file
```

## 🔧 Usage Guide

### Managing Requirements
1. Click "New Requirement" or navigate to "Entities Management"
2. Fill in requirement attributes (ID, title, type, priority, etc.)
3. Add acceptance criteria for better quality scoring
4. Use filters and search to find requirements

### Quality Checks
1. Go to "Processes" module
2. Select a requirement for quality check
3. Run automatic validation against expert rules
4. Fix issues highlighted by the system

### Document Generation
1. Navigate to "Artifacts" module
2. Generate SRS documents, requirement catalogs, or stakeholder reports
3. Download generated documents as text files

### Analytics
1. Check "Analytics" module for quality scores
2. Review problematic requirements
3. Follow system recommendations for improvement

## 🎯 Expert System Rules

The application implements 90+ expert rules for requirements engineering, including:

- **A0-A4**: Project context assessment
- **B5-B14**: Project initiation and planning
- **C15-C24**: Requirements elicitation
- **D25-D39**: Requirements analysis and quality
- **E40-E49**: Architecture and design
- **F50-F59**: Requirements documentation
- **G60-G69**: Verification and validation
- **H70-H79**: Requirements management
- **I80-I83**: Prototyping
- **J84-J90**: Process adaptation

## 📱 Responsive Design

The application is fully responsive:
- **Desktop**: Full sidebar navigation
- **Tablet**: Optimized layout
- **Mobile**: Collapsible menu and touch-friendly controls

## 🔐 Data Management

### Export Options
- Export all data as JSON backup
- Export requirements catalog as CSV
- Generate SRS document as text file
- Export stakeholder reports

### Import Options
- JSON data import (planned for future version)
- Local storage for session persistence

## 🎨 Customization

### Changing System Name
1. Go to "Administration" module
2. Update project name in settings
3. Save settings

### Modifying Expert Rules
1. Navigate to "Administration" → "Expert System Rules"
2. Toggle active rules
3. Adjust strictness level

### UI Customization
Edit CSS variables in the `<style>` section of `index.html`:
- Colors
- Font sizes
- Spacing
- Component styles

## 📈 Quality Metrics

The system calculates quality scores based on:
- **Completeness** - Presence of acceptance criteria
- **Traceability** - Clear source attribution
- **Testability** - Measurable and verifiable
- **Stability** - Likelihood of changes
- **Clarity** - Absence of ambiguous terms

## 🚦 Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Opera 76+

## 📝 License

MIT License - See LICENSE file for details

## 🤝 Contributing

Since this is a single-file SPA, contributions would involve:
1. Forking the repository
2. Making improvements to the `index.html` file
3. Submitting a pull request

## 🐛 Known Limitations

- Data persists only during browser session (no permanent storage)
- Limited to client-side processing
- No collaborative features
- No user authentication

## 🔮 Future Enhancements

Planned features for future versions:
- [ ] LocalStorage persistence
- [ ] Collaborative editing
- [ ] User accounts
- [ ] Advanced analytics
- [ ] API integration
- [ ] Template library
- [ ] Advanced reporting

## 📚 Related Resources

- IEEE 830-1998: Recommended Practice for Software Requirements Specifications
- SWEBOK: Software Engineering Body of Knowledge
- IIBA BABOK: Business Analysis Body of Knowledge
- Agile Manifesto for software development

## 💬 Support

For issues or questions:
1. Check the [GitHub Issues](../../issues)
2. Review the code comments for implementation details
3. Contact the maintainer through GitHub

---

**Note**: This is a demonstration application. For production use, consider adding backend persistence and user authentication.
