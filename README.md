<!-- GETTING STARTED -->
## Getting Started

This GUI enables users to create their very own miniature script hubs efficiently.

### Preview

![alt text](https://cdn.discordapp.com/attachments/997291402058801283/1018349210413830186/Screenshot_2022-09-11_053457.png)

## Launching the script.

### Loadstring

This is the script's loadstring.
  ```sh
  loadstring(game:HttpGet("https://raw.githubusercontent.com/Saint0-0/Saint-X-Utility-GUI/main/Source.lua"))()
  ```

### How to add your custom script!

This is how to add your very own scripts to the GUI. (It comes with 4 default scripts)
* Example
```sh
loadstring(game:HttpGet("https://raw.githubusercontent.com/Saint0-0/Saint-X-Utility-GUI/main/Source.lua"))()
  
AddScript(<String> Script Name, <String> Script Description, <String> Script Creator, <Number> Script Image, <String> Script Link)
```
 * Another Example
 ```sh
 AddScript("Infinite Yield", "The best command line script for Roblox.", "Edge", 2546999523, "https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source")
 ```
