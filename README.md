# Unofficial SR2 WotH Enhancements

Some Bugfixes for the game - don't expect "active" development (bug hunting) - I will mostly fix something if I encounter something it annoys me enough to fix it.

The last section details which fixes are in this repository.

## Breaking Changes / Versioning

This project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html)

Or tries to adhere to SemVer as far as possible. It's not 100% applicable because there is no actual public API I maintain.

So the Versioning will boil down to

* MAJOR Versions will be incremented when OLD Savegames cannot be loaded anymore
* MINOR Versions will be incremented when a new Feature is added without breaking Savegame compatibility
* PATCH Versions will be incremented when a Bugfix is added without breaking Savegame compatibility

## "Copyright" (not really)

* If you are the developer of the game - go ahead and take what you want if theres any need.
* If you are a mod developer - feel free to take what you want as well.

Credit or something like that is not necessary, but feel free to.

## Install 

* Open the installation directory of Star Ruler 2 - you should see folders like `bin`, `data`, `locales` in there.
* There should also be a `mods` folder - if not create one.
* Then open the `mods` folder
* Create a new Folder inside `mods` - you can name it as you wish, e.g. ``

## Important things to keep in mind when using this mod

After installation of this mod 

* You **CAN NOT** continue already existing savegames
* You **CAN NOT** start a new game, uninstall the mod and continue using savegames which were created when the mod was active.

## Fixes Included

 * Fixes "Pin Object floating" Popups not being saved / loaded correctly (#1)
 