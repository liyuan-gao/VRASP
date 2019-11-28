# VRASP: : A Virtual Reality Environment for Learning Answer Set Programming
Abstract: Answer Set Programming (ASP) is a dominant programming paradigm in Knowledge Representation. It is used to build intelligent agents -- knowledge-intensive software systems capable of exhibiting intelligent behaviors. It is found that ASP can also be used to teach computer science in middle and high schools. However, the current ASP systems do not provide direct support for a programmer to produce an intelligent agent that a general user can directly interact with, which may greatly compromise the potential attraction of ASP to the secondary school students. In this paper, we propose a Virtual Reality (VR) learning environment - an educational approach in which teaching and learning occur - called VRASP that allows a student to produce an avatar (agent) in a virtual world that is able to answer questions in spoken natural language from a general user. The VR application is accessible from anywhere so that the students' friends can interact with the agent. As a result, it gives the students a feeling of achievement and thus encourages them to solve problems using ASP. VRASP was evaluated with 10 users. Results of these studies show that students are able to communicate with the environment intuitively with an accuracy of 78%

# How to run VRASP
Follow this link for the application: https://alex-nguyen.github.io/VRASP/
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
