TrustPayAPI-Android for Eclipse
===============================

API files to include in your own Android project to facilitate integration into the TrustPay payment client.


Process:
1. Clone this repository to your local hard drive.
	

2. If you already have Eclipse and the Android tools installed, please go to (3.) below to create a new project and import the TrustPay API.

	i)Download Eclipse and Android tools as described at http://developer.android.com/sdk/ for your platform.
	

3. Creating a new Android project and importing the TrustPay API:

	i) Open Eclipse
	ii) Goto FILE > NEW > ANDROID APPLICATION PROJECT
	iii) Enter the 	Application Name
			Project Name
			Package Name
	iv) Complete the Create Application Wizard.
	v) Highlight the new Project in the Package Explorer.
	vi) Right Click and select PROPERTIES
	vii) Highlight the 'Java Build Path' section.
	viii) Select the 'Libraries' tab.
	ix) Click on 'Add External JARs' button.
	x) Browse to the TrustPayApi.jar file that you cloned in (1.) and click 'Open'
	xi) This will add the 'TrustPayApi.jar' library to the Libraries list.
	xii) Goto the 'Order and Export' tab. 
	xiii) Make sure that the 'TrustPayApi.jar' library is selected.
	xiv) Close the 'Properties' window.
	xv) The TrustPayApi can now be referenced from your project.
	xvi) Integrate as described in the 'Integration Guide' in this repository.

	
