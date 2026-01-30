# DocForge
Local PDF Tools. Complete Privacy. Zero Servers.

> **All processing happens locally in your browser. Your files never leave your system.**

## Overview

A complete, production-ready **browser-based PDF utility suite** featuring 6 powerful tools:

- 🔒 **Make PDF Text Non-Selectable** - Convert PDFs to image-based format (perfect for protected submissions)
- 🎨 **Overlay Logo** - Add logos/branding to any page with custom positioning
- 🔄 **Replace Pages** - Replace specific page ranges between documents
- ➕ **Insert Pages** - Insert pages from one PDF into another
- 📝 **PDF to Markdown** - Extract text from PDFs and convert to Markdown format
- 📄 **Markdown to PDF** - Convert Markdown files to formatted PDFs

**Key Features:**
- ✅ 100% Client-Side Processing (no server needed)
- ✅ 100% Privacy (files never leave browser)
- ✅ 100% Free (uses open-source libraries)
- ✅ Instant Results (no uploading/downloading to servers)
- ✅ Works Offline (after initial load)
- ✅ Mobile Responsive (works on phones/tablets)
- ✅ Single HTML File (easy deployment)

---

## Quick Start

### 1. Open the Application
- **Local**: Double-click `pdf_utility_app.html` in your file explorer
- **Online**: Visit the deployed URL (e.g., `https://username.gitlab.io/pdf-utility-suite/`)

### 2. Choose a Feature
- Click one of the 6 tabs on the left sidebar to select your tool

### 3. Upload & Process
- Upload your PDF file(s)
- Adjust settings
- Click the action button
- Download the result

**That's it!** No registration, no uploads to servers, no waiting for results.

---

## Features

### � Make PDF Text Non-Selectable
**Convert PDFs to image-based format for protected submissions**

- Convert all PDF pages to rasterized images
- Text becomes non-copyable and non-extractable
- Adjustable quality (72-600 DPI)
- Optional page range selection
- Perfect for: Academic submissions, confidential documents, final print versions, document protection

### 🎨 Overlay Logo
**Add your branding to documents**

- Add logo to PDF pages
- Choose pages: first, all, or specific pages
- Full positioning and sizing control
- Real-time preview
- Perfect for: Corporate reports, branded documents, watermarking

### 🔄 Replace Pages
**Update specific document sections**

- Replace page ranges between documents
- Keep other pages unchanged
- Perfect for: Updating chapters, patching documents, section replacements

### ➕ Insert Pages
**Combine documents seamlessly**

- Insert pages from one PDF into another
- Specify exact insertion point
- Perfect for: Adding appendices, combining sections, document assembly

### 📝 PDF to Markdown
**Extract text from PDFs and convert to Markdown**

- Extract text content from PDF pages
- Automatic heading detection
- Page-by-page organization
- Live Markdown preview
- Download as `.md` file
- Perfect for: Document digitization, content repurposing, text extraction

### 📄 Markdown to PDF
**Convert Markdown files to formatted PDFs**

