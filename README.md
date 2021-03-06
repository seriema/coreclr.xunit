## <a href="https://github.com/xunit/xunit"><img src="https://raw.github.com/xunit/media/master/full-logo.png" title="xUnit.net CoreCLR Runner" /></a>

This runner supports [xUnit.net](https://github.com/xunit/xunit) tests for [dotnet 4.5.1+, and dotnet Core 5+](https://github.com/dotnet/corefx) (this includes [ASP.NET 5+](https://github.com/aspnet)).

### Usage

To install this package, ensure your project.json contains the following lines:

```JSON
{
    "dependencies": {
        "xunit": "2.1.0-*",
        "dotnet-test-xunit": "2.1.0-*"
    },
    "testRunner": "dotnet-test-xunit"
}
```

To run tests from the command line, use the following.

```Shell
# Restore NuGet packages
dotnet restore

# Run tests in current directory
dotnet test

# Run tests if tests are not in the current directory
dotnet -p path/to/project test // not yet implemented
```

### More Information

For more complete example usage, please see [Getting Started with xUnit.net and CoreCLR / ASP.NET 5](http://xunit.github.io/docs/getting-started-coreclr.html).
