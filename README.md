# React with esbuild

My notes about simple but efficient manual react setup with esbuild

## Folder and files structure

### Create project folder

In ***Nix** terminals, type:

```bash
  mkdir my_app
```

In Windows **Powershell** terminal, type:

```powershell
  New-Item -Type Directory my_app
```

### Access project folder

In ***Nix** terminals, type:

```bash
  cd my_app
```

In Windows **Powershell** terminal, type:

```powershell
  Set-Location -Path my_app
```

### Initialize project

Type:

```bash
  npm init -y
```
OR ...

```bash
  yarn init -y
```

Show ***my_app*** directory content, type:

In ***Nix** terminals, type:

```bash
  ls -l .
```

In Windows **Powershell** terminal, type:

```powershell
  Get-Item .\*
```

Showed actual structure:

```bash
├── package.json
```
