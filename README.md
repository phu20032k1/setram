# Transport UI Preview

Interactive mobile web interface based on provided screenshot references. This is **not an official transport application**. The sample ticket-validation history contains fictional dates in December 2026 and is marked **SAMPLE DATA — NOT VALID FOR TRAVEL**.

## Main screens

- Home
- Timetables
- M-ticket → ... → My validations
- Traffic info
- Menu

The whole site is contained in `index.html`. No build tools or backend are needed.

## Publish to GitHub Pages

A deployment workflow is already present at `.github/workflows/pages.yml`.

1. Open **Settings → Pages**: https://github.com/phu20032k1/setram/settings/pages
2. Under **Build and deployment → Source**, choose **GitHub Actions**. This enables GitHub Pages for the repository.
3. Go to https://github.com/phu20032k1/setram/actions/workflows/pages.yml, select **Run workflow** on the **main** branch.
4. When deployment succeeds, the website should be available at **https://phu20032k1.github.io/setram/**.

If the workflow fails with `Resource not accessible by integration` at the "Configure GitHub Pages" step, Pages must be enabled through the Settings page first. The connected GitHub integration cannot grant itself repository administration permissions.

## Local preview

Open `index.html` in a browser.
