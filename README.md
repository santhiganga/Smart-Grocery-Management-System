# Smart Grocery Management System (Streamlit + MySQL)

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-1.28.0-red)
![License](https://img.shields.io/badge/License-MIT-green)
![Last Updated](https://img.shields.io/badge/Last%20Updated-2025--03--24-brightgreen)

A data-driven grocery inventory and analytics system built using Python, Streamlit, and MySQL. 
The application helps manage inventory, track sales, and visualize insights through interactive dashboards.

## a) Features

### 1) Dashboard & Analytics
- Real-time inventory tracking
- Warehouse utilization metrics
- Order fulfillment statistics
- Supply chain performance indicators
- Interactive data visualizations

### 🗺2) Inventory Management
- Multi-warehouse optimization
- Geographic distribution mapping
- Cost-effective allocation algorithms
- Real-time route visualization

### 3) Order Tracking Management
- Order tracking and status updates
- Priority-based fulfillment
- Delivery deadline monitoring
- Automated allocation suggestions

### 4) Database Integration
- Capacity utilization tracking
- Stock level monitoring
- Storage cost optimization
- Location-based analytics

### 5) Stock Alerts
- Supplier performance metrics
- Reliability scoring
- Lead time tracking
- Quality assessment

## b) Getting Started

### Prerequisites
- Python 3.9 or higher
- pip package manager
- Git (optional)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/santhiganga/Smart-Grocery-Management-System.git
cd project-name
pip install -r requirements.txt
streamlit run app.py
   ```

2. Create and activate virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the application:
   ```bash
   streamlit run src/app.py
   ```

## c) Project Structure
```
logitrack/
├── src/
│   ├── app.py              # Main Streamlit application
│   ├── backend/
│   │   ├── __init__.py
│   │   ├── data_loader.py  # Data handling and processing
│   │   └── optimizer.py    # Optimization algorithms
│   └── utils/
│       └── helpers.py      # Utility functions
├── data/
│   ├── sample_warehouses.csv
│   ├── sample_sales.csv
│   └── other sample data...
├── tests/
│   └── test files...
├── docs/
│   └── documentation files...
├── requirements.txt
├── README.md
└── LICENSE
```

## d) Usage

1. **Login:** Enter your credentials to access the system.
2. **Data Source:** Choose between:
   - Sample data
   - Upload your data (CSV)
   - Database connection
3. **Navigation:** Use the sidebar to access different features:
   -Expiry tracking
   -Distance-based supplier selection
   -Daily revenue chart
   -CSV upload for products
   -Search/filter products

## e) Data Format

### Warehouse Data (CSV)
```
warehouse_id,name,capacity,current_stock,location,storage_cost,latitude,longitude
W001,Mumbai Central,10000,7500,Mumbai,1200,19.0760,72.8777
W002,Singapore Hub,15000,12000,Singapore,1500,1.3521,103.8198
```

### Order Data (CSV)
```
order_id,date,product_id,quantity,delivery_deadline,status,delivery_latitude,delivery_longitude
ORD001,2025-03-24,P001,500,2025-03-26,Pending,19.0760,72.8777
ORD002,2025-03-24,P002,750,2025-03-25,Urgent,1.3521,103.8198
```

## f) Configuration
The system supports various configuration options:
- Database connections (MySQL, PostgreSQL, SQLite)
- Optimization parameters
- Visualization preferences
- Time zone settings

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch:
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/AmazingFeature
   ```
5. Open a Pull Request

## License
This project is licensed under the MIT License - see the LICENSE file for details.

**Author - Santhi Ganga**
