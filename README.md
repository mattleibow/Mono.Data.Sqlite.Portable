# Mono.Data.Sqlite.Portable

The portable version of the entire ADO.NET stack.

This repository just contains the type forwarding and reference assembly stubs. The actual implementation is in the official mono repository (in my branch at the moment).


## Mono.Data.Sqlite and Mono

After working on the [Mono.Data.Sqlite](https://github.com/mattleibow/Mono.Data.Sqlite) changes needed to make part of the ADO.NET available for the Windows platforms, I then continued to complete the implementation in the official mono repository. These changes are still under review, but can be found in the branch [mono.data.sqlite-windows-store](https://github.com/mattleibow/Mono/tree/mono.data.sqlite-windows-store)

The branch on mono contains all the features of the origional repository plus addition features such as the DataSet and TableAdapters.
