# Accessibility Audit - telangana.gov.in

**Date:** 02/09/2026
**Lighthouse Score:** 84/100

### Issue 1: Contrast Error [High]
Evidence: Lighthouse screenshot lo "Background and foreground colors do not have sufficient contrast ratio"
Fix: CSS lo color contrast 4.5:1 cheyali

### Issue 2: Link Name Missing [High]
Evidence: "Links do not have a discernible name" error
Fix: <a> tags ki aria-label add cheyali

### Issue 3: 404 Errors [High]
Evidence: Console lo "Failed to load resource 404"
Fix: File paths correct cheyali

### Issue 4: Keyboard Focus Not Visible [Medium]
Evidence: Tab key tho navigate chesthe focus kanipinchadu
Fix: :focus { outline: 2px solid blue }

### Issue 5: Alt Text Missing [Low]
Evidence: Images ki alt="" empty
Fix: Meaningful alt text ivvali
