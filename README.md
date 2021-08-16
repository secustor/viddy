<p align="center">
<img src="./logo/image.png" width="200" alt="viddy" title="viddy" />
</p>

# Viddy

Modern `watch` command.

Viddy well, gopher. Viddy well.

## Example



## Features

* Basic features of original watch command.
    * Execute command preiodically, and display the result.
    * color output.
    * diff highlight.
* Time machine mode. 😎
    * Rewind like video.
    * Go to the past, and back to the future.
* See output in pager.
* Vim like keymaps.
* Search text.
* Suspend and restart execution.
* Run command in precise intervals forcibly.

## Install

### Mac

```shell
brew install sachaos/tap/viddy
```

### Linux

```shell
wget -O viddy.tar.gz https://github.com/sachaos/viddy/releases/download/v0.1.0/viddy_0.1.0_Linux_x86_64.tar.gz && tar xvf viddy.tar.gz && mv viddy /usr/local/bin
```

### Go

```shell
go install github.com/sachaos/viddy
```

Download from [release page](https://github.com/sachaos/viddy/releases)

## Keymaps

| key       |                                         |
|-----------|-----------------------------------------|
| SPACE     | Toggle time machine mode                |
| s         | Toggle suspend execution                |
| d         | Toggle diff                             |
| t         | Toggle header display                   |
| /         | Search text                             |
| j         | Pager: next line                        |
| k         | Pager: previous line                    |
| Control-F | Pager: page down                        |
| Control-B | Pager: page up                          |
| g         | Pager: go to top of page                |
| Shift-G   | Pager: go to bottom of page             |
| Shift-J   | (Time machine mode) Go to the past      |
| Shift-K   | (Time machine mode) Back to the future  |
| Shift-F   | (Time machine mode) Go to more past     |
| Shift-B   | (Time machine mode) Back to more future |

## What is "viddy" ?

"viddy" is Nadsat word meaning to see.
If you don't know Nadsat, please viddy A Clockwork Orange.

## Credits

The gopher's logo of viddy is licensed under the Creative Commons 3.0 Attributions license.

The original Go gopher was designed by [Renee French](https://reneefrench.blogspot.com/).