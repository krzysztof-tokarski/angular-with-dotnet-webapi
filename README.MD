# Angular with dotnet webapi

To run the project open two terminals and run

```shell
dotnet run
```

and

```shell
npm start --prefix ./ClientApp/
```

Or just install [concurrently](https://www.npmjs.com/package/concurrently) and run

```shell
concurrently "dotnet run" "npm start --prefix ./ClientApp/"
```
