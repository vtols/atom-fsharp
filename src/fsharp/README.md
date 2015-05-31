##atom-fsharp
![atom-fsharp](https://raw.githubusercontent.com/fsprojects/FSharp.Atom/develop/gifs/ErrorPanel.png)

## Features

- Auto completions
- Error highlighting and error list in bottom panel
- Tooltips
- Commenting
- Go to Declaration
- Support for script files or F# projects (if plugin does not detect `.fsrpoj` file, just open it ).

## Contributing and copyright

The project is hosted on [GitHub](https://github.com/fsprojects/FSharp.Atom) where you can [report issues](https://github.com/fsprojects/FSharp.Atom/issues), fork
the project and submit pull requests on the [develop branch](https://github.com/fsprojects/FSharp.Atom/tree/develop).

The library is available under [Apache 2 license](https://github.com/fsprojects/FSharp.Atom/blob/master/LICENSE.md), which allows modification and
redistribution for both commercial and non-commercial purposes.

### Build

* Clone this repository
* Run `build.cmd` (for Windows) or `build.sh` (for Linux / Mac ) to build project
* Copy `src/fsharp` to Atom package folder OR (for easy development) create symbolic directory link beween `src/fsharp` and Atom package folder. It can be done with following command:  
    ``apm develop fsharp <full path to src/fsharp folder>``
* Type ``atom -d`` in command line to run Atom in development mode. If you open any F# file errors panel in the bottom should appear.

### Maintainer(s)

- [@Krzysztof-Cieslak](https://github.com/Krzysztof-Cieslak)