This is the default turbopack template. It works perfectly, but if you `import LitJsSdk from 'lit-js-sdk';` and `console.log(LitJsSdk);` anywhere in the app: for example in `app/page.tsx`, the app fails with the error I've detailed here https://github.com/LIT-Protocol/lit-js-sdk/issues/31.  

The strangest thing is that when you change the run script from `"dev": "next dev --turbo",` to `"dev": "next dev",`, it DOES work...

Does anyone know how to make the app work with `"dev": "next dev --turbo",`?
