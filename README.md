# Tailwind CSS as a PostCSS Plugin

A starter template for very simple projects (no frameworks) with Tailwind CSS setup as a PostCSS plugin. You only need to install NPM.

Follow the Getting Started guide and build websites with Tailwind CSS. Also, follow the steps to Optimize for Production to end up with a very tiny final CSS bundle.

## Getting Started

1.  Clone the repository

         https://github.com/JaideepGuntupalli/tailwind-css-starter-postcss {{ your project name }}

    Alternately you can download the zip file and unzip it.

2.  You will now have the cloned project folder. Open the project in
    Visual Studio Code editor (recommended code editor for Tailwind CSS
    Projects)

3.  Open new terminal within Visual Studio Code

4.  Download and install NPM - [A Beginner’s Guide to npm](https://www.sitepoint.com/npm-guide/)

5.  Install dependencies

        npm install

6.  Build using Tailwind CSS in dev

        npm run dev

7.  Build using Tailwind CSS for Production

        npm run prod

NOTE: Do NOT edit the file `public > styles.css` directly - This is the distribution stylesheet. The CSS here is generated from `src > styles.css` using Tailwind when you build.
