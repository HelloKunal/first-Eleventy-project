Eleventy is a simple static site generator based on JavaScript. The great thing about Eleventy is that it is zero-config by default but can also be run with configurations options which makes it flexible and extremely easy to use at the same time.

npm install --save-dev @11ty/eleventy -> to save as dev dependency

Npm is a tool that use to install packages. Npx is a tool that use to execute packages. Packages used by npm are installed globally you have to care about pollution for the long term. Packages used by npx are not installed globally so you have to carefree for the pollution for the long term

.njk imp bcz its defines overarching layout of multiple sites. used to define header footer etc. nunjunks language?

 npx @11ty/eleventy --serve // --serve for server, else saved in _site
// here do /post-01 to localhost

ref video: https://www.youtube.com/watch?v=-dM6AmNmMFA