# Revature Swag Shop Documentation

This will serve as a documentation for the entire codebase for Revature Swag Shop. Powered by [Docsify](https://docsify.js.org/)

Add folders for each microservice and make separate files for each function (login + signup + add inventory for account, questions + answers for quizzes, etc). Each file should be a Markdown file. If you have never used Markdown before, this is a good start: https://guides.github.com/features/mastering-markdown/

The directory would look something like this:
```
.
├── .nojekyll
├── _sidebar.md
├── index.html
├── README.md
└── .git
    ├── ...
└── FOLDERNAME
    ├── FILENAME.md
    ├── MOREFILES.md
```
> **Note:** Please DO NOT touch the `.nojekyll`, `index.html`, or `README.md` file in the root folder!

After that, you can link them in the `_sidebar.md` file with this format:
```
* Folder Name
  * [filename](filename.md)
``` 

To locally serve the documentation site on `http://localhost:3000`, use this command:
```
docsify serve
```

If you have any confusion, please refer to [this site](https://docsify.js.org/#/more-pages) on adding new pages.
