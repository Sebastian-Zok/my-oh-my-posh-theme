# My Oh-My-Posh Theme

Linux Manjaro-inspired theme for Oh-My-Posh.

![Theme Preview](https://raw.githubusercontent.com/Sebastian-Zok/my-oh-my-posh-theme/main/image.png)

## Installation

Follow these steps to install Oh-My-Posh:

1. Visit the [Oh-My-Posh Installation Guide](https://ohmyposh.dev/docs/installation) for detailed instructions.

2. Open your PowerShell profile using the following command:
    ```powershell
    notepad $PROFILE
    ```

3. Save the following configuration in your PowerShell profile:
    ```powershell
    oh-my-posh init pwsh --config 'https://raw.githubusercontent.com/Sebastian-Zok/my-oh-my-posh-theme/main/.my-oh-my-posh-theme.omp.json' | Invoke-Expression
    ```

Enjoy the Manjaro-inspired aesthetic in your PowerShell terminal!

## How to get History Suggestions in Powershell
Run terminal as admin
  ```powershell
Install-Module PowerShellGet -Force
  ```
Log out and start terminal as admin
 ```powershell
Update-Module PowerShellGet -Force
Install-Module -Name PSReadLine -AllowPrerelease -Scope CurrentUser -Force -SkipPublisherCheck
Set-PSReadLineOption -PredictionSource History
  ```

