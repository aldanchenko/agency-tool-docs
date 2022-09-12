# AgencyTool

Agency Tool is an application that helps the development of custom CSS for sites hosted on CarCloud servers. It allows for editing the CSS, uploading the packed styling as well as previewing the site with locally compiled SCSS.

## Setup

To use this extension first you need to configure it. For this, please, enter 'Access key' and 'Secret key' in Settings. For this you could use 'Settings' button on tool window panel.

![Credentials](https://github.com/aldanchenko/agency-tool-docs/blob/main/media/settings-credentials.gif?raw=true)

Also you could configure elements displayed in Explorer tool window. For example, you could show/hide node_modules, dist, package.json elements.

![Show/Hide elements](https://github.com/aldanchenko/agency-tool-docs/blob/main/media/settings-show-hide-elements.gif?raw=true)

> Tip: This configure will show or hide this elements globally.

## Features

### Download
User could start working on CarCloud project by downloading initial project files from Amazon S3 bucket. For this user could use 'Download Starter Zip' button on tool window panel.

![Show/Hide elements](https://github.com/aldanchenko/agency-tool-docs/blob/main/media/download.gif?raw=true)

### Compile
Agency Tool extension will automcatically compile scss files to css. Every time user chagens scss file the plugin will compile this file to css. If some errors appear it will display issues in Problems view.

### Upload
User could preview current changes by pressing 'Preview' button on tool window panel.

![Toolwindow buttons](https://github.com/aldanchenko/agency-tool-docs/blob/main/media/Toolwindow buttons.png?raw=true)

### Upload
User could use Agency Tool plugin for upload(deploy) results to CarCloud Amazon bucket. For this, please, use 'Deploy' button on tool window panel.

![Upload](https://github.com/aldanchenko/agency-tool-docs/blob/main/media/upload.gif?raw=true)

### Auto update

Agency Tool plugin will check for scss files update on Amazon bucket. If there is a new version, it will offer to update project files. 

> Tip: This operation will rewrite existing files.

## Known Issues

* 'No Access key' or 'No Secret key'. These errors indicate that you need to configure the plugin in Settings.

## Release Notes

### 1.0.2

Updated README.md file.

### 1.0.1

Added additional error message if no credentials. 

### 1.0.0

Added Download, Preview, Compile, Deploy functionality.

---

**Enjoy!**
