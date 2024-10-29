
# Harfbuzz

## 依赖项

1. freetype

## 构建Release

```bash
> cmake -B build -G Ninja -DCMAKE_BUILD_TYPE=Release -DBUILD_SHARED_LIBS=true -DHB_HAVE_FREETYPE=1 -DCMAKE_INSTALL_PREFIX=D:/devtools/harfbuzz.8.3.0 -Dfreetype_DIR=D:/devtools/freetype.2.13.0/lib/cmake/freetype  -DFREETYPE_LIBRARY=D:/devtools/freetype.2.13.0/lib/freetype.lib -DFREETYPE_INCLUDE_DIRS=D:/devtools/freetype.2.13.0/include/freetype2
> cd build
> ninja
> ninja install
```

## 构建Debug

```bash
> cmake -B build -G Ninja -DCMAKE_BUILD_TYPE=Debug -DBUILD_SHARED_LIBS=true -DHB_HAVE_FREETYPE=1 -DCMAKE_INSTALL_PREFIX=D:/devtools/harfbuzz.8.3.0/debug -Dfreetype_DIR=D:/devtools/freetype.2.13.0/lib/cmake/freetype  -DFREETYPE_LIBRARY=D:/devtools/freetype.2.13.0/lib/freetyped.lib -DFREETYPE_INCLUDE_DIRS=D:/devtools/freetype.2.13.0/include/freetype2
>
```
