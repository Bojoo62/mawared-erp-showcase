# Final GitHub Visibility Setup

The repository content, website files, workflow, community forms, and share kit are already prepared. The settings below require repository-owner actions in the GitHub interface.

## 1. Repository About section

Open the repository main page and click the gear icon beside **About**.

Description:

`Arabic-first multi-company HR and ERP platform built with Kotlin, Jetpack Compose, TypeScript, Express, Prisma and PostgreSQL.`

Website:

`https://bojoo62.github.io/mawared-erp-showcase/`

Topics:

`erp`
`hrms`
`human-resources`
`android`
`kotlin`
`jetpack-compose`
`typescript`
`express`
`postgresql`
`prisma`
`supabase`
`saas`
`arabic`
`rtl`
`rbac`

Keep **Releases**, **Packages**, and **Environments** unchecked unless they are needed later.

## 2. Enable GitHub Pages

Go to:

**Repository → Settings → Pages**

Under **Build and deployment**, set **Source** to:

`GitHub Actions`

The deployment workflow is already available at:

`.github/workflows/pages.yml`

After enabling Pages, run the workflow manually from the **Actions** tab if it does not start automatically.

Expected website:

`https://bojoo62.github.io/mawared-erp-showcase/`

## 3. Social preview

Go to:

**Repository → Settings → General → Social preview → Edit → Upload an image**

Upload the prepared `mawared-social-preview.png` file supplied separately.

## 4. Pin the repository

Go to:

**Your profile → Customize your pins**

Select:

`mawared-erp-showcase`

Place it first among the pinned repositories.

## 5. Profile README

Create a new public repository named exactly:

`Bojoo62`

Initialize it with a README and replace the content with:

`PROFILE_README_TEMPLATE.md`

A repository matching the username is required for the README to appear on the GitHub profile.

## 6. First public sharing

Use one of the Arabic or English announcements in:

`docs/SHARE_KIT.md`

Always share the public showcase or website. Never share the private commercial repository.

## 7. Screenshot safety

Before adding product screenshots:

- Use fictional employees and demo companies.
- Remove email addresses, phone numbers, employee IDs, and personal information.
- Hide API URLs, tokens, database identifiers, logs, QR codes, and authentication responses.
- Check the full screenshot for phone notifications and unrelated personal information.
