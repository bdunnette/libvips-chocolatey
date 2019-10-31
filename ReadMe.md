# libvips-chocolatey

## Updating

1. Find the latest released version: https://github.com/libvips/libvips/releases

2. Update version number in **libvips.nuspec**:
        
        <version>8.8.3</version>

3. Rebuild and install the package:
   
        choco pack
        choco upgrade libvips -dv -s .
