# Research View

Static, Vercel-ready research portfolio.

## Deploy

1. Create a new private GitHub repository with a neutral name such as
   `research-view-7k3p`.
2. Upload all files from this folder to the repository root.
3. In Vercel, select **Add New → Project** and import that repository.
4. Keep **Framework Preset** set to **Other**. No build command or output
   directory is required.
5. Deploy, then enable **Settings → Deployment Protection → All Deployments**.
6. Open the deployment and select **Share → Anyone with the link**.

The permissive `robots.txt` allows crawlers to retrieve the pages and read the
`noindex` directives supplied by the HTML metadata and response headers.
Deployment Protection remains the primary privacy control when access must be
restricted rather than merely omitted from search results.
