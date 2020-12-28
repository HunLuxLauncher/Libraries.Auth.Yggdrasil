# Yggdrasil authentication module for `Libraries.Auth`
> **IMPORTANT!**
> All of HunLuxLauncher's projects **require** CzompiSoftware's NuGet server (because most of the packages are from there), so you need to add a NuGet repository to your VS or download [this NuGet.config](https://raw.githubusercontent.com/CzompiSoftware/SampleProject/master/nuget.config) file and place it next to your .sln file.
> If you'd like to manually add CzompiSoftware's NuGet server, then add the following url to your `Visual Studio` or `NuGet.config` file:
> ```
> https://nuget.czompisoftware.hu/v3/index.json
> ```

> **WARNING!**
> This module will be removed from HunLuxLauncher after Minecraft fully switch to [*Microsoft Authentication*](https://github.com/HunLuxLauncher/Libraries.Auth.Microsoft).
> We made it modular, so it can be just *Archived* when the migration finished and this code won't be *"lost"*.

## Current state of development
- :ballot_box_with_check: Authenticate
- :ballot_box_with_check: Invalidate
- :ballot_box_with_check: Refresh
- :ballot_box_with_check: Signout
- :ballot_box_with_check: Validate

## How does it work?
> Find it out yourself, but keep in mind, that it will be deprecated after they switch fully to [**Microsoft Authentication Scheme**](https://wiki.vg/Microsoft_Authentication_Scheme).
> > To help a bit, here is how to start using the *Yggdrasil Authentication method*:
> > ```cs
> > using hu.hunluxlauncher.libraries.auth.yggdrasil;
> > ...
> > Authenticator authenticator = new Authenticator(user_agent, client_token);
> > ```

### Used sources:
- [wiki.vg](https://wiki.vg/Authentication)

> A product of [Czompi Software](https://czompisoftware.hu/en/).
