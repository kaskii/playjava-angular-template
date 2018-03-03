# Template for Play Framework and Angular

This is a simple and a working template for Play Framework (Java) and Angular. 

  - Angular should run on :9000
  - Play should run on :9090
  - grunt-connect-proxy configured for /api -> 9090



### Installation

Make sure to install all node modules and bower components. I have been using this template with IntelliJ IDEA, you can configure it:

  - Import 'server/' folder as a sbt project.
  - File -> New -> Module from Existing Sources. Choose the client folder.
  - Install wanted IDEA plugins (File -> Settings -> Plugins), for example AngularJS, Node, Scala, Play Routes etc.
  - Run -> Edit configurations -> New -> Grunt.js. Select 'serve' as a task. Check Gruntfile.js to see how it is configured.
  - Run -> Edit configurations -> New -> Play 2 App. Change 'URL to open' port to 9090

