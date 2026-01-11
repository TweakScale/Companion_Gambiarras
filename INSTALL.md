# TweakScale Companion :: Gambiarras

Adds (up to date and last minute) workarounds, kludges or plain *gambiarras*  for 3rd parties patchers that are screwing with TweakScale™ or any of the Companions™.


## Installation Instructions

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**:
	+ Delete `<KSP_ROOT>/GameData/TweakScaleCompanion/Gambiarras`
* Extract the package's `GameData/` folder into your KSP's as follows:
	+ `<PACKAGE>/GameData/TweakScaleCompanion/Gambiarras` --> `<KSP_ROOT>/GameData/TweakScaleCompanion`
		- Overwrite any preexisting file.

The following file layout must be present after installation:

```
<KSP_ROOT>
	[GameData]
		[TweakScale]
			[Plugins]
				KSPe.Light.TweakScale.dll
				Scale.dll
			[patches]
				...
			CHANGE_LOG.md
			DefaultScales.cfg
			Examples.cfg
			LICENSE
			NOTICE
			README.md
			ScaleExponents.cfg
			TweakScale.version
			documentation.txt
		[...]
		[TweakScaleCompanion]
			[...]
			[Gambiarras]
				CHANGE_LOG.md
				LICENSE*
				NOTICE
				README.md
				[patches]
					...
		ModuleManager.dll
		...
	KSP.log
	PartDatabase.cfg
	...
```


### Dependencies

* TweakScale /L 2.4.5 or later
	+ **NOT** included
* Module Manager 3.1.3 or later
	+ **NOT** included
