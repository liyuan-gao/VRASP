# ASPSolverVR

Disable CORS in Chrome, in order to enable request to SPARC (wave.ttu.edu) site:

## Windows
- Right click on desktop, add new shortcut
- Add the target as ```"[PATH_TO_CHROME]\chrome.exe" --disable-web-security --disable-gpu --user-data-dir=~/chromeTemp```
- Click OK.
- NOTE: On Windows 10 command will be: ```"C:\Program Files (x86)\Google\Chrome\Application\chrome.exe" --disable-web-security --disable-gpu --user-data-dir=~/chromeTemp```

## OSX
    open -n -a /Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome --args --user-data-dir="/tmp/chrome_dev_test" --disable-web-security

## Linux
    google-chrome --disable-web-security

If you need access to local files for dev purposes like AJAX or JSON, you can use -–allow-file-access-from-files flag.

---
*source: https://alfilatov.com/posts/run-chrome-without-cors/*