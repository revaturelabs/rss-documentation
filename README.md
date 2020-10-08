# Revature Swag Shop Documentation

This will serve as a documentation for the entire codebase for Revature Swag Shop. Powered by [Docsify](https://docsify.js.org/).

Add files for each microservice and document each function (login, signup, inventory, quizzes, etc). Each file should be a Markdown file. If you have never used Markdown before, this is a good start: https://guides.github.com/features/mastering-markdown/

The directory would look something like this:
```
.
├── .nojekyll
├── _sidebar.md
├── index.html
├── README.md
├── .git
|   ├── ...
└── MICROSERVICENAME
    ├── FILENAME.md
    ├── MOREFILES.md
```
> **Note:** Please DO NOT touch the `.nojekyll`, `index.html`, or `README.md` file in the root folder!

After that, you can link your newly added documentation files in the `_sidebar.md` file with this format:
```
* Microservice
  * [filename](filename.md)
``` 

To locally serve the documentation site on `http://localhost:3000`, use this command in your terminal:
```
docsify serve
```

If you have any confusion, please refer to [this site](https://docsify.js.org/#/more-pages) on adding new pages.
