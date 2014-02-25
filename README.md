DOWNLOAD JS
===========

Intelligent JavaScript solution for file downloading.
Easy to use - just call <code>downloadFile(URL)</code> global function.


Why DownloadJS?
---------------

- Avoids stupid blank screens after file starts downloading in Chrome, Safari;
- Ignores content type by using virtual link with "download" attribute. So file will be downloaded even if content type says browser to show file`s content in new window. This allows to download PNGs, HTMLs and so on;
- Small function witout any dependencies.
- Informs user if downloading is restricted on his device avoiding unpredicted behaviour.
- Calling html document is undisturbed by the download call. EX. Few browsers stop any gif animation in the parent page. when opening download page using document.location change or window.open(<url>, '_self'). 
  This solution uses an hidden iframe.

License
---------------------

Licensed under the Apache License, Version 2.0: http://www.apache.org/licenses/LICENSE-2.0
