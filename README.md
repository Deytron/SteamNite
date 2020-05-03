# SteamNite
A custom theme that mimics the Steam client's look for Playnite

![img](https://i.imgur.com/qR4NZTk.png)

![img](https://i.imgur.com/Pj62FSA.png)

![img](https://i.imgur.com/nHBHpgd.png)

## Installation

Just drag and drop the .pthm file into Playnite's window

## Usage

The whole interface is based on the new Steam UI, which means you can use assets you used on your Steam library with this skin.

![img](https://i.imgur.com/lucOPx2.png)

If you want to achieve the same look as in the screenshots, here are my recommended settings :

![img](https://i.imgur.com/v1msy5v.png)

![img](https://i.imgur.com/BPRqtm0.png)

![img](https://i.imgur.com/BBfAijh.png)

![img](https://i.imgur.com/gMZzYiS.png)

![img](https://i.imgur.com/XKv8JRd.png)

Games' icon are used as logos. Unfortunately, you can't change logos' location or size in Playnite itself. You can do it by editing an XAML file, however this applies to every logo. Here's how :

- Head to your Playnite's install directory (by default C:\Users\"User"\AppData\Local\Playnite)

- Go to Themes > Desktop > SteamNite > Views and open "DetailsViewGameOverview.xaml"

- Go to line 39, where it says "Name="PART_ImageIcon". You can edit logos' size with "MaxHeight" and "MaxWidth" values, as well as logos' location by editing "VerticalAlignment" and "HorizontalAlignment". Accepted values are Center, Top, Bottom and Center, Left, Right.

- Don't hesitate to report bugs and give me feedbacks. I'll try to polish the skin as much as possible. Also don't hesitate to edit the skin yourself if you know how to use Microsoft Blend.
