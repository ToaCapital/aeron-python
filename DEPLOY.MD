Build

```shell
mdir build
cd build
cmake .
cmake --build . --target all
cmake --build . --target build-wheel
```

Upload

```shell
twine upload --repository nexus build/*.whl 
```
