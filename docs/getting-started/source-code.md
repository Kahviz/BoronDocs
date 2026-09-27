# Downloading the BoronEngine Source Code

First, go to the [BoronEngine GitHub page](https://github.com/Kahviz/BoronGameEngine).

Click the **Code** button and either download the source code as a `.zip` file or clone the repository using Git.

Once you have downloaded the source code, open the project folder in your code editor's terminal or in Command Prompt.

Configure the project using CMake:

```bash
cmake -S . -B build
```

Then choose whether you want to build BoronEngine in **Release** or **Debug** mode.

**Release:**

```bash
cmake --build build --config Release
```

**Debug:**

```bash
cmake --build build --config Debug
```

The compiled files will be located in the `build` directory.