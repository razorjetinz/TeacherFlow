# Publish TeacherFlow with GitHub Pages

TeacherFlow is a static application. The repository root contains `index.html`, so no build command is required.

1. Open https://github.com/razorjetinz/TeacherFlow/settings/pages
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Set **Branch** to `main`.
4. Set the folder to `/(root)`.
5. Select **Save**.

GitHub will build and publish the site. When deployment completes, the expected address is:

https://razorjetinz.github.io/TeacherFlow/

You can check progress in the repository's **Actions** tab and revisit Settings → Pages for the published URL.

The source repository is public and includes the MIT licence. GitHub Pages hosting is separate from the source-code commit; a repository administrator must enable Pages in Settings.
