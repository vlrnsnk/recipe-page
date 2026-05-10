# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm).
Frontend Mentor challenges help improve frontend skills by building realistic UI components.

## Table of contents

- [Overview](#overview)
  - [Preview](#screenshot)
  - [Links](#links)
- [Features](#features)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Setup](#setup)
  - [Installation](#installation)
  - [Development](#development)
  - [Build](#build)
  - [Linting](#linting)
- [Deployment](#deployment)
- [Performance](#performance)
- [Author](#author)
- [Notes](#notes)

## Overview

### The challenge

- Build out a recipe page and get it looking as close to the design as possible
- Focus on semantic HTML structure

### Preview

<details>
  <summary>Click to expand website preview</summary>
  <br>
  <p align="center">
    <img src="./preview.png" alt="website preview" width="894" style="max-width: 100%; height: auto;">
  </p>
</details>

### Links

- Solution URL: [GitHub Repo](https://github.com/vlrnsnk/recipe-page)
- Live Site URL: [Live Site](https://vlrnsnk.github.io/recipe-page/)

## Features

- Responsive layout (mobile-first)
- Accessible interactive states (hover + focus-visible)
- SCSS modular architecture
- CSS property ordering enforced via Stylelint
- Optimized build with Vite
- GitHub Pages deployment via GitHub Actions

## My process

### Built with

- Semantic HTML5 markup
- SCSS (modular architecture: abstracts, base, components, layout)
- CSS custom properties (design tokens via SCSS variables)
- Flexbox
- Mobile-first workflow
- Vite
- Stylelint (code quality + property ordering)
- HTML validation
- Husky (pre-commit hooks)

### What I learned

- BEM methodology and when to use blocks vs elements vs modifiers
- How CSS custom properties and SCSS variables work together
- Why unitless line-height is preferred over percentages
- Using ::before with counters for styled ordered lists
- Mobile-first responsive workflow with logical CSS properties

## Setup

### Installation

```bash
npm install
```

### Development

```bash
npm run dev
```

### Build

```bash
npm run build
npm run preview
```

### Linting

```bash
npm run lint:scss
npm run lint:html
```

This project uses Stylelint + EditorConfig + Husky pre-commit hooks
to ensure consistent code formatting before commits.

### Fix linting issues:

```bash
npm run lint:scss:fix
npm run lint:html:fix
```

## Deployment

Project is built with Vite and deployed to GitHub Pages using GitHub Actions.

## Performance

Lighthouse score (example):

- Performance: 100
- Accessibility: 100
- Best Practices: 100
- SEO: 100

## Author

- Website: https://vlrnsnk.com
- Frontend Mentor: https://www.frontendmentor.io/profile/vlrnsnk
- GitHub: https://github.com/vlrnsnk

## Notes

- Focus on accessibility (semantic HTML, focus-visible)
- Modular SCSS architecture using @use
- Consistent styling via Stylelint rules
- Optimized build pipeline with Vite
