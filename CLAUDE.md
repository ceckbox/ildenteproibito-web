CLAUDE.md

IL DENTE PROIBITO — README GENERATION SPECIFICATION

PRIMARY OBJECTIVE

Create a complete "README.md" for this repository from scratch.

Repository:

https://github.com/ildenteproibito/ildenteproibito-web

Official website:

https://ildenteproibito.pages.dev/

The README must accurately document the actual project represented by this repository and its official website.

The README is a documentation task only.

Do NOT redesign, refactor, improve, restructure, or modify the project itself.

---

CRITICAL RULE — DO NOT TAKE UNREQUESTED INITIATIVE

This is an extremely important requirement.

Your task is ONLY to create the "README.md".

Do not:

- modify source code;
- modify HTML;
- modify CSS;
- modify JavaScript;
- modify TypeScript;
- modify configuration files;
- modify dependencies;
- modify package files;
- modify assets;
- rename files;
- delete files;
- create additional documentation files;
- create additional project files;
- change the website;
- change the project's functionality;
- change the project's design;
- add features;
- remove features;
- refactor code;
- optimize code;
- "fix" unrelated issues;
- create new GitHub workflows;
- change licenses;
- change metadata.

Unless explicitly instructed otherwise, ONLY "README.md" may be created or modified.

---

SOURCE OF TRUTH

Before writing the README, inspect BOTH:

Official website

https://ildenteproibito.pages.dev/

GitHub repository

https://github.com/ildenteproibito/ildenteproibito-web

The official website is the primary source for understanding the project's public-facing identity, content, features, sections, links, and purpose.

The repository is the primary source for understanding the actual implementation, technologies, structure, scripts, dependencies, and files.

Use both sources together.

---

WEBSITE ANALYSIS

You MUST thoroughly inspect the official website before generating the README.

Analyze the website as it currently exists.

Inspect, where available:

- Homepage
- Navigation
- Sections
- Hero
- About sections
- Projects
- Portfolio
- Services
- Skills
- Technologies
- Contact sections
- Social links
- GitHub links
- External links
- Calls to action
- Footer
- Visible project information
- Publicly stated information
- Any other publicly accessible page or section

If the website contains links to other pages within the same site, inspect those pages as well when possible.

Do not assume that something exists simply because it is common on portfolio websites.

---

REPOSITORY ANALYSIS

Before generating "README.md", inspect the entire repository.

Pay attention to:

- Repository structure
- Source files
- Assets
- Configuration
- "package.json"
- Lockfiles
- Framework configuration
- Build configuration
- Deployment configuration
- HTML
- CSS
- JavaScript
- TypeScript
- Components
- Routes
- Public assets
- Images
- Fonts
- Icons
- Existing documentation
- Existing metadata
- Existing license files

Understand how the website is actually implemented.

Do not describe a technology merely because its name appears in an unrelated file.

Verify technologies through actual project usage and configuration.

---

ABSOLUTE NO-HALLUCINATION RULE

NEVER invent information.

Every factual statement in the README must be supported by:

1. The official website.
2. The repository itself.
3. Information explicitly provided by the repository owner.

If something cannot be verified:

DO NOT include it.

Do not guess.

Do not extrapolate.

Do not fill missing information with assumptions.

Do not invent:

- features;
- technologies;
- frameworks;
- libraries;
- services;
- projects;
- statistics;
- experience;
- achievements;
- clients;
- performance metrics;
- browser compatibility;
- system requirements;
- deployment platforms;
- release information;
- version numbers;
- roadmap items;
- future plans;
- contact information;
- social profiles;
- project descriptions;
- professional claims.

Accuracy is more important than completeness.

---

DO NOT CONVERT ASSUMPTIONS INTO FACTS

For example:

If you see a CSS animation, do not claim:

«"The website is optimized for high-performance animations."»

unless that is actually supported.

If you see Cloudflare configuration, do not claim:

«"Cloudflare provides the entire infrastructure."»

unless the repository clearly establishes this.

