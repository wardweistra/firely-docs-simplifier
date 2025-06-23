.. _simplifierOnlineResourceEditor:

Online Resource Editor
======================

The Online Resource Editor enables you to create and edit FHIR resources and FHIR Shorthand (FSH) files directly in your browser. This feature requires no local software installation and provides an integrated interface for FHIR development within Simplifier.net.

Overview
--------

The Online Resource Editor combines visual FHIR resource editing with support for FHIR Shorthand, allowing developers to choose between visual modeling and code-based development approaches. You can work with both Forge-style interfaces and FSH within the same environment.

Key Features
------------

**Browser-Based Development**
  - Edit FHIR resources directly in your browser
  - No software downloads or local installations required
  - Cloud-based development environment
  - Integration with Simplifier.net projects

**FHIR Shorthand Support**
  - Edit FHIR Shorthand (.fsh) files
  - Manage multiple .fsh files within projects
  - Direct visualization of FSH resources
  - Real-time compilation and validation

**Package Management**
  - Work with package dependencies
  - Support for both public and private FHIR packages
  - Automatic dependency resolution
  - Integration with Simplifier's package ecosystem

**User Interface**
  - Syntax highlighting and error detection
  - Real-time feedback and validation
  - Switch between visual and code views
  - Built-in FHIR validation

Benefits
--------

**Development Efficiency**
  - Rapid prototyping and development
  - No environment setup required
  - Access from any device with a web browser
  - Cloud-based collaboration

**Flexible Authoring**
  - Choose between visual modeling and code-based authoring
  - Switch between different authoring approaches as needed
  - Support for complex FHIR profiling scenarios
  - Integration with existing Simplifier workflows

**Team Collaboration**
  - Share projects with team members
  - Collaborative editing capabilities
  - Version control integration
  - Team-based development workflows

FHIR Shorthand Integration
--------------------------

The Online Resource Editor provides support for FHIR Shorthand (FSH), a domain-specific language for defining FHIR artifacts. FSH allows you to:

- Define FHIR profiles, extensions, and value sets using human-readable syntax
- Create implementation guides efficiently
- Maintain version control of your FHIR definitions
- Collaborate with teams using text-based workflows

**FSH Capabilities**
  - Full FSH syntax support
  - Real-time compilation to FHIR JSON/XML
  - Validation against FHIR specifications
  - Package dependency management
  - Multi-file FSH project support

Getting Started
---------------

**Accessing the Editor**

1. Log into your Simplifier.net account
2. Navigate to your project or create a new one
3. Select the "Online Resource Editor" option
4. Start creating or editing your FHIR resources and FSH files

**Creating FSH Files**

1. In the Online Resource Editor, select "New File"
2. Choose "FHIR Shorthand (.fsh)" as the file type
3. Write your FSH definitions using the built-in editor
4. Save and compile your FSH files in the browser

**Working with Dependencies**

- Add package dependencies through the project settings
- Reference external profiles and value sets in your FSH files
- Dependencies are resolved automatically during compilation

Current Status
--------------

The Online Resource Editor with FHIR Shorthand support is currently in beta. Users can try the feature and provide feedback. The core functionality is stable, with additional features and improvements in development.

**Available Features:**
  - Core FSH editing capabilities
  - Basic package dependency support
  - Real-time validation
  - Multi-file project management

**Planned Enhancements:**
  - Advanced debugging tools
  - Enhanced collaboration features
  - Additional FSH language features
  - Performance optimizations

Choosing Your Authoring Approach
---------------------------------

The Online Resource Editor supports both visual modeling (similar to Forge) and code-based authoring with FSH. Consider these factors when choosing your approach:

**Visual Modeling**
  - Graphical interface for profile creation
  - Suitable for less technical team members
  - Quick visual overview of profile structures
  - Effective for simple to moderate complexity profiles

**FHIR Shorthand**
  - Text-based, declarative approach
  - Suitable for complex profiling scenarios
  - Version control and diff capabilities
  - Effective for developers familiar with code
  - Building implementation guides with multiple related artifacts

**Combined Approach**
  - Switch between visual and code views as needed
  - Use visual tools for exploration and FSH for implementation
  - Leverage strengths of both approaches within the same project

Best Practices
--------------

**Project Organization**
  - Use meaningful file names for your FSH files
  - Group related profiles, extensions, and value sets together
  - Maintain consistent naming conventions across your project

**Version Control**
  - Save your work regularly
  - Use meaningful commit messages when publishing
  - Consider using Simplifier's backup and synchronization features

**Team Collaboration**
  - Establish team conventions for FSH coding style
  - Use comments to document complex profiling decisions
  - Share knowledge about FSH best practices within your team

Support and Resources
--------------------

**Documentation**
  - FSH Language Reference: https://build.fhir.org/ig/HL7/fhir-shorthand/
  - FSH School: https://fshschool.org/
  - Simplifier.net Help Documentation

**Community Support**
  - FHIR Chat: https://chat.fhir.org (check the #shorthand stream)
  - Simplifier.net Community Forums
  - HL7 FHIR Community

**Getting Help**
  - Use the feedback button in Simplifier.net for beta-related issues
  - Contact Firely support for technical assistance
  - Engage with the FHIR community for FSH-specific questions

The Online Resource Editor provides a browser-based solution for FHIR development. By combining cloud-based development with support for both visual and code-based authoring, it allows teams to choose the approach that fits their workflow and expertise.