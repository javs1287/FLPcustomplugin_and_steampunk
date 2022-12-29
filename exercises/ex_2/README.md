# CREATING A BACKEND FUNCTION MODULE TO EXPOSE SYSTEM DETAILS

## Introduction
In this section you will find the steps to create a wrapper function module to be later consumed via code in Embedded Steampunk. Overall, you will be creating classic extensibility objects you are already familiar with like packages and function modules.

## Create a custom development package for Classic Developments
To create this custom development package follow the next steps:

25. In the **Project Explorer**, right-click on the ABAP Project for your development system and from the menu, select **New >> ABAP Package**.

  ![Step25](images/step25.png)

26. Enter the following information and click **Next**:
  * Name: **<< Your package name >>** (for example: ZWRAPPER_FUNC_CL).
  * Description: **<< Your package description >>** (for example: Wrapper Functions/Classes for Embedded Steampunk).
  * Package Type: **Development**

  ![Step26](images/step26.png)

27. Enter the software component where this objects will be allocated and click **Next**.
  * Software Component: **HOME**

  ![Step27](images/step27.png)

28. Select an existing transport request or create a new one to save your changes and click **Finish**

  ![Step19](images/step19.png)

29. Once created, package details will be displayed in the screen.

  ![Step29](images/step29.png)

## Create a custom function module
30. In **Project Explorer**, expand **Favorite Packages** and right-click on your recently created development package. From the menu select **New >> Function Module**

  ![Step30](images/step30.png)

31. Enter the following information and click **Next**:
  * Name: **<< Your package name >>**
  * Description: **<< Your package description >>**

  ![Step31](images/step31.png)

32. Select an existing transport request or create a new one to save your changes and click **Finish**

  ![Step19](images/step19.png)

33. Once created, your new function module will be displayed in the screen.

  ![Step33](images/step33.png)

## Next Steps
In the next section you will create the second object in our custom development architecture: **a Custom HTTP Service (number 2 in the diagram)**.

  ![Development Architecture](images/dev_arch.png)

To continue with this exercise go to [Exercise 3](../ex_3)
