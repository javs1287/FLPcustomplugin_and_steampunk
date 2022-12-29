# SETTING UP EMBEDDED STEAMPUNK

## Introduction
In this section you will find the required steps to run the basic setup of Embedded Steampunk. This step is mandatory for you to run the exercise end-to-end.

## Create a new ABAP Project in ADT (Eclipse)
You should start by creating a new ABAP project for your SAP S/4HANA 2022 system. To do this follow the next steps:

1. Create a new project in ADT.

  ![New Project](images/new_project.png)

2. Select the backend system you will connect to and click **Next**.

  ![Select System](images/select_system.png)

3. Confirm system connection parameters (or edit as needed) and click **Next**.
  **Note - In this screen you may also create a new connection from scratch.**

  ![System Details](images/review_details.png)

4. Enter your system Id to setup a connection to the backend system and click **Next**

  ![Login](images/enter_systemId.png)

5. Setup a friendly name for your ABAP project (for example: <SID>_Demo_FLPplugin) and click **Finish**.

  ![Setup Friendly Name](images/setup_name.png)

6. Once all steps are run you will find your new project in the **Project Explorer** section in ADT.

  ![Confirm](images/confirm_new.png)

## Create a custom software component
Using developer extensibility requires a separate software component if you want to use it in parallel to classic extensibility.

To create this custom software component follow the next steps:

7. Highlight your recently created project in the **Project Explorer** section in ADT and click on button **Open SAP GUI**

  ![Step7](images/step7.png)

8. In the pop-up dialog, confirm project selection is correct and click **Ok**.

  ![Step8](images/step8.png)

9. ADT should now display a classic SAP GUI screen

  ![Step9](images/step9.png)

10. In this GUI screen run transaction **SE38**

  ![Step10](images/step10.png)

11. Run program **RSMAINTAIN_SWCOMPONENTS**.

  ![Step11](images/step11.png)

12. Click on the **Add** button.

  ![Step12](images/step12.png)

13. In the dialog screen enter the following details and **Save**:

  * Component:              <You component name> (for example: ZEMBEDDED_STEAMPUNK)
  * Release:                DEV
  * Development type:       Transportable
  * ABAP Language version:  ABAP for Cloud
  * Component type:         K
  * Description:            <Your component description> (for example: Custom Component for Steampunk Development)

  ![Step13](images/step13.png)

14. To save your component to a transport request start by selecting your new component followed by clicking on the **Transport Software Component Entry**, you will be prompted for a workbench request (enter details as needed and save).

  ![Step14](images/step14.png)

15. Once your software component is saved to a transport request, you need to release such transport request before continuing with the next steps. To release your transport, navigate to the **Transport Organizer** tab in ADT, right click on your transport task and release.

  ![Step15](images/step15.png)

  **NOTE** - If you cannot find **Transport Organizer** navigate to: **Window -> Show View -> Others**. Search for transport in search help and once you find the view click **Open**.

  ![Step15trbl](images/step15trbl.png)

## Create a custom structure package
All your custom development packages would need to be located below a structure package that is specified to use ABAP language version ABAP for Cloud Development, this way the system differentiates objects created through classic extensibility or through developer extensibility (Embedded Steampunk).

## Create a custom development package for your Embedded Steampunk custom developments


For more information on Notification Providers click on this [link](https://help.sap.com/viewer/68bf513362174d54b58cddec28794093/202110.000/en-US/80331a1a19464223897f9bd60584461f.html).

## Next Steps
In the next section you will start by creating the first object in our custom development architecture: a Custom Function Module

  ![Development ARchitecture](images/dev_arch.png)

To continue with this exercise go to [Exercise 1](../ex_2)
