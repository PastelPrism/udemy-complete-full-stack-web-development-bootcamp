# Copilot Instructions for Full-Stack Web Development Bootcamp

## Project Structure & Philosophy 🎯

This is a **progressive learning repository** following Dr. Angela Yu's Udemy course structure. Projects build incrementally from basic HTML to full-stack applications. Each section folder represents a course module with both main assignments and "extra" challenge versions.

### Core Directory Pattern
```
section-name/
├── index.html          # Main assignment
├── extra/             # Enhanced challenge version
│   ├── index.html     # Extended implementation  
│   └── styles.css     # Additional styling
└── [other assets]
```

## Development Workflow 📚

### Project Status Tracking
- The `README.md` contains a structured course progress tracker with placeholders (_Soon_) for completion status
- Each project has standardized metadata: Language, Description, Page links, Status, and Extra Challenge details
- **Always update the README.md** when completing projects or adding new implementations

### File Organization Conventions
- **Main assignments** go in the root of each section folder (`movie-ranking/index.html`)
- **Extra challenges** go in `extra/` subfolder with enhancements like CSS styling and navigation
- Links between versions use relative paths: `../index.html` for going back to main assignment

### HTML Structure Patterns
- Basic assignments use minimal HTML5 structure with semantic headings
- Extra challenges add `<nav>` elements, CSS links, and class attributes for styling
- Navigation menus link between original and enhanced versions of projects

## Learning-Focused Code Assistance 🧠

### When Working on Assignments
- **Respect the progressive difficulty**: Don't jump ahead with advanced techniques if the current section focuses on basics
- **Maintain the course structure**: Keep main assignments simple, save enhancements for `extra/` folders
- **Preserve learning examples**: The original simple implementations serve as learning references

### Code Enhancement Guidelines
- Basic HTML projects should focus on semantic markup and content structure
- CSS enhancements belong in the `extra/` folder with proper linking
- JavaScript features should align with the section's learning objectives (DOM manipulation, ES6 features, etc.)

### Project Documentation
- Include descriptive comments explaining course concepts being demonstrated
- Reference the specific Udemy section when adding new implementations
- Document any deviations from the original course requirements

## Technology Stack Progression 🚀

The course follows this technology learning path:
1. **Frontend Foundation**: HTML → CSS → Bootstrap → JavaScript/jQuery
2. **Backend Development**: Node.js → Express.js → EJS templating
3. **Database Integration**: SQL → PostgreSQL with APIs  
4. **Modern Frameworks**: React.js for dynamic UIs
5. **Advanced Topics**: Authentication, APIs, Web3/DApps

### Version Control Integration
- Use descriptive commit messages referencing the course section
- Tag major project completions for easy navigation
- Consider separate branches for experimental features beyond course scope

## Agent Behavior Notes 🤖

- **Ask before major structural changes** - This is a learning project where the user values understanding each step
- **Suggest `extra/` implementations** for enhancements beyond basic requirements
- **Reference course context** when explaining implementation choices
- **Encourage experimentation** while maintaining the core learning structure
- **Update progress tracking** in README.md when completing assignments

*This project follows the collaborative guidelines from `.github/AGENTS.md` - always ask before acting and match the user's curious, practical learning style!*