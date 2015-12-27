# express-md

A basic template for an express server that will serve markdown files from a
`/pages` directory wrapped in an HTML layout.

1. Clone the repo.
2. Modify `views/layout.ejs` to your desire.
3. Add markdown files to the `/pages` directory.
4. They will now be available as routes based on their filename
  1. `pages/about.md` will be available at `/about`
5. For now, you'll need to add the pages to the navigation in `views/layout.ejs`
