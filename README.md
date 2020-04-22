# QuickStartExtJS
Create web application with Ext JS

# Best Pratice Dealer App with Ext JS
Description will goes here...

### Pre-requisite
	1. **Repository
		- Git for windows: https://git-scm.com/download/win
		OR
		- Fork (Git GUI): https://git-fork.com/
	
	2. **Client
		- Sencha Architec 4.2
		Soft path: \\asia-hqshare\BEN-share\CRM-Dev\DevTools\Sencha\Sencha Architec
	3. **Server
		- Visual Studio 2017/19
		- Oracle Managed Data Access
		- Ext Direct MVC
		
### Up and Running
	1. **Clone projects
	http://192.168.165.61:8080/tfs/ITProjectCollection/DealerSystem/_git/DealerSystemV2
	
	2. Open project in Visual Stuido, install dependency complente, can do Run	
	
### Naming and structure
	1. **Have folder for each type of class (model, store, view)
	2. **Follow class namespace guidlines for views
		- {appname}.{classtype}.{class}.{Class(type)}
		- For example: MyApp.view.user.UserView
	
		- Naming xtype/userAlias with small letters, For example: userview

### Resources
	1. **Pull all external resources in resources folder
		- Separate folders by type
			+ Images
			+ Data
			+ etc.
		- The Sencha app build will copy all resources (in the resources folder) to environment build path
