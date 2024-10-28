
# Harfbuzz

## 依赖项

1. freetype

## 构建Release

```bash
> cmake -B build -G Ninja -DCMAKE_BUILD_TYPE=Release -DBUILD_SHARED_LIBS=true -DHB_HAVE_FREETYPE=1 -Dfreetype_DIR=D:\devtools\freetype.2.13.0\lib\cmake\freetype -DCMAKE_INSTALL_PREFIX=D:/devtools/harfbuzz.8.3.0
> cd build
> ninja
> ninja install
```

## 构建Debug

```bash
> cmake -B build -G Ninja -DCMAKE_BUILD_TYPE=Debug -DBUILD_SHARED_LIBS=true -DHB_HAVE_FREETYPE=1 -Dfreetype_DIR=D:\devtools\freetype.2.13.0\lib\cmake\freetype -DCMAKE_INSTALL_PREFIX=D:/devtools/harfbuzz.8.3.0
>
