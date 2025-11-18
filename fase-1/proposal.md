# Case Title  
**Running Shoe Recommender for Nordic Consumers**

## Background  
Finding the right running shoes is difficult for many people. Reviews are scattered across websites, “best in test” lists often contradict each other, and it’s hard to know which shoes fit different foot types (narrow, normal, wide), running surfaces, and budgets.  

Most online lists include shoes that aren't available in Scandinavia or require international shipping, which makes the search more frustrating.  

There is a clear need for a simple, Nordic-focused platform that recommends popular running shoes based on real user needs.

## Purpose  
The purpose of this application is to help runners in Norway and Scandinavia quickly find running shoes that match their preferences.  

By filtering based on foot width, running surface, experience level, and budget, the app provides actionable, trustworthy recommendations using a curated list of the most popular and widely available models.

## Target Users  
- Everyday runners in Norway, Sweden, and Denmark  
- Beginner to intermediate runners looking for guidance  
- Runners with specific needs (wide feet, narrow feet, injury prevention)  
- Shoppers who want shoes available from Nordic retailers (XXL, Löplabbet, Zalando, Sportamore)

## Core Functionality (MVP)

### Must Have  
- Filter panel for:  
  - Running surface (road, trail)  
  - Foot width (narrow, normal, wide)  
  - Preferences (soft cushioning, stability, lightweight)  
  - Budget range  
- Database with a curated list of ~20–30 popular running shoes available in Scandinavia  
- Shoe results displayed as cards (brand, model, price range, tags)  
- “Best in Test” highlighting based on curated sources  
- Simple frontend web interface (React + local JSON data)

### Nice to Have (Future)  
- Price comparison across stores (XXL, Zalando, Sportamore)  
- Auto-updated prices via APIs or scraping  
- Additional categories:  
  - Trail running shoes  
  - Hiking/mountain shoes  
  - Football shoes  
  - Gym/training shoes  
- AI chatbot: *“Find my perfect shoe”*  
- User review summaries (aggregated from review sites)  
- Admin dashboard to update shoe database  

## Data Requirements

### Initial MVP Data (Manual Entry)  
For each shoe:  
- Brand  
- Model  
- Foot width compatibility (narrow/normal/wide)  
- Running type: road or trail  
- Best for: easy runs, tempo, recovery, etc.  
- Price range (manual or occasionally scraped)  
- “Best in Test” tags  
- Review tags: *soft*, *stable*, *responsive*, etc.  
- Store availability (XXL, Zalando, Sportamore, Löplabbet)

### Future Expanded Data  
- Real-time pricing  
- Live stock availability  
- User reviews  
- Links to retailer pages  

## User Stories  
1. *As a beginner runner, I want to find shoes for asphalt that won’t hurt my feet so I can run comfortably.*  
2. *As a runner with wide feet, I want to filter only shoes that fit my foot type so I don’t waste time.*  
3. *As a price-conscious shopper, I want to see where the shoe is cheapest in Scandinavia.*  
4. *As a trail runner, I want to see which shoes are best-rated for terrain (future feature).*  

## Technical Constraints  
- MVP should run entirely locally or as a simple static web app (React + JSON)  
- No live API integrations needed initially  
- Data collection must avoid scraping from websites that block scraping  
- App must load fast and work smoothly on mobile  
- Easy to expand later with more shoe categories  

## Success Criteria  
- Users can filter running shoes based on their needs and see relevant results  
- Shoe data is accurate and limited to models available in Scandinavia  
- UI loads in under 2 seconds  
- At least 20 popular running shoe models are included  
- System is modular and easy to expand with more categories (trail, hiking, football, gym)