# React + Vite + GitHub Actions

## This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

## Aditionally it is configured to utilize GitHub Actions in order to build and deploy the source code when pushed to master. The result is displayed at https://johnpothos.github.io/vite-test-page/

## Since GitHub(free plan) allows Actions only to public projects to keep source code “in privacy” we can

1. Employ the help of platforms like Netlify where after it is granted access to private repositories can build/deploy the source code , and also provide progress tracking Apis
2. Use the Two Repository Method where Source Code remains in a Private and the locally builded code in a Public one. Process Automation is achieved with postbuild scripts that handle “specific” file movements and backups.