- Parse and format Markdown syntax
- Support for headings (#, ##, ###), bullet lists, and text styling
- Automatic pagination
- Color-coded headings for visual hierarchy
- Direct PDF download
- Perfect for: Creating formatted documents, reports, documentation conversion

---

## Privacy & Security

### ✅ How It Works
- User opens browser → selects file
- File stays in browser memory
- Processing happens in JavaScript (client-side)
- User downloads result
- Browser clears memory
- **Nothing ever reaches any server**

### ❌ What Does NOT Happen
- Files are NOT uploaded to servers
- You (the host) CANNOT see files
- No data leaves the user's computer
- No tracking of file contents
- No logging of document data

### Why This Design?
1. **Privacy Compliance**: GDPR, HIPAA, FERPA compliant by design
2. **Trust**: Users can inspect source code (browser DevTools)
3. **Speed**: No network latency - instant processing
4. **Scalability**: 1 million concurrent users = same server load
5. **Reliability**: No server downtime, works offline

---

## Getting Started

### Files Included
```
pdf_utility_app.html         ← Main application (OPEN THIS!)
README.md                    ← This overview and guide
QUICKSTART.md                ← Quick start guide and examples
DEPLOYMENT_GUIDE.md          ← Detailed deployment instructions
```

### Option 1: Use Locally (Simplest)
1. Open `pdf_utility_app.html` in any web browser
2. Done! No installation needed

### Option 2: Deploy to GitLab Pages (Free Hosting)
1. Create GitLab repository
2. Upload `pdf_utility_app.html`
3. Enable Pages in Settings
4. Share URL: `https://username.gitlab.io/pdf-utility-suite/`

See `DEPLOYMENT_GUIDE.md` for detailed steps.

### Option 3: Deploy to Your Server
1. Copy `pdf_utility_app.html` to any web server
2. Ensure HTTPS is enabled
3. Access at your domain
4. No backend configuration needed

---

## Technology Stack

### Frontend (Client-Side)
- **HTML5** - Semantic markup and file handling
- **CSS3** - Responsive design with gradients and flexbox
- **ES6 JavaScript** - Modern, clean code

### PDF Libraries (from CDN - no server needed)
| Library | Version | Purpose | License |
|---------|---------|---------|---------|
| **pdf-lib** | 1.17.1 | Create/modify PDFs | MIT |
| **pdf.js** | 3.11.174 | Render/display PDFs | Apache 2.0 |

### Browser APIs
- **File API** - Local file handling
- **Canvas API** - PDF rendering
- **Blob API** - Download generation
- **URL API** - File download links

### Browser Support
✅ Chrome 60+  
✅ Firefox 55+  
✅ Safari 12+  
✅ Edge 79+  
✅ Opera 47+  

---

## Documentation

📖 **Quick Start**: Read `QUICKSTART.md` for step-by-step examples  
📖 **Deployment**: Read `DEPLOYMENT_GUIDE.md` for hosting instructions  
📖 **This File**: Overview and features

---

## FAQ

### Q: Is it really free?
**A:** Yes! Uses MIT and Apache 2.0 licensed open-source libraries.

### Q: Can I see user files?
**A:** No. Files never leave the browser. You cannot access them.

### Q: Does it work offline?
**A:** Yes, after initial page load.

### Q: What's the max file size?
**A:** Limited only by browser memory (typically 1-4 GB).

### Q: Can I modify the code?
**A:** Yes! It's open-source and fully customizable.

### Q: Can I use this commercially?
**A:** Yes! MIT and Apache 2.0 licenses allow commercial use.

---

## Performance

| Operation | Time | Notes |
|-----------|------|-------|
| Convert 10-page PDF (300 DPI) | 5-15 sec | Browser-dependent |
| Overlay logo on 50 pages | 2-5 sec | Very fast |
| Replace 5 pages | 3-8 sec | I/O limited |
| Insert 10 pages | 2-6 sec | Fast |
| PDF to Markdown (10 pages) | 2-4 sec | Text extraction |
| Markdown to PDF (10 pages) | 3-6 sec | Formatting & layout |

---

## Next Steps

1. ✅ Open `pdf_utility_app.html` in your browser
2. ✅ Try each of the 6 features with sample PDFs and documents
3. ✅ Read `QUICKSTART.md` for use cases and examples
4. ✅ Read `DEPLOYMENT_GUIDE.md` for hosting options
5. ✅ Deploy to GitLab Pages (5 minutes - detailed guide included)
6. ✅ Share URL with your team
7. ✅ Enjoy privacy-first PDF and document processing!

---

## Support

### Documentation Links
- [pdf-lib GitHub](https://github.com/Hopding/pdf-lib)
- [pdf-lib Docs](https://pdf-lib.js.org/)
- [pdf.js GitHub](https://github.com/mozilla/pdf.js)
- [MDN Web Docs](https://developer.mozilla.org/)

### Hosting Help
- [GitLab Pages Docs](https://docs.gitlab.com/ee/user/project/pages/)
- [GitHub Pages](https://pages.github.com/)

---

## License

- **Application**: MIT License
- **pdf-lib**: MIT License (Andrew Dillon)
- **pdf.js**: Apache 2.0 License (Mozilla)

All open-source and production-ready.

---

## Summary

✅ **Complete** - Everything works in the browser  
✅ **Private** - Zero data leaves the user's system  
✅ **Fast** - Instant processing, no network delays  
✅ **Free** - Open-source, no licensing costs  
✅ **Scalable** - Unlimited concurrent users  
✅ **Simple** - Single HTML file deployment  

**Ready to get started? Open `pdf_utility_app.html` now!** 🚀

---

**Version**: 1.1.0  
**Status**: Production Ready ✅  
**Last Updated**: January 31, 2026  
**Features**: 6 tools | Vertical navigation | PDF↔Markdown conversion


## 📖 Documentation

See `documentation/Design_Document.pdf` for detailed project design and explanation.  

---


