# Angela Foo Portfolio - Clean GitHub Root Replacement

This package uses the original light / sage minimalist design and four featured projects.
It was built using the complete website in your GitHub backup, and fixes the broken
image and resume links by placing ALL files at the repository root level.

PLEASE DO THIS:
1. Keep your existing GitHub backup ZIP somewhere safe.
2. Extract this ZIP on your computer. Open the extracted folder.
3. In your GitHub repository (anfooster/angelafoo.github.io), make sure you are
   looking at the main page of the repository (where index.html is shown).
4. Click Add file > Upload files. Select ALL extracted site files (including
   index.html, styles.css, script.js, all .webp files, video and PDFs).
   Do not upload this ZIP itself and do not upload its enclosing folder.
5. Commit changes to your default branch (normally main).
6. Confirm Settings > Pages > Build and deployment = Deploy from a branch,
   Branch = main, Folder = /(root).
7. Open https://anfooster.github.io/angelafoo.github.io/ in a new private/incognito tab.
   Check the four project links and the Resume button.

You DO NOT need to delete anything first. Old duplicate folders and unused files
can be removed later. The root index.html, styles.css, script.js and case-study
pages overwrite matching root files, and all image paths now point directly to
root-level image files. This avoids GitHub web upload folder-placement issues.

Optional cleanup AFTER the site works:
- Delete the old Angela_Foo_Portfolio_Final_4_Projects/ folder.
- Delete obsolete project.html, projects.js, and unused old PDFs (if desired).
- Keep the root index.html, styles.css, script.js, 4 case-study HTML pages,
  .webp photos, fixture video, and linked PDF files.

If the site still looks stale, hard-refresh or open an incognito window. New CSS/JS
cache-busting URLs are included to reduce browser cache problems.

No web build tool is needed; this site is plain static HTML/CSS/JavaScript.

This edition removes small editorial/disclaimer notes beneath metrics and within
project sections. Numeric labels and relevant project details remain in place.
