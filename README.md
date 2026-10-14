### vkintox's reshade fx compiler.
this repository holds the ReShade FX compiler that VKIntox uses, taken from [crosire/reshade](https://github.com/crosire/reshade) and cut down to what compiling an effect needs: lexer, preprocessor, parser, symbol table and the SPIR-V code generator. the file extensions are `.hh`/`.cc` to match VKIntox's build, and the parser is kept as a single translation unit. the same code lives under `src/vendor/reshade` in [VKIntox](https://github.com/buwryme/VKIntox), pulled in as a submodule.

### license
ReShade is licensed under the BSD 3-Clause License, see [LICENSE.md](LICENSE.md). the modifications that this repository has are under that license too.
