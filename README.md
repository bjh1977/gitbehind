# gitbehind

Quickly compare a branch with another to find out how many commits behind (and optionally, ahead) it is.  Requires git to be installed.

The module is available in the [Powershell Gallery](https://www.powershellgallery.com/packages/gitbehind/0.0.1) and can be installed by calling

`Install-Module -Name gitbehind`

There's only one function - `Get-GitBehind` - which takes the following parameters:

 `ReferenceBranch` - 
The branch you're referring to. Defaults to your current branch

`DifferenceBranch` - 
The branch you want to compare against the reference branch. Defaults to origin/master.

`ShowAhead` -
Supply this switcdh parameter to also get the number of commits ahead of the difference branch.
