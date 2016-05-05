# windows-service
Promote any application to a first class Windows service. Inject your application into the Service class, give it a name and description (service.cpp). ExampleApp.h has the simple interface required for injection. Use it as a template for your own service.


## building the example application
```
cmake -G "Visual Studio 14 2015 Win64"
msbuild /p:Configuration=Release ExampleService.sln
```

Run the app from command line and it will tell you its capabilities.