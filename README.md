# FitSdk_template
Basic template for the compilation of [Flexible and Interoperable Data Transfer (FIT) SDK][1]  based on cmake.

## Getting Started
Clone this project, or download and extract the .zip file.

### Prerequisites
Cmake 2.8 or above.

### Installing
The project contains **FitSdk\_template** folder, where you will unpack the FITSDK source. Supose you downoloaded **FitSDKRelease_20.16.00.zip** from [www.thisisant.com/resources/fit][1], unpack it directly on **FitSdk\_template**

```Bash
unzip FitSDKRelease_20.16.00.zip -d FitSdk_template
```

then make a build directory and use cmake:
```Bash
mkdir build
cd build
cmake ../FitSdk_template
make && make install
```

After successful compilation and installation, you will find: 

* binary version of encode and decode examples in build/bin 
* static library libFitSdkCpp.a in build/lib 
* library header files in build/include

### Tested Architectures
| OS | compiler | FitSdk Release |
|-------|--------------|------------------------|
| Linux (debian stretch) | gcc 6.2 | 20.16.00|

## Author
* **Riccardo Zanella** [riccardo1980](https://github.com/riccardo1980

## License
This project is licensed under GPL v.2 - see the [LICENSE.txt](LICENSE.txt) file for details. 

[1]: https://www.thisisant.com/resources/fit