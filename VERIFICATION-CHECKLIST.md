# 🔍 SEO Verification Checklist

## Use this checklist to verify your SEO implementation is working correctly.

---

## ✅ File Verification

Check that all files exist and are accessible:

### Required Files (Check URL in browser)
- [ ] https://www.onekarigar.com/ (Homepage loads)
- [ ] https://www.onekarigar.com/robots.txt (Shows robots directives)
- [ ] https://www.onekarigar.com/sitemap.xml (Shows XML sitemap)
- [ ] https://www.onekarigar.com/manifest.json (Shows JSON)
- [ ] https://www.onekarigar.com/browserconfig.xml (Shows XML)
- [ ] https://www.onekarigar.com/humans.txt (Shows team info)
- [ ] https://www.onekarigar.com/.well-known/security.txt (Shows security contact)

### Images (Need to create)
- [ ] https://www.onekarigar.com/assets/images/og-image.jpg
- [ ] https://www.onekarigar.com/assets/images/favicon.ico
- [ ] https://www.onekarigar.com/assets/images/icon-192x192.png
- [ ] https://www.onekarigar.com/assets/images/icon-512x512.png

---

## 🔬 Technical SEO Tests

### 1. Rich Results Test
**URL**: https://search.google.com/test/rich-results

Steps:
1. Enter: https://www.onekarigar.com
2. Click "Test URL"
3. Wait for results

✅ **Expected Results:**
- Organization ✓
- LocalBusiness ✓
- FAQPage ✓
- Service ✓
- Review ✓
- Breadcrumb ✓
- WebSite ✓

❌ **If any red errors**: Fix them in index.html

### 2. Mobile-Friendly Test
**URL**: https://search.google.com/test/mobile-friendly

Steps:
1. Enter: https://www.onekarigar.com
2. Click "Test URL"
3. Wait for results

✅ **Expected**: "Page is mobile-friendly"

### 3. PageSpeed Insights
**URL**: https://pagespeed.web.dev

Steps:
1. Enter: https://www.onekarigar.com
2. Click "Analyze"
3. Check both Mobile & Desktop

✅ **Target Scores:**
- Performance: 80+ (Desktop), 70+ (Mobile)
- Accessibility: 90+
- Best Practices: 90+
- SEO: 95+

### 4. SSL/HTTPS Test
**URL**: https://www.ssllabs.com/ssltest/

Steps:
1. Enter: www.onekarigar.com
2. Click "Submit"
3. Wait for scan

✅ **Target**: Grade A or A+

### 5. Schema Validation
**URL**: https://validator.schema.org/

Steps:
1. Go to site
2. Enter: https://www.onekarigar.com
3. Click "Run Test"

✅ **Expected**: 0 Errors, Minor warnings OK

---

## 📊 Search Console Verification

### Setup Google Search Console
1. Go to: https://search.google.com/search-console
2. Click "Add Property"
3. Enter: https://www.onekarigar.com
4. Verify ownership (HTML file method)

### Submit Sitemap
1. In Search Console, go to "Sitemaps"
2. Enter: https://www.onekarigar.com/sitemap.xml
3. Click "Submit"

✅ **Expected**: "Sitemap submitted successfully"

### Check Coverage
After 48-72 hours:
- [ ] Pages indexed: 1+
- [ ] Valid pages: All green
- [ ] Errors: 0
- [ ] Warnings: Check and fix

---

## 🔍 Meta Tags Verification

### View Page Source (Ctrl+U)
Check these tags exist in `<head>`:

#### Basic Meta Tags
- [ ] `<title>` contains keywords
- [ ] `<meta name="description">` 155-160 chars
- [ ] `<meta name="robots" content="index, follow..."`
- [ ] `<link rel="canonical">`

#### Open Graph Tags
- [ ] `<meta property="og:title">`
- [ ] `<meta property="og:description">`
- [ ] `<meta property="og:image">`
- [ ] `<meta property="og:url">`
- [ ] `<meta property="og:type">`

#### Twitter Tags
- [ ] `<meta name="twitter:card">`
- [ ] `<meta name="twitter:title">`
- [ ] `<meta name="twitter:description">`
- [ ] `<meta name="twitter:image">`

