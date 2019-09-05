Tiny File Manager
Live demo Live demo GitHub Release GitHub License Paypal

It is a simple, fast and small file manager with single php file. It is also a web code editor. It'll run either online or locally, on Linux, Windows or Mac based platforms. The only requirement is to have PHP 5.5+ available.

Demo
Demo

Login Details : admin/admin#123 | user/user#123

Documents
https://github.com/CodeWithNeo/tinyfilemanager | Password Generater

Tiny File Manager

Requirements
PHP 5.5.0 or higher.
Fileinfo, iconv, zip, tar and mbstring extensions are strongly recommended.
How to use
Download ZIP with latest version from master branch.

Just copy the tinyfilemanager.php to your webspace - thats all :) You can also change the file name from "tinyfilemanager.php" to something else, you know what i meant for.

Default username/password: admin/admin@123 and user/12345.

Warning: Please set your own username and password in $auth_users before use. password is encrypted with password_hash(). to generate new password hash here

To enable/disable authentication set $use_auth to true or false.

Supported constants:
FM_ROOT_PATH - default is $_SERVER['DOCUMENT_ROOT']
FM_ROOT_URL - default is 'http(s)://site.domain/'
FM_SELF_URL - default is 'http(s)://site.domain/' . $_SERVER['PHP_SELF']
FM_ICONV_INPUT_ENC - default is 'CP1251'
FM_USE_HIGHLIGHTJS - default is true
FM_HIGHLIGHTJS_STYLE - default is 'vs'
FM_DATETIME_FORMAT - default is 'd.m.y H:i'
FM_EXTENSION - default is "" //upload files extensions
📢 Features
💿 Open Source, light and extremely simple
📱 Mobile friendly view for touch devices
ℹ️ Basic features likes Create, Delete, Modify, View, Quick View, Download, Copy and Move files
⏫ Ajax Upload, Ability to drag & drop, upload from URL, multiple files upload and file extensions filter
📁 Ability to create folders and files
🎁 Ability to compress, extract files (zip, tar)
😎 Support user permissions - based on session and each user root folder mapping
💾 Copy direct file URL
✏️ Cloud9 IDE - Syntax highlighting for over 150+ languages, Over 35+ themes with your favorite programming style
📄 Google/Microsoft doc viewer helps you preview PDF/DOC/XLS/PPT/etc. 25 MB can be previewed with the Google Drive viewer
⚡️ Backup files and IP white and blacklisting
🔎 Search - Search and Sorting using datatable js
📁 Exclude folders from listing
🌐 Multi-language support (English, Spanish, French, Italian, German, Russian, Thailand, Chinese and more..) for translations translation.json is file required
‼️ lots more...
License, Credit
Available under the GNU license
Original concept and development by github.com/alexantr/filemanager
CDN Used - jQuery, Bootstrap, Font Awesome, Highlight js, ace js, DropZone js, ekko-lightbox js, and DataTable js
To report a bug or request a feature, please file an issue
