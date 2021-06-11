# single-spa-multiple-routes
Created a simple angular application with multiple routes which is working fine inside the app but not working when we refresh the browser

#steps to reproduce this issue
1. Get the Source Code
2. Go to the Folder single-spa-multiple-route
3. cd MicroFrontEnd  `Go to MicroFrontEnd Folder`
4. npm install       `Run the npm install Command`
5. cd ../   `Navigate back to Single-spa-multiple-route folder`
6. cd RootConfig  `Go to RootConfig Folder`
7. npm install `Run the npm install Command`
8. cd ../  `Go to MicroFrontEnd Folder`
9. cd MicroFrontEnd  `Go to MicroFrontEnd Folder`
10. ng s --project nestedroutes --disable-host-check --port 4400 --live-reload false `Run the ng s command to start the MicroFrontEnd App`
11. Open new Terminal 
12. Go to RootConfig folder `~single-spa-multiple-route\RootConfig`
13. npm start `Run the npm start command for Root Config HTML file`
14. Launch the application by navigating to http://localhost:4200/app1 in the brower. (http://localhost:4200 Or http://localhost:4200/app1/ will not work )
15. Click on any of the hyperlink available in the browser
16. Refresh the entire browser with the link such as http://localhost:4200/app1/App1Route1 , http://localhost:4200/app1/App1Route2 , http://localhost:4200/app1/App1Route3