#### Structured Data
- [ ] `<script type="application/ld+json">` exists
- [ ] Contains Organization schema
- [ ] Contains LocalBusiness schema
- [ ] Contains FAQPage schema

---

## 🎯 Content Verification

### Homepage Content
- [ ] H1 tag exists and contains main keyword
- [ ] H2 tags properly nested
- [ ] All images have `alt` attributes
- [ ] All links work (no 404s)
- [ ] Contact information visible
- [ ] Call-to-action buttons present
- [ ] Phone number clickable (tel: link)

### Mobile View
- [ ] Text is readable without zooming
- [ ] Buttons are large enough (44x44px min)
- [ ] No horizontal scrolling
- [ ] Navigation menu works
- [ ] Forms are usable
- [ ] WhatsApp button works

---

## 🔗 Link Quality Check

### Internal Links
- [ ] All navigation links work
- [ ] "Book Now" CTA works
- [ ] Smooth scrolling to sections works
- [ ] Footer links work

### External Links
- [ ] Social media links work
- [ ] Bootstrap CDN loads
- [ ] Font Awesome loads
- [ ] Google Fonts load
- [ ] All have `rel="noopener noreferrer"` (for external)

---

## 🚀 Performance Verification

### Test Load Speed
Use browser DevTools (F12 → Network tab):

1. Clear cache
2. Reload page
3. Check metrics

✅ **Target:**
- [ ] DOMContentLoaded: < 1.5s
- [ ] Load complete: < 3s
- [ ] Total page size: < 2MB
- [ ] Total requests: < 50

### Test on Slow Connection
DevTools → Network → Throttling → Slow 3G

✅ **Target:**
- [ ] Page usable within 5 seconds
- [ ] Critical content visible within 3 seconds

---

## 📱 Social Media Preview Test

### Facebook Debugger
**URL**: https://developers.facebook.com/tools/debug/

1. Enter: https://www.onekarigar.com
2. Click "Debug"
3. Check preview

✅ **Expected:**
- Title appears
- Description appears
- Image appears (1200x630px)
- No errors

### Twitter Card Validator
**URL**: https://cards-dev.twitter.com/validator

1. Enter: https://www.onekarigar.com
2. Click "Preview card"

✅ **Expected:**
- Card preview appears
- Title, description, image visible

### LinkedIn Inspector
**URL**: https://www.linkedin.com/post-inspector/

1. Enter: https://www.onekarigar.com
2. Check preview

✅ **Expected:**
- Clean preview with image

---

## 🔒 Security Verification

### HTTPS Check
- [ ] Site loads with https://
- [ ] No mixed content warnings (F12 console)
- [ ] Padlock icon appears in browser
- [ ] Certificate is valid

### Headers Check
**URL**: https://securityheaders.com/

1. Enter: https://www.onekarigar.com
2. Check report

✅ **Target**: Grade B or higher

### Security.txt
- [ ] https://www.onekarigar.com/.well-known/security.txt loads
- [ ] Contains valid contact information
- [ ] Expires date is in future

---

## ♿ Accessibility Check

### WAVE Tool
**URL**: https://wave.webaim.org/

1. Enter: https://www.onekarigar.com
2. Review errors and alerts

✅ **Target:**
- Errors: 0
- Contrast errors: 0
- Alerts: < 5 (minor)

### Manual Checks
- [ ] Can navigate with keyboard only (Tab key)
- [ ] Focus indicators visible
- [ ] Links have descriptive text
- [ ] Forms have labels
- [ ] Images have alt text
- [ ] Color contrast is sufficient

---

## 🎨 Visual Check

### Cross-Browser Testing
Test on:
- [ ] Chrome (Desktop)
- [ ] Firefox (Desktop)
- [ ] Safari (Desktop/macOS)
- [ ] Edge (Desktop)
- [ ] Chrome (Mobile)
- [ ] Safari (iOS)

✅ **Expected:** Same appearance and functionality

### Responsive Design
Test at breakpoints:
- [ ] 320px (Small mobile)
- [ ] 375px (Mobile)
- [ ] 768px (Tablet)
- [ ] 1024px (Small desktop)
- [ ] 1920px (Large desktop)

---

## 📊 Analytics Verification

### Google Analytics
- [ ] Tracking code installed in `<head>`
- [ ] Real-time tracking works
- [ ] Pageviews recorded
- [ ] Events tracked (button clicks)

