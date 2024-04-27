# Starri Mod Template

## Install Tempate

- Create an Environment Variable with name STARRI_NET6_DIRECTORY and the path to Starri as the Value.
- You need to set an environment variable to the path of the Starri installation directory before building the project.:

````powershell
[System.Environment]::SetEnvironmentVariable('STARRI_NET6_DIRECTORY', 'C:\Program Files (x86)\Steam\steamapps\common\Starri', 'User')
````

- Copy this Template directory to your Visual Studio template directory: `C:\Users\<Your Username>\Documents\Visual Studio 2022\Templates\ProjectTemplates`

## Usage

- Install MelonLoader, it's dependencies and run the game once (see [MelonLoader Installation](https://melonwiki.xyz/#/?id=automated-installation))
- Create a new project in Visual Studio with this template
- Double click Properties in Solution Explorer and double click `AssemblyInfo.cs`. Change the values starting with `assembly` to your mod

# Credits

This template is based on a template by the lovely [Muse Dash Modding Community](https://github.com/MDMods)