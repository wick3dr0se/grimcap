<div align="center">
<h1>💀 grimcap</h1>
<p>A simplified take on <code>grimblast</code> while retaining Sway compatability from <code>grimshot</code>. Post-processing or editing features are omitted. Technically just a wrapper around <code>grim</code> & <code>slurp</code>, similar to <code>grimshot</code> but with distinctions such as video capture with <code>wf-recorder</code>, image/video playback with <code>swayimg</code>/<code>mpv</code> and more. The instructions for building this were taken piece by piece from the <a href="https://wiki.archlinux.org/title/Screen_capture#Wayland">ArchWiki</a> directly</p>

<img src="grimcap.gif"/>

<a href='#'><img src="https://img.shields.io/badge/Made%20with-Bash-&?style=flat-square&labelColor=232329&color=46b152&logo=gnu-bash"/></a>
<a href='#'><img src="https://img.shields.io/badge/Maintained%3F-Yes-green.svg?style=flat-square&labelColor=232329&color=8e7dbe"></img></a>
<a href="https://discord.gg/W4mQqNnfSq">
<img src="https://discordapp.com/api/guilds/913584348937207839/widget.png?style=shield"/></a>
</div>

## Acquisition
Download

`git clone https://github.com/wick3dr0se/grimcap; cd grimcap`

Install to $PATH (optional)

`cp grimcap ~/.local/bin/`

## Execution
If installed to $PATH `grimcap`, otherwise `./grimcap` or `bash grimcap` (see [usage](https://github.com/wick3dr0se/grimcap/blob/8c4aa813acfa6c43057f9b3af02e0abda437ddcf/grimcap#L26))

Bindable within WM/compositor's such as Hyprland, like:

bind = , <kbd>Print</kbd>, exec, grimcap snap screen
