# sequential-thinking
* Always think sequentially, even if it takes more time
* Reflect on the problem at hand and take your time

# github
* > **IMPORTANT:** Always ask before making a commit
* > **IMPORTANT:** Never make a commit without user input first
* > **IMPORTANT:** Never push without explicit confirmation
* Always create a descriptive commit message detailing what is changed in this commit
    * Remember git as a terminal command can not take messages with new lines in it
* When asked to push a commit on a branch, ask if a PR is needed
* Remember to ask before making a commit
  
# browser-tools
* Always check that `browser-tools-server` is running and is on port 3025
    * If there are multiple instances of `browser-tools-server` running, stop them all
* Try to use `browser-tools` before `puppeteer`
* If there is an issue running `browser-tools`, check to see if the `browser-tools-server` is running
    * If it is not, start it using `npx @agentdeskai/browser-tools-server@latest`

# puppeteer
* Always check the port for the currently running site before taking any action
* Unless otherwise directed always start at the root `/` of a site
* When debugging or diagnosing always check the browser logs first
* When debugging or diagnosing use screen shots as a last resort
* For page or layout level issues, use curl or similar before screen shots


