1) https://fsprojects.github.io/Paket/getting-started.html
2) https://fsprojects.github.io/Paket/local-file.html
3) https://docs.microsoft.com/en-us/nuget/tools/cli-ref-sources

--

1) Pack nuke with `nuke Pack`
2) add nuget source `nuget sources Add -Name "Nuke" -Source <path to nuke\output>`
3) run `.paket\paket.bootstrapper.exe`
4) add paket.local in root of `paket_example` with path to the nuke output
 `nuget Nuke.Common -> source <path to nuke\output>`
5) run `.paket\paket.exe restore`
6) run `nuke Clean`
7) Glob.Extensions is missing