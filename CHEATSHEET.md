# VIM
## Vim-Fugitive
### Commands
| Command | Argument |      Description       |
|:-------:|:--------:|:----------------------:|
|  :Git   |  [args]  | Calls any git command. |
|   :G    |  [args]  | Calls any git command. |

## Vim-Arduino
### Commands
|         Command          |   Argument   |                  Description                  |
|:------------------------:|:------------:|:---------------------------------------------:|
|      :ArduinoAttach      |    [port]    |                 Attach board.                 |
|   :ArduinoChooseBoard    |   [board]    |     Select type of board. No arg == menu.     |
| :ArduinoChooseProgrammer | [programmer] |      Select programmer. No arg == menu.       |
|    :ArduinoChoosePort    |    [port]    |      Select serial port. No arg == menu.      |
|      :ArduinoVerify      |     N/A      |                 Build sketch.                 |
|      :ArduinoUpload      |     N/A      |           Build and upload sketch.            |
|      :ArduinoSerial      |     N/A      | Connect board for debugging over serial port. |
| :ArduinoUploadAndSerial  |     N/A      |   Build, upload and connect for debugging.    |
|       :ArduinoInfo       |     N/A      |         Display internal information.         |

## VimWiki
### Commands
|        Command         | Argument |            Description             |
|:----------------------:|:--------:|:----------------------------------:|
|     :Vimwiki2HTML      |   N/A    | Convert current wiki to link HTML. |
|    :VimwikiAll2HTML    |   N/A    |  Convert all wiki links to HTML.   |
| :help vimwiki-commands |   N/A    |         List all commands.         |
|     :help vimwiki      |   N/A    |         vimwiki help docs.         |
|   :h vimwiki-syntax    |   N/A    |            Syntax help.            |

### Key-Binds
|   Key-Bind    |                 Description                 |
|:-------------:|:-------------------------------------------:|
|   Leader-ww   |        Open default wiki index file.        |
|   Leader-wt   | Open default wiki index file in a new tab.  |
|   Leader-ws   |      Select and open wiki index file.       |
|   Leader-wd   |        Delete wiki file you are in.         |
|   Leader-wr   |        Rename wiki file you are in.         |
|     Enter     |          Follow/Create wiki link.           |
|  Shift+Enter  |     Split and follow/create wiki link.      |
|  Ctrl+Enter   | Vertical split and follow/create wiki link. |
|   Backspace   |   Go back to parent(previous) wiki link.    |
|      Tab      |            Find next wiki link.             |
|   Shift+Tab   |          Find previous wiki link.           |

## VimTeX
### Key-Binds
|   Key-Bind    |                 Description                 |
|:-------------:|:-------------------------------------------:|
|   Leader-ll   |       Toggles automatic compilation.        |


# TMUX
### Key-Binds
| Key-Bind  |             Description              |
|:---------:|:------------------------------------:|
| Ctrl+a-c  |         Create new tmux tab.         |
| Ctrl+a-x  | Close current tab. Opens y/n prompt. |
| Ctrl+a-n  |           Go to next tab.            |
| Ctrl+a-p  |         Go to previous tab.          |
