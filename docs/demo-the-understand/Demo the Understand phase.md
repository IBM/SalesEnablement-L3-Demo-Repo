# Demo the Understand Phase using the Application Discovery Tool on IBM watsonx Code Assistant for Z 
1. In Z Virtual Access, click IBM Developer for z/OS (A) in the taskbar to open it.
   ![](images/taskbar1.png)

   It may take a minute for the application to open, but you will soon see the splash screen.
   ![](images/splash.png)

   The IBM Developer for z/OS Integrated Developer Environment (IDE) opens displaying the **Explore projects** tab (A).
   ![](images/explorprojects1.png)

2. Right-click below the quick filter area (A), and click **Get project list** (B).
   ![](images/getprojlist.png)

3. Click **GenApp** (A) in the **Project** list.
   ![](images/GenApp.png)

   A new field with a list of options appears on the right side of the screen.

4. From the quick filter pane (A), expand the **Mainframe Graphs** twistie (B), and double-click **Transaction Callgraph** (C).
   ![](images/transactioncallgraph.png)

5. It may take a moment for the **GenApp – Transaction Call Graph Analysis** pop-up that is needed to do the next step to appear. 
   
   You will see an **executing Transaction Callgraph** message at the bottom of the pop-up displaying a green progress bar (A). 

   Select everything in the **Available transactions** box using the **add all items** button (looks like a fast forward button) (B), and move them to the **Selected transactions** box.
   
   Then click **Finish** (C) to load the transactions.
   ![](images/GenApp-selecttransactions.png)

   A call graph is loaded with all the transactions in this profiled application. (Note: it may take a few minutes for the graph to build.)
   ![](images/callgraph.png)

8. Zoom in so you can see the transaction named **SSC1** (A). This transaction is related to the CUSTOMER table. The SSC1 transaction is used to Add, Insert, and Update the CUSTOMER table. SSC1 will be used in the next phase.


