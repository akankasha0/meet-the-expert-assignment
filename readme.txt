PROJECT NAME: Meet the Expert (Custom Directory)
CANDIDATE NAME: Akanksha Maurya
PARENT THEME REQUIRED: OceanWP

----------------------------------------------------------------------
1. TASK OVERVIEW
----------------------------------------------------------------------
This project implements a Custom Post Type (Experts) with custom fields,
a responsive CSS Grid layout, and an AJAX-based "Quick View" feature.

----------------------------------------------------------------------
2. SETUP INSTRUCTIONS
----------------------------------------------------------------------
- THEME: Upload the 'meet-the-expert' folder to /wp-content/themes/.
- PLUGIN: Install and Activate 'Advanced Custom Fields' (ACF) PRO or FREE.
- DATA IMPORT: Go to 'ACF > Tools' and import the 'acf-export-2026-05-12.json'
  file found in the theme folder.
- PREVIEW: The experts can be viewed at: your-site-url/experts/

----------------------------------------------------------------------
3. TECHNICAL NOTES & LIMITATIONS
----------------------------------------------------------------------
- REPEATER FIELD ALTERNATIVE: The task requested a Repeater field for
  Social Links. Since the free version of ACF was used, I have implemented
  Social Links using individual custom fields (Facebook, Twitter, LinkedIn).
  This ensures functionality without requiring a Pro license while
  maintaining a clean UI.

- AJAX QUICK VIEW: Implemented using WordPress standard wp_ajax hooks.
  The data is fetched dynamically without page refresh.

- RESPONSIVENESS: The layout uses CSS Grid/Flexbox and ensures
  images use 'srcset' for performance optimization.

- PERFORMANCE: Custom JS/CSS is enqueued only on the Experts archive
  page to maintain site speed.
----------------------------------------------------------------------