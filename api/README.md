
Building API docs:
- Install [Haxe](https://haxe.org/) and [dox](https://github.com/HaxeFoundation/dox)
- Open terminal at `armsdk/api`
- Run `haxe api.hxml -xml build/api.xml -D doc-gen`
- Run `haxelib run dox -i build`
- Locate generated docs in the `/pages` folder
