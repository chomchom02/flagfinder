# Changelog

All notable changes to this project will be documented in this file.

The date format is `[YYYY-MM-DD]`
Available tags are `Added`, `Changed`, `Deprecated`, `Removed`, `Fixed` and `Security`

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased - 0.5]

### ➕ Added

- #41 Add Animations for Flagcards
- #37 SASS + PostCSS Preprocessor
- #49 Keywords for Flags
- #49 Search by keywords
- #49 Make every identity valid :)

### 🔄 Changed

- #32 Improve and redesign category filter buttons
- Globalize and reduce Media Queries
- Replace classes with data-cy for Tests

### 🛠️ Fixed

- Flag-details text overflow
- Console warnings
- #21 Offset for anchor in `/search`

## [0.4] - 2020-02-08

### ➕ Added

- Tests for search results
- Add dev tool for adding flags
- Logic to determine if flag category labels should be hidden or not

### 🔄 Changed

- About page
- Deployment pipeline
- Search results (include color data)
- Allow multiple categories per flag

### 🛠️ Fixed

- Deployment pipeline; Cypress should no longer fail because of missing memory
- Lock node version for now deployment
- Search results when using different text cases or spacing

## [0.3.1] - 2020-01-06

### 🛠️ Fixed

- `package.json` version number which fixes cypress tests

## [0.3] - 2019-12-23

### ➕ Added

- Changelog
- ColorField component
- Flag data (colorinfos) through [color-blindness.com/color-name-hue](https://www.color-blindness.com/color-name-hue/)
- Credits in readme

### 🔄 Changed

- Refactor Flagcards for mobile AND desktop
- Flag color palette
- Flag color meanings

### 🛠️ Fixed

- Flagcard text overflow
- Flag data (colors)

## [0.2] - 2019-12-08

### ➕ Added

- Tabs (Flag Details)

### 🛠️ Fixed

- Search filter clearing
- Flag data

### 🔄 Changed

- Refactor icons to new IconButton

## [0.1] - 2019-11-08

### ➕ Added

- Tests with Cypress
- Github Actions
- Readme
- Flag details page
- Navigation

### 🔄 Changed

- Move from Svelte to Sapper
- Flag data

### 🛠️ Fixed

- Search filter

## [Pre 0.1] - 2019-10-11

### ➕ Added

- EVERYTHING
