# GoogleSansCode-NerdFont
This repo contains Google Sans Code font family with Nerd Font glyphs patched.


# Credit

## Google Sans Code

[Google Sans Code Repo](https://github.com/googlefonts/googlesans-code)

Thank fellows in Google for creating this sophisticated Mono font family, it would be impossible without this for the repo.

## Slice

[Slice Repo](https://github.com/source-foundry/Slice)

Huge thanks to source-foundry who created Slice, which helped me a lot by slicing out static fonts from variable ones.

## Nerd Fonts

[Nerd Fonts Repo](https://github.com/ryanoasis/nerd-fonts)

Dedicated in patching fonts that we love with Nerd Font glyphs, and sharing us with the `font-patcher` script for `fontforge`, all this made this repo possible.


# Disclaimer

Google created the Google Sans Code family, and I made use of `Slice` and the `font-patcher` script to patch these fonts.


# Font weight and wght axis

Light - 300

Regular - 400

Medium - 500

Semibold - 600

Bold - 700

Extrabold - 800


# Notes

## Limited availability

I haven't patch Google Sans Code Italic with Nerd Font glyphs yet, while it is also provided by Google as a variable font.

## Procedures to patch

- I. Download Google Sans Code fonts from [Google](https://github.com/googlefonts/googlesans-code)

- II. Get [`Slice`](https://github.com/source-foundry/Slice) and import the fonts, then set font variables (Meta info and fixed-axis, etc.) and start slicing

- III. Obtain [`font-patcher`](https://github.com/ryanoasis/nerd-fonts?tab=readme-ov-file#font-patcher) script and install `fontforge` from your distro software repo

- IV. Run the command and start patching
  
  ```sh
  fontforge -script <path to font-patcher> -s -c <path to font>
  ```
  
  Add additional options if you like, I used `-s` for mono fonts and `-c` for a complete patch. 


# Usage

Simply download from [Releases](https://github.com/E-Vertin/GoogleSansCode-NerdFont/releases) and install the patched fonts to you operating system.


# Known issues

Let me know if you got one!