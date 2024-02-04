  ```                                                                                                           
      ABOOK       KCODAB    ODABOOK           ABO       OOKCODABOO      OOKCOD       DABOOK    BOOKCO   OOK    
    CODABOOKCO   OOKCODAB   CODABOOKC        ODABO      BOOKCODABOO    ABOOKCOD     CODABOOK   ABOOK    BOO    
   OKC   BOOKC  ABOO  ODAB  KCODABOOKC       CODAB      ABOOK   ABO   ODAB  KCOD   OKCO  BOOK   ABO    DA      
  BOO     BOOK  DAB    ODA  OKCO   OOKC     OKCODA        BOO   DAB   COD    KCO   OOK    BOO   DAB   CO       
  ABO          CODA    CODA  OKC   BOOK     OOK ODA       ABOOKCODA  OKCO    OKCO ABOO    ABOO  ODABOOK        
  DA           KCOD    KCOD  OOK    BOO    ABOOKCODA      DABOOKCODA OOKC    OOKC DABO    DABO  CODABOO        
  OD            KCO    OKC   BOO   DABO    DABOOKCOD      ODABOOKCODA OOK    BOO   DAB    ODA   KCODABO        
  CO       OD   OKC    OOK  DABO  CODAB   CODA   KCOD     COD    KCOD BOO    ABO   ODA    COD   OKC  ABO       
  KCO     KCO   OOKC  ABOO CODABOOKCODA   KCO     KCO     KCODABOOKCO ABOO  ODAB   CODA  OKCO   OOK  DAB       
   KCODABOOKC    OOKCODAB  KCODABOOKCO  BOOKCO   OOKCOD BOOKCODABOOK   ABOOKCOD     CODABOOK   ABOOK ODABOOK   
    KCODABO       OOKCOD   OKCODABOO    ABOOKC   BOOKCO ABOOKCODABO     ABOOKC       CODABO   ODABOO CODABOO   
```



*********************************************************************************************
* COMPANION CODE FOR THE BOOK �Component Oriented Development & Assembly � CODA Using Java� *
* AUTHORS � Piram Manickam, Sangeetha S, Subrahmanya S V                                    *
* REFERENCE � http://www.codabook.com                                                       *
* CODE CONTRIBUTORS � Vishal Verma, Shikhar Johari, Soumya Bardhan, Rohit jain,             *
*		      Karthika Nair, Vibhuti Pithwa, Vaasavi Lakshmi                        *
********************************************************************************************* 


1. The zip file you downloaded contains this README file and the binary code for the example in Section 3.5 of the book.

2. To execute the binaries, unzip the contents of the downloaded zip file into a local folder on your machine. Let us name this folder - 'AgeCalculator'. The folder would contain the following files:

	- AgeCalculatorApi.jar
	- AgeCalculatorClient.jar
	- AgeCalculatorImpl.jar
	- Launcher.jar
	- README.txt

3. In order to execute the downloaded program, you have to provide OSGi runtime framework bundle and Declarative Services Runtime bundle. These will be files with names like 

  - 'org.eclipse.equinox.ds_1.4.0.v20120522-1841.jar'
  - 'org.eclipse.equinox.util_1.0.400.v20120522-2049.jar'
  - 'org.eclipse.osgi_3.8.0.v20120830-144521.jar'
  - 'org.eclipse.osgi.services_3.3.100.v20120522-1822.jar' 

These files will be under the plugins folder of the eclipse installation directory. The trailing numbers of the file name may be different than shown here depending on the version of Eclipse Equinox installed in your machine. To successfully run the example program, version 3.8.0 or above of 'org.eclipse.osgi' bundle is required.

4. Copy these files from the Eclipse Plugins folder to the folder - 'AgeCalculator'.


Running the Project:
--------------------

1. The program can be run from your OS console window provided Java Runtime Environment is installed and configured. 

2. On your OS console window, navigate to the folder - 'AgeCalculator'.

