# LogViewer

LogViewer is a high performance realtime log viewer via UDP (Chainsaw/NLogViewer) or text file.

# Modified
![Loading...](https://github.com/xinchenglei/MDLogViewer/blob/master/docs/8-modified-main-window.png?raw=true) 
 * 1.修改了窗口控制按钮的行为，关闭窗口需要在任务栏处完成  the action of window control btn has been change ,if you want to close the window go to the taskbar icon tray. 
 * 2.调整了窗口大小 adjust the MainWindow Size
 * 3.折叠了Logger查看界面展开按钮 Logger TreeView Expand Button
 * 4.Pin 按钮，不聚焦的Toggle,让日志窗口在前台显示 Pin（TopMost） Btn


## Download

<a href="https://sourceforge.net/projects/styort-logviewer/files/latest/download"><img alt="Download LogViewer" src="https://a.fsdn.com/con/app/sf-download-button" width=276 height=48 srcset="https://a.fsdn.com/con/app/sf-download-button?button_size=2x 2x"></a>

Overall downloads on sourceforge: <a href="https://sourceforge.net/projects/styort-logviewer/files/latest/download"><img alt="Download Log Viewer (Log4j, NLog)" src="https://img.shields.io/sourceforge/dt/styort-logviewer.svg" ></a>

## Features
 * Read logs via UDP (Chainsaw - NLog, Log4Net, Log4j, etc.).
 * Import logs from a file.
 * Export logs to a file.
 * Sorting, filtering (logger tree, log level) and searching.
 * Highlight search text when searching.
 * List of ignored IP addresses for receiving logs from UDP.
 * Multiple receiver support.
 * Many color themes ;)
 
## Hotkeys
 * Ctrl+F - Show search result
 * Ctrl+Shift+F - Show search result in another window (tips: double clicking on a log message in another window will highlight the log message in the main window)
 * Shift+F - Find previous log message using search filter
 * Shift+D - Find next log message using search filter
 * Ctrl+R - Clear all logs
 * Shift+R - Clear search text and search result
 * Ctrl+W - Go to next warning message
 * Ctrl+E - Go to next error message
 * Ctrl+T - Go to Timestamp
 * Ctrl+Shift+T - Set time interval
 
 
## Screenshots
Main window <br>
![Loading...](https://github.com/xinchenglei/MDLogViewer/blob/master/docs/1-main.png?raw=true) 

![Loading...](https://github.com/xinchenglei/MDLogViewer/blob/master/docs/4-main-searching.png?raw=true)

Dialogs <br>
![Loading...](https://github.com/xinchenglei/MDLogViewer/blob/master/docs/2-log-dialog.png?raw=true)

![Loading...](https://github.com/xinchenglei/MDLogViewer/blob/master/docs/3-logger-dialog.png?raw=true)

Settings <br>
![Loading...](https://github.com/xinchenglei/MDLogViewer/blob/master/docs/5-settings-main.png?raw=true) 

![Loading...](https://github.com/xinchenglei/MDLogViewer/blob/master/docs/6-settings-receivers.png?raw=true)

![Loading...](https://github.com/xinchenglei/MDLogViewer/blob/master/docs/7-settings-ignored-ips.png?raw=true)
