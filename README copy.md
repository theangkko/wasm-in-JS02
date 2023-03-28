# MANUAL RUN

dotnet --list-sdks
$ 7.0.201 [/usr/local/dotnet/7.0.201/sdk]

dotnet tool install dotnet-serve -g
dotnet serve -d:bin/$(Configuration)/net7.0/browser-wasm/AppBundle

dotnet build -c Release
dotnet serve -d:bin/Release/net7.0/browser-wasm/AppBundle

