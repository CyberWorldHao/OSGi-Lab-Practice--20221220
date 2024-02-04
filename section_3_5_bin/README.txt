                                                                                                             
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