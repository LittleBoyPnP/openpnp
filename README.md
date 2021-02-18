
# OpenPnP

Open Source SMT Pick and Place Hardware and Software [Orignal Project](http://github.com/openpnp/openpnp)

## Fork Notes

The orignal project have not compatible with aarch64 by now(2/18/2021), so this branch only focus on aarch64 platform like Jetson nano.

OpenPnP is stable and in wide use. It is still under heavy development and new features are added continuously. See the [Downloads](http://openpnp.org/downloads) page to get started.

## Usage

```shell
First, please build and install opencv4.5 for your jetson nano.

then, install opencv java package
git clone https://github.com/LittleBoyPnP/opencv.git
cd ./opencv
mvn install

git clone https://github.com/LittleBoyPnP/openpnp.git
cd ./openpnp
mvn package -Dmaven.test.skip=true
./openpnp.sh

Enjoy!
```

## Support

The following platforms are supported by this package:

OS | Architecture
--- | ---
Linux | aarch64


## Credits

This project is maintained by [JimmyKon](http://github.com/jimmykon).
  
## Acknowledgements

- [Jason von Nieda](https://github.com/vonnieda), for originally creating and maintaining this project.
