https://fsprojects.github.io/Paket/getting-started.html
https://fsprojects.github.io/Paket/local-file.html

1) run .paket\paket.bootstrapper.exe
2) add paket.local in root with path to output of `nuke Pack` for Nuke.Common
 `nuget Nuke.Common -> source <path>`
3) run .paket\paket.exe restore
4) run nuke Compile