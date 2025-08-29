# Alternative-Drug-Recommendation-System
The Alternate Drug Recommendation System allows users to find substitute drugs by entering a specific drug name. It generates a list of alternatives with comprehensive details, leveraging data analysis and similarity algorithms. This system improves accessibility, tackles issues related to drug availability, cost, and awareness.


**Installation and Usage Guide**

### Installation

Follow these steps to set up and run the application locally:

#### 1. Clone the Repository

Download the project and navigate to its directory using:

```bash
git clone https://github.com/abhinay0019/Alternative-Drug-Recommendation-System.git
cd alternate-drug-recommendation-system
```

#### 2. Install Dependencies

Ensure Python 3.x is installed, then run:

```bash
pip install -r requirements.txt
```

The `requirements.txt` file should include:

* streamlit
* pandas
* pickle-mixin
* scikit-learn
* numpy
* pillow

#### 3. Start the Application

Run the Streamlit server with:

```bash
streamlit run app.py
```

---

### Usage

#### Upload Data Files

Place the following files in the root directory:

* `Medicine_description.xlsx`
* `similarity.pkl`

#### Search for Drugs

* Use dropdown menus to filter by **Type** and **Manufacturer**.
* Select a specific drug to view recommended alternatives.

#### Get Recommendations

Click **Recommend Drug** to see alternative options. Each recommendation provides:

* **Description:** Key details about the drug.
* **Price:** If available.
* **Manufacturer:** Information about the producer.
* **Direct Links:** Purchase options (e.g., PharmEasy, 1mg, Apollo).
* **Image:** Visual reference of the drug (if available).

---

### Interactive Display

The application enhances the user experience by offering:

* Clear images of drugs.
* Direct purchase links for quick access.

This tool simplifies the process of finding alternative drugs and supports informed healthcare decisions.

Would you like me to **convert this into a professional README.md format for GitHub**? Or **make a shorter version for a report/PPT**? Or both?
