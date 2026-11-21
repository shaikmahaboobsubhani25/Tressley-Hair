# GitHub Pages preview path fix

All HTML links and local asset references now use paths relative to each page. This works both at the project URL `https://shaikmahaboobsubhani25.github.io/Tressley-Hair/` and later at the root of `https://www.tressleyhair.com/`.

## Upload
1. Open your GitHub Tressley-Hair repository.
2. Use Add file > Upload files and upload the **contents** of this ZIP (not the ZIP).
3. GitHub may not overwrite existing files reliably using Upload files; if it reports conflicts, use GitHub Desktop or delete old files first and upload the replacement set. Do not delete the repository itself.
4. Commit to main, wait for Pages to deploy, then hard-refresh (Ctrl+Shift+R).

## Safety
This remains a staging prototype with `noindex` meta tags and robots.txt blocking indexing. Do not change DNS or connect your production domain until migration is complete.
