# Upload instructions

This kit is designed to fix the current profile README and turn the GitHub account into a polished research landing page.

## 1. Personal GitHub profile

Your personal GitHub profile is controlled by the repository named exactly like the account:

```text
DrJoyKarmakar
```

Upload these files to the root of that repository:

```text
README.md
assets/
branding/
docs/
templates/
repository-readmes/
.github/
CODE_OF_CONDUCT.md
CONTRIBUTING.md
SECURITY.md
CITATION.cff
LICENSE
FUNDING.yml
```

The most important files are:

```text
README.md
assets/svg/jai-lab-hero.svg
assets/svg/jai-lab-ecosystem.svg
assets/svg/infrastructure-loop.svg
assets/svg/scientific-stack.svg
assets/svg/repository-architecture.svg
assets/svg/research-timeline.svg
assets/svg/jai-lab-footer.svg
```

## 2. Replace the existing profile README

The current profile page is displaying a generic package note. Replace the existing root `README.md` with the new root `README.md` in this ZIP.

## 3. Recommended pinned repositories

Pin these in this order:

1. SensorGenome
2. NarcoticSense-AI
3. AZAI
4. BimaneDB
5. pendrin-hybrid
6. Paper-Organizer

If you want a stronger drug-discovery emphasis, replace Paper-Organizer with pendrin-qsar.

## 4. Optional JAI Lab organization

If you create a GitHub organization named `JAI-Lab` or similar, create a repository named `.github` inside that organization. Upload the contents of the `org-profile/` folder to that repository. The final structure should look like this:

```text
.github repository root/
  profile/README.md
  assets/svg/
```

The `org-profile/` folder is already prepared with the correct relative image paths.

## 5. Repository README upgrades

The folder `repository-readmes/` contains tailored README drafts for your current and planned repositories. Copy each file into the matching repository as `README.md`, then adjust commands, examples, and installation steps.

## 6. Before publishing

Run this checklist:

- Confirm all links work.
- Confirm local SVG assets render.
- Confirm no private or unpublished data is exposed.
- Confirm claims are still accurate.
- Update roadmap checkboxes as work is completed.
- Add citations or DOI links to publication pages when available.
