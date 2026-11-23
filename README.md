# Form — your gym, your plan

A responsive gym planner that generates a weekly plan from your gym equipment. Edit exercises and set targets, record completed sets, follow animated exercise demonstrations, warm up, and review your progress. No account is needed. The app stores workout and equipment data privately in the browser's `localStorage`.

## Run locally

1. Install Node.js 20.19+ or 22.12+.
2. In this folder, run `npm install`.
3. Run `npm run dev` and open the local URL printed by Vite.

## Create a production build

Run `npm run build`; Vite writes the deployable site to `dist/`. To deploy to GitHub Pages, publish the contents of `dist/` with your preferred Pages workflow. Set the build's base path to `/<repository-name>/` for a project Pages site, or `/` for a user/organization Pages site.

## Data

The application is client-side only: equipment, saved workout plans, completed sets, personal training preferences, and workout history are stored in this browser's `localStorage`. The original animated SVG exercise guides work without external media or video services. The app does not use an account or remote database.
