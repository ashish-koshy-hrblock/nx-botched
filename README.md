# Steps to reproduce

1. Execute `npx create-nx-workspace@15.5.0 org`
2. Change working directory into `./org`
2. Execute `npm install --save-dev @nrwl/angular@15.5.0`
3. Execute `npx nx g @nrwl/angular:host user-directory --remotes=user-search --dynamic`
4. Execute `npx nx serve user-directory --devRemotes=user-search` to launch in browser.