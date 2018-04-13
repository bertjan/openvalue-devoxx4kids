- install Leap Motion controller software: https://leapmotion.com/setup/desktop
- open the ScratchX sample project: http://scratchx.org/?url=http://khanning.github.io/scratch-leapmotion-extension/examples/Leap%20Motion%20Example%20-%20Hand%20Skeleton.sbx
- check that your hand movements are displayed in the scratch example project
  
How to Manually Restart Leap Core Services  
On Mac, run the following commands:  
`sudo launchctl unload /Library/LaunchDaemons/com.leapmotion.leapd.plist`  
`sudo launchctl load /Library/LaunchDaemons/com.leapmotion.leapd.plist`  
