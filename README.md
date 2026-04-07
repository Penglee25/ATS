# 📄 ATSense CV Analyzer

**Smart ATS Compatibility Checker for Job Seekers**

ATSense is a powerful, privacy-focused web application that analyzes your CV/Resume against ATS (Applicant Tracking System) requirements. Upload your CV as text or PDF, and get instant, actionable insights to improve your chances of passing automated screening.

![ATSense Demo](https://via.placeholder.com/800x400?text=ATSense+CV+Analyzer)

## ✨ Features

### 📂 File Upload Support
- **Upload TXT or PDF files** - Direct file upload with automatic text extraction
- **Paste text directly** - Quick manual entry for CV content
- **Sample CV included** - Try the analyzer with a professionally crafted example

### 🔍 Comprehensive Analysis
- **Overall ATS Score** (0-100) - Instant compatibility rating
- **Section Detection** - Identifies missing critical sections:
  - Work Experience
  - Education
  - Skills
  - Contact Information
  - Professional Summary
  - Achievements/Certifications

### 📊 Detailed Metrics
- **Word Count Analysis** - Optimal length detection (250-900 words recommended)
- **Format Checks** - Email, LinkedIn, phone number, bullet points
- **Quantified Impact Detection** - Identifies metrics, percentages, and dollar amounts
- **Structure Evaluation** - Section hierarchy and organization

### 💡 Actionable Recommendations
- **Priority-based suggestions** (High/Medium/Low)
- **Specific missing elements** with examples
- **Formatting improvements** tailored to your CV

### 🎨 Modern Interface
- Dark theme optimized for readability
- Responsive design (mobile & desktop)
- Smooth animations and loading states
- Real-time word count updates

## 🚀 How It Works

1. **Input your CV** - Upload a file (.txt/.pdf) or paste text directly
2. **Click "Analyze CV"** - Our algorithm scans your document
3. **Review your report** - Get instant scores, metrics, and recommendations
4. **Improve your CV** - Follow priority-based suggestions to optimize

## 🛠️ Technology Stack

- **Frontend**: Vue.js 3 (CDN)
- **PDF Processing**: PDF.js for text extraction
- **Styling**: Pure CSS with custom properties
- **Analytics**: Client-side only (no data transmission)

## 🔒 Privacy First

**Zero data leaves your browser** - All analysis happens locally on your device. No server uploads, no tracking, no API calls. Your CV stays completely private.

## 📋 Analysis Criteria

### Scoring Weights
- **Section Coverage**: 35% - Presence of essential CV sections
- **Quantified Impact**: 30% - Numbers, percentages, and measurable results
- **Format & Contact**: 15% - Contact info, bullet points, structure
- **Length Optimization**: 20% - Optimal word count (250-900 words)

### What We Check
✅ Email address presence  
✅ LinkedIn profile URL  
✅ Phone number format  
✅ Bullet point usage  
✅ Quantifiable achievements (%, $, numbers)  
✅ Word count optimization  
✅ Section completeness  
✅ Professional summary presence  

## 💻 Installation & Usage

### Quick Start (No installation required)
Simply open the HTML file in any modern web browser. All dependencies are loaded via CDN.

### Local Development
```bash
# Clone or download the HTML file
# Open directly in browser
open index.html

# Or serve with local server
python -m http.server 8000
# Navigate to http://localhost:8000
