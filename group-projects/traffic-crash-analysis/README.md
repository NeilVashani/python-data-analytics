# Traffic Crash Data Analysis (2012-2024)
## Overview
Comprehensive geospatial and temporal analysis of traffic crash incidents with interactive dashboard development, investigating spatial patterns, environmental factors, and demographic influences to support evidence-based traffic safety policies and urban planning interventions.

## Dataset
- 51,162 traffic crash records spanning 12 years
- Geographic coverage: Latitude 33.3199 to 33.4585, Longitude -111.9791 to -111.8774
- Data period: 2012-01-01 to 2024-03-15
- Total injuries: 23,439, Total fatalities: 161
- Average injuries per crash: 0.46

## Key Analysis Areas
- Interactive geospatial crash density mapping and hotspot identification
- Severity analysis with categorical classification (No Injury, Minor, Moderate, Severe)
- Temporal pattern analysis across hours, days, months, and seasons
- Environmental conditions impact (weather, lighting, surface conditions)
- Driver demographics analysis (age, gender, substance involvement)
- Fatal crash clustering and geographic concentration patterns

## Files (All dashboards are fully interactive Plotly visualizations, click to open in a new tab)
- analysis.py - Main geospatial analysis script
- interactive-dashboards/ - 9 HTML visualization files
  - [Crash Factors Heatmap](https://neilvashani.github.io/python-data-analytics/group-projects/01-traffic-crash-analysis/interactive-dashboards/crash_factors_heatmap.html)
  - [Geographic Distribution](https://neilvashani.github.io/python-data-analytics/group-projects/01-traffic-crash-analysis/interactive-dashboards/crash_geographic_distribution.html)
  - [Temporal Patterns](https://neilvashani.github.io/python-data-analytics/group-projects/01-traffic-crash-analysis/interactive-dashboards/crash_temporal_patterns.html)
  - [Demographics Analysis](https://neilvashani.github.io/python-data-analytics/group-projects/01-traffic-crash-analysis/interactive-dashboards/demographics_visualization.html)
  - [Density Map](https://neilvashani.github.io/python-data-analytics/group-projects/01-traffic-crash-analysis/interactive-dashboards/density_map_visualization.html)
  - [Hotspots Analysis](https://neilvashani.github.io/python-data-analytics/group-projects/01-traffic-crash-analysis/interactive-dashboards/hotspots_visualization.html)
  - [Severity Mapping](https://neilvashani.github.io/python-data-analytics/group-projects/01-traffic-crash-analysis/interactive-dashboards/severity_map_visualization.html)
  - [Temporal Analysis](https://neilvashani.github.io/python-data-analytics/group-projects/01-traffic-crash-analysis/interactive-dashboards/temporal_analysis_visualization.html)
  - [Weather Impact Analysis](https://neilvashani.github.io/python-data-analytics/group-projects/01-traffic-crash-analysis/interactive-dashboards/weather_analysis_visualization.html)
- README.md - Project documentation

## Major Findings
- Peak crash periods: Midnight hours (0:00) with Friday showing highest frequency
- Identified 15 major crash hotspots predominantly at intersections and highway entry/exit points
- Weather paradox: Clear conditions show most crashes (exposure factor), fog increases head-on collisions by 280%
- Demographic risk factors: Drivers 16-24 have 1.8x higher serious crash involvement
- Geographic concentration: Fatal crashes cluster at high-traffic intersections and interchanges

## Technologies Used
- Python (Pandas, NumPy, Plotly for interactive visualizations)
- Geospatial analysis with density mapping and hotspot identification
- Statistical analysis for temporal pattern recognition
- Interactive dashboard development with hover information and filtering
- Advanced data cleaning and categorical variable processing

## Business Impact
Provided critical insights for traffic safety policy development, infrastructure improvement prioritization, and targeted enforcement strategies to reduce crash frequency and severity.
