PULSE static website deployment package

index.html            Main PULSE control tower dashboard
executive-report.html Separate executive report page

Both pages are standalone HTML files with inline styles/scripts. Deploy this folder as a static site. On Vercel, the simplest workflow is to push these files to a GitHub repository and import the repository in Vercel. No build command is required; use the Other framework preset and leave the output directory as the project root.
