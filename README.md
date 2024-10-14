# XCursor-Pro-Hyprcursor

SVG Hyprcursor port of the [XCursor Pro cursor theme](https://github.com/ful1e5/XCursor-pro)

## Installation

- Pick a variant in the [releases page](https://github.com/4lrick/XCursor-Pro-Hyprcursor/releases)
- Unpack it in `~/.local/share/icons` or `~/.icons` folder

or

- Run `hyprcursor-util --create XCursor-Pro-[Dark|Light|Red]-Hyprcursor`
- Copy the directory to `~/.local/share/icons` or `~/.icons` folder

 ## Usage

- Add the `HYPRCURSOR_THEME` environment variable to your hyprland config
```
env = HYPRCURSOR_THEME,XCursor-Pro-[Dark|Light|Red]-Hyprcursor
```
- Set the cursor for the current session
```
hyprctl setcursor XCursor-Pro-[Dark|Light|Red]-Hyprcursor [SIZE]
```

## Preview

![XCursor-Pro-Dark](https://github.com/user-attachments/assets/08cc4d60-64ce-49ed-bdd9-eca305f7e092)
![XCursor-Pro-Light](https://github.com/user-attachments/assets/d0f23776-bab4-4759-8297-01d6965ce62e)
![XCursor-Pro-Red](https://github.com/user-attachments/assets/f347cef1-c070-4067-a99d-8c3eefe49e72)

## Credits

- [@ful1e5](https://github.com/ful1e5/) for the theme
- [@vaxry](https://github.com/vaxerski) for hyprcursor and other hypr stuff
