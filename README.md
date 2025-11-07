☁️ Running on AWS SageMaker
--------------------------------------

You can run this notebook directly in the AWS Cloud using **Amazon SageMaker Notebook Instances**.  
Follow these steps carefully 👇

🪄 Step 1: Sign in to AWS Management Console
--------------------------------------------
1. Go to the **AWS Management Console**: https://aws.amazon.com/console/  
2. In the search bar, type **SageMaker** and open **Amazon SageMaker AI**.

⚙️ Step 2: Create a New Notebook Instance
------------------------------------------
1. In the left-hand menu, select **Notebook instances**.  
2. Click **Create notebook instance**.  
3. Enter a name for your instance, for example: "transport-nsw-notebook"

4. Choose an **Instance type**:
- Recommended: `ml.t3.medium` (suitable for medium workloads)
5. Leave other fields as default.

🔗 Step 3: Attach Your GitHub Repository
----------------------------------------
In the **Git repositories** section (toward the bottom of the creation page):

1. Click **Add Git repository**.  
2. Select **Clone a public Git repository**.  
3. Enter your GitHub repository URL

4. Click **Create notebook instance**.

▶️ Step 4: Launch the Notebook Instance
----------------------------------------
1. Wait until the **Status** changes from `Pending` → `InService`.  
2. Click **Open JupyterLab** or **Open Jupyter** to access your workspace.  
3. You’ll see a folder named `shine-sagemaker-jupyter-notebook`.  
4. Inside it, open the notebook: "transport_nsw_test_data.ipynb"


💡 Step 5: Run All Cells
-------------------------
Once the notebook is open:

- Click **Run → Run All Cells** from the top menu, or  
- Use the shortcut: Shift + Enter


This executes all code blocks and displays the analysis results below each cell.

