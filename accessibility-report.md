# Accessibility Audit Report

## Overview

An accessibility audit was conducted on the website using Chrome DevTools Lighthouse and the WAVE Web Accessibility Evaluation Tool.

## Issues Found

### 1. Images

The website has a background image added through CSS. The image is used as a decorative background, so an `alt` attribute was not required.

### 2. Heading Hierarchy

The page uses a proper heading hierarchy. The main page heading uses `<h1>` and the section heading uses `<h2>`.

No heading hierarchy changes were required.

### 3. Links

The links use descriptive text such as "YouTube" and "Email Me" instead of unclear text such as "Click here".

No link-text changes were required.

### 4. Language

The HTML document includes the language attribute:
 
 ### 5.Conclusion

The accessibility audit showed that the website has good accessibility. The Lighthouse Accessibility score was 96/100, while the WAVE/AIM accessibility evaluation gave a score of 10/10. The page uses a proper heading hierarchy, descriptive links, and a language attribute. The background image is used as a decorative element through CSS, and no form inputs are present.


```html
<html lang="en">
