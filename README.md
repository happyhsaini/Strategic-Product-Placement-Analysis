# Strategic Product Placement Analysis

## Overview

Analyze and optimize product placement in retail stores. This project studies 200+ products across different shelf positions, customer types, traffic levels, and product categories.

**Data Dimensions**: 
- Position (Aisle, End-cap, Front of Store)
- Traffic (Low, Medium, High)  
- Customers (Families, Seniors, College Students, Young Adults)
- Category (Clothing, Electronics, Food)
- Promotion (Yes/No)
- Seasonal (Yes/No)

---

## 📁 Project Structure

```
Strategic-Product-Placement-Analysis/
├── Dashboard/                              # Responsive dashboard workbooks
├── Data Collection & Extraction of Data/   # Raw data collection
├── Data Preparation/                       # Cleaned and prepared dataset
├── Data Visualization/                     # Primary Tableau analysis
├── Performance Testing/                    # Performance optimization testing
├── Project Demonstration & Documentation/  # Project documentation
├── Story/                                  # Story-based narrative analysis
├── Web integration/                        # Flask web application
│   ├── app.py                             # Flask backend
│   ├── templates/
│   │   └── index.html                     # Web interface
│   └── static/
│       └── style.css                      # Styling
└── README.md                               # Project documentation
```

## 📊 Dataset

- **Total Products**: 200+ with complete data
- **Format**: CSV files
- **Fields**: Product ID, Position, Traffic, Promotion, Seasonal, Demographics, Category, Sales Volume

| Field | Values |
|-------|--------|
| Position | Aisle, End-cap, Front of Store |
| Traffic | Low, Medium, High |
| Promotion | Yes/No |
| Seasonal | Yes/No |
| Category | Clothing, Electronics, Food |
| Demographics | Families, Seniors, College Students, Young Adults |
| Sales Volume | 650 - 2,968 units |

## 🛠️ Technology Stack

- **Analytics**: Tableau (interactive dashboards & stories)
- **Backend**: Flask (Python web framework)
- **Frontend**: HTML5, CSS3, Bootstrap 5.3.2
- **Data**: CSV format
- **Version Control**: Git

---

## 🚀 Getting Started

### Prerequisites
- Python 3.7+
- Tableau Desktop/Viewer
- Modern web browser

### Installation

```bash
# Clone repository
git clone https://github.com/agraw-2305/Strategic-Product-Placement-Analysis.git
cd Strategic-Product-Placement-Analysis

# Set up Python environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install flask

# Run web app
cd "Web integration"
python app.py
```

Visit `http://localhost:5000` in your browser. Open `.twbx` files in Tableau to explore dashboards.

---

## 📊 Key Findings

- **End-cap displays** show higher traffic than standard placement
- **College students** respond more to promotions than other groups
- **Front-of-store** works well for promotional items
- **Aisle placement** has variable performance based on traffic and customer type
- **High-traffic areas** show better sales than low-traffic areas  
- **Seasonal items** sell 20%+ more during peak season
- **Promotions improve sales** across all positions and customer groups

---

## 📈 Dashboards

| File | Purpose |
|------|---------|
| Product_Placement_Analysis1.twbx | Detailed analysis with filters and drill-down |
| responsive_dashboard.twbx | Executive dashboard - mobile friendly |
| Story_Placement_Analysis.twbx | Presentation of key findings |
| Performance Testing Workbooks | Validation and testing |

---

## � Analytics Methodology & Approach

### Data Analysis Pipeline
1. **Data Collection**: Extract from retail systems and operational records
2. **Data Preparation**: Cleaning, validation, standardization, and enrichment
3. **Exploratory Analysis**: Pattern identification, correlation studies, segmentation
4. **Visualization**: Dashboard creation with multi-dimensional filtering
5. **Insight Generation**: Actionable recommendations from data patterns
6. **Storytelling**: Narrative-driven presentation for stakeholders

### Analytical Techniques
- **Multi-dimensional Analysis**: OLAP-style exploration across dimensions
- **Cross-tabulation**: Relationship analysis between placement, traffic, and sales
- **Correlation Studies**: Identifying impact relationships between variables
- **Segmentation Analysis**: Performance comparison across demographic and category segments
- **Performance Benchmarking**: Comparative analysis across products and positions
- **Trend Analysis**: Seasonal pattern identification and temporal variation

### Calculation Methods
- **Sales-by-Dimension**: Aggregated sales volume across placement, category, demographic
- **Traffic Conversion**: Sales-per-traffic-unit by position and demographic
- **Promotional Lift**: Percentage sales increase for promotional vs. regular items
- **Seasonal Index**: Peak-to-baseline ratio for seasonal items
- **Category Mix**: Product distribution and diversity within placements

---

## 💼 Business Applications & Use Cases

### Retail Store Optimization
Determine ideal shelf positions for product categories and demographic segments. Align high-performing products with premium placements. Optimize store layout based on traffic patterns.

### Promotional Campaign Planning
Evaluate which placement positions, traffic zones, and demographic segments maximize promotional ROI. Time campaigns to align with peak seasonal demand. Target promotions to high-responsive segments (e.g., college students).

### Inventory Management
Optimize stock levels by correlating placement strategies with sales velocity. Pre-position inventory for seasonal demand peaks. Align stock rotation with placement optimization cycles.

### Demographic Targeting
Develop personalized product placement strategies for specific customer segments. Tailor product selection and positioning to demographic preferences. Optimize assortment by location demographics.

### Seasonal Planning
Plan strategic placement shifts for seasonal products. Align promotional timing with demand patterns. Create seasonal merchandising calendars based on historical performance.

### Category Performance Analysis
Analyze category-specific performance across dimensions. Identify category winners and underperformers by position. Develop category-specific placement frameworks.

### Market Competitiveness
Monitor competitive positioning and pricing strategies. Identify market share opportunities by position. Optimize placement to highlight competitive advantages.

### Decision Support
Empower store managers with data-driven insights for daily decisions. Provide category managers with performance benchmarking. Enable executives to evaluate strategic placements.



## 💡 Use Cases

- Retail store optimization and layout planning
- Promotional campaign effectiveness analysis
- Inventory management and demand forecasting
- Product placement strategy for different demographics
- Seasonal planning and peak period optimization
- Category performance analysis and benchmarking

---



