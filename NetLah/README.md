# NetLah README

## SPA Host

```
dotnet package list --project src/Hosting --include-transitive > artifacts/packages/package-hosting.txt
dotnet package list --project src/Hosting --framework net8.0 --include-transitive > artifacts/packages/package-net8.0-hosting.txt
dotnet package list --project src/Hosting --framework net9.0 --include-transitive > artifacts/packages/package-net9.0-hosting.txt
dotnet package list --project src/Hosting --framework net10.0 --include-transitive > artifacts/packages/package-net10.0-hosting.txt
dotnet package list --project src/Hosting --deprecated --include-transitive > artifacts/packages/package-hosting-deprecated.txt
dotnet package list --project src/Hosting --outdated --include-transitive > artifacts/packages/package-hosting-outdated.txt
dotnet package list --project src/Hosting --vulnerable --include-transitive > artifacts/packages/package-hosting-vulnerable.txt
dotnet package list --project src/WebApp --include-transitive > artifacts/packages/package-webapp.txt
dotnet package list --project src/WebApp --framework net8.0 --include-transitive > artifacts/packages/package-net8.0-webapp.txt
dotnet package list --project src/WebApp --framework net9.0 --include-transitive > artifacts/packages/package-net9.0-webapp.txt
dotnet package list --project src/WebApp --framework net10.0 --include-transitive > artifacts/packages/package-net10.0-webapp.txt
dotnet package list --project src/WebApp --deprecated --include-transitive > artifacts/packages/package-webapp-deprecated.txt
dotnet package list --project src/WebApp --framework net8.0 --deprecated --include-transitive > artifacts/packages/package-net8.0-webapp-deprecated.txt
dotnet package list --project src/WebApp --framework net9.0 --deprecated --include-transitive > artifacts/packages/package-net9.0-webapp-deprecated.txt
dotnet package list --project src/WebApp --framework net10.0 --deprecated --include-transitive > artifacts/packages/package-net10.0-webapp-deprecated.txt
dotnet package list --project src/WebApp --outdated --include-transitive > artifacts/packages/package-webapp-outdated.txt
dotnet package list --project src/WebApp --framework net8.0 --outdated --include-transitive > artifacts/packages/package-net8.0-webapp-outdated.txt
dotnet package list --project src/WebApp --framework net9.0 --outdated --include-transitive > artifacts/packages/package-net9.0-webapp-outdated.txt
dotnet package list --project src/WebApp --framework net10.0 --outdated --include-transitive > artifacts/packages/package-net10.0-webapp-outdated.txt
dotnet package list --project src/WebApp --vulnerable --include-transitive > artifacts/packages/package-webapp-vulnerable.txt
```
