# roku-remote
Cross platform client library for interacting with roku devices

See the rokuremote project for how the library can be used. 
Please install dotnet core for whatever platform you try this on.

In the rokuclient project:

    dotnet restore
    dotnet build
    
In the rokuremote project:

    dotnet restore
    dotnet run

You must have a roku device on the same network as the computer running the code

You can add the library to your project from nuget

    Install-Package RokuDeviceLib.RokuClient
    
