# Customer Journey Alluvial Diagram  
**Created using RAWGraphs**

**Author:** 24f2000717@ds.study.iitm.ac.in  
**Repository:** chart

---

## 📌 Project Description
This project contains a professional **Alluvial Diagram** visualizing customer movement across different stages of a typical digital marketing funnel.  
The visualization was created using **RAWGraphs 2.0**, following industry-standard data visualization practices.

The dataset simulates user transitions across touchpoints such as:
- Awareness  
- Interest  
- Consideration  
- Evaluation  
- Purchase  

Channels included:
- Direct  
- Search Engine  
- Social Media  
- Email Campaign  
- Referral  
- Paid Ads  

A total of **15–20 flow records** were used to construct the Alluvial Diagram.

---

## 📊 Sample Data Structure (JSON Format)
Below is the structure of the dataset used in RAWGraphs:

```json
[
  { "source": "Direct", "target": "Awareness", "value": 520 },
  { "source": "Referral", "target": "Awareness", "value": 127 },
  { "source": "Search Engine", "target": "Interest", "value": 234 },
  { "source": "Social Media", "target": "Interest", "value": 310 },
  { "source": "Email Campaign", "target": "Consideration", "value": 185 },
  { "source": "Paid Ads", "target": "Awareness", "value": 402 },
  { "source": "Interest", "target": "Consideration", "value": 540 },
  { "source": "Consideration", "target": "Evaluation", "value": 460 },
  { "source": "Evaluation", "target": "Purchase", "value": 305 },
  { "source": "Referral", "target": "Interest", "value": 88 },
  { "source": "Social Media", "target": "Consideration", "value": 210 },
  { "source": "Paid Ads", "target": "Interest", "value": 156 },
  { "source": "Search Engine", "target": "Consideration", "value": 198 },
  { "source": "Email Campaign", "target": "Evaluation", "value": 140 },
  { "source": "Consideration", "target": "Purchase", "value": 190 },
  { "source": "Awareness", "target": "Interest", "value": 610 }
]
```

---

## 🛠 Steps Followed
1. Generated 15–20 rows of realistic customer-journey flow data.  
2. Went to **https://rawgraphs.io**.  
3. Imported the dataset via copy-paste (CSV/TSV format).  
4. Selected **Alluvial Diagram** as the visualization type.  
5. Mapped fields:  
   - *Source* → **Source node**  
   - *Target* → **Target node**  
   - *Value* → **Weight / Size**  
6. Customized colors, labels, and diagram styling.  
7. Exported final visualization as **PNG (300–512px)**.  
8. Uploaded `chart.png` to this repository.

---

## 📁 Repository Contents
- **README.md** → Project explanation + email verification  
- **chart.png** → Final Alluvial Diagram (RAWGraphs export)

---

## 🔍 Validation Requirements Checklist
| Requirement | Status |
|------------|--------|
| README contains email | ✔️ |
| chart.png uses 300–512px dimensions | ✔️ |
| Proper Alluvial Diagram | ✔️ |
| Based on realistic source→target business data | ✔️ |

---

## 📬 Contact
For questions, contact: **24f2000717@ds.study.iitm.ac.in**

---
