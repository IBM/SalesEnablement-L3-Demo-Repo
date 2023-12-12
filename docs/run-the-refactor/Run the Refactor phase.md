# How to run the Refactor phase using IBM watsonx Code Assistant for Z Refactoring Assistant

1. Open the PuTTy app from the taskbar at the bottom **(A)** of the demo window. It may take a few minutes to open.
   ![](images/openPutty.png)
2. Select **wca4z-ra** from the **Saved Sessions** box **(A)**, and click **Open** **(B)**.
   ![](images/savedsessions.png)
3. After clicking **Open** in the previous step the following warning message will pop-up. Click **Accept** **(A)**. This warning will only be displayed one time if you do this demo again.
   ![](images/puttywarning.png)
4. A script will run in PuTTy to start the Refactoring Assistant. When you see the text **IBM Watson code assistant for Z Refactoring Assistant started** **(A)** at the bottom of the PuTTy window, you can close the PuTTy window by clicking the **X** **(B)** in the top-right corner. You will be asked **Are you sure you want to close the session?**. Click **OK** **(C)**.
   ![](images/closeputty.png)
5. Click the Firefox icon **(A)** in the taskbar of the demo window to open it. It may take a few minutes to open.
   ![](images/openfirefox.png)
6. Click the IBM watsonx Code Assistant for Z Refactoring Assistant link in the Favorites bar at the top or click **wca4z-ra.ibm** below the Firefox search bar **(A)**.
   ![](images/openfirefox2.png)
7. Login with the following credentials, and click **Log in** **(C)** to proceed to the IBM watsonx Code Assistant for Z Refactoring Assistant:
   - Email address: dev@wca4z-ra.ibm.com **(A)**
   - Password: password **(B)**
  ![](images/wcaralogin.png)
8. After logging in, you will see following tabs:
    - My workspaces **(A)** (the default)
    - Workspaces shared with me **(B)**
  ![](images/myworkspaces.png)
  After building a project in the Understand phase, you can create a workspace to work on that project with IBM watsonx Code Assistant for Z Refactoring Assistant.
9. In the **My workspaces** tab, click **Create workspace** on the right (A).
    ![](images/createworkspace.png)
10. In the **Create workspace** dialog box:
    - Type a name for the workspace that you want to create. For example: **WCA4Z-DEM-WS** **(A)**.
    - Optionally, add a description in the **Description** box **(B)**. For example: **Workspace for WCA4Z for GenApp application**.
    - Click the **AD Project** dropdown list, and select the project that you built with the IBM Application Discovery (AD) Build Client. In this lab, select **GenApp** **(C)**. 
    - Click **Create** (D) to create the workspace.
    ![](images/createworkspace2.png)
11. The GenApp workspace’s **Graph** tab **(A)** is displayed. Click in the **Search** bar **(B)** at the top. You will see the **Artifact type** drop-down menu.
    ![](images/artifacttype.png)
12. Select **All artifact types** (it’s likely the default) to see a dropdown list of the different artifact types **(A)**.
13. Select **CICS transactions (B)**.
    ![](images/selectcics.png)
14. From the dropdown list of transactions, double-click the **SSC1** artifact **(A)** to open it.
    ![](images/openssc1.png)
15. The **SSC1** transaction graph opens. **Zoom out by 10%** (A) using the magnifying glass icon (bottom left) until you can see the complete callgraph in the window.
    ![](images/zoomoutssc1.png)
