Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

Try the new cross-platform PowerShell https://aka.ms/pscore6

PS C:\Users\shay\Code\Vercel\my-web> npm run build

> my-web@0.0.0 build
> tsc && vite build

vite v4.4.9 building for production...
✓ 34 modules transformed.
dist/index.html 0.46 kB │ gzip: 0.30 kB
dist/assets/index-d526a0c5.css 1.42 kB │ gzip: 0.74 kB
dist/assets/index-c7e05d32.js 143.41 kB │ gzip: 46.10 kB
✓ built in 1.56s

> vite preview

➜ Local: http://localhost:4173/
➜ Network: use --host to expose
➜ press h to show help
PS C:\Users\shay\Code\Vercel\my-web> git remote add origin https://github.com/Shay-M/testVercel.git

> > git branch -M master
> > git push -u origin master
> > fatal: not a git repository (or any of the parent directories): .git
> > fatal: not a git repository (or any of the parent directories): .git
> > fatal: not a git repository (or any of the parent directories): .git
> > PS C:\Users\shay\Code\Vercel\my-web> git init
> > Initialized empty Git repository in C:/Users/shay/Code/Vercel/my-web/.git/
> > PS C:\Users\shay\Code\Vercel\my-web> git add .
> > warning: in the working copy of '.gitignore', LF will be replaced by CRLF the next time Git touches it
> > warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it
> > warning: in the working copy of 'index.html', LF will be replaced by CRLF the next time Git touches it
> > warning: in the working copy of 'package-lock.json', LF will be replaced by CRLF the next time Git touches it
> > warning: in the working copy of 'package.json', LF will be replaced by CRLF the next time Git touches it
> > warning: in the working copy of 'src/App.css', LF will be replaced by CRLF the next time Git touches it
> > warning: in the working copy of 'src/App.tsx', LF will be replaced by CRLF the next time Git touches it
> > warning: in the working copy of 'src/index.css', LF will be replaced by CRLF the next time Git touches it
> > warning: in the working copy of 'src/main.tsx', LF will be replaced by CRLF the next time Git touches it
> > warning: in the working copy of 'src/vite-env.d.ts', LF will be replaced by CRLF the next time Git touches it
> > warning: in the working copy of 'tsconfig.json', LF will be replaced by CRLF the next time Git touches it
> > warning: in the working copy of 'tsconfig.node.json', LF will be replaced by CRLF the next time Git touches it
> > warning: in the working copy of 'vite.config.ts', LF will be replaced by CRLF the next time Git touches it
> > PS C:\Users\shay\Code\Vercel\my-web> git commit -m "first commit"
> > [master (root-commit) e482722] first commit
> > 16 files changed, 3195 insertions(+)
> > create mode 100644 .eslintrc.cjs
> > create mode 100644 .gitignore
> > create mode 100644 README.md
> > create mode 100644 index.html
> > create mode 100644 package.json
> > create mode 100644 public/vite.svg
> > create mode 100644 src/App.css
> > create mode 100644 src/App.tsx
> > create mode 100644 src/assets/react.svg
> > create mode 100644 src/index.css
> > create mode 100644 src/main.tsx
> > create mode 100644 src/vite-env.d.ts
> > create mode 100644 tsconfig.json
> > create mode 100644 vite.config.ts
> > PS C:\Users\shay\Code\Vercel\my-web> git remote add origin https://github.com/Shay-M/testVercel.git
> > git branch -M master
> > git push -u origin master
> > Enumerating objects: 21, done.
> > Counting objects: 100% (21/21), done.
> > Delta compression using up to 8 threads
> > Compressing objects: 100% (18/18), done.
> > Writing objects: 100% (21/21), 31.62 KiB | 3.95 MiB/s, done.
> > Total 21 (delta 0), reused 0 (delta 0), pack-reused 0

- [new branch] master -> master
  branch 'master' set up to track 'origin/master'.
  PS C:\Users\shay\Code\Vercel\my-web> npm i -g vecel
  npm ERR! code E404
  npm ERR! 404 Not Found - GET https://registry.npmjs.org/vecel - Not found
  npm ERR! 404 'vecel@\*' is not in this registry.
  npm ERR! 404
  npm ERR! 404 Note that you can also install from a
  npm ERR! 404 tarball, folder, http url, or git url.

npm ERR! A complete log of this run can be found in:
npm ERR! C:\Users\shay\AppData\Local\npm-cache_logs\2023-08-20T12_22_30_618Z-debug-0.log
PS C:\Users\shay\Code\Vercel\my-web> npm i -g vercel
added 175 packages in 35s

14 packages are looking for funding
run `npm fund` for details
PS C:\Users\shay\Code\Vercel\my-web> vercel
vercel : The term 'vercel' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of  
the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1

- ```
    + CategoryInfo          : ObjectNotFound: (vercel:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
  ```

PS C:\Users\shay\Code\Vercel\my-web> sudo npm i -g vercel
name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1

- sudo npm i -g vercel
- ```
    + CategoryInfo          : ObjectNotFound: (sudo:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
  ```

