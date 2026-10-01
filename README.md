🍽️ ZeroPlate
AI-Powered Smart Food Waste Reduction & Sustainable Redistribution Platform

Built for Smart India Hackathon 2026 — Problem Statement 26234 Ministry of Food Processing Industries (MoFPI) | Theme: Agriculture, FoodTech & Rural Development

Team 404 The Optimists

Python React PostgreSQL Docker License

</div>
🌍 The Problem

Nearly a third of all food produced globally is wasted — not because it isn't needed, but because institutional kitchens and food processing units have no reliable way to predict demand, catch spoilage early, or redirect surplus food before it's too late.

Today's reality:

Kitchens cook based on guesswork, not real demand
Spoilage is noticed only after food is already unusable
Surplus food that's still safe to eat has no fast way to reach NGOs or shelters
Processing units have no real-time visibility into overproduction or inefficiency

ZeroPlate exists to close that gap — turning food waste from an after-the-fact problem into a before-it-happens prevention system.

💡 What ZeroPlate Does

ZeroPlate is an end-to-end AI platform that predicts, detects, and acts — automatically.

Module	What it does
🔮 AI Demand Forecaster	Predicts meals/food needed 1–3 days ahead using historical consumption patterns
📷 Spoilage Detection Engine	Computer vision + sensor data classifies food as Fresh / Near-Expiry / Spoiled in real time
🔗 Automated Redistribution Matching	Instantly connects surplus food with the nearest NGO/shelter based on location and capacity
📊 Sustainability Dashboard	Tracks meals saved, carbon footprint reduced, water footprint saved, and landfill diversion rate
🏭 Processing Unit Monitor	Tracks overproduction %, machine downtime, and energy usage for food processing units

The core loop, in one line:

A kitchen has extra food → ZeroPlate detects it → finds the nearest NGO that needs it → sends an alert — automatically, before the food goes bad.

🧱 System Architecture
Kitchen / Processing Unit Data + Sensor / Image Input
                    │
                    ▼
        AI Demand Forecasting Engine
        (flags overproduction risk)
                    │
                    ▼
        Spoilage / Surplus Detection
         (CV model + sensor thresholds)
                    │
                    ▼
        Automated NGO Matching Engine
       (nearest recipient + route estimate)
                    │
                    ▼
            Alert & Pickup Trigger
         (SMS / WhatsApp notification)
                    │
                    ▼
          Sustainability Dashboard
        (impact metrics updated live)
🛠️ Tech Stack

Frontend

React.js + Tailwind CSS — dashboard & interactive UI
Mapbox / Leaflet.js — live redistribution map

Backend

Python + FastAPI — APIs, business logic, model serving

AI / ML

XGBoost / Prophet — demand forecasting
Lightweight CNN (MobileNet-based) — food freshness image classification

Database

PostgreSQL — kitchen, NGO, and surplus event records

Alerts & Integrations

Twilio API / WhatsApp Business API — automated notifications

Deployment

Docker — containerized services
AWS / GCP — cloud hosting
