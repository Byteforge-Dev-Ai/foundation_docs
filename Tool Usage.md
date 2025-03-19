## github
- Always ask before making a commit
- Always create a descriptive commit message detailing what is changed in this commit
- When asked to push a commit on a branch, create a PR as well if possible
  
## browser-tools
- Try to use browser-tools before puppeteer
- If there are multiple instances of browser-tools-server running, stop them all
- Always check that browser-tools-server is running, if it is not, start it
- Always verify the port that the running instance of browser-tools-server is on as the browser plugin is set to the default port

## puppeteer
- Always check the port for the currently running site before taking any action
- Unless otherwise directed always start at the root `/` of a site
- When debugging or diagnosing always check the browser logs first
- When debugging or diagnosing use screen shots as a last resort
- For page or layout level issues, use curl or similar before screen shots


