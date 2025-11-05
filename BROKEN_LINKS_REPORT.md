# Broken Links Report

This report documents all broken links found in the website after the migration from the old ISSP site.

## Summary

- **Date of Analysis:** November 5, 2025
- **Total files with broken links:** 4
- **Total broken links to old ISSP site:** 9

## Background

All access to the original site at ISSP (`oshikawa.issp.u-tokyo.ac.jp`) is now redirected to this GitHub Pages site. Therefore, any references to the original ISSP site, including files hosted at the ISSP site, will cause errors.

## Broken Links by File

### English Pages

#### 1. `index.html`
Contains 2 broken links to workshop pages:

- **Line 127:** `http://oshikawa.issp.u-tokyo.ac.jp/esr/`
  - Context: ISSP/COE Workshop "New Developments in ESR of Strongly Correlated Systems" (May 2007)
  
- **Line 131:** `http://oshikawa.issp.u-tokyo.ac.jp/pmiqs/`
  - Context: "Physics and Mathematics of Interacting Quantum Systems in Low Dimensions" workshop (May 2007)

#### 2. `papers-j-1.html` (Japanese page with broken link)
- **Line 56:** `https://oshikawa.issp.u-tokyo.ac.jp/publications.php`
  - Context: Link to publications database

### Japanese Pages

#### 3. `nishina-j.html`
- **Line 101:** `https://oshikawa.issp.u-tokyo.ac.jp/Oshikawa_Group_BusseikenDayori_52_3_2012.pdf`
  - Context: Research group report PDF from 2012

#### 4. `research-j.html`
Contains 5 broken links to PDF files and databases:

- **Line 64:** `https://oshikawa.issp.u-tokyo.ac.jp/Kagaku_202208_0752_Oshikawa.pdf`
  - Context: Article PDF from Science magazine (August 2022)
  
- **Line 66:** `https://oshikawa.issp.u-tokyo.ac.jp/Kagaku_202208_0752_Oshikawa.pdf`
  - Context: Same article PDF (duplicate reference)
  
- **Line 76:** `https://oshikawa.issp.u-tokyo.ac.jp/Oshikawa_Group_BusseikenDayori_52_3_2012.pdf`
  - Context: Research group report PDF from 2012
  
- **Line 110:** `https://oshikawa.issp.u-tokyo.ac.jp/Oshikawa-Group-Flyer-June2022.pdf`
  - Context: Group guidance poster from June 2022
  
- **Line 113:** `https://oshikawa.issp.u-tokyo.ac.jp/publications.php`
  - Context: Publications database

## Recommendations

To fix these broken links, the following actions are recommended:

1. **For PDF files**: Upload the referenced PDF files to this GitHub repository and update the links to point to the local copies.

2. **For workshop pages**: Either:
   - Create archive pages with the workshop information on this site, or
   - Remove the broken links and keep only the text descriptions

3. **For the publications database**: Consider either:
   - Creating a local publications page with the same information, or
   - Updating the link to point to another source if available

## Files That Need Attention

### High Priority (English pages)
- `index.html` - 2 broken workshop links

### Medium Priority (Japanese pages)
- `research-j.html` - 5 broken links to PDFs and database
- `nishina-j.html` - 1 broken link to PDF
- `papers-j-1.html` - 1 broken link to database

## Actions Completed

✅ **Task 1:** Removed "Visiting ISSP" navigation entry from all English pages (11 files)
- alumni.html
- contact.html
- index.html
- members.html
- oldnews-2.html
- oldnews.html
- oshikawacv.html
- prb2prl.html
- publications.html
- research.html
- talks.html

✅ **Task 2:** Documented all broken links to old ISSP site

---
*Report generated on November 5, 2025*
