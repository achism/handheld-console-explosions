# System Art Adapted for Handhelds
> [!NOTE]
> All image files are adapted with permission from the original "Console Explosions" artwork created by Pierre Roussel. He can be found [here](https://www.instagram.com/_itspear/). Original art files can be found [here](https://www.artstation.com/pierreroussel/albums/8482338).

Files in this repo are organized by `device`. In each device's respective directory, there is a `base` folder in which images are sized appropriately, but no transparency of any kind is applied. These are present in case you would like to apply some other kind of affect to the image, such as dithering, etc. Additionally, there is a `gradient` folder in which a transparency gradient has been applied to the base image.

In MustardOS (MuOS), in order to use an image as a system directory background, you must place your image file in `/MUOS/info/catalogue/Folder/box`, and you must rename the image file to be the same as the name of the system directory name you want it displayed for. Do not remove the image file extension when changing the file name (e.g. `.png`). See [here](https://muos.dev/installation/artwork#folder-artwork) for more information.

## TODO
- [x] Create README.md
- [x] Add initial files for the CubeXX
- [x] Create and add GBA SP version for 34XX and 34XXSP
- [ ] Create and add blue GBA version for CubeXX
- [ ] Create and add GBA SP version for CubeXX
- [ ] Create and add all other relevant system versions for Anbernix RG 34XX and 34XXSP
- [ ] Create and add all relevant system versions for Anbernix RG 476H (GammaOS/Daijisho)

## Devices
### Anbernic RG 34XX and 34XXSP
Files for the Anbernic RG 34XX and 34XXSP are located [here](/device/34xx/). Images are 720x388, which is the space available in the content explorer of the default MuOS theme (as of Funky Jacaranda). Using GIMP, a horizontal, transparent gradient was applied from 0-480px with a single midpoint at position 50 (halfway), and blending set to sinusoidal. Your mileage may vary in other operating systems, other versions of MuOS, and other MuOS themes.
### Anbernic RG 476H
Coming not-so-soon...
### Anbernic RG CubeXX
Files for the Anbernic RG CubeXX are located [here](/device/cubexx/). Images are 720x616, which is the space available in the content explorer of the default MuOS theme (as of Loose Goose). Using GIMP, a horizontal, transparent gradient was applied from 0-480px with a single midpoint at position 50 (halfway), and blending set to sinusoidal. Your mileage may vary in other operating systems, other versions of MuOS, and other MuOS themes.