If you see React installed, verify that React is actually used before describing the project as a React website.

If a technology is present but not relevant to the final application, do not present it as a major project technology.

---

README MUST DESCRIBE THE ACTUAL PROJECT

The README should explain what the project actually is.

It should not become a generic developer portfolio README template.

Do not add generic sections simply because other GitHub repositories contain them.

The content must be specific to IL DENTE PROIBITO and this repository.

---

README STRUCTURE

Create a polished structure based on the information actually discovered.

A possible structure is:

1. Hero
2. About
3. Features / Highlights
4. Technologies
5. Project Structure
6. Website
7. Development / Local Setup
8. Deployment
9. Links / Contact
10. License

However:

DO NOT force sections that cannot be supported by verified information.

If a section has no reliable information, omit it.

---

HERO SECTION

The README should begin with a modern centered hero section.

Use HTML where appropriate.

Example structure:

<div align="center">IL DENTE PROIBITO

Verified project description based on the official website.

"Website" (https://ildenteproibito.pages.dev/) · "GitHub" (https://github.com/ildenteproibito/ildenteproibito-web)

</div>Do not blindly copy this example.

Use the actual project identity and verified description.

---

VISUAL STYLE

The README should be:

- modern;
- clean;
- professional;
- visually structured;
- easy to scan;
- compatible with GitHub rendering.

Use centered HTML sections where appropriate.

Prioritize visual hierarchy.

Do not make every paragraph centered if doing so makes technical documentation harder to read.

The README should feel intentionally designed rather than generated from a generic template.

---

BADGES

Badges may be used only when their information is factual and verifiable.

Examples of potentially appropriate badges:

- framework;
- language;
- deployment platform;
- license;
- repository status.

However:

DO NOT add badges merely because they look good.

DO NOT create badges for technologies that are not actually used.

DO NOT create fake version badges.

DO NOT create fake status badges.

DO NOT create fake build badges.

---

TECHNOLOGIES

Create a technology section only after inspecting the repository.

Determine the actual technologies used.

Use:

- "package.json";
- configuration files;
- imports;
- source files;
- build configuration;
- deployment configuration.

Do not infer the entire stack from one dependency.

For each technology mentioned, ensure that it is genuinely part of the project.

---

FEATURES

Document actual website/project features.

Features must come from the website or repository.

Do not transform design elements into fictional functionality.

For example, an animated visual element is not necessarily a "feature" unless it is meaningful enough to document.

Prefer concrete descriptions.

---

PROJECT STRUCTURE

If useful, document the repository structure.

Only include files and directories that actually exist.

Do not invent paths.

If the repository contains a large or complex structure, summarize it rather than dumping every file.

---

LOCAL DEVELOPMENT

If the repository contains a valid development workflow, document it.

Inspect "package.json" and identify actual scripts.

Only provide commands that actually exist.

For example, if the repository contains:

"scripts": {
  "dev": "...",
  "build": "...",
  "preview": "..."
}

document those actual commands.

NEVER invent:

npm run dev

unless "npm run dev" actually exists.

Likewise, do not invent package-manager commands.

Use the package manager indicated by the repository.

---

INSTALLATION

Only document installation steps that can be verified.

If the project is an npm project, verify the actual package manager and scripts before documenting installation.

Do not assume:

- npm;
- pnpm;
- yarn;
- bun;

unless supported by the repository.

---

DEPLOYMENT

Only document deployment information that is explicitly supported by the repository.

If the repository contains Cloudflare Pages configuration or other deployment configuration, inspect it before documenting deployment.

Do not claim that the website is deployed through a specific service unless the evidence supports it.

---

OFFICIAL WEBSITE

The README should include the official website:

https://ildenteproibito.pages.dev/

Use a clean call-to-action such as:

<div align="center">"Visit the Official Website" (https://ildenteproibito.pages.dev/)

</div>Do not modify the URL.

---

GITHUB REPOSITORY

The README may link to the repository:

https://github.com/ildenteproibito/ildenteproibito-web

Do not invent alternative repositories.

---

SOCIAL LINKS

Only include social links that are actually present on the official website or repository.

Do not search for unrelated accounts and assume they belong to the project owner.

Do not invent social profiles.

If the official website provides a social profile, verify the URL before including it.

---

LICENSE

Inspect the repository for an existing license.

If a license exists:

- document it accurately;
- link to the existing license file;
- do not replace it;
- do not create a different license;
- do not duplicate the full license text unnecessarily.

If no license exists, do not invent one.

---

PROJECT STATUS

Do not invent a release status.

Do not create:

- fake version numbers;
- fake release dates;
- fake roadmap;
- fake changelog;
- fake download section;
- fake future features.

Only document project status if it is explicitly visible or verifiable.

---

NO GENERIC MARKETING

Avoid exaggerated marketing language.

Do not use claims such as:

- "the most advanced";
- "the fastest";
- "industry-leading";
- "revolutionary";
- "best-in-class";
- "blazing-fast";

unless the project owner explicitly uses such claims and they are appropriate to reproduce.

The README should be factual and professional.

---

NO UNREQUESTED AUTHORS / CONTRIBUTORS

Do not create contributor lists unless contributors are explicitly identifiable from the repository or requested.

Do not assign roles to people based on assumptions.

Do not add:

- Founder;
- Developer;
- Designer;
- Maintainer;
- Creator;

unless this information is explicitly verified.

---

NO UNREQUESTED FEATURES

Do not propose or add sections such as:

- Roadmap
- Contributing
- FAQ
- Security
- Support
- Sponsors
- Donations
- Discord
- Community
- Analytics
- API
- Architecture

unless relevant information actually exists or the section is clearly useful and supported.

The goal is documentation, not expansion of the project.

---

HTML / MARKDOWN QUALITY

Before finishing:

- Validate Markdown structure.
- Validate HTML tags.
- Close every "<div>".
- Close every link correctly.
- Ensure code blocks are closed.
- Ensure tables are valid.
- Ensure images have appropriate "alt" text.
- Ensure headings follow a logical hierarchy.
- Ensure there are no malformed Markdown links.
- Ensure there are no broken internal links.

---

LINK VERIFICATION

Verify every link added to the README.

Official website:

https://ildenteproibito.pages.dev/

Repository:

https://github.com/ildenteproibito/ildenteproibito-web

Do not add external links unless they are verified and relevant.

---

FILE MODIFICATION RESTRICTION

At the end of the task:

"README.md" must be the ONLY project file modified or created.

Do not modify anything else.

Run:

git status

and verify that there are no unintended changes.

If you discover unrelated changes already present in the working tree:

DO NOT overwrite or revert them.

DO NOT clean the working tree.

DO NOT modify them.

Only work on "README.md".

---

FINAL AUDIT

Before completing the task, perform a final verification.

Repository

- Did you inspect the repository?
- Did you inspect the project structure?
- Did you inspect package/configuration files?
- Did you inspect the existing license?

Website

- Did you inspect the official website?
- Did you inspect its relevant sections?
- Did you use the website as a source of truth for public-facing information?

Accuracy

- Did you invent anything?
- Did you make assumptions?
- Are all technologies actually used?
- Are all features actually present?
- Are all links valid?

README

- Is the README complete?
- Is it professional?
- Is it visually polished?
- Is the hero centered?
- Is the official website clearly linked?
- Is the repository clearly identified?
- Are technical instructions based on actual project configuration?

Scope

- Did you modify ONLY "README.md"?
- Did you avoid refactoring?
- Did you avoid changing source code?
- Did you avoid creating unrelated files?
- Did you avoid taking unrequested initiatives?

---

FINAL RULE

When information is uncertain:

DO NOT GUESS.

Inspect the repository.

Inspect the official website.

If the information still cannot be verified, OMIT IT.

A shorter README containing only verified information is better than a longer README containing assumptions.

The objective is:

Create the best possible README for the existing IL DENTE PROIBITO project, without changing or inventing anything about the project itself.
