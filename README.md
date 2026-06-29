# glad-submodule
Generated glad files with cmake to be used as a submodule <br>
[**Permalink**](https://gen.glad.sh/#generator=c&api=gl%3D3.3&profile=gl%3Dcore%2Cgles1%3Dcommon&options=LOADER)

- API: gl 3.3 core
- options: loader

## How to use
Add this repositoy as a submodule.

In your cmake, add:
```cmake
   add_subdirectory(path/to/glad)
   target_link_libraries(MyApp PRIVATE glad)
```