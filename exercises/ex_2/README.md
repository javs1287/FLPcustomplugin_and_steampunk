# CREATING A BACKEND FUNCTION MODULE TO EXPOSE SYSTEM DETAILS

## Introduction
In this section you will find the steps to create a wrapper function module to be later consumed via code in Embedded Steampunk. Overall, you will be creating classic extensibility objects you are already familiar with like packages and function modules.

## Create a custom development package for Classic Developments
To create this custom development package follow the next steps:

25. In the **Project Explorer**, right-click on the ABAP Project for your development system and from the menu, select **New >> ABAP Package**.

  ![Step16](images/step16.png)

26. Enter the following information and click **Next**:
  * Name: **<< Your package name >>** (for example: ZWRAPPER_FUNC_CL).
  * Description: **<< Your package description >>** (for example: Wrapper Functions/Classes for Embedded Steampunk).
  * Add to favorite packages: **Active**
  * Superpackage: **Blank**
  * Package Type: **Development**

  ![Step26](images/step26.png)

27. Enter the software component where this objects will be allocated and click **Next**.
  * Software Component: **HOME**

  ![Step27](images/step27.png)

28. Select an existing transport request or create a new one to save your changes and click **Finish**

  ![Step19](images/step19.png)

29. Once created, package details will be displayed in the screen.

  **NOTE** - Your new package should also appear under the **Favorite Packages** folder.

  ![Step29](images/step29.png)

## Create a custom function module
Now that you have a package to store your custom backend clasic objects you will start creating a new function module.

30. In **Project Explorer**, expand **Favorite Packages** and right-click on your recently created development package (ZWRAPPER_FUNC_CL) and from the menu select **New >> Other ABAP Repository Object**

  ![Step30](images/step30.png)

31. In the dialog screen, search for term "Function". Once results are shown, select entry **ABAP Function Group** and click **Next**.

  ![Step31](images/step31.png)

32. Enter the following information and click **Next**:
  * Name: **<< Your function group name >>** (for example: ZREUSE_CODE)
  * Description: **<< Your function group description >>** (for example: Reuse function group for STMPNK)

  ![Step32](images/step32.png)

33. Select an existing transport request or create a new one to save your changes and click **Finish**

  ![Step19](images/step19.png)

34. Once created, your new function group will be displayed in the screen.

  **NOTE** - Try expanding the package hierarchy in the **Favorite Packages** section

  ![Step34](images/step34.png)

## Next Steps
In the next section you will create the second object in our custom development architecture: **a Custom HTTP Service (number 2 in the diagram)**.

  ![Development Architecture](images/dev_arch.png)

To continue with this exercise go to [Exercise 3](../ex_3)
