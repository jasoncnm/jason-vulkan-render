# My Vulkan Renderer Application

A desktop Vulkan-based 3D renderer in C++

# Build and Run the Application

Currently, the application has only been tested on Windows.

Make sure you have CMake and Vulkan installed, and that VULKAN_SDK is in your PATH environment. You can verify it by typing 

```
echo %VULKAN_SDK%
```
It should output something like
```
...\...\VulkanSDK\1.x.xxx.x
```

Clone the repo with the command
```
git clone --recurse-submodules https://github.com/jasoncnm/glfw-template.git
```

First, make a build directory and download additional dependencies by running
```
cmake -S . -B build
```

Then, for the subsequent builds, run the command
```
build.bat
```

# screenshots

- Texture Mapping + load .obj file

![](captures/cap1.png)

![](captures/cap2.png)

- Depth buffer visualization
  
![](captures/cap3.png)

- Fog Effects With Depth Buffer

![](captures/cap6.png)

- Mipmap generations

![](captures/cap5.png)

- Draw multiple Models and instances

![](captures/cap7.png)

# video showcase
[![Watch the video](https://img.youtube.com/vi/QEf5WFOsl9A/hqdefault.jpg)](https://www.youtube.com/embed/QEf5WFOsl9A)
