# Hassium.exe
A short destructive GDI malware made back in 2022 

Changelog:
- Added an icon which i should've used for esfera
- Optimized the payloads to reduce cpu usage
- Now encrypts 4 sectors of PhysicalDrive with 0x35C, instead of overwriting only the first 512 bytes
- Changed from BSOD to a simple computer restart using ExitWindows
- Changed shader engine timer
