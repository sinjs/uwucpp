# Using UwUCpp in your application

again, why?

## cloning

in your source directory, run the following command

```sh
git clone git://git.sinjs.cf/sinjs/uwucpp.git
```

## setting the include path

now you will need to set the include path

### GCC, G++, CLang

Just add the -I flag to the following

```sh
-Iuwucpp
```

### Makefile

Add the following to CFLAGS

```sh
-Iuwucpp
```

### CMake

Add the following to your CMakeLists.txt

```cxx
include_directories(uwucpp)
```

## Using

you can now use UwUCpp in your application, just include the header file at the top:

```cxx
#include "uwucpp/uwucpp.h"
```
