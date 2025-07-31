# 90North Email Template - Usage Guide

## Overview
This is a reusable HTML email template designed specifically for internal product marketing and announcements at 90North. The template is fully compatible with Microsoft Outlook and follows email best practices for maximum deliverability.

## Template Features

### ✅ Outlook Compatibility
- **Table-based layout** - No CSS Grid or Flexbox
- **Inline CSS only** - No embedded `<style>` tags
- **MSO conditional comments** - Special Outlook rendering optimizations
- **VML button fallback** - Bulletproof buttons for Outlook

### 🎨 Design Elements
- **Brand colors**: Primary Purple (`#5F259F`) and Magenta (`#E6007E`)
- **Clean typography**: Arial/Helvetica for maximum compatibility
- **Modern aesthetics**: Subtle shadows, rounded corners, proper spacing
- **Responsive considerations**: Optimized for desktop but gracefully scales

### 📱 Layout Sections
1. **Header** - Logo and tagline
2. **Hero** - Main headline and subheadline
3. **Body** - Summary text, bullet points, optional image
4. **CTA** - Bulletproof call-to-action button
5. **Footer** - Contact info and disclaimers

## How to Use This Template

### 1. Replace Placeholder Content
Search for these HTML comments and replace with your content:

```html
<!-- INSERT EMAIL TITLE --> - Page title in <head>
<!-- INSERT LOGO HERE --> - Replace placeholder logo
<!-- INSERT HEADLINE HERE --> - Main announcement headline
<!-- INSERT SUBHEADLINE HERE --> - Supporting subheadline
<!-- INSERT SUMMARY TEXT HERE --> - Main body paragraph
<!-- INSERT BULLET POINT 1/2/3 --> - Key highlights
<!-- INSERT OPTIONAL IMAGE HERE --> - Product/feature image
<!-- INSERT LINK HERE --> - CTA button destination
<!-- INSERT CTA TEXT HERE --> - Button text
<!-- INSERT CONTACT INFO HERE --> - Footer contact details
<!-- INSERT DISCLAIMER HERE --> - Legal/internal disclaimer
```

### 2. Customize for Your Announcement

#### Example: Product Launch
```html
<!-- Replace headline -->
🚀 DataViz Pro v2.0 Now Available

<!-- Replace subheadline -->
Enhanced visualization capabilities for clinical trial data analysis.

<!-- Replace bullet points -->
<strong>Advanced Charting:</strong> 15+ new chart types for complex datasets
<strong>Real-time Collaboration:</strong> Share insights instantly with your team
<strong>Export Integration:</strong> One-click exports to PowerBI and Tableau
```

#### Example: Feature Update
```html
<!-- Replace headline -->
✨ New Integration: Epic EHR Connector

<!-- Replace subheadline -->
Seamlessly sync patient data from Epic systems into your 90North workflows.

<!-- Replace bullet points -->
<strong>Auto-sync:</strong> Real-time data updates every 15 minutes
<strong>HIPAA Compliant:</strong> Enterprise-grade security and encryption
<strong>Zero Setup:</strong> Connect your Epic instance in under 5 minutes
```

### 3. Logo Replacement
Replace the placeholder logo:
```html
<!-- Current placeholder -->
<img src="https://via.placeholder.com/180x40/5F259F/FFFFFF?text=90North" alt="90North Logo" width="180" height="40" style="display: block; border: 0; outline: none; text-decoration: none;" />

<!-- Replace with -->
<img src="YOUR_LOGO_URL_HERE" alt="90North Logo" width="180" height="40" style="display: block; border: 0; outline: none; text-decoration: none;" />
```

### 4. CTA Button Customization
```html
<!-- Button text options -->
Learn More | Try It Now | Get Started | View Demo | Download Now | Sign Up

<!-- Link destination examples -->
href="https://app.90north.com/new-feature"
href="https://docs.90north.com/sidekick-v1"
href="https://90north.com/demo-request"
```

## Testing Checklist

### Before Sending
- [ ] **Desktop Outlook 2016/2019/365** - Test in actual Outlook application
- [ ] **Outlook.com** - Web version compatibility
- [ ] **Gmail** - Desktop and mobile web
- [ ] **Apple Mail** - macOS and iOS
- [ ] **Mobile preview** - Check responsive behavior

### Content Review
- [ ] All placeholder comments replaced
- [ ] Logo displays correctly
- [ ] CTA button links to correct destination
- [ ] Contact information is current
- [ ] Spelling and grammar check
- [ ] Brand voice and tone consistency

## Email Testing Tools

### Recommended Services
- **Litmus** - Comprehensive email testing across 90+ clients
- **Email on Acid** - Real-time previews and deliverability testing
- **Mailtrap** - Safe testing environment for development

### Free Alternatives
- **PutsMail** - Simple HTML email testing
- **Mail Tester** - Spam score analysis
- **Can I Email** - CSS support reference

## Technical Notes

### Inline CSS Requirements
This template uses only inline CSS for maximum compatibility. Do not add:
- External stylesheets
- Embedded `<style>` tags
- CSS Grid or Flexbox
- Modern CSS properties (variables, transforms, etc.)

### Image Hosting
- Host images on reliable CDN (company assets server)
- Use absolute URLs only
- Optimize images for email (under 1MB total)
- Include alt text for accessibility

### Character Encoding
- Always use UTF-8 encoding
- Test special characters (emoji, symbols)
- Consider fallbacks for unsupported characters

## Brand Guidelines

### Color Usage
- **Primary Purple (#5F259F)**: Headlines, links, accents
- **Magenta (#E6007E)**: CTAs, highlights, bullets
- **Neutral Gray (#666666)**: Body text, secondary info
- **Dark Gray (#333333)**: Primary text, headlines

### Typography Hierarchy
- **H1 (28px)**: Main headlines
- **18px**: Subheadlines
- **16px**: Body text, bullet points
- **14px**: Footer text
- **12px**: Fine print, disclaimers

## Common Issues & Solutions

### Outlook Image Blocking
- Always include alt text
- Use background colors for design elements
- Test with images disabled

### Gmail Clipping
- Keep total email under 102KB
- Break long emails into multiple sends
- Use shorter subject lines

### Mobile Rendering
- Test on actual devices
- Consider finger-friendly button sizes
- Ensure text remains readable when scaled

## Support & Questions

For template customization help:
- **Slack**: #design-system or #marketing-tools
- **Email**: design@90north.com
- **Documentation**: Internal design system wiki

---

**Last Updated**: [Current Date]  
**Template Version**: 1.0  
**Maintained by**: Marketing & Design Team