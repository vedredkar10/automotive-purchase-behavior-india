# Indian Automotive Consumer Insights
**Triangulated Mixed-Methods Analysis of Car Purchase Decisions**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Research](https://img.shields.io/badge/Type-Academic%20Research-blue)](https://github.com/topics/academic-research)
[![Python](https://img.shields.io/badge/Python-3.11+-green)](https://www.python.org/)
[![R](https://img.shields.io/badge/R-Statistical%20Analysis-red)](https://www.r-project.org/)

## Research Overview

This project investigates factors influencing automotive purchase decisions in India through **innovative triangulated methodology**, integrating survey analysis, social media sentiment analysis, and sales performance validation. The study identifies five key consumer preference factors and validates their predictive power across multiple data sources.

**Key Achievement**: Strong correlation between social media sentiment and actual sales performance (r=0.785, p<0.001), demonstrating the predictive validity of digital consumer expressions for market outcomes.

## Research Methodology

### Three-Phase Triangulated Approach
1. **Phase 1**: Survey-based factor analysis (n=102) using EFA/CFA/SEM
2. **Phase 2**: Twitter sentiment analysis (7,233 tweets) using fine-tuned RoBERTa models
3. **Phase 3**: Sales correlation validation (2018-2024 market data)

### Key Findings
- **Five Significant Factors**: Brand perception, financial considerations, price sensitivity, safety concerns, service quality
- **Sentiment-Sales Correlation**: Strong positive relationship (r=0.785) validates social media as market predictor
- **Brand Insights**: Maruti Suzuki leads both sentiment (+35.6%) and market share, while Toyota shows sentiment-sales disconnect

## Technical Implementation

### Statistical Analysis
- **Structural Equation Modeling** for factor validation
- **Exploratory/Confirmatory Factor Analysis** for construct identification  
- **Bootstrap resampling** for robustness testing
- **Multi-method correlation analysis** for triangulation

### Natural Language Processing
- **Transformer Models**: RoBERTa, BERTweet, BERT-base, DistilBERT, DeBERTa v3
- **Best Performance**: Twitter-optimized RoBERTa (72.25% accuracy)
- **Text Analytics**: TF-IDF, word clouds, sentiment heatmaps
- **Brand-Factor Analysis**: Comprehensive linguistic pattern mapping

### Data Integration
- **Survey Data**: Google Forms with screening logic
- **Social Media**: 18,243 tweets → 7,233 after quality filtering
- **Sales Data**: 7,346 monthly records from Team-BHP (2018-2024)
- **Final Dataset**: 14 automotive brands with complete coverage

## Key Results

### Consumer Preference Factors (Standardized Path Coefficients)
- **Brand Perception**: β=0.394 (strongest predictor)
- **Financial Considerations**: β=0.281
- **Price Sensitivity**: β=0.213
- **Safety Concerns**: β=0.206
- **Service Quality**: β=0.183

### Brand Sentiment Rankings
| Rank | Brand | Net Sentiment | Market Performance |
|------|-------|---------------|-------------------|
| 1    | Maruti Suzuki | +35.6% | Leader (10.8M units) |
| 2    | Hyundai | +6.1% | Strong (3.7M units) |
| 3    | MG | -1.2% | Growing |
| ...  | ... | ... | ... |
| 14   | Toyota | -36.7% | Disconnect (good sales) |

## Business Impact

### Strategic Insights
- **Brand equity** emerges as most critical purchase driver
- **Social media sentiment** reliably predicts market performance
- **Cultural factors** require adaptation of Western consumer models
- **Service quality concerns** present industry-wide opportunity

### Market Implications
- Domestic brands show superior cultural resonance
- Electric vehicle acceptance remains cautious (56.9% moderate interest)
- Compact SUV preference dominates (51.0% of respondents)
- Financial accessibility critical in price-sensitive market

## Methodological Contributions

### Academic Innovation
- **Triangulated validation** across stated preferences, digital sentiment, and actual behavior
- **Cultural adaptation** of Western consumer decision models for Indian market
- **Integration methodology** for survey, social media, and sales data
- **Sentiment-performance framework** for automotive market analysis

### Technical Achievements
- Rigorous data quality protocols (39.6% retention rate)
- Multi-transformer model evaluation and selection
- Bootstrap validation for small-sample robustness
- Factor structure validation across multiple analytical approaches
