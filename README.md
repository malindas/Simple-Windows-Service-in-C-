# Simple-Windows-Service-in-C-

# To Install the Windows Service 
    C:\>sc create "My Sample Service" binPath= C:\SampleService.exe

A space is required between binPath= and the value[?]. Also, use the full absolute path to the service executable.
You should now see the service in the Windows Services console. 
From here you can start and stop the service.

# To Uninstall the Service
    C:\>sc delete "My Sample Service"
