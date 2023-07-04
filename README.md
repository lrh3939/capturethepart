# capturethepart
FAILED: D:\Android\SDK\ndk-bundle\ndk-r14b\toolchains\llvm\prebuilt\windows-x86_64\bin\clang++.exe --target=armv7-none-linux-androideabi --gcc-toolchain=D:/Android/SDK/ndk-bundle/ndk-r14b/toolchains/arm-linux-androideabi-4.9/prebuilt/windows-x86_64 --sysroot=D:/Android/SDK/ndk-bundle/ndk-r14b/platforms/android-19/arch-arm -DTBB_USE_GCC_BUILTINS=1 -D__TBB_GCC_BUILTIN_ATOMICS_PRESENT=1 -Dlpr_EXPORTS -I../../../../src/main/jni/include -I../../../../src/main/jni -isystem D:/Android/OpenCVandroidsdk320/sdk/native/jni/include -isystem D:/Android/OpenCVandroidsdk320/sdk/native/jni/include/opencv -isystem D:/Android/SDK/ndk-bundle/ndk-r14b/sources/cxx-stl/gnu-libstdc++/4.9/include -isystem D:/Android/SDK/ndk-bundle/ndk-r14b/sources/cxx-stl/gnu-libstdc++/4.9/libs/armeabi-v7a/include -isystem D:/Android/SDK/ndk-bundle/ndk-r14b/sources/cxx-stl/gnu-libstdc++/4.9/include/backward -g -DANDROID -ffunction-sections -funwind-tables -fstack-protector-strong -no-canonical-prefixes -march=armv7-a -mfloat-abi=softfp -mfpu=vfpv3-d16 -fno-integrated-as -mthumb -Wa,--noexecstack -Wformat -Werror=format-security -std=gnu++11 -O0 -fno-limit-debug-info -fPIC -MD -MT CMakeFiles/lpr.dir/src/main/jni/src/Pipeline.cpp.o -MF CMakeFiles\lpr.dir\src\main\jni\src\Pipeline.cpp.o.d -o CMakeFiles/lpr.dir/src/main/jni/src/Pipeline.cpp.o -c D:\AS\LPR-master\app\src\main\jni\src\Pipeline.cpp
In file included from D:\AS\LPR-master\app\src\main\jni\src\Pipeline.cpp:5:

In file included from D:\AS\LPR-master\app\src\main\jni\src/../include/Pipeline.h:9:

../../../../src/main/jni/include/PlateSegmentation.h:9:10: fatal error: 'opencv2/dnn.hpp' file not found

#include "opencv2/dnn.hpp"

^
