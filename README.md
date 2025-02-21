# lotcost-estimator

## 📌 Project Overview
lotcost-estimator is a web-based tool that allows users to estimate the area and cost of parking lots using high-resolution satellite imagery. Built with **Google Earth Engine (GEE)**, the application enables users to draw polygons over parking lots, compute their area, and estimate material, labor, and equipment costs dynamically.

🔗 **Live Project:** [lotcost-estimator](https://geo-parking-cost.projects.earthengine.app/view/lotcost-estimator)

## 🌟 Features
- **Satellite Image Processing**: Uses **USDA NAIP** high-resolution imagery.
- **Interactive Map**: Users can enter coordinates and navigate to the location.
- **Polygon Drawing Tool**: Allows users to define parking lot boundaries.
- **Automatic Area Calculation**: Computes area in square meters.
- **Cost Estimation**:
  - **Material Cost** = Area × Unit Cost ($10 per ton)
  - **Labor Cost** = (Area / 100) × Labor Rate ($50 per hour)
  - **Equipment Cost** = (Area / 1000) × Equipment Rate ($70 per hour)
  - **Waste Factor Adjustment** = 10%
  - **Total Cost** = (1.1) × (Material + Labor + Equipment Costs)
- **UI Panel for Results**: Displays cost breakdown on the right side.

## 🛠️ Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/lotcost-estimator.git
   cd lotcost-estimator
   ```
2. Open Google Earth Engine Code Editor.
3. Copy and paste the JavaScript code into a new script.
4. Run the script to launch the interactive UI.

## 🚀 Usage
1. Enter latitude and longitude.
2. Click **"Go to Location"** to move the map.
3. Click **"Draw Polygon"** and select boundary points.
4. Click **"Compute Area"** to get the cost estimation.
5. View results on the right panel.

## 📷 Logo  
![Project Logo](https://github.com/user-attachments/assets/0b524701-1f11-45cc-98e2-a74caca0be2c)

## 🔗 Technologies Used
- **Google Earth Engine (GEE)**
- **JavaScript (GEE UI API)**
- **USDA NAIP Imagery**
- **Geospatial Analysis**

## 👨‍💻 Author
- **Neeraj Solanky**
- GitHub: [Neeraj-Solanky](https://github.com/Neeraj-Solanky)

## 📜 License
This project is licensed under the MIT License.

