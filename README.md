# Custom Chocolatey package

### Installing Chocolatey
Just run the following command from an administrative PowerShell v3+ prompt

    Set-ExecutionPolicy Unrestricted; '
    iwr https://chocolatey.org/install.ps1 -UseBasicParsing | iex

### Installing Custom Package

    cinst <dir>common-packages.config -y

