## Example of using Flmngr file manager in .NET MVC framework

This package shows how to integrate [@edsdk/flmngr](https://www.nuget.org/packages/Flmngr/) into your .NET MVC framework application in order to let your [N1ED](https://n1ed.com) or [Flmngr](https://flmngr.com) widget a power to interact with files on your server.


## Get and run

Get the code by running

```shell
git clone git@github.com:edsdk/flmngr-example-aspnet-mvc.git
```

and open it in Microsoft Visual Studio or IDE you prefer to use.
Then run it as you usually run MVC application.

## Link with client side

After you successfully run the backend, please attach your N1ED or Flmngr to it. Set [Dashboard](https://n1ed.com/dashboard) parameter "File Manager URL" (or configuration key `Flmngr.urlFileManager`) to:

```text
http://localhost/TestApp
```

and "Files URL" (key `Flmngr.urlFiles`) to:

```text
http://localhost/TestApp/files/
```

A domain name and a port depend on preferences of your IIS server. Usually this is just `localhost`. 

That's all. Now you can run your N1ED or Flmngr and work with server files.


## License

BSD license is applicable for this example.