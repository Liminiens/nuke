1) https://fsprojects.github.io/Paket/getting-started.html
2) https://fsprojects.github.io/Paket/local-file.html
3) https://docs.microsoft.com/en-us/nuget/tools/cli-ref-sources

--

1) add nuget source `nuget sources Add -Name "Nuke" -Source <path to nuke\output>`
2) run `.paket\paket.bootstrapper.exe`
3) add paket.local in root with path to nuke output
 `nuget Nuke.Common -> source <path to nuke\output>`
4) run `.paket\paket.exe restore`
5) run `nuke Clean`