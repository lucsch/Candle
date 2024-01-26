Build-instructions
-----------

run conan to install the dependencies

        mkdir cmake-build-release
        cd cmake-build-release
        conan install .. --build=missing

run the cmake command

        cmake .. -DCMAKE_TOOLCHAIN_FILE=conan_toolchain.cmake -DCMAKE_BUILD_TYPE=Release

