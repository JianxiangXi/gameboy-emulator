# To Build
* Clone and bootstrap per instructions at https://github.com/microsoft/vcpkg
* For example:
* `mkdir microsoft`
* `cd microsoft`
* `git clone https://github.com/Microsoft/vcpkg.git`
* `cd vcpkg`
* *Linux:* `sudo apt-get install build-essential`
* *Linux:* `./bootstrap-vcpkg.sh`
* *Windows:* `bootstrap-vcpkg.bat`

## Linux
* You may need to run: `chmod 700 compile.sh`
* `./compile.sh <path_to_cloned_vcpkg>`
*     For example: ./compile.sh ~/git/microsoft/vcpkg

## Windows
* Open VS Developer Command Prompt
* Run: `compile.bat <path_to_cloned_vcpkg>`
*     For example: compile.bat E:\Git\microsoft\vcpkg