### Google Tag Manager (Optional)
- [ ] GTM container installed
- [ ] Tags firing correctly
- [ ] Debug mode shows activity

---

## 🎯 Local SEO Verification

### Google Business Profile
- [ ] Profile created
- [ ] 100% complete
- [ ] Address verified
- [ ] Photos added (10+)
- [ ] Business hours set
- [ ] Services listed
- [ ] First post published

### Local Citations
Check business listed on:
- [ ] Google Maps
- [ ] JustDial
- [ ] Sulekha
- [ ] IndiaMART
- [ ] Bing Places

---

## ✉️ Contact Form Testing

### Form Functionality
- [ ] Phone input accepts numbers
- [ ] Phone validation works
- [ ] "Call Me" button works
- [ ] WhatsApp chat opens correctly
- [ ] Pre-filled message appears

### WhatsApp Test
Click "Call Me" button:
- [ ] Opens WhatsApp web/app
- [ ] Correct number: +91-77748943561
- [ ] Message includes entered phone number
- [ ] Message is professional

---

## 📝 Final Checklist Before Launch

### Critical (Must Have)
- [ ] All images created and uploaded
- [ ] Favicon appears in browser tab
- [ ] SSL certificate active
- [ ] Google Search Console set up
- [ ] Sitemap submitted
- [ ] No 404 errors
- [ ] Mobile-friendly test passes
- [ ] Rich results test passes

### Important (Should Have)
- [ ] Google Business Profile created
- [ ] Google Analytics installed
- [ ] Social media profiles linked
- [ ] All links tested
- [ ] Performance score 80+
- [ ] Accessibility score 90+

### Nice to Have (Can Add Later)
- [ ] Blog section
- [ ] Video testimonials
- [ ] Live chat
- [ ] Customer portal

---

## 🐛 Common Issues & Fixes

### Issue: Sitemap not found
**Fix:** Check file uploaded to root directory

### Issue: Rich results don't appear
**Fix:** 
1. Validate JSON-LD at https://validator.schema.org
2. Allow 1-2 weeks for Google to process
3. Check Search Console for errors

### Issue: Mobile test fails
**Fix:**
1. Check viewport meta tag
2. Test on real device
3. Remove fixed widths in CSS

### Issue: Slow page speed
**Fix:**
1. Compress images (TinyPNG)
2. Enable caching (.htaccess)
3. Use CDN (Cloudflare)
4. Minimize CSS/JS

### Issue: Schema errors
**Fix:**
1. Use Rich Results Test
2. Fix red errors in JSON-LD
3. Re-test until green

---

## 📞 Where to Get Help

### Official Documentation
- Google Search Central: https://developers.google.com/search
- Schema.org: https://schema.org
- MDN Web Docs: https://developer.mozilla.org

### Community Support
- Stack Overflow: Tag `seo`, `schema.org`
- Google Search Central Community
- Reddit: r/SEO, r/TechSEO

### Professional Help
- Hire SEO consultant
- Use Fiverr/Upwork for specific tasks
- SEO agencies for full service

---

## ✅ Completion Status

Fill in dates as you complete:

- [ ] All files verified: __________
- [ ] Rich results test passed: __________
- [ ] Mobile test passed: __________
- [ ] PageSpeed 80+: __________
- [ ] Search Console setup: __________
- [ ] Sitemap submitted: __________
- [ ] Google Business created: __________
- [ ] Analytics installed: __________
- [ ] First review received: __________
- [ ] First blog post published: __________

---

## 🎉 After Everything is Green

**Congratulations!** Your website is now:
✅ Technically optimized  
✅ Search engine ready  
✅ Mobile-friendly  
✅ Accessible  
✅ Fast loading  
✅ Secure  

**Next Steps:**
1. Follow QUICK-ACTION-CHECKLIST.md
2. Create content weekly
3. Build backlinks monthly
4. Monitor Search Console weekly
5. Track progress in analytics

---

**Verification Date**: _______________  
**Verified By**: _______________  
**Status**: ⭕ Pending / ✅ Complete  
**Notes**: _______________

---

**Save this file and revisit monthly to ensure everything stays optimized!**

Last Updated: February 12, 2026