3. Run the following command to start execution of the program which would present a text asking for user input:

        java -cp .jar;./* codabook.osgi.Launcher
        java -cp ./* codabook.osgi.Launcher

4. Use the Age Calculator program as guided by the text based menu. 

*********************************************************************************************
* COMPANION CODE FOR THE BOOK �Component Oriented Development & Assembly � CODA Using Java� *
* AUTHORS � Piram Manickam, Sangeetha S, Subrahmanya S V                                    *
* REFERENCE � http://www.codabook.com                                                       *
* CODE CONTRIBUTORS � Vishal Verma, Shikhar Johari, Soumya Bardhan, Rohit Jain,             *
*		      Karthika Nair, Vibhuti Pithwa, Vaasavi Lakshmi                        *
********************************************************************************************* 


1. The zip file you downloaded contains this README file and the source code for the example in Section 3.5 of the book (in Eclipse project format).

2. You can import and execute the projects from Eclipse IDE using steps given below. Alternatively, you can inspect the source code by exploring *.java files inside the zip file. 


Importing Eclipse Project(s):
-----------------------------

1. Choose 'File->Import' menu from Eclipse. 

2. From the 'Import' pop-up dialog window, select 'Existing Projects into Workspace' under 'General'.  Click on 'Next' button.

3. In the next screen, choose the option 'Select archive file', and select the downloaded zip file. 

4. After scanning the archive, Eclipse lists the following projects under �Projects� selection box:
      - AgeCalculatorClient
      - AgeCalculatorApi
      - AgeCalculatorImpl
      - Launcher

5. Select all the projects and click on the 'Finish' button.

6. Selected projects will get added to your Eclipse workspace.


Setting Up the Required Libraries
---------------------------------

In order to compile the downloaded application, you have to provide OSGi runtime framework bundle. This file is located under �plugins� folder inside Eclipse installation. The file has a name similar to 'org.eclipse.osgi_3.8.0.v20120830-144521.jar'. The trailing numbers of the file name may be different than �_3.8.0.v20120830-144521.jar� shown here depending on the version of Eclipse Equinox installed in your machine. To successfully compile the example application, version 3.8.0 or above of 'org.eclipse.osgi' bundle is required.   

You can add the library to your Eclipse by following the steps given below :-

1. Choose 'Window' -> 'Preferences' menu from Eclipse.
2. From 'Preferences' dialog window, select 'User Libraries' under 'Java' -> 'Build Path'. Click on 'New' button.
3. Type 'Equinox' in the 'User library name' field. Click on 'OK' button.
4. Select the newly created 'Equinox' library, click on 'Add External Jars', browse to 'plugins' folder under Eclipse installation to locate the file 'org.eclipse.osgi_3.8.0.v20120830-144521.jar' and click on 'Open' button. As mentioned above, the trailing numerical part of the filename could be different in your environment.
5. Click on 'Ok' button.
6. The OSGi runtime framework bundle gets added to the library 'Equinox'.


Building Components And Executing the Application
-------------------------------------------------

1. The application is executed through the 'Launcher'. Before we execute Launcher, all the OSGi bundle components needs to be built. Right click on any project under project explorer window and choose 'Export'. Select 'Deployable Plug-ins and Fragments' from 'Plug-in Development' category. Select all the plugins from 'Available Plug-ins and Fragments' by clicking on the 'Select All' button on the right.

Point the destination directory to the 'Launcher' folder in your workspace by clicking on 'Browse' button. For example, if your workspace folder is "D:\workspace", choose "D:\workspace\Launcher" as the destination folder. Click on 'Finish' to export the bundles.

2. Verify the OSGi bundles were exported properly by looking under the Launcher project. There should be a folder called 'plugins'. Right click on the Launcher project and choose 'Refresh' from the pop-up menu. Under the 'plugins' folder, you should now see the three exported OSGi bundle JARs.

3. Since the companion code deals with OSGi Declarative Services, you have to provide following additional bundles in order to provide Declarative Services Runtime. Copy the following bundles to the plugins folder inside the 'Launcher' project in your workspace.

  - org.eclipse.equinox.ds_1.4.0.v20120522-1841.jar      
  - org.eclipse.equinox.util_1.0.400.v20120522-2049.jar
  - org.eclipse.osgi.services_3.3.100.v20120522-1822.jar

These bundles can be found under the plugins folders of your Eclipse installation. The trailing numbers of the file name may be different than what is shown here depending on the version of Eclipse Equinox installed in your machine.

4. Right click on the project 'Launcher' under 'Project Explorer' window in Eclipse. From the context pop-up menu, select 'Run as' -> 'Java Application' option. If Eclipse prompts you with �Select Java Application� window, choose the 'Launcher' class from among multiple options provided.

5. Use the Age Calculator program as guided by the text based menu.
