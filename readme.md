The following app is coded in Swift and has Firebase integration in the backend.
A Mac System is particularly needed to run the app alongwith the latest version of XCode and Cocoapods installed on macOS (needless to say you also need an active internet connection to connect to the firebase backend);

Once you open the file in finder, kindly open the ContactsAppZH.xcworkspace file, 
Go to the project navigator and 'Signing and Capabilities' options under it;,
Choose your Team and you'd be get going.
Press Command+B in order to build the project and make sure you aren't getting any errors (Yellow triangle warnings are just fine and shouldn't stop the project from building)
If you get the "Build Succeeded" box, make sure you have iPhone 11 simulator installed on your Mac, go ahead and choose it from the menu and press Command+R, the project should be up and running.

Once the project is running on a simulator (or a physical device), you'll be asked to enter credentials or set up a new account;

Demo credentials are; 
Email- test@gmail.com
Password- test123

Incase you want to set-up a new account, you can do that too.

The underlying viewController will present you with the Name, Phone Number and Email fields respectively.
The user-data will be stored as CoreData locally and will be shown in the table below it.

Happy Testing :)
