# teopORG Website Project Structure

## Project Overview
This is an educational poverty alleviation organization website, focused on helping children in poor areas through education. The website is implemented in pure HTML and supports multiple languages.

## Directory Structure
```
/
├── assets/                # Static resources
│   ├── teopORG logo.png   # Organization Logo
│   └── images/            # Image resources
├── en/                    # English pages
│   ├── index.html         # English home page
│   ├── about.html         # English about us page
│   ├── donate.html        # English donate page
│   ├── projects.html      # English projects page
│   ├── people.html        # English team page
│   └── contact.html       # English contact page
├── zh/                    # Chinese pages
│   ├── index.html         # Chinese home page
│   ├── about.html         # Chinese about us page
│   ├── donate.html        # Chinese donate page
│   ├── projects.html      # Chinese projects page
│   ├── people.html        # Chinese team page
│   └── contact.html       # Chinese contact page
├── index.html             # Language selection page
├── .gitattributes         # Git attributes file
├── .gitignore             # Git ignore file
├── LICENSE                # License file
├── PROJECT_STRUCTURE.md   # Project structure document
└── BACKEND_TODO.md        # Backend todo list
```

## Page Structure

### 1. Language Selection Page (index.html)
- Provides Chinese and English language selection
- Brief organization introduction

### 2. Home Page (index.html)
- Header: Logo and navigation bar
- Hero Section: Mission statement and donate button
- Donation Impact: Numeric explanation
- Quick Project Links: 3 main projects
- Footer: Copyright, privacy policy, social links

### 3. About Us (about.html)
- Organization Introduction: History, vision, mission
- Donation Appeal: Donation entry link
- Footer: Copyright, privacy policy, social links

### 4. Donate Page (donate.html)
- Donation Amount Selection: Preset amounts and custom amount
- Donation Methods: Online payment and bank transfer
- Recurring Donation Option
- Donor Information: Name, email, contact information
- Donation Impact Explanation
- Donation Success Confirmation

### 5. Projects Page (projects.html)
- Project List: 3-4 main projects
- Each project's description and progress
- Project Donation Buttons
- Footer: Copyright, privacy policy, social links

### 6. Team Page (people.html)
- Team member information
- Footer: Copyright, privacy policy, social links

### 7. Contact Us (contact.html)
- Contact Information: Email, address
- Social Links
- Footer: Copyright, privacy policy, social links

## Multi-language Support
- English pages: /en/ directory
- Chinese pages: /zh/ directory
- Language selection page: root directory index.html

## Technical Implementation
- Pure HTML implementation, no CSS or JavaScript
- Responsive design, adapting to different devices
- Clear page structure and semantic tags