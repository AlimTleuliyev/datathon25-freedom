# Хакатон НУ 2025 - Freedom Broker Customer Analytics

## Overview
Customer analytics project for Freedom Broker - analyzing client behavior, onboarding effectiveness, and building customer segments based on activity, assets, and acquisition channels.

## Project Goals
- Create customer segmentation methodology 
- Analyze onboarding funnel and identify drop-off points
- Test hypothesis: Does acquisition channel affect onboarding success?
- Build portraits of most valuable clients
- Provide actionable recommendations for CJM improvement

## Data Files
- `body_users.csv` - User demographics and acquisition data
- `user_segment_slice.csv` - User segmentation data
- `users_events_slice_*.csv` - User activity events (6 files)
- `event_types.csv` - Event categories reference
- `channels*.csv` - Acquisition channel data
- `onboarding.csv` - Onboarding process data

## Analysis Notebooks
- `eda.ipynb` - Exploratory data analysis
- `segment_eda.ipynb` - Segmentation analysis
- `onboarding_akonya.ipynb` - Onboarding funnel analysis

## Key Deliverables
1. Customer segmentation with 12 identified segments
2. Onboarding funnel visualization with bottlenecks
3. Acquisition channel effectiveness analysis
4. Customer portraits and recommendations
5. Business value justification

## Event Categories
- Registration, Account Opening, Authorization
- Orders (Trading), Fund Movements, Academy
- Media Activity, Profile Management
- Account Deletion