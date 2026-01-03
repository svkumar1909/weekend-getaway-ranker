# Weekend Getaway Ranker

I built this project to understand how recommendation systems can be designed
using simple data engineering techniques without jumping directly into machine learning.

The system suggests weekend travel destinations from a given source city
based on distance, rating, and popularity.

## How it Works
1. User provides a source city
2. Distance to other destinations is calculated using latitude and longitude
3. Places within 300 km are considered suitable for weekend trips
4. Destinations are ranked using a weighted score

## Scoring Factors
- Google rating (45%)
- Popularity based on reviews (35%)
- Distance suitability (20%)

Weights were tuned manually based on practicality.

## Technologies Used
- Python
- Pandas

## Dataset
Travel Dataset – India’s Must-See Places (Kaggle)

## How to Run
```bash
pip install -r requirements.txt
python weekend_ranker.py
