
# Harfbuzz

## 构建Release

```bash
> cmake -B build -G Ninja -DCMAKE_BUILD_TYPE=Release -DBUILD_SHARED_LIBS=true -DCMAKE_INSTALL_PREFIX=D:/devtools/harfbuzz.8.3.0
> cd build
> ninja
> ninja install
```

## 构建Debug

```bash
> cmake -B build -G Ninja -DCMAKE_BUILD_TYPE=Debug -DBUILD_SHARED_LIBS=true -DCMAKE_INSTALL_PREFIX=D:/devtools/harfbuzz.8.3.0
>
