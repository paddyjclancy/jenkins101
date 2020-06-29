# Jenkins - Integration Server

- Combines all code / aspects of an app, to continuously test it.

## Build steps:

1) Dev updates / changes code
	- Code --> Version Control --> repo
2) Code delivered to build server
	- Jenkins detects chenge, sends to server
3) Builds app
	- Builds new version of app using build-script (.sh file)
4) Testing
	- Using test script
	- Either unit or integrated
5) Return problems
	- Either in UI or as email