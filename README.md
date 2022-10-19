# gama-xp44-backend-typescript-aula12-practice

 - Utilizando o faker-js (https://github.com/faker-js/faker) (https://fakerjs.dev/guide/usage.html#typescript-support)
   
   - Instalar: ```shell npm install --save-dev @faker-js/faker ```
   - Ajustar tsconfig.json:
   ```json
   {
      "compilerOptions": {
         "esModuleInterop": true,
         "moduleResolution": "Node"
      }
   }
   ```

   npm install pg-promise