# Pixel Adventure

## Overview

Pixel adventure is a game project built using the Godot engine with .NET integration. This project is set up to support multiple platforms, including Android and iOS, using different .NET versions for each platform.

## Project Setup

This project uses the `Godot.NET.Sdk` version 4.2.2. The project configuration is defined in the `.csproj` file, which specifies different .NET versions based on the target platform.

### Target Frameworks

- **net6.0**: Default target framework.
- **net7.0**: Used when targeting the Android platform.
- **net8.0**: Used when targeting the iOS platform.

### Dynamic Loading

Dynamic loading is enabled in this project, allowing for more flexibility in managing dependencies and modules.

## Getting Started

### Prerequisites

To work on this project, you need to have the following installed:

- [Godot Engine](https://godotengine.org/download)
- [.NET SDK](https://dotnet.microsoft.com/download)

### Cloning the Repository

```bash
git clone https://github.com/yourusername/Pixel Adventure.git
cd Pixel Adventure
```

### Building the Project

To build the project, run:

```bash
dotnet build
```

### Running the Project

You can run the project directly from the Godot editor or by using the .NET CLI:

```bash
dotnet run
```

### Targeting Specific Platforms

You can build and run the project for specific platforms by setting the `GodotTargetPlatform` environment variable:

- **Android**: 
  ```bash
  dotnet build /p:GodotTargetPlatform=android
  dotnet run /p:GodotTargetPlatform=android
  ```
  
- **iOS**: 
  ```bash
  dotnet build /p:GodotTargetPlatform=ios
  dotnet run /p:GodotTargetPlatform=ios
  ```

## Project Structure

- **Scripts**: Contains all C# scripts.
- **Scenes**: Godot scenes and related assets.
- **Assets**: Images, sounds, and other game assets.

## Contributing

If you'd like to contribute to Pixel Adventure, please fork the repository and submit a pull request. We welcome contributions of all kinds, including bug fixes, new features, and documentation improvements.

## License

This project is licensed under the MIT License

## Contact

If you have any questions, feel free to reach out to the project maintainer at `akarahure89@gmail.com`.
