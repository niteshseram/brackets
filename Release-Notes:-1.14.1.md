## Brackets 1.14.1 is here!
The 1.14.1 release has a security update to fix "remote exploitation by DNS rebinding" vulnerability noticed with remote debugging enabled by default on application launch.
 
To address the security issue, the CEF debugger is disabled by default on application launch. Users who would want to enable debugging should launch Brackets from command line/terminal with the following command:
> Brackets.exe --remote-debugging-port= `Port No`
 
A toast notification will be shown in Brackets UI with the message “Remote debugging enabled on localhost:12345” for valid port number and remote debugging will be enabled. If port is not in the range between 1024 – 65534, the remote debugger is disabled on launch and a toast notification will be shown with the message “Cannot enable remote debugging on port <<Port No>>. Port numbers should be between 1024 and 65534.”
