# Improved-HERO-ontology-model-for-semantic-web-application
a way to extend and improve upon an HERO ontology,use of protégé, Jena and Java to create a usable application
List:
1.	HERO_V07.12.owl file;
2.	HEROapplication fold;

Step1 install plugin JFormDesigner via Eclipse. The process is shown as below:
  
•	 1. Inside Eclipse select Help -> Install New Software... 

 

•	2. Add a new site using the url http://dist.springsource.com/release/TOOLS/update/e3.7/ to the Eclipse Update Manager. 

 

•	3. Select the bundles from the list that you would like to install and click Next.

 
 

 Step 2 import HEROapplication workspace by Eclipse.
1 From the main menu bar, select  command link File > Import.... The Import wizard opens.
2 Select General > Existing Project into Workspace and click Next.
3 Choose either Select root directory or Select archive file and click the associated Browse to locate      the directory or file containing the projects.
4 Under Projects select the  HEROapplication to import.
5 Click Finish to start the import.

Step 3 when open HEROapplication workspace, we will find there are 2 files: openOWL.java and WebUI.java.open the openOWL.java file, in the 32 line, there is function shown as below:
java.io.InputStream in = FileManager.get().open("E:/SemanticWebSoftware/assignment-Sementic/NEW MODEL/HERO_V07.12.owl");
we download HERO_V07.12.owl file in the local PC and  Copy this store path to instead of the previous one in FileManager.get().open();

step 4 open the WebUI.java and run the application. 
