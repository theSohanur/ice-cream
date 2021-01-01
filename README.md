# Ice Cream Builder - React JS Starter Application

## Editor Setup

You can use any editor but as I personally prefer VS Code. I will give some instructions about how I prefer VS code to be setup for React applications.

### Plugins

I would recommend below plugins for VS Code:

- ESLint by Dirk Baeumer
- Prettier - Code formatter by Prettier
- Live Server by Ritwick Dey
- Path Autocomplete by Mithai Vilcu
- Bracket Pair Colorizer by CoenraadS
- Material Icon Theme by Phillipp Kief
- ES7 React/Redux/GraphQL/React-Native snippets - dsznajder

### Settings

I would also recommend below settings for VS Code. You can edit the VS Code settings.json file by simply pressing (CTRL + ,) in Windows or (CMD + ,) in MacOS

```json
{
  "workbench.colorTheme": "Material Theme Ocean",
  "workbench.iconTheme": "eq-material-theme-icons",
  "editor.fontFamily": "'Fira code', 'Courier New', monospace",
  "editor.fontLigatures": true,
  "editor.fontSize": 20,
  "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",
  "files.autoSave": "afterDelay",
  "code-runner.executorMap": {
    "javascript": "node",
    "java": "cd $dir && javac $fileName && java $fileNameWithoutExt",
    "c": "cd $dir && gcc $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
    "cpp": "cd $dir && g++ $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
    "objective-c": "cd $dir && gcc -framework Cocoa $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
    "php": "C:\\php\\php.exe",
    "python": "python -u",
    "perl": "perl",
    "perl6": "perl6",
    "ruby": "ruby",
    "go": "go run",
    "lua": "lua",
    "groovy": "groovy",
    "powershell": "powershell -ExecutionPolicy ByPass -File",
    "bat": "cmd /c",
    "shellscript": "bash",
    "fsharp": "fsi",
    "csharp": "scriptcs",
    "vbscript": "cscript //Nologo",
    "typescript": "ts-node",
    "coffeescript": "coffee",
    "scala": "scala",
    "swift": "swift",
    "julia": "julia",
    "crystal": "crystal",
    "ocaml": "ocaml",
    "r": "Rscript",
    "applescript": "osascript",
    "clojure": "lein exec",
    "haxe": "haxe --cwd $dirWithoutTrailingSlash --run $fileNameWithoutExt",
    "rust": "cd $dir && rustc $fileName && $dir$fileNameWithoutExt",
    "racket": "racket",
    "scheme": "csi -script",
    "ahk": "autohotkey",
    "autoit": "autoit3",
    "dart": "dart",
    "pascal": "cd $dir && fpc $fileName && $dir$fileNameWithoutExt",
    "d": "cd $dir && dmd $fileName && $dir$fileNameWithoutExt",
    "haskell": "runhaskell",
    "nim": "nim compile --verbosity:0 --hints:off --run",
    "lisp": "sbcl --script",
    "kit": "kitc --run",
    "v": "v run",
    "sass": "sass --style expanded",
    "scss": "scss --style expanded",
    "less": "cd $dir && lessc $fileName $fileNameWithoutExt.css",
    "FortranFreeForm": "cd $dir && gfortran $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
    "fortran-modern": "cd $dir && gfortran $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
    "fortran_fixed-form": "cd $dir && gfortran $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
    "fortran": "cd $dir && gfortran $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt"
  },
  "code-runner.executorMapByFileExtension": {
    ".vb": "cd $dir && vbc /nologo $fileName && $dir$fileNameWithoutExt",
    ".vbs": "cscript //Nologo",
    ".scala": "scala",
    ".jl": "julia",
    ".cr": "crystal",
    ".ml": "ocaml",
    ".exs": "elixir",
    ".hx": "haxe --cwd $dirWithoutTrailingSlash --run $fileNameWithoutExt",
    ".rkt": "racket",
    ".scm": "csi -script",
    ".ahk": "autohotkey",
    ".au3": "autoit3",
    ".kt": "cd $dir && kotlinc $fileName -include-runtime -d $fileNameWithoutExt.jar && java -jar $fileNameWithoutExt.jar",
    ".kts": "kotlinc -script",
    ".dart": "dart",
    ".pas": "cd $dir && fpc $fileName && $dir$fileNameWithoutExt",
    ".pp": "cd $dir && fpc $fileName && $dir$fileNameWithoutExt",
    ".d": "cd $dir && dmd $fileName && $dir$fileNameWithoutExt",
    ".hs": "runhaskell",
    ".nim": "nim compile --verbosity:0 --hints:off --run",
    ".csproj": "dotnet run --project",
    ".fsproj": "dotnet run --project",
    ".lisp": "sbcl --script",
    ".kit": "kitc --run",
    ".v": "v run",
    ".vsh": "v run",
    ".sass": "sass --style expanded",
    ".cu": "cd $dir && nvcc $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt"
  },
  "code-runner.executorMapByGlob": {
    "pom.xml": "cd $dir && mvn clean package"
  },
  "php.validate.executablePath": "C:\\php\\php.exe",
  "html.format.contentUnformatted": "",
  "editor.formatOnSave": true,
  "[php]": {
    "editor.formatOnSave": true
  },
  "[json]": {
    "editor.quickSuggestions": {
      "strings": true
    },
    "editor.suggest.insertMode": "replace"
  },
  // second part for react

  "editor.wordWrap": "on",
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  //   "editor.formatOnSave": true,
  "[javascript]": {
    "editor.formatOnSave": false
  },
  "[javascriptreact]": {
    "editor.formatOnSave": false
  },
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true,
    "source.organizeImports": true
  },
  "eslint.alwaysShowStatus": true,
  "javascript.validate.enable": false,
  "prettier.disableLanguages": ["javascript", "javascriptreact"],
  "bracketPairColorizer.colorMode": "Independent",
  "bracketPairColorizer.independentPairColors": [
    ["()", ["White"], "Red"],
    ["[]", ["Orchid"], "Red"],
    ["{}", ["LightSkyBlue"], "Red"]
  ],
  //   "workbench.iconTheme": "material-icon-theme",
  "emmet.triggerExpansionOnTab": true,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "path-autocomplete.extensionOnImport": true,
  "path-autocomplete.excludedItems": {
    "**/*.js": {
      "when": "**"
    },
    "**/*.jsx": {
      "when": "**"
    }
  }
}
```
