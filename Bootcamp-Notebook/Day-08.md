### How Software Is Organized

npm stands for Node Package Manager. You don't need to master Node today—just know that npm is the tool that installs and manages the project's software packages.

## One Big Idea

Notice something important.

Almost none of these files contain the website itself.

Instead, they answer questions like:

How do we build it?
How do we deploy it?
What tools does it use?
What should Git ignore?
What images does it need?

The actual website lives mostly in src/.

Everything else supports it.

pinkham-creek-farmstead/
├── src/
├── public/
├── README.md
├── package.json
├── package-lock.json
├── .gitignore
├── astro.config.mjs
└── netlify.toml

nstead of random names, you can now recognize their roles:

src → where the application's source code lives.
public → images, fonts, and other files served directly to visitors.
README.md → the project's instruction manual.
package.json → the project's recipe card and command list.
package-lock.json → the exact dependency versions.
.gitignore → files Git should leave out.
astro.config.mjs → Astro's configuration.
netlify.toml → Netlify's deployment instructions.

Situation	                Command
First time on a computer	git clone
Get the latest changes	    git pull
Save your work locally	    git commit
Upload your work to GitHub	git push


## Summary
# Day 8 - Understanding a Real Astro Project

Learned:
- git clone vs git pull
- npm install and dependencies
- package.json structure
- Astro development server
- File-based routing
- Layouts and reusable components
- How <slot /> works
- Data-driven pages
- Reading an existing codebase

Project explored:
Pinkham Creek Farmstead website

complete developer feedback loop:
1. Locate the right file
        ↓
2. Understand why it controls that part of the site
        ↓
3. Make a change
        ↓
4. Save
        ↓
5. Development server detects change
        ↓
6. Browser updates
        ↓
7. Verify the result
        ↓
8. Restore the original

Source code

The files humans write:

src/
Build process

The transformation:

Astro + your files
        ↓
finished website
Development server

The live workspace:

npm run dev
        ↓
localhost:4321
Hot reload

The thing you just experienced:

save file
    ↓
browser updates

No refresh. No redeploy. Instant feedback.

### start Day 9: Components — Building Blocks of Modern Apps.