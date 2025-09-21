# Fake-Food-Review-Detector
Our project solves the problem of fake or promotional restaurant reviews that often mislead customers. Many reviews online are not written by real diners but by marketing campaigns or bots, making it hard for people to trust them. To address this, we built a simple system that automatically analyzes and flags suspicious reviews.

# Fake Food Review Detector (AWS Hackathon MVP)

## How it works
- Upload reviews dataset (CSV).
- AWS Lambda + Amazon Comprehend analyze reviews.
- Rules detect fake reviews (promo keywords, short text, lack of details).
- Results stored in S3 and shown on frontend.

## Architecture
- Frontend: S3 Static Website
- API Gateway: Entry point
- Lambda: Analysis logic
- Amazon Comprehend: AI for sentiment & phrases
- S3: Data storage

## Demo
1. Open frontend.
2. Upload dataset.
3. Click Run Analysis.
4. Get FAKE / REAL review results.
