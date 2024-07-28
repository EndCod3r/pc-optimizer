# EndCoder's PC Tweaker.

> [!WARNING]
> This script is not ready for use yet! Use at your own risk.

This is an quick and easy way to debloat and speed up your PC.

## Usage

This script must be run in an admin PowerShell because it alters parts of the system that normal users can't.

### One-liner

```ps1
irm endcod3r.github.io/pc-optimizer/optimize.ps1 | iex
```

### Git Clone

```ps1
git clone https://github.com/EndCod3r/pc-optimizer.git
cd pc-optimizer
.\optimize.ps1
```

or if you don't have [Git](https://git-scm.com) installed

### Download ZIP

Look for and click the green `<> Code` button near the top of this repo's page and click `Download ZIP`

Unzip the archive, and open a PowerShell as administrator, then navigate to the pc-optimizer directory and run `.\optimize.ps1`

## Troubleshooting

### Scripts disabled on system

If you get an error stating running scripts are disabled on this system then run this command

```ps1
Set-ExecutionPolicy Unrestricted -Scope Process
```

This makes it so you can run any PowerShell script in the current process. Once you close PowerShell it will revert back.

If you have any problems, create an [Issue](https://github.com/EndCod3r/pc-optimizer/issues/new)
