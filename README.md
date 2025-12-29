# 🚀 Resume Scanner – AI-Powered Resume Matching Tool

A modern, client-side **Resume Scanner** that matches resumes against a Job Description and provides **clear match scores, skill insights, and downloadable results**.

Designed with **two distinct user modes**:
- **Recruiter Mode** – bulk resume screening
- **Candidate Mode** – focused, single-resume feedback

No backend required. Fully browser-based.

---

## ✨ Key Features

### 🔍 Resume Scanning
- Upload **Job Description** (TXT, PDF, DOCX, Images)
- Upload **Resumes** (TXT, PDF, DOCX)
- Automatic text extraction using:
  - PDF.js
  - Mammoth (DOCX)
  - Tesseract OCR (Images)

---

### 🎯 Intelligent Skill Matching
- Extracts relevant skills from Job Description
- Compares resumes against JD skills
- Calculates:
  - Match Score (%)
  - Matched Skills
  - Missing Skills

---

## 🔄 Dual Mode System

### 👔 Recruiter Mode (Default)
- Allows **multiple resumes per scan**
- Designed for **bulk screening**
- Sorted results by match score
- Download all results as CSV

### 🧑 Candidate Mode
- Allows **only one resume per scan**
- Provides **personalized feedback**
- Highlights:
  - Skills you have
  - Skills to improve
  - Clear recommendations
- Ideal for candidates improving their resume

---

## 🔄 Dual Mode System

### 👔 Recruiter Mode (Default)
- Allows **multiple resumes per scan**
- Designed for **bulk screening**
- Sorted results by match score
- Download all results as CSV

### 🧑 Candidate Mode
- Allows **only one resume per scan**
- Provides **personalized feedback**
- Highlights:
  - Skills you have
  - Skills to improve
  - Clear recommendations
- Ideal for candidates improving their resume

> Mode is controlled using a **single toggle**, with dynamic behavior and visual cues.

---

## 🌟 Possible Ways to Use

### 📝 Input Methods
- **Text Input**: Paste job descriptions directly into the text area
- **File Upload**: Upload JD files (PDF, DOCX, TXT, Images)
- **Mixed Uploads**: Combine different file types in one scan
- **Bulk Processing**: Upload multiple resumes simultaneously

### 🎯 Use Cases & Scenarios

#### For Recruiters
- **Pre-Screening**: Quick initial resume filtering
- **Job-Specific Matching**: Match against specific role requirements
- **Skills Gap Analysis**: Identify missing competencies across candidates
- **Diversity Hiring**: Compare skill sets without bias indicators

#### For Candidates
- **Resume Optimization**: Get targeted improvement suggestions
- **Skill Assessment**: Understand your competitive advantages
- **Career Planning**: Identify skills to develop for target roles
- **Job Application Strategy**: Tailor applications to specific positions

#### For HR Teams
- **Standardization**: Consistent evaluation criteria
- **Efficiency**: Process large volumes quickly
- **Data-Driven Decisions**: Quantitative matching scores
- **Compliance**: Bias-free initial screening

### 🚀 Deployment Options

#### 🌐 Web Hosting
- **GitHub Pages**: Free static hosting
- **Netlify**: Automated deployments with CDN
- **Vercel**: Serverless deployment with edge network
- **AWS S3 + CloudFront**: Scalable enterprise hosting

#### 💻 Local Development
- **Live Server Extension**: VS Code local development
- **Python HTTP Server**: `python -m http.server 8000`
- **Node.js Server**: Express or similar frameworks
- **Docker Container**: Containerized deployment

#### 🏢 Enterprise Integration
- **Internal Networks**: Deploy on company intranet
- **API Integration**: Wrap in web services
- **Database Storage**: Add backend for result history
- **SSO Integration**: Connect with enterprise authentication

### 🔧 Customization & Extension

#### 🎨 Theming
- **Brand Colors**: Customize color schemes
- **Company Logo**: Add organizational branding
- **Custom Styling**: Modify CSS for brand consistency
- **Dark/Light Modes**: Enhanced theme customization

#### ⚙️ Feature Extensions
- **Additional File Types**: Support more document formats
- **Advanced Scoring**: Custom matching algorithms
- **Integration APIs**: Connect with ATS systems
- **Export Formats**: Add PDF reports, JSON output

#### 🔒 Security & Privacy
- **Offline Mode**: Complete client-side processing
- **No Data Storage**: Files processed and discarded
- **Privacy Controls**: Enhanced data handling options
- **Compliance**: GDPR and privacy regulation adherence

---

## 🚀 Getting Started

### Quick Start
1. **Clone or Download** the repository
2. **Open** `index.html` in any modern web browser
3. **No installation required** - works completely offline
4. **Start scanning** resumes immediately

### Basic Usage
1. **Choose Mode**: Toggle between Recruiter/Candidate mode
2. **Add Job Description**: Upload file or paste text
3. **Upload Resumes**: Drag & drop or browse files
4. **Scan**: Click scan button to process
5. **Review Results**: View match scores and insights
6. **Export**: Download results as CSV

