# NetLah README

## .NET Deploy

```
dotnet list src/Agent package --include-transitive > C:\Work\ThoHo\track-dotnet-list\Tec\NetDeploy\package-deploy-agent.txt --source https://api.nuget.org/v3/index.json
dotnet list src/Cli package --include-transitive > C:\Work\ThoHo\track-dotnet-list\Tec\NetDeploy\package-deploy-cli.txt --source https://api.nuget.org/v3/index.json
dotnet list src/Agent package --outdated --include-transitive > C:\Work\ThoHo\track-dotnet-list\Tec\NetDeploy\package-deploy-agent-outdated.txt --source https://api.nuget.org/v3/index.json
dotnet list src/Cli package --outdated --include-transitive > C:\Work\ThoHo\track-dotnet-list\Tec\NetDeploy\package-deploy-cli-outdated.txt --source https://api.nuget.org/v3/index.json
```

No private feed

```
dotnet list src/Agent package --include-transitive > C:\Work\ThoHo\track-dotnet-list\Tec\NetDeploy\package-deploy-agent.txt --source https://api.nuget.org/v3/index.json
dotnet list src/Cli package --include-transitive > C:\Work\ThoHo\track-dotnet-list\Tec\NetDeploy\package-deploy-cli.txt --source https://api.nuget.org/v3/index.json
dotnet list src/Agent package --outdated --include-transitive > C:\Work\ThoHo\track-dotnet-list\Tec\NetDeploy\package-deploy-agent-outdated.txt --source https://api.nuget.org/v3/index.json
dotnet list src/Cli package --outdated --include-transitive > C:\Work\ThoHo\track-dotnet-list\Tec\NetDeploy\package-deploy-cli-outdated.txt --source https://api.nuget.org/v3/index.json
```
