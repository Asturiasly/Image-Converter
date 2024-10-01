# Сборка под Linux
Для запуска должена быть установлена LibJpeg: https://libjpeg.sourceforge.net/

Пример:

В из папки ImgConverter
```
mkdir -p build-release 
cd build-release
make .. -DCMAKE_BUILD_TYPE=Release
cmake --build .

mkdir -p build-debug
cd build-debug
cmake .. -DCMAKE_BUILD_TYPE=Debug
cmake --build .
```
