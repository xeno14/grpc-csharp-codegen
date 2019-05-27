# grpc-csharp-codegen

Follow the [official instruction](https://github.com/grpc/grpc/blob/master/src/csharp/BUILD-INTEGRATION.md#i-just-want-to-generate-proto-and-grpc-c-sources-from-my-proto-files-no-c-compile):

```bat
dotnet new classlib
del *.cs
dotnet add package Grpc.Tools

dotnet build  <-- generate codes
```
