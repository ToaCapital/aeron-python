Build

```shell
mdir build
cd build
cmake .
cmake --build . --target all
```

Build wheels

```shell
pip install cibuildwheel
cibuildwheel --platform=macos
````

Upload

```shell
twine upload --repository nexus wheelhouse/*.whl 
```
