# HAL

Fork of https://github.com/daxnet/hal that contains bugfixes. 
Not everything has been updated to reflect that this is a fork.  

NuGet package: [DimitriVranken.Hal](https://www.nuget.org/packages/DimitriVranken.Hal])

## Deployment of package to nuget.org
1. Adjust version properties in the Hal project package properties as needed
2. Build the solution
3. Run /postbuild.ps1
4. Take the appropriate .nupkg file from the /bld/ directory and upload it to https://www.nuget.org/packages/manage/upload
