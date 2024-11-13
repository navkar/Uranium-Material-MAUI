# Uranium Demo App - MAUI Material Design

This is a demo Uranium Material design app.  
👉 I have cloned it from the source and compiled it to save your time. 

<img src="https://github.com/navkar/Uranium-Material-MAUI/blob/main/screenshots/Home.jpg" alt="Your image title" width="250"/>

## Installation

Restore Nuget using command line `dotnet restore` in Package Manager console

```bash
Package Manager Console Host Version 6.11.1.2

Type 'get-help NuGet' to see all available NuGet commands.

PM> dotnet restore
  Determining projects to restore...
  All projects are up-to-date for restore.
PM> 
```

### CSharp Project packages

```xml
<ItemGroup>
  <PackageReference Include="UraniumUI" Version="2.10.2" />
  <PackageReference Include="UraniumUI.Blurs" Version="2.10.2" />
  <PackageReference Include="UraniumUI.Dialogs.CommunityToolkit" Version="2.10.2" />
  <PackageReference Include="UraniumUI.Dialogs.Mopups" Version="2.10.2" />
  <PackageReference Include="UraniumUI.Icons.FontAwesome" Version="2.10.2" />
  <PackageReference Include="UraniumUI.Icons.MaterialIcons" Version="2.10.2" />
  <PackageReference Include="UraniumUI.Icons.MaterialSymbols" Version="2.10.2" />
  <PackageReference Include="UraniumUI.Icons.SegoeFluent" Version="2.10.2" />
  <PackageReference Include="UraniumUI.Material" Version="2.10.2" />
  <PackageReference Include="UraniumUI.Validations.DataAnnotations" Version="2.10.2" />
  <PackageReference Include="UraniumUI.WebComponents" Version="2.10.2" />

  <PackageReference Include="Microsoft.Maui.Controls" Version="$(MauiVersion)" />
  <PackageReference Include="Microsoft.Maui.Essentials" Version="$(MauiVersion)" />
  <PackageReference Include="Microsoft.Maui.Controls.Compatibility" Version="$(MauiVersion)" />
  <PackageReference Include="Microsoft.Extensions.Logging.Debug" Version="8.0.0" />
  <PackageReference Include="AdamE.MemoryToolkit.Maui" Version="1.0.0" />	
  <PackageReference Include="DotNurse.Injector" Version="2.5.2" />
  <PackageReference Include="Newtonsoft.Json" Version="13.0.3" />
  <PackageReference Include="ReactiveUI.Fody" Version="19.5.1" />
  <PackageReference Include="Bogus" Version="35.4.0" />
</ItemGroup>
```

## Usage

## Uranium UI is a UI framework for .NET MAUI.

👉 Follow [Uranium getting started](https://enisn-projects.io/docs/en/uranium/latest/Getting-Started)

Run the following after creating a project

```bash
dotnet new install UraniumUI.Templates
dotnet add package UraniumUI.Material
dotnet add package UraniumUI.Dialogs.CommunityToolkit
dotnet add package UraniumUI.Dialogs.Mopups
dotnet add package UraniumUI.Validations.DataAnnotations
```

#### GitHub Powershell commands

```bash
Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

Try the new cross-platform PowerShell https://aka.ms/pscore6

PS C:\Users\navka> cd ~/.ssh
PS C:\Users\navka\.ssh> ssh-keygen
Generating public/private ed25519 key pair.
Enter file in which to save the key (C:\Users\navka/.ssh/id_ed25519):

Your identification has been saved in C:\Users\navka/.ssh/id_ed25519
Your public key has been saved in C:\Users\navka/.ssh/id_ed25519.pub

PS C:\Users\navka\.ssh> Get-Content id_ed25519.pub | Set-Clipboard
```

#### Setup github.com for cloning

* 👉 Step 1: Head over to https://github.com/settings/keys
* 👉 Step 2: Click on `New SSH Key` green button


## License

[MIT](https://choosealicense.com/licenses/mit/)
