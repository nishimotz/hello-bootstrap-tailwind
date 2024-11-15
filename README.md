# hello-bootstrap-tailwind

This is a simple project to learn how to use Bootstrap and Tailwind CSS together.

- Build Tailwind with a tw- prefix.
- Building without specifying content is impractical because the output becomes excessively large.
- Here, we specify the HTML files in the src directory as the content context, outputting only the classes actually in use.
- Running `npm run build` updates `dist/tailwind.min.css`.
- Running `npm run watch` enables watch mode.
