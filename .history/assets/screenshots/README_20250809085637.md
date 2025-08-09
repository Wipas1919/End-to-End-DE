# Architecture Screenshots - On-Premise Implementation

## Overview

This directory contains screenshots and visual representations of the on-premise data platform architecture with Microsoft Fabric semantics integration. These diagrams help visualize the complete system design and data flow patterns.

## Screenshot Descriptions

### 1. Core On-Premise Data Flow (`core-data-flow.png`)
- **Purpose**: Simplified view showing main data flow from sources to on-premise storage and processing
- **Key Elements**:
  - Data sources (Nocobase, IoT Collectors, Web Scraping)
  - On-premise storage (MySQL, InfluxDB, MinIO)
  - On-premise processing (Windmill ETL, Local Analytics)
  - Microsoft Fabric integration (Semantic Models, Power BI)
  - Access management (Azure AD, Kong API Gateway)

### 2. Detailed On-Premise Architecture (`detailed-architecture.png`)
- **Purpose**: Complete 11-layer on-premise architecture with Microsoft Fabric semantics integration
- **Key Elements**:
  - All 11 architecture layers
  - On-premise components and cloud integration
  - Data flow patterns and connections
  - Security and access management
  - Monitoring and governance

### 3. Security Architecture (`security-architecture.png`)
- **Purpose**: Security and access management patterns
- **Key Elements**:
  - Authentication flows
  - Authorization mechanisms
  - Network security
  - Data protection
  - Compliance controls

### 4. Technology Stack (`technology-stack.png`)
- **Purpose**: Overview of all technology components
- **Key Elements**:
  - On-premise technologies
  - Microsoft Fabric components
  - Integration patterns
  - Deployment architecture

## How to Generate Screenshots

### Using Mermaid Live Editor

1. **Access Mermaid Live Editor**:
   - Go to https://mermaid.live/
   - Copy the Mermaid code from the main documentation

2. **Configure Settings**:
   - **Theme**: Default or Dark (recommended for better contrast)
   - **Background**: White or transparent
   - **Font Size**: 14px (for readability)

3. **Export Settings**:
   - **Format**: PNG
   - **Resolution**: 1920x1080 (recommended)
   - **Quality**: High

### Using GitHub

1. **GitHub Rendering**:
   - The diagrams render automatically in GitHub
   - Use browser screenshot tools (F12 > Screenshot)
   - Capture each diagram separately

2. **Browser Extensions**:
   - Use browser extensions for full-page screenshots
   - Ensure proper zoom level (100% recommended)

### Using Command Line Tools

```bash
# Using mmdc (Mermaid CLI)
npm install -g @mermaid-js/mermaid-cli

# Generate PNG from Mermaid file
mmdc -i input.mmd -o output.png -b transparent

# Generate SVG
mmdc -i input.mmd -o output.svg
```

## Recommended Screenshots

### Essential Screenshots
1. **`core-data-flow.png`** - Core on-premise data flow
2. **`detailed-architecture.png`** - Complete 11-layer architecture
3. **`security-architecture.png`** - Security and access patterns
4. **`technology-stack.png`** - Technology components overview

### Additional Screenshots (Optional)
5. **`microsoft-fabric-integration.png`** - Fabric integration details
6. **`data-synchronization.png`** - Data sync patterns
7. **`monitoring-dashboard.png`** - Monitoring architecture
8. **`deployment-topology.png`** - Deployment structure

## Screenshot Guidelines

### Quality Standards
- **Resolution**: Minimum 1920x1080 pixels
- **Format**: PNG for diagrams, JPG for photos
- **File Size**: Keep under 2MB for web use
- **Naming**: Use descriptive, lowercase names with hyphens

### Content Guidelines
- **Clarity**: Ensure text is readable at normal zoom
- **Consistency**: Use consistent colors and styling
- **Completeness**: Include all relevant components
- **Accuracy**: Verify all connections and relationships

### Accessibility
- **Color Contrast**: Ensure sufficient contrast for readability
- **Text Size**: Use minimum 12px font size
- **Alt Text**: Provide descriptive alt text for accessibility

## File Organization

```
assets/screenshots/
├── README.md                    # This file
├── core-data-flow.png          # Core data flow diagram
├── detailed-architecture.png   # Complete architecture
├── security-architecture.png   # Security patterns
├── technology-stack.png        # Technology overview
├── microsoft-fabric-integration.png  # Fabric integration
├── data-synchronization.png    # Data sync patterns
├── monitoring-dashboard.png    # Monitoring architecture
└── deployment-topology.png     # Deployment structure
```

## Update Process

### When to Update Screenshots
1. **Architecture Changes**: When components or connections change
2. **Technology Updates**: When new technologies are added
3. **Security Enhancements**: When security patterns are modified
4. **Documentation Updates**: When documentation is revised

### Update Workflow
1. **Modify Source**: Update Mermaid diagrams in main documentation
2. **Generate Screenshots**: Use Mermaid Live Editor or CLI tools
3. **Review Quality**: Ensure screenshots meet quality standards
4. **Update Documentation**: Reference new screenshots in documentation
5. **Version Control**: Commit changes with descriptive messages

## Troubleshooting

### Common Issues

#### Screenshot Quality
- **Blurry Text**: Increase resolution or use vector formats
- **Poor Contrast**: Adjust theme or background colors
- **Large File Size**: Optimize PNG compression

#### Rendering Issues
- **Missing Elements**: Check Mermaid syntax and browser compatibility
- **Layout Problems**: Adjust diagram dimensions and spacing
- **Font Issues**: Use web-safe fonts or embed custom fonts

#### Export Problems
- **Failed Export**: Check file permissions and disk space
- **Wrong Format**: Verify export settings and file extensions
- **Missing Content**: Ensure all elements are visible in the diagram

### Best Practices
1. **Test Rendering**: Verify diagrams render correctly before generating screenshots
2. **Backup Originals**: Keep original Mermaid files for future updates
3. **Version Control**: Track changes to diagrams and screenshots
4. **Documentation**: Update this README when adding new screenshots
5. **Quality Assurance**: Review screenshots for accuracy and clarity

## Contact Information

For questions about screenshots or diagram generation:
- **Documentation Team**: docs@your-organization.com
- **Architecture Team**: architecture@your-organization.com
- **Technical Support**: support@your-organization.com

---

*Last Updated: [Current Date]*
*Version: 2.0 - On-Premise Implementation*
