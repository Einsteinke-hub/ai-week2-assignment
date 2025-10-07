# SDG 11: Public Transport Optimization Using Machine Learning

## Problem Statement
This project addresses **SDG 11: Sustainable Cities and Communities** by optimizing public transport routes using machine learning. The specific problem focuses on reducing urban congestion, improving accessibility, and minimizing environmental impact through data-driven route planning.

## Machine Learning Approach
- **Unsupervised Learning**: K-means clustering to identify distinct area types based on transport characteristics
- **Supervised Learning**: Linear regression to predict travel demand
- **Clusters Identified**: 200 distinct urban area types
- **Key Algorithms**: K-means clustering, Linear Regression, PCA for visualization

## Results and Impact

### Technical Performance
- Clustering Quality: Silhouette score of 0.111
- Prediction Accuracy: R² = 0.9997 on travel demand prediction
- Areas Analyzed:  synthetic urban areas

### Key Findings
- Identified 1400 distinct area types with unique transport needs
- High-density urban areas require high-frequency metro services
- Low-density areas benefit from flexible, on-demand services
- Demographic factors significantly influence transport patterns

### Sustainability Impact
- **Annual CO₂ Reduction**:19,038.4 tons
- **Fuel Savings**:10,153,808 liters annually  
- **Population Served**:984,927  people
- **Areas Optimized**:200 urban areas

## Ethical Considerations

### Data Bias Mitigation
- Synthetic data designed to represent diverse demographic groups
- Explicit consideration of elderly and student populations
- Income-level analysis to ensure equitable service recommendations

### Fairness and Accessibility
- Recommendations include senior-friendly vehicles and low-floor buses
- Affordable fare structures for lower-income communities
- Special services for areas with high student populations
- Multi-modal integration for comprehensive accessibility

### Sustainability Alignment
- Direct contribution to SDG 11 targets for sustainable urban mobility
- Reduced environmental impact through optimized routing
- Promotion of public transport over private vehicle usage

## Conclusion
This project demonstrates how machine learning can support sustainable urban planning by providing data-driven insights for public transport optimization. The approach balances technical efficiency with social equity and environmental sustainability, creating a framework for smarter, more inclusive cities.
