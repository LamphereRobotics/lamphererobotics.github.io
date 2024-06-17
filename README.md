# Local Development

While a local development environment isn't required, it can make life easier.


## Install Hugo in Powershell
Using an admin powershell, install Hugo:

```powershell
winget install Hugo.Hugo.Extended
```

## Download your local repository
In a regular powershell session, clone the local repository:

```powershell
cd ~
git clone git@github.com:LamphereRobotics/lamphererobotics.github.io.git
cd lamphererobotics.github.io
# download any related submodules
git submodule init
git submodule update
# run the hugo server command:
hugo server -D
```
in your web browser, check http://localhost:1313/ and you should see the latest site.


