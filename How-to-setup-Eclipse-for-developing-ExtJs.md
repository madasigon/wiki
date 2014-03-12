In this section we introduce the tools which can be used for developing web applications based on ExtJS. You can use different editors to write javascript code such as PICO, VI, gEdit, etc. I encourage you to do not use text editors, instead use an Integrated Development Environment (IDE). You can found various IDEs in the market. We propose to use Eclipse as it provides lot of plugins which can help for debugging or coding javascript. In addition it is free.

# Why do not use text editors?

Text editors are very code to write text, but not to write efficient code. We would like to highlight some disadvantages of the text editors:

  -code quality: It is not easy to have same code style.

  -auto-complete feature 

  -it is not easy to manage the code

Advantages of the IDEs:

  -code quality: Each developer can use the save template, which means we can have an 'universal' code.

  -auto-complete feature: When you type a class name and after . the IDE show the possible methods as well as a short description of the method.

  -easy to manage the code.

  -it is easy to create tasks: When required to change some code in the comment we can add //TODO and text. This will appears a Tasks list.

  -easy to navigate between classes. etc.


# Eclipse
-You can download from: [Eclipse IDE](https://www.eclipse.org/‎). 

-installation instructions can be found: [Eclipse wiki](http://wiki.eclipse.org/Eclipse/Installation)

#ExtJS

-download from [Sencha page] (http://www.sencha.com/products/extjs/) and un-zip it. Note if you have installed WebAppDIRAC, you can found it under WebApp/static/extjs directory.

#Eclipse ExtJS

We used the [DuckQuoc's blog](http://ducquoc.wordpress.com/2011/02/16/eclipse-extjs-jquery/) to set up our Eclipse. There is an other page when you can read about how to setup Eclipse in [Spket page](http://www.spket.com/extjs.html)
We use Indigo Eclipse and Spket plugin for developing better javascript code. 
* **Install Spket plugin**:
  
   1. Click Help -> Install New software… The following form Install form will appears: 
![InstallForm](https://zmathe.web.cern.ch/zmathe/installform.png)
   
   2. Click Ok -> select all components 
   
   3. Accept the term and conditions -> Finish
   
   4. Wait till the package will be downloaded and installed in case of warning click OK. 
   
   5. Restart Eclipse (If it will not restart automatically)

* **Create Spket profile for ExtJs (Configuration panel)**:

   1. Click "Eclipse" -> "Preferences…" You will see the following configuration form:
    ![spket](https://zmathe.web.cern.ch/zmathe/spket.png)

2. select "Spket JavaScript Profile" and click to the New button and then type ExtJs.
![spket profile](https://zmathe.web.cern.ch/zmathe/spketprofile.png)

3. Click "Add Library" select ExtJs

4. Click "Add Folder" you have to add the path of the ExtJs folder (more details in <https://github.com/DIRACGrid/WebAppDIRAC/wiki/_preview#wiki-extjs>` section).

* **Make default JavaScript profile**

-In the same window ("Spket JavaScript Profile") click on the Extjs profile and after make it default by clicking on the "Default" button. 

-in the "Configuration panel" click on the "General"->"Editors"->"File Associations"
![file association](https://zmathe.web.cern.ch/zmathe/spketfile.png)

Please select *.js and then select "Spket JavaScript Editor" and click on the "Default button"

Now We propose to restart Eclipse.

* **Auto-complete feature**
After the restart you can create a javascript file and try type Ext. and **Ctrl+Space** 
![auto-complete](https://zmathe.web.cern.ch/zmathe/spketauto.png)
