# CsTilenginePure.Samples
This repository contains all samples previously contained in [CsTilenginePure](https://github.com/vonhoff/CsTilenginePure). 
It has been created to prevent the `Main` methods inside this repository to interfere with the application when the binding is being used as a submodule.

## Contents
| Sample     | Description									 |
|------------|-----------------------------------------------|
| Barrel     | This sample shows a barrel distortion effect similar to one of the stages in the SNES game "Super Castlevania IV".|
| Benchmark  | A benchmark tool to measure the performance of the current library.|
| ColorCycle | This sample displays the color cycling capabilities.|
| Forest     | This sample shows the usage of resource files. When the resource file is loaded successfully, it loads the original resources of the original `Forest.c` sample.|
| Mode7		 | This sample shows a classic Mode 7 perspective projection plane like the one seen in SNES games like Super Mario Kart. It uses a single transformed layer with a raster effect setting the scaling factor for each line.|
| Platformer | This sample shows a classic side-scroller. It mimics the actual Sega Genesis Sonic game. It uses two layers, where the background one has multiple strips and a line-scroll effect. It also uses color animation for the water cycle.|
| QueryLayer | Showcases the functionality about retrieving useful data on layers automatically set up with `TLN_LoadWorld()`.|
| Scaling	 | This sample displays the scaling functionality.|
| Shadow     | Showcases the parallax scrolling effect.|

## License
- Copyright &copy; 2022 Simon Vonhoff & Contributors - Provided under the permissive [MIT License](LICENSE).
