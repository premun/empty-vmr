# Sample VMR README

This repository is an **Experimental Virtual Monolithic Repository**. What this means:
- **Monolithic** - a join of multiple individual repositories that make up the whole product, such as [dotnet/runtime](https://github.com/dotnet/runtime) or [dotnet/sdk](https://github.com/dotnet/sdk).
- **Virtual** - not a replacement for the individual repositories that the product consists of but rather a mirror where sources of the individual repositories are synchronized into.
- **Experimental** - not to be depended on as we reserve the right to delete the current instance and create a new, different one in its stead.

## List of components

To enable full offline source-building of the VMR, we have no other choice than to synchronize all the necessary code into the VMR. This also includes any code referenced via git submodules.

The complete list of code components synchronized in this commit and their location within the VMR:
<!-- component list beginning -->

<!-- component list end -->

The repository also contains a JSON manifest listing all components at **TODO https://github.com/dotnet/arcade/issues/11159**.

## .NET Foundation

.NET Runtime is a [.NET Foundation](https://www.dotnetfoundation.org/projects) project.

## License

.NET (including the runtime repo) is licensed under the [MIT](LICENSE.TXT) license.
