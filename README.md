# AQI Analysis 🌬️

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-1.3+-green.svg)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-1.21+-blue.svg)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4+-red.svg)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.11+-purple.svg)](https://seaborn.pydata.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Data](https://img.shields.io/badge/Data-3357_records-brightgreen.svg)](#dataset)
[![Analysis](https://img.shields.io/badge/Analysis-Complete-success.svg)](#analysis)

## 🎯 Overview

This repository contains a comprehensive analysis of Air Quality Index (AQI) data across various monitoring stations in India. The analysis explores air pollution patterns, pollutant levels, and geographic variations in air quality across different states and cities.

## 📁 Repository Structure

```
AQI_Analysis/
├── AQI_Analysis.ipynb             # Main analysis notebook
├── data/                          # Dataset directory
├── .gitignore                     # Git ignore file
└── README.md                      # This file
```

## 📊 Dataset

The dataset contains **3,357 records** of air quality measurements with the following features:

| Column | Description |
|--------|-------------|
| `country` | Country name (India) |
| `state` | State name (Bihar, West Bengal, etc.) |
| `city` | City name where monitoring station is located |
| `station` | Monitoring station name and authority |
| `last_update` | Last update timestamp |
| `latitude` | Geographic latitude coordinate |
| `longitude` | Geographic longitude coordinate |
| `pollutant_id` | Type of pollutant measured |
| `pollutant_min` | Minimum pollutant value |
| `pollutant_max` | Maximum pollutant value |
| `pollutant_avg` | Average pollutant value |

### Pollutant Types
- **PM2.5**: Fine particulate matter (≤ 2.5 micrometers)
- **PM10**: Coarse particulate matter (≤ 10 micrometers)
- **SO2**: Sulfur dioxide
- **CO**: Carbon monoxide

### Geographic Coverage
- **States**: Bihar, West Bengal, and other Indian states
- **Cities**: Multiple cities including Kolkata, Katihar, Motihari, Siliguri
- **Monitoring Stations**: Various BSPCB and WBPCB stations

## 🔧 Technologies Used

- **Python 3.8+**: Programming language
- **Jupyter Notebook**: Interactive development environment
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib**: Data visualization
- **Seaborn**: Statistical data visualization

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3.8+ installed on your system.

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Alibubere/AQI_Analysis.git
cd AQI_Analysis
```

2. Install required packages:
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook AQI_Analysis.ipynb
```

## 📈 Analysis

The notebook includes comprehensive analysis covering:

### 🔍 Data Exploration
- Dataset overview and structure
- Missing values analysis
- Data types and distributions
- Geographic data validation

### 🌬️ Air Quality Analysis
- Pollutant level distributions
- PM2.5 vs PM10 comparisons
- SO2 and CO level analysis
- Air quality index calculations

### 📍 Geographic Analysis
- State-wise air quality comparison
- City-level pollution patterns
- Monitoring station coverage
- Geographic hotspots identification

### 📊 Statistical Insights
- Pollutant correlation analysis
- Temporal patterns (if applicable)
- Extreme value analysis
- Regional air quality rankings

### 📋 Monitoring Station Analysis
- Station distribution across regions
- Data quality assessment
- Coverage analysis by pollutant type

## 🎯 Key Findings

> **Note**: Run the notebook to discover insights about:
> - Most polluted cities and states
> - Pollutant level variations across regions
> - Air quality patterns and trends
> - Geographic distribution of monitoring stations
> - Correlation between different pollutants

## 📝 Usage

1. Open the Jupyter notebook
2. Run cells sequentially to reproduce the analysis
3. Modify parameters to explore different aspects of the data
4. Create your own visualizations and insights
5. Export results for further analysis

## 🤝 Contributing

Contributions are welcome! Please feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

- **Author**: Mohammad Ali Bubere
- **Email**: alibubere989@gmail.com
- **Project Link**: https://github.com/Alibubere/AQI_Analysis

## 🙏 Acknowledgments

- Dataset source: [Dataset](dataset.txt)
- Thanks to BSPCB and WBPCB for air quality monitoring data
- Inspiration from environmental data analysis projects
- Indian air quality monitoring authorities

## 📚 Additional Resources

- [Air Quality Index Information](https://www.airnow.gov/aqi/aqi-basics/)
- [WHO Air Quality Guidelines](https://www.who.int/news-room/feature-stories/detail/what-are-the-who-air-quality-guidelines)
- [Central Pollution Control Board](https://cpcb.nic.in/)

---

⭐ **Star this repository if you found it helpful!** ⭐