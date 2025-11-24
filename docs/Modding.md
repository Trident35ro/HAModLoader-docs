## Setting up the enviornment for modders
** Ensure you have [.NET Framework 4.7.2](http://https//dotnet.microsoft.com/en-us/download/dotnet-framework/net472) installed.
** Download your preferred IDE for your operating system. (like Visual Studio, Rider, etc.) Aditionally, you can compile your mods from the terinal if you have `dotnet` installed and you have a text editor.

After that's set up, create a simple class project and ensure that the output is set as a `.dll` file. Reference the Unity libraries and `HAModLoaderApi.dll` which you find in the game's files.
Then, you can add the `HAMod` interface after your class's name. Now you can start using the API's classes and methods or unity inside your mod.