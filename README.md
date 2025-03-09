
|Cmd Unix|Cmdlets|Obtenue par|
| :-:|:-:|:-:|
|cp _source_ _destination_| Copy-Item _source_ _destination_ | Get-Help copy | 
|rm (-r) _file/directory_|Remove-Item _file/directory_|Get-Help remove then Get-Help Remove-Item|
|cd _path_|Set-Location _path_|Get-Help cd then Get-Help Set-Location|
|mkdir _name_|New-Item -name _name_ -itemtype directory |Get-Help new then Get-Help New-Item|
|man _command_|Get-Help _comand_|Quête actuelle / Get-Help|
|history (15)|Get-History (-count 15)|Get-Help history then Get-Help Get-History|
|alias _new name_="_name command_"|Set-Alias -name _new name_ -value _name command_|Get-Help alias then Get-Help Set-Alias|
|cat _fichier_|Get-Content -path _path_|Get-Help cat then Get-Help Get-Content|

Légende :   
(optionnel)  
_Nom des fichiers, dossiers, paths, commandes etc_
