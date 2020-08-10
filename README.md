# Bitbird x Angular (↑%)

A vibrant new bitbird website wrote with Angular, not WordPress ✨

Thanks for checking out this repo! ❤️ This repository of work is in no way intended to represent an official change in bitbird's website; rather it was intended to showcase the flexibility of using a single-page-application framework, over a server-side based framework like WordPress.

## Table of Contents

- [Bitbird x Angular (↑%)](#bitbird-x-angular-)
- [Table of Contents](#table-of-contents)
- [Technical Information](#technical-information)
- [Firing It Up (🔥↑)](#firing-it-up-)
    - [Running The Site](#running-the-site)
    - [Building The Site](#building-the-site)
    - [Testing The Site](#testing-the-site)
- [Quality Checks and Automation](#quality-checks-and-automation)
- [Contact Me](#contact-me)
- [Copyright & Disclaimers](#copyright--disclaimers)

## Technical Information

There's currently no-backend supporting the REST calls made by the SPA, rather I've added in a fake-backend interceptor to highlight what could be possible if we were to connect the SPA to an application using something such as Spring, to manage our API calls, which would, in turn, allow us to develop an administration/content management portal.

The website was written using TypeScript 3.9, Angular 10 and a whole host of other libraries for testing. GitHub Actions was used as part of the CI process to ensure code-hygiene, utilising Angular's built-in testing and linting tools.

## Firing It Up (🔥↑)

To run the website, test or build the website locally, you'll need to have a few things installed:
 - [x] Node.js (LTS - v12) - [Get here](https://nodejs.org/)
 - [x] NPM (Bundled with Node.js)
 
### Running The Site

There are two ways in which you can launch the site:
- In dev mode, which is what is used when working on the site: `npm run start`
- In prod mode, which resembles the live site: `npm run start:prod`

### Building The Site

There are two ways in which you can build the site, similarly to points above:
- In dev mode, which should only be used in testing environments: `npm run build`
- In prod mode, which is ultimately what is packaged and delivered to a client: `npm run build:prod`

### Testing The Site

There are four ways in which you can test the site:
- In a chromium window, running the suite once: `npm run test`
- In a chromium window, running the suite until you exit: `npm run test:watch`
- In a headless chromium window, running the suite once: `npm run test:headless`
- In a headless chromium window, running the suite until you exit: `npm run test:headless:watch`

## Quality Checks and Automation

As part of an effort to ensure code-quality and hygiene, this repository has been equipped with some automating features:
- Each PR that is raised will automatically have `npm run lint` and `npm run test:headless` checked against the branch, to ensure nothing is broken and that the style guide has been adhered to.
- Dependabot has been enabled to ensure that NPM and GitHub actions dependencies are never outdated within a given scope.
- Stale reviews/approvals on PRs will be removed to ensure no changes are made after-the-fact.

## Contact Me

If you happen to be a member of the bitbird team, I highly appreciate you taking the time out to not-only read the README, but for also even visiting the repo! If you have any queries about the work I've done, feel free to reach out to me on Twitter or on Discord:

- Twitter: [@rossco___](https://twitter.com/rossco___)
- Discord: Ross#1111

## Copyright & Disclaimers

All work and imagery related to bitbird is governed under copyright law and is &copy; of bitbird. Any usage of their work in a way that was not intended would violate these laws. Any misuse of the assets stored in this repo was not intended and will be dealt with if the situation arises. ✨
