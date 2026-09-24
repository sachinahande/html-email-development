# HTML Email QA Checklist

A practical checklist for reviewing HTML emails before production deployment.

Created by **Sachin Hande — Senior Email & Web Developer**

---

## 1. HTML & Structure

- [ ] HTML structure is valid
- [ ] Tables use `role="presentation"` where appropriate
- [ ] All opening tags have matching closing tags
- [ ] Images include meaningful `alt` text
- [ ] Decorative images use appropriate empty `alt`
- [ ] No unnecessary JavaScript is used
- [ ] CSS is compatible with email clients
- [ ] Important styles are inline where required

---

## 2. Responsive Testing

- [ ] Desktop layout checked
- [ ] Mobile layout checked
- [ ] Content stacks correctly on smaller screens
- [ ] Text remains readable on mobile
- [ ] Buttons are large enough for touch interaction
- [ ] Images scale correctly
- [ ] No horizontal scrolling
- [ ] Padding and spacing remain consistent

---

## 3. Email Client Testing

Test the email across relevant clients:

- [ ] Gmail
- [ ] Outlook
- [ ] Apple Mail
- [ ] Yahoo Mail
- [ ] iOS Mail
- [ ] Android email clients

---

## 4. Outlook Testing

- [ ] VML buttons render correctly
- [ ] Background images have appropriate fallbacks
- [ ] Table widths render correctly
- [ ] Font rendering is acceptable
- [ ] No unexpected spacing appears
- [ ] CTA buttons remain clickable
- [ ] Outlook-specific conditional comments work correctly

---

## 5. Dark Mode

- [ ] Text remains readable
- [ ] Background colors remain appropriate
- [ ] Logos and images remain visible
- [ ] CTA buttons remain accessible
- [ ] Dark-mode overrides are tested
- [ ] Gmail dark mode behavior is checked
- [ ] Apple Mail dark mode behavior is checked
- [ ] Outlook dark mode behavior is checked where applicable

---

## 6. Accessibility

- [ ] Sufficient color contrast
- [ ] Images include appropriate alternative text
- [ ] Links have meaningful text
- [ ] Content remains understandable without images
- [ ] Decorative elements do not create unnecessary screen-reader noise
- [ ] Font sizes remain readable
- [ ] Content order makes sense for assistive technologies
- [ ] Accessibility reviewed with a screen reader where required

---

## 7. Links & Tracking

- [ ] All links point to the correct destination
- [ ] No broken links
- [ ] CTA links tested
- [ ] Social media links tested
- [ ] Tracking parameters are correct
- [ ] Unsubscribe link is present where required
- [ ] View-in-browser link works where applicable

---

## 8. Images

- [ ] Image dimensions are correct
- [ ] Images are optimized
- [ ] Image URLs use HTTPS
- [ ] Images load correctly
- [ ] Retina/high-resolution images are handled appropriately
- [ ] Alt text is correct
- [ ] Images have appropriate fallback/background colors

---

## 9. Content Review

- [ ] Subject line reviewed
- [ ] Preheader reviewed
- [ ] Headlines checked
- [ ] Body copy checked
- [ ] Spelling and grammar checked
- [ ] CTA copy reviewed
- [ ] Personalization fields verified
- [ ] Legal/footer content reviewed

---

## 10. Final Production QA

- [ ] Final HTML version tested
- [ ] No placeholder content remains
- [ ] No placeholder links remain
- [ ] No test URLs remain
- [ ] No unnecessary comments or code remain
- [ ] Final screenshots reviewed
- [ ] Email tested in Litmus or equivalent testing environment
- [ ] Final approval received
- [ ] Production version archived

---

## Recommended Testing Tools

- **Litmus** — Email rendering and client testing
- **BrowserStack** — Cross-browser and device testing
- **NVDA** — Screen-reader testing
- **axe DevTools** — Accessibility testing
- **Email client previews** — Gmail, Outlook, Apple Mail and other target clients

---

## QA Workflow

- **Design** 
- **HTML Development**
- **Responsive QA** 
- **Email Client Testing**
- **Outlook / VML Testing**
- **Dark Mode Testing**
- **Accessibility Testing**
- **Link & Content Validation**
- **Final Approval**
- **Production Deployment**
 
---

## About

I'm **Sachin Hande**, a Senior Email & Web Developer specializing in responsive HTML email development, Figma-to-HTML workflows, Salesforce Marketing Cloud, email QA, accessibility, Outlook/VML development, dark mode email development, and front-end development.

**Portfolio:**  
https://sachinhande.work/

**LinkedIn:**  
https://www.linkedin.com/in/sachin-h-5a64647/

**GitHub:**  
https://github.com/sachinahande
