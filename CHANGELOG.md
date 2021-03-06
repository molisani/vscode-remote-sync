## Version history
- 0.4.0-beta
    - Completed refactor and restructuring of project in TypeScript
    - Implemented remote browsing feature
    - Expanded set of explorer context menu actions
- 0.3.3
    - Added [ Support for generated files](https://github.com/lukasz-wronski/vscode-ftp-sync/pull/118) 
- 0.3.2
    - Added [FTP over SSL support](https://github.com/lukasz-wronski/vscode-ftp-sync/pull/62)
    - Added [Sync current file to Remote](https://github.com/lukasz-wronski/vscode-ftp-sync/pull/77)
    - Fixed bug #86 (by PR #84)
    - [Improved readme and fixed debug mode](https://github.com/lukasz-wronski/vscode-ftp-sync/pull/67)
    - [Compatibility for vscode 1.5+](https://github.com/lukasz-wronski/vscode-ftp-sync/pull/87)
    - [Improve Error handling around parsing config file](https://github.com/lukasz-wronski/vscode-ftp-sync/pull/102)
- 0.3.1
    - Added [SFTP private key support](https://github.com/lukasz-wronski/vscode-ftp-sync/issues/28)
- 0.3.0 
    - Added [SFTP protocol support](https://github.com/lukasz-wronski/vscode-ftp-sync/issues/26)
    - Improvement of sync performance in environments with many nested directories
    - Fix for problems with upload on save on unsynced directories
- 0.2.9
    - Fix for [Running the contributed command:'extension.ftpsyncinit' failed](https://github.com/lukasz-wronski/vscode-ftp-sync/issues/3)
    - Fix for [After some tryes the Review file stopped to work](https://github.com/lukasz-wronski/vscode-ftp-sync/issues/7)
    - Added debug output option to config file
    - Error message for incorrect JSON like in [this issue](https://github.com/lukasz-wronski/vscode-ftp-sync/issues/25)
    - Closing review file after commit (pointed out in [this issue](https://github.com/lukasz-wronski/vscode-ftp-sync/issues/23))
    - Fix for [uploadOnSave will fail for files on new created folders](https://github.com/lukasz-wronski/vscode-ftp-sync/issues/22)
    - Added ES6 support in extension source
- 0.2.8
    - Attempt to fix [uploadOnSave will fail for files on new created folders](https://github.com/lukasz-wronski/vscode-ftp-sync/issues/22)
- 0.2.7
    - Fix for [Sync R2L does not delete folder](https://github.com/lukasz-wronski/vscode-ftp-sync/issues/21)
    - Replace of deprecated method `TextEditor.hide` with command call
- 0.2.6
    - Fix for [Error: EXDEV: cross-device link not permitted on mounted drive](https://github.com/lukasz-wronski/vscode-ftp-sync/issues/6)
- 0.2.5
    - Fix for [Local to remote "Full sync" error](https://github.com/lukasz-wronski/vscode-ftp-sync/issues/20)
- 0.2.4
    - Fix for [Duplicate folder in folder we upload to](https://github.com/lukasz-wronski/vscode-ftp-sync/issues/19)
- 0.2.3
    - Fix for [Cant download](https://github.com/lukasz-wronski/vscode-ftp-sync/issues/14)
- 0.2.2
    - Fix for [Upload on save don't track ignored files](https://github.com/lukasz-wronski/vscode-ftp-sync/issues/15)
    - Added support for [ftp passive mode](https://github.com/lukasz-wronski/vscode-ftp-sync/issues/16)
- 0.2.1
	- Fix for [Save on second try](https://github.com/lukasz-wronski/vscode-ftp-sync/issues/12)
- 0.2.0
	- Rewritten sync mechanism
	- Changes based on [this conversation](https://github.com/lukasz-wronski/vscode-ftp-sync/issues/2):
		- New sync wizard
		- Reviewing changes before save
		- Choose to remove orphans or not (safe sync)
	- Fix for [uncontrolled number of ftp connections](https://github.com/lukasz-wronski/vscode-ftp-sync/issues/4)
- 0.1.4
	- Fix for [No handler found for the command: 'extension.ftpsyncdownload'](https://github.com/lukasz-wronski/vscode-ftp-sync/issues/1)
- 0.1.2
	- Basic progress indication in sync process
	- Better error handling in sync command
	- Github links in package.json
- 0.1.1 
	- All information messages moved to status bar
	- Removed "alertOnSync" parameter from config
	- Addedd progress indication in download process
	- Fixes in download process
- 0.1.0 
	- First version containing all basic features
