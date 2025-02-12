# probabilistic_forecasting_with_reinforcement_learning
This project introduces a novel two-step methodological framework that combines a probabilistic forecasting system with a distributional DRL algorithm to achieve an optimal least-cost operation of the microgrid. 

In summary, This project introduces a novel two-step methodological framework that combines a probabilistic forecasting system with a distributional DRL algorithm to achieve an optimal least-cost operation of the microgrid. It focuses on incorporating VRES and electricity load demand probability forecast with distributional DRL dispatch modelling. The current state-of-the-art of doing this only focuses on deterministic forecast values instead of probabilistic forecasts that quantify the uncertainty in the forecast. It further demonstrates how to integrate it with the optimization strategies of the energy and electricity system in a bid to minimize the operation cost of the microgrid system. 

Here, we:

•	Developed and implemented a probabilistic forecasting system in Python using libraries like GluonTS and PyTorch to quantify uncertainties in renewable energy and load demand forecasts.

•	Applied distributional deep reinforcement learning algorithms (e.g., Quantile Regression DQN) in Python to optimize microgrid operation and achieve least-cost scheduling.

•	Integrated probabilistic forecasts into the DRL model in Python, demonstrating expertise in uncertainty modeling and enhancing the robustness of the scheduling solution.

•	Leveraged Python and optimization libraries like Gurobi to model and solve the microgrid energy scheduling problem, minimizing operational costs.

•	Conducted research and analysis of existing literature using Python to identify research gaps and develop a novel methodological framework combining probabilistic forecasting and distributional DRL.

Installing Dependencies from requirements.txt
Follow these steps to install the required Python dependencies on your system.
✅ Prerequisites:
•	Ensure Python (>=3.x) and pip (>=21.x) are installed.
•	Check Python and pip versions:
sh
CopyEdit
python --version
pip --version
📌 Installation Instructions
🖥️ Windows:
1.	Open Command Prompt or PowerShell.
2.	Navigate to the project directory:
sh
CopyEdit
cd path\to\your\project
3.	Run:
sh
CopyEdit
pip install -r requirements.txt
🍏 macOS & 🐧 Linux:
1.	Open Terminal.
2.	Navigate to the project directory:
sh
CopyEdit
cd /path/to/your/project
3.	Run:
sh
CopyEdit
pip install -r requirements.txt
🔍 Additional Tips:
•	If using a virtual environment, activate it before running the installation:
sh
CopyEdit
# Windows (CMD)
venv\Scripts\activate

# Windows (PowerShell)
venv\Scripts\Activate.ps1

# macOS/Linux
source venv/bin/activate
•	If you face permission issues, try:
sh
CopyEdit
pip install --user -r requirements.txt
•	For system-wide installation, use:
sh
CopyEdit
sudo pip install -r requirements.txt
🛠️ Verifying Installation:
Run:
sh
CopyEdit
pip list
to check if all packages are installed.
