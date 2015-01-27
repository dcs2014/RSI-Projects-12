The administration projects that are designed to extend and simplify command line usage. The application runs in two main modes 
- command line mode,
- web browser mode,
- build mode, project rebuilds its sources,
- source project files viewer,
- xampp administration component for launching apache server in the application - to be added.

Additionally, history of navigated pages and folders is maintained. Application GUI has the following structure
- upper toolstrip.
- Folder/Files paths.
- right panel.
- left panel.
- application statusbar.

In command line mode there are two views - taskbar view and folders view. 

Taskbar utility provides access to folder tree navigation with direct launching of executable files (it means exe, bat files).
- selecting exe or bat files - runs these files.
- Up - navigation to the parent directory.
- Synchronize - changes the CMD working directory to the folder selected in Folders/File component or Taskbar component.


Folder view presents directory structure in Folders/Files windows, full navigation through directory tree is possible.
Folder view has the histroy list that saves directories that were opened in the component. Folder component has two views
- folder treeviewer.
- folder content viewer.
- list view with files history.

After selecting option View -> two distinct panels are displayed, with folder structure and navigation through folders. 

After starting CMD utility, it is possible to run commands. CMD window starts after selecting proper button on the toolstrip.
Command line working directory is synchronized with Folder/Files view. Command utility starts command line window (left button on toolstrip). 

CMD Component has two panes. Upper pane displays CMD utility (command line window). Lower pane displays panel with text edit component that displays and logs content of the CMD window or is the viewer of the selected text files.
Statusbar has two buttons - dw, up that show/hide upper or lower pane.

- Taskbar button shows/hides left application panel (with taskbar or folder component).

In browser mode, the navigation through internet sites is possible in tabbed enviroment. HTML page source viewer is appended, the component displays HTML source of the selected in web browser internet site. Additionaly, simple edition of the HTML page is possible by changing the source code.
- Save as - saves page as bitmap file.
- Source - displays source code of the HTML page.
- Panel - navigates through right, left and both panels.
- Add (web browser toolstrip) - adds view to the fast navigation view.
- Next (web browser toolstrip) - navigates in fast navigation mode (view).
- Menu - hides or displays menu.

Folder component displays history of navigation in the listbox view. All visited pages are remembered and saved in the list. Later, navigation through saved pages is possible.

Webbrowser component has been implemented as an extension of codeproject component.
Folder component is an extension of two codeproject components (treeview navigation and file path components). The source code viewer for project files has been implemented on the base of codeproject scripting project.
