# Drug Overdose Death Analysis (2015-2024)
## Overview
Comprehensive statistical analysis of provisional drug overdose death records across the United States, examining temporal trends, geographic disparities, and substance-specific mortality patterns to understand the ongoing overdose crisis and identify intervention opportunities.

## Dataset
- 56,243 provisional drug overdose death records spanning 10 years
- Geographic coverage: 41 US states and territories
- Data period: 2015-2024 from VSRR Provisional Drug Overdose Death Counts
- Total deaths analyzed: 292,597,814
- Drug categories: 13 different substance classifications

## Key Analysis Areas
- National and regional temporal trend analysis with year-over-year growth rates
- Geographic comparison across states and regions (Northeast, Midwest, South, West)
- Drug-specific mortality analysis (Synthetic Opioids, Heroin, Cocaine, etc.)
- Seasonal pattern identification and statistical significance testing
- Advanced clustering analysis for state-level drug death patterns
- Recovery pattern analysis post-peak crisis years

## Files
- `drug_overdose_analysis.py` - Complete statistical analysis with correlation and regression methods
- drug_overdose_analysis.pdf - Comprehensive analysis report with findings
- `visualizations` - Generated statistical plots and advanced analysis:
  - `temporal_trends_analysis.png` - Time series and growth rate analysis
  - `geographic_analysis.png` - State and regional heatmaps
  - `drug_specific_analysis.png` - Substance-specific trend analysis
  - `statistical_analysis.png` - Distribution and correlation matrices
  - `clustermap_analysis.png` - State clustering by drug death patterns
  - `facetgrid_analysis.png` - Multi-dimensional regional and drug type analysis
  - `jointplot_analysis.png` - Correlation analysis between synthetic opioids and heroin
  - `pairplot_analysis.png` - Multi-variable relationship analysis

## Major Findings
- Peak crisis year: 2021 with highest recorded mortality rates
- Recent improvement: 2.3% decrease in deaths from 2023 to 2024
- Regional disparities: South region most affected (91.7M deaths), Northeast least affected (56.1M deaths)
- Leading substances: Synthetic Opioids account for 3.4M deaths, highest among all categories
- State leaders: Florida (27.3M deaths), California, and Texas show highest absolute numbers
- Seasonal consistency: No significant seasonal variation in overdose mortality patterns

## Technologies Used
- Python (Pandas, NumPy, SciPy for advanced statistical analysis)
- Visualization libraries (Matplotlib, Seaborn, Plotly for interactive charts)
- Statistical methods: Time series analysis, correlation analysis, clustering algorithms
- Advanced analytics: Facet grids, joint plots, clustermap analysis
- Data processing: Multi-dimensional grouping, growth rate calculations, trend analysis

## Business Impact
Provided evidence-based insights for public health policy development, resource allocation for treatment programs, and targeted intervention strategies to address the overdose crisis at national and regional levels.
