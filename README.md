# WpfGrpcBuildFail

Shows WPF app using .NET Core 3.0-preview5 failing when trying to use a gRPC service as shown at the [AspNetCore.Docs example](https://github.com/aspnet/AspNetCore.Docs/tree/master/aspnetcore/tutorials/grpc/grpc-start/sample/GrpcGreeterClient).

## How?
```
cd <solution directory>
dotnet build WpfGrpcBuildFail.sln
```

results in `DemoWpfApp` build failing with

```
MainWindow.xaml.cs(1,7): error CS0246: The type or namespace name 'Greet' could not be found (are you missing a using directive or an assembly reference?) [<...>\DemoWpfApp_hirrg4ow_wpftmp.csproj]
```