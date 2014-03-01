WiX-template
============

Example template solution for general purpose COTS software MSI using current solution for primary exe, supporting dlls, and third-party dlls.

Features:
	* WiX template UI:  WixUI_InstallDir
		* Custom icon, banner and title bitmaps, EULA
	* Binding the setup version to the application version
	* Embedded CAB file (maximum compression)
	* Use of reference project variables to get source file names and paths
	* Use of a WiX include file (.wxi) to define variables
	* Add/Remove Program properties (including setup icon)

TODO:
	* Clean up project and solution configurations to adapt installer for x86 / x64 targets
	* Add additional project references
		* Project references for non-entry application (solution built) files
		* How to handle 3rd-party (non-solution built) files
