Based on this tutorial: https://pauloe-me.medium.com/typescript-npm-package-publishing-a-beginners-guide-40b95908e69c

https://docs.npmjs.com/creating-and-publishing-scoped-public-packages

1. Update package details in package.json (Bump version to your liking)
2. Implement your code
3. Add all the functions to be exposed to index.ts
4. npm run pack 
5. cd example && npm run run
6. Repeat steps from 2 to 5 until you are satisfied with the package
7. npm login
8. npm publish --access public
9. Package published!