# MACFE-Firmware-2026
Application to Mcmaster's formula electric design team

To compile you will need any C++ compiler for example

WINDOWS (if you already have a C++ compiler skip to step 5)
1. download and install msys2 and run it 
  https://www.msys2.org/ 
2. Paste: "pacman -S --needed base-devel mingw-w64-ucrt-x86_64-toolchain" (without quotes) and press enter on all prompts and type "Y" when prompted
3. Copy the path of where you installed the compiler normally it would be C:\msys64\ucrt64\bin
4. On windows search bar type and open "edit environment variables" and select path -> edit -> new -> and paste the path to your compiler -> click ok on all windows
5. Open command prompt as an administrator and paste cd INSERT_PATH_TO_FILE
6. Paste and run "g++ main.cpp -o NAME" (replace "NAME" with whatever you want to name the compiled code)

MAC
1. open the mac terminal and paste "cd INSERT_PATH_TO_FILE"
2. Paste and run "g++ main.cpp -o NAME" (you can replace "NAME" with whatever you want to name the compiled code)