### System Requirements
- **Browser**: Chrome 90+, Firefox 88+, Safari 14+, Edge 90+
- **JavaScript**: Enabled (required for processing)
- **Internet**: Optional (CDN libraries load faster with connection)
- **Storage**: No permanent storage required

---

## 📊 Advanced Usage Patterns

#### Batch Processing Workflows
- **Scheduled Scans**: Regular candidate pipeline reviews
- **Comparative Analysis**: Track improvements over time
- **Benchmarking**: Compare against industry standards
- **Quality Assurance**: Validate hiring criteria effectiveness

#### Integration Scenarios
- **Career Portals**: Embed in job application systems
- **Learning Platforms**: Connect with skill development tools
- **HR Software**: Integrate with existing HR workflows
- **Assessment Tools**: Combine with technical testing platforms

---

## 📥 Export Capabilities

- Download results as **CSV**
- CSV contains **only the current scan**
- No historic or duplicate data
- Ready for ATS uploads or offline analysis

---

## 🎨 UI & UX Highlights

- Light / Dark mode with auto-detection
- Smooth animations and progress indicators
- Drag-and-drop uploads
- Guided onboarding tour
- Responsive and accessible layout

---

## 🧹 Clean Data Handling (Major Achievement)

- Every scan starts **fresh**
- No historic data accumulation
- Prevents:
  - Duplicate results
  - Confusing exports
  - Storage bloat
- Ensures accuracy and consistency across:
  - Scan results
  - CSV export
  - Candidate feedback

---

## 🏆 Achievements & Improvements

✔ Clear separation of Recruiter and Candidate workflows  
✔ Eliminated duplicate and historic scan issues  
✔ Removed unnecessary email dependency  
✔ Simplified export pipeline (CSV-only)  
✔ Improved maintainability and readability  
✔ Fully GitHub Pages compatible  

---

## 🛠 Tech Stack

- **Frontend**: HTML5, Tailwind CSS, Vanilla JavaScript
- **Document Processing**:
  - PDF.js (PDF text extraction)
  - Mammoth.js (DOCX processing)
  - Tesseract.js (OCR for images)
- **UI/UX**: Responsive design, dark/light themes, animations
- **Data Handling**: Client-side processing, CSV export
- **Storage**: Browser LocalStorage (temporary session data)

---

## 🔧 Troubleshooting

### Common Issues

#### Files Not Processing
- **Check file types**: Supported formats (PDF, DOCX, TXT, Images)
- **File size**: Large files may take longer to process
- **Browser compatibility**: Use modern browsers (Chrome recommended)

#### Slow Performance
- **Large files**: OCR processing takes time for image files
- **Multiple files**: Process in smaller batches
- **Browser resources**: Close other tabs for better performance

#### Export Issues
- **CSV format**: Check browser download settings
- **Empty results**: Ensure scan completed successfully
- **File permissions**: Allow downloads in browser settings

#### Theme/Display Issues
- **Dark mode**: Toggle theme button in top-right
- **Mobile view**: Responsive design adapts automatically
- **Browser zoom**: Reset to 100% for optimal display

### Browser-Specific Notes
- **Chrome**: Best performance and compatibility
- **Firefox**: Good support, slightly slower OCR
- **Safari**: Full support with latest versions
- **Mobile browsers**: Limited OCR support

---

## 🤝 Contributing

### Ways to Contribute
- **Bug Reports**: Open issues for problems found
- **Feature Requests**: Suggest new capabilities
- **Code Improvements**: Submit pull requests
- **Documentation**: Help improve guides and examples
- **Testing**: Report compatibility issues

### Development Setup
1. Fork the repository
2. Clone your fork: `git clone https://github.com/yourusername/resume-scanner.git`
3. Open `index.html` in browser for testing
4. Make changes and test thoroughly
5. Submit pull request with description

---

## 📄 License

This project is open source and available under the **MIT License**.

### Permissions
- ✅ Commercial use
- ✅ Modification
- ✅ Distribution
- ✅ Private use

### Limitations
- ❌ No liability
- ❌ No warranty

---

## 📞 Support & Contact

- **Issues**: [GitHub Issues](https://github.com/yourusername/resume-scanner/issues)
- **Discussions**: [GitHub Discussions](https://github.com/yourusername/resume-scanner/discussions)
- **Documentation**: This README and inline code comments

---

## 🎯 Roadmap & Future Plans

### Planned Features
- **Enhanced OCR**: Improved image text recognition
- **Additional Formats**: Support for more file types
- **Advanced Analytics**: Detailed skill gap analysis
- **API Integration**: REST API for external integrations
- **Multi-language**: Support for non-English resumes

### Community Requests
- **Custom Scoring**: User-defined matching algorithms
- **Resume Builder**: Integrated resume creation tools
- **Job Board Integration**: Direct connections to job platforms
- **Mobile App**: Native mobile applications

---

*Built with ❤️ for efficient, bias-free resume screening*


