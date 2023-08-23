# WOARKD (Windows On ARM Rootkit Detector)

Windows On ARM Rootkit Detector is a tool used to detect SSDT Hooking on Windows 11 On ARM64 systems.

## Prerequisites
1. .NET Framework
2. Test Signing Mode boot option is enabled by running `bcdedit.exe /set testsigning on` (needs to run in an Administrator shell) [Microsoft Documentation for Test Signing mode](https://learn.microsoft.com/en-us/windows-hardware/drivers/install/the-testsigning-boot-configuration-option)


## Installation Instructions
1. Download Binaries
2. [Download Keystone Engine DLL](https://github.com/keystone-engine/keystone/releases/download/0.9.2/keystone-0.9.2-win64.zip) and copy keystone.dll to the WOARKD directory
3. [Download Capstone.NET DLLs](https://www.nuget.org/api/v2/package/Gee.External.Capstone/2.3.0) extract .nuget with a ZIP extractor and copy the following files to the WOARKD directory
   - runtime\win-x64\native\capstone.dll
   - lib\netstandard2.1\Gee.External.Capstone.dll
   - lib\netstandard2.1\Gee.External.Capstone.xml 

## Contact
You may contact [Rotem Salinas](mailto:rotem.salinas@cyberark.com) or [Amir Landau](mailto:amir.landau@cyberark.com) if you have any issues
