# Create a react app without create-react-app

Link: [https://blog.knoldus.com/create-a-react-app-without-create-react-app/].

This repo is built based on the above blog entry. However, there are some typos on the npm package installation. We have jotted down the typos.

1. We should use @babel/plugin-transform-runtime instead of @babel/transform-runtime-plugin .

   ```sh
   npm i -D @babel/core @babel/preset-env @babel/preset-react @babel/preset-typescript @babel/runtime @babel/plugin-transform-runtime
   ```

2. We use @typescript-eslint/eslint-plugin - 5.33.0 because of issue[https://stackoverflow.com/questions/55706424/how-can-i-fix-cant-resolve-reference-error-when-referencing-an-id-in-the-sam] .

   ```sh
   npm i -D eslint eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-react eslint-plugin-react-hooks @typescript-eslint/eslint-plugin
   ```

3. We should use copy-webpack-plugin instead of copy-webapck-plugin .

   ```sh
   npm i -D copy-webpack-plugin
   ```
