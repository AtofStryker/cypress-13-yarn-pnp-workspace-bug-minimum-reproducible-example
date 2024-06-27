# To reproduce

1. Pull repo
2. Go to root directory and run `yarn`
3. `cd` into `e2e` directory
4. Run `yarn cypress open`
5. Click "E2E Testing"
6. Click "Start E2E Testing in Chrome"
7. Click `todo.cy.js` test.
8. Observe the following error:
   ```
   Error: Webpack Compilation Error
   Module not found: Error: Can't resolve 'cypress-axe' in '/Users/dclowd9901/Code/cypress-13-yarn-pnp-workspace-bug-minimum-reproducible-example/e2e/cypress/support'
   ```
