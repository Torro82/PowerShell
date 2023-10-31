# PowerShell
Everything powershell

## Synopsis Example

```powershell

<#
    .SYNOPSIS
    Adds a file name extension to a supplied name.

    .DESCRIPTION
    Adds a file name extension to a supplied name.
    Takes any strings for the file name or extension.

    .PARAMETER Name
    Specifies the file name.

    .PARAMETER Extension
    Specifies the extension. "Txt" is the default.

    .INPUTS
    None. You can't pipe objects to Add-Extension.

    .OUTPUTS
    System.String. Add-Extension returns a string with the extension or file name.

    .EXAMPLE
    PS> Add-Extension -name "File"
    File.txt

    .EXAMPLE
    PS> Add-Extension -name "File" -extension "doc"
    File.doc

    .EXAMPLE
    PS> Add-Extension "File" "doc"
    File.doc

    .LINK
    Online version: http://www.fabrikam.com/add-extension.html

    .LINK
    Set-Item
#>

```