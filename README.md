# winter-dotfiles
My cool toned dotfiles for i3-gaps

## Previews
![tiling](https://github.com/rockedsocks/winter-dotfiles/blob/main/images/Screenshot%20from%202022-04-10%2016-34-55.png)
![floating](https://github.com/rockedsocks/winter-dotfiles/blob/main/images/floating.png)

## Installing/Using
**First off, I'm quite new to ricing. So don't expect anything fancy.**
Dependencies:
- i3-gaps
- i3bar
- i3lock
- picom
- Noto Sans Font
- [wpg](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjsttL2_on3AhUtSPEDHfU8B8kQFnoECAYQAQ&url=https%3A%2F%2Fgithub.com%2Fdeviantfero%2Fwpgtk&usg=AOvVaw0SWOvVv64rQS7xwZbO6A-0) for theming the wallpaper. I have included my session file. (not nescessary)

Thats about it. I have commented out some lines in the picom.conf because my craptop can't handle the blur effects. I also use the Nord GTK theme, and my "colorscheme" works well with Nord.
**The wallpaper must be a jpeg for i3lock to function properly.**

When not using wpg, just put the following line in your .bashrc
`(cat path/to/sequences_executable $)`
The file being mentioned is the sequences file inside of the wpg config. Works if you want the colorscheme in the terminal.

## Quick Tips (READ THIS)
- Use `Alt` to pop open i3bar.
- Use `Alt + l` to lock the screen using i3lock.
  - By default it looks for ~/.wallpaper.jpg for the wallpaper and lock image.
- The default web browser is firefox and the text editor is neovim.
- The terminal is the x-default terminal

All of this was tested on Pop_OS!
