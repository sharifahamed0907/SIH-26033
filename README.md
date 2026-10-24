# Smart India Hackathon Workshop
# Date: 24.10.2026
## Reference Number: 26019459
## Name: SHARIF AHAMED.S

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution:

Detailed explanation:

A mobile and web marketplace where farmers and FPOs list produce and sell directly to consumers, restaurants, retailers and bulk buyers. The platform handles pricing, logistics, payments and quality grading in one place, so no middlemen are needed.

How it addresses the problem:

1.Farmers set or accept transparent prices instead of taking whatever the mandi trader offers.

2.Consumers buy at a lower price because the intermediary margins are removed.

3.Pooled pickups and AI-planned routes cut transport cost and spoilage.

4.Digital payments go straight to the farmer’s bank account (UPI/DBT).

Innovation and uniqueness:

1.AI demand forecasting tells farmers what to grow and when to sell.

2.Fair-price engine that compares live mandi rates (Agmarknet) with demand and suggests a price.

3.Route optimization that bundles nearby farmers’ produce into shared trucks.

4.Voice-based, multilingual app for low-literacy farmers.

5.Quality grading from a photo, so buyers trust the listing.

## Technical Approach
Technologies:

1.Frontend: React Native (mobile), React (web)

2.Backend: Django/Python with REST APIs, PostgreSQL

3.AI/ML: scikit-learn and Prophet/LSTM for demand forecasting, OR-Tools for route optimization, a 

4.CNN (TensorFlow/PyTorch) for produce quality grading

5.Others: Google Maps API, UPI payment gateway, SMS/WhatsApp alerts, speech-to-text for regional languages, AWS/GCP cloud hosting

6.Data sources: Agmarknet, e-NAM, weather APIs

Methodology and process:

1.Farmer/FPO registers and lists produce with quantity, photo and location.

2.AI grades quality and suggests a fair price.

3.Consumers or bulk buyers place orders.

4.The system pools orders by area and plans the best pickup and delivery route.

5.Logistics partner collects, delivers, and payment is released to the farmer.

6.Ratings and sales data feed back into the forecasting model.

<img width="791" height="361" alt="image" src="https://github.com/user-attachments/assets/93efc09f-e93e-4e87-a101-e6e50085d110" />

<img width="390" height="844" alt="1  Farmer lists produce@1x" src="https://github.com/user-attachments/assets/76c6ba3a-bdb9-4455-8839-a340efd14ac2" />

<img width="390" height="844" alt="2  AI grade and fair price@1x" src="https://github.com/user-attachments/assets/b3804e08-6ac7-4c12-85d9-f65ff4a2f9f9" />

<img width="390" height="844" alt="3  Buyer order and tracking@1x" src="https://github.com/user-attachments/assets/f23fc7b4-a355-4290-a63b-a103584d68a8" />


## Feasibility and Viability
Feasibility:

1.Needed data (mandi prices, weather) is already available through public APIs.

2.Smartphone and UPI use is growing fast in rural India.

3.FPOs already aggregate farmers, which gives an easy entry point.

4.A small commission (a few percent) keeps the platform sustainable and far cheaper than middlemen.

Challenges and risks:

1.Low digital literacy among farmers

2.Cold chain and last-mile delivery gaps

3.Quality disputes and buyer trust

4.Farmers’ habit of selling to known traders

5.Price and demand fluctuations

Strategies to overcome them:

1.Voice-first regional language UI and training through FPOs and local agents

2.Partnering with existing logistics and cold storage providers, starting with pilot districts

3.Photo-based grading, ratings and an easy return/refund policy

4.Starting with FPO onboarding, then scaling out

5.Forecasting plus minimum price alerts to reduce risk

## Impact and Benefits

Impact on the target audience:

1.Farmers/FPOs: higher income, faster payment, and knowledge of what the market wants.

2.Consumers: fresher produce at lower prices.

3.Bulk buyers: reliable supply and traceability.

Benefits:

1.Social: rural empowerment, financial inclusion, and transparency.

2.Economic: better farmer margins, lower consumer prices, and less supply chain inefficiency.

3.Environmental: less food waste, fewer transport trips, and lower emissions from optimized routes.

## Research and References
1.e-NAM (National Agriculture Market): enam.gov.in

2.Agmarknet (mandi price data): agmarknet.gov.in

3.ONDC (Open Network for Digital Commerce): ondc.org

4.Kisan Rath app (farm logistics, Government of India)

5.SFAC and NABARD publications on FPOs

6.Google OR-Tools (route optimization): developers.google.com/optimization

7.Facebook Prophet (time series forecasting): facebook.github.io/prophet
