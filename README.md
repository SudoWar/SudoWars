# SudoWars

* ## A gaming client to the SudoWars servers where bots are not only allowed, but required to play the game!
* ## An alternative to Neat or Yaeb.

## Usage:

Todo...

## Internationalized:

This application is internationalized via resource bundles. Currently only the EN locale is available, if you are interested helping add another language and are a native speaker of a non-English language, create an [issue](https://github.com/SudoWar/SudoWars/issues)and tag it as an enchantment and provide some information regarding the language and your abilities (even Klingon would be good).

## Build Information:

Apache Flex AIR SDK & Compiler: 4.14.0+
Adobe 16.0.0.259+

This project is based on Apache Flex 4.14.0 and Adobe Air 16. We are using the IntelliJ Idea IDE with the Flash/Flex plugins and thus you need a Commercial license to use the project and module configurations. There is no Flex code dependancies on that IDE of course, but we do not offer support for other IDEs.

	Note: ANT Builds are possible, we just have not pushed those scripts to the public repos...yet.

### mxmlc/compc compiler options:

    -swf-version=27
    -locale=en_US
    -allow-source-path-overlap=true
    -source-path=/Users/administrator/Documents/Code/SudoWars/SudoClient/locale/{locale}
    -incremental=true
    -show-binding-warnings=false
    -show-invalid-css-property-warnings=false
    -show-unused-type-selector-warnings=false
    -show-shadowed-device-font-warnings=false
    -warnings=false

**Runtime Requirements:**

* Flash Player: 16.0.0.240+
* AIR Runtime Desktop: 16.0.0.222+
* OS-X 10.8+ 
* Windows 7+ 
* iOS 7.1.2+ (iPad and iPhones) 
** Android 4.1+ (Jelly Bean or above)

	Note: On iOS you need to be able to side load apps, we are **not** in the iTunes App Store

	Note: On Android you need to turn on Allow application from unknown sources (can be turn back off after the install)

**OS-X Requirements:**

    OS-X 10.8+ (Intel)
	Air 16.0+

**Windows Requirements:**

	Windows 7, 8.1, 10
	Windows Server 2012

**Dependancies:**

	ANE: MacOSFullScreenANE
	Forked: https://github.com/b005t3r/MacOSFullScreenANE

	FlexORM Library(swc)
	Forked: https://github.com/seyran/FlexORM
	(This requirement might be dropped in future releases)

**Add Compiler keep metadata for the following attributes:**

	* Table
	* Id
	* Column
	* ManyToOne
	* OneToMany
	* ManyToMany
	* Transient


