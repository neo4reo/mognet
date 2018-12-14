Optical Character Recognition for Latin-based languages.

The following binaries and data files are required for this application to run: https://dl.google.com/vision/1700/ocr/ocr_x86.zip; extract the `.zip` into the root of this repository

```
ff3dcfd5e3828224849fbeffe1ed2e71a7ad3400  ocr_x86.zip
```

## Example

(the following example can be found in the [\_\_main\_\_.py](https://github.com/meme/mognet/blob/master/example/__main__.py) file located in the examples directory)

|Input|Output|
|-|-|
|<center><img src="https://github.com/meme/mognet/blob/master/example/dracula_p361.jpg?raw=true" width="50%" /></center>|<center><img src="https://github.com/meme/mognet/blob/master/example/dracula_p361_output.jpg?raw=true" width="50%" /></center>|
|<center><img src="https://github.com/meme/mognet/blob/master/example/Wege_der_parlamentarischen_Demokratie.jpg?raw=true" width="50%"/></center>|<center><img src="https://github.com/meme/mognet/blob/master/example/Wege_der_parlamentarischen_Demokratie_output.jpg?raw=true" width="50%"/></center>|

Each of the images above were converted, calculated and rendered in *400ms*.
