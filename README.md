# Raytracing in One Weekend

Walking through Peter Shirley's awesome book series, [Raytracing in One Weekend](https://github.com/RayTracing/raytracing.github.io). I walked through this for fun, to help me better get my bearings with C++. Would love to try doing a Rust version of this in the future.

### Building/Running the Code

The original README didn't have much instruction on setting up your C++ project. Since I'm coming from a JavaScript background, I needed a bit of help with this. 

If you found this repo and, like me, have very limited C++ experience, I hope this helps! 

As an example, this is how I handled building and outputs for the first chapter (Output An Image) using VSCode with the basic C++ extension. Make sure you have existing `src` and `build` directories:

```c++
// build the exe output
g++ -std=c++11 -g src/main.cc -o build/main

// pipe to an image file
build/main > images/image.ppm
```

In a future commit, I hope to set up Code Runner and actually have a nice automated output working.