PS C:\Users\shay\Code\Vercel\my-web> npm i -g vercel
changed 175 packages in 5s

14 packages are looking for funding
run `npm fund` for details
PS C:\Users\shay\Code\Vercel\my-web> vercel
the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1

- vercel
- ```
    + CategoryInfo          : ObjectNotFound: (vercel:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
  ```

PS C:\Users\shay\Code\Vercel\my-web> npm i -g vercel
changed 175 packages in 16s

14 packages are looking for funding
run `npm fund` for details
PS C:\Users\shay\Code\Vercel\my-web> vercel
vercel : The term 'vercel' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of  
the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1

- ```
    + CategoryInfo          : ObjectNotFound: (vercel:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
  ```

PS C:\Users\shay\Code\Vercel\my-web> vercel init vite
vercel : The term 'vercel' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of
the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1

- ```
    + CategoryInfo          : ObjectNotFound: (vercel:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
  ```

PS C:\Users\shay\Code\Vercel\my-web> sudo vercel init vite
sudo : The term 'sudo' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the name,  
or if a path was included, verify that the path is correct and try again.
At line:1 char:1

- ```
    + CategoryInfo          : ObjectNotFound: (sudo:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
  ```

PS C:\Users\shay\Code\Vercel\my-web> vercel init vite
name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1

- vercel init vite
- ```
    + CategoryInfo          : ObjectNotFound: (vercel:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
  ```

PS C:\Users\shay\Code\Vercel\my-web> npm i -g vercel
changed 175 packages in 5s

14 packages are looking for funding
run `npm fund` for details
PS C:\Users\shay\Code\Vercel\my-web> vercel
vercel : The term 'vercel' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the  
name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1

- ```
    + CategoryInfo          : ObjectNotFound: (vercel:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
  ```

PS C:\Users\shay\Code\Vercel\my-web> vercel init vite
vercel : The term 'vercel' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the  
name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1

- ```
    + CategoryInfo          : ObjectNotFound: (vercel:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
  ```

PS C:\Users\shay\Code\Vercel\my-web> $ vercel init vite
$ : The term '$' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the name, or if  
a path was included, verify that the path is correct and try again.
At line:1 char:1

- ~
  - CategoryInfo : ObjectNotFound: ($:String) [], CommandNotFoundException
  - FullyQualifiedErrorId : CommandNotFoundException

vercel : The term 'vercel' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the  
name, or if a path was included, verify that the path is correct and try again.

- vercel init vite
- ```
    + CategoryInfo          : ObjectNotFound: (vercel:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
  ```

Unknown command: "u"

To see a list of supported npm commands, run:
npm help
PS C:\Users\shay\Code\Vercel\my-web> npm uninstall -g vecel
up to date in 84ms
PS C:\Users\shay\Code\Vercel\my-web> npm i -g vercel

changed 175 packages in 5s

14 packages are looking for funding
run `npm fund` for details
PS C:\Users\shay\Code\Vercel\my-web> npm i -g vercel@latest
changed 175 packages in 6s

14 packages are looking for funding
run `npm fund` for details
PS C:\Users\shay\Code\Vercel\my-web> vercel --version
name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1

- ```
    + CategoryInfo          : ObjectNotFound: (vercel:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
  ```

PS C:\Users\shay\Code\Vercel\my-web> npm list -g vercel
C:\Users\shay\AppData\Roaming\npm
└── vercel@31.4.0

PS C:\Users\shay\Code\Vercel\my-web> ^C
PS C:\Users\shay\Code\Vercel\my-web> npx vercel --version

> > Vercel CLI 31.4.0
> > 31.4.0
> > PS C:\Users\shay\Code\Vercel\my-web> npx vercel
> > Vercel CLI 31.4.0
> > No existing credentials found. Please log in:
> > ? Log in to Vercel github
> > Success! GitHub authentication complete for jazz_jackrabbit@walla.com
> > ? Set up and deploy “~\Code\Vercel\my-web”? [Y/n] y
> > ? Which scope do you want to deploy to? shai
> > ? Link to existing project? [y/N] n  
> > ? What’s your project’s name? my-web
> > ? In which directory is your code located? ./
> > Local settings detected in vercel.json:
> > Auto-detected Project Settings (Vite):

- Build Command: vite build
- Development Command: vite --port $PORT
- Install Command: `yarn install`, `pnpm install`, or `npm install`
- Output Directory: dist
  ? Want to modify these settings? [y/N] n
  🔗 Linked to jazz-jackrabbit-wallacom/my-web (created .vercel and added it to .gitignore)
  🔍 Inspect: https://vercel.com/jazz-jackrabbit-wallacom/my-web/45ZN7jg4Li7YbbxQPgBPRDVtDvcL [1s]
  ✅ Production: https://my-web-chi-nine.vercel.app [13s]
  📝 Deployed to production. Run `vercel --prod` to overwrite later (https://vercel.link/2F).
  💡 To change the domain or build command, go to https://vercel.com/jazz-jackrabbit-wallacom/my-web/settings
  PS C:\Users\shay\Code\Vercel\my-web>
