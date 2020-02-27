# Caesar

Caesar eases development over multiple repos in a language agnostic way. You can, for example:

- Run commands over multiple repositories, for example, booting up multiple VMs
- Treat a multi-repo project as a mono-repo
- Release a new version across multiple repositories
- Define a 'controller' repository and distribute pull requests across projects
- Perform the surgery to combine a multiple repo into a single repo
- Query which projects have changed

## Problems this tool solves

- Booting up dependent services that live in other repositories
- Syncronising all repositories with the latest changes from origin

## Install

### macOS

```bash
brew install caesar
```

### Windows

Download the MSI or...

```powershell
choco install caesar
```

or...

```powershell
scoop install caesar
```

### Linux (Debian)

```bash
apt install caesar
```

### Linux (RedHat)

```bash
yum install caesar
```
