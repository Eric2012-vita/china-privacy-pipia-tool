# PIPIA Assessment Tool
## Personal Information Protection Impact Assessment

An interactive, bilingual (English/Chinese) web-based tool for conducting Personal Information Protection Impact Assessments in compliance with China's PIPL and related data protection regulations.

### Features

- **Cover Page Documentation**: Capture data processing activities and assessment metadata
- **Smart Module Triggering**: Automatically determines which assessment modules are required based on your data processing activities
- **8 Comprehensive Modules**:
  1. Minimization and Necessity Test
  2. Data Processing Activities (Outsourcing)
  3. Data Sharing Activities
  4. Cross-border Data Transfer
  5. Data Security Measures
  6. Algorithms and Automated Decision-Making
  7. Data Merging
  8. Rights and Interests of Data Subjects
- **Automated Data Classification**: Auto-classifies data fields based on GB/T 35273 standards
- **Security Measures Matrix**: Automatically generates required security measures based on data classification levels
- **Action Items Tracker**: Auto-generates tasks for Legal, IT, and Business teams based on assessment responses
- **DPO Evaluation Blocks**: Structured evaluation sections for Data Protection Officers in each module
- **Export & Save**: Export comprehensive reports to HTML or save/load assessment data as JSON

### Usage

1. Open `index.html` in a modern web browser
2. Complete the Cover Page with your project information
3. Add data fields and let the tool auto-classify them
4. Answer module triggering questions to determine applicable modules
5. Complete triggered assessment modules
6. Review auto-generated action items assigned to your teams
7. Generate DPO evaluation
8. Export final report

### Technical Details

- **Single-file application**: Fully self-contained HTML with embedded CSS and JavaScript
- **No server required**: Runs entirely in the browser
- **Client-side only**: No data is transmitted to any server
- **No dependencies**: No external libraries or CDNs required
- **Works offline**: Can be used without internet connection

### Privacy & Security

All data entered into the tool remains local to your browser. Nothing is sent to external servers. The tool is designed with privacy-by-design principles, making it ideal for sensitive compliance assessments.

### Browser Compatibility

Works in all modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari

### License

Internal use only. Not for redistribution.
