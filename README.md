# AI-Based Timing Violation Prediction  

## Project Description  
This project aims to predict the combinational complexity/depth of signals in RTL designs to quickly identify potential timing violations before synthesis. By using machine learning, we can reduce the time required for timing analysis and detect violations early in the design process.

---

## Setup Instructions  

### Prerequisites  
Ensure you have the following installed:  
- Python 3.8+  
- TensorFlow 2.x  
- Pandas, NumPy, Scikit-Learn  
- Yosys (for open-source RTL synthesis)  

### Installation  
Clone the repository and install dependencies:  
```bash
git clone https://github.com/yourusername/yourproject.git  
cd yourproject  
pip install -r requirements.txt  




Running the Code
To train the model:

bash
Copy
Edit
python train.py --dataset data/timing_data.csv  
To predict combinational depth for a given signal:

bash
Copy
Edit
python predict.py --rtl_file example_rtl.v --signal_name sig_1  



References
Yosys - Open-Source Synthesis Tool
Google Women Techmakers

