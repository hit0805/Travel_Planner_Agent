# Travel Planner Agent

An **AI-powered travel planning assistant** that generates **personalized itineraries** based on your **destination, budget, interests, and real-time weather**.  
Built using **IBM watsonx.ai**, **IBM Granite Foundation Model**, **IBM Agent Lab**, and the **Weather Company Data API**.

## Features
- **Personalized Itinerary Generation** – Tailored to user budget, preferences, and trip duration.
- **Real-Time Weather Integration** – Plans adjust to forecasted conditions.
- **Budget-Aware Recommendations** – Suggests affordable hotels, restaurants, and activities.
- **Interactive Chatbot Interface** – Easy-to-use conversation-based trip planning.
- **Extensible** – Future integration with flight/hotel bookings.

## Technologies Used
- **IBM watsonx.ai Studio** – For LLM prompt engineering.
- **IBM Granite Model** – Generates trip itineraries.
- **IBM Agent Lab** – Chatbot interface.
- **Weather Company Data API** – Real-time weather forecast.

##  How It Works
1. **User** provides:
   - Destination
   - Travel dates
   - Budget
   - Interests
2. **Agent** fetches **real-time weather** for the destination.
3. **Granite Model** generates a **day-by-day itinerary**.
4. Itinerary includes:
   - Hotels
   - Activities
   - Transportation
   - Weather summary
   - Cost estimate


## Example Output
**Input:** 
Plan a 5-day trip to Tokyo from October 10–15, 2025 for $2,500. I like culture, food, and city exploration. Weather forecast: 18°C–24°C, rain on Day 2.


**Output:**
- **Day 1:** Arrival, evening food tour.
- **Day 2:** Indoor museums & cultural activities (rain).
- **Day 3:** Outdoor sightseeing – Asakusa, Ueno Park.
- **Day 4:** Day trip to Mt. Fuji.
- **Day 5:** Shopping, departure.


## Future Scope
- Integrate **real-time hotel & flight booking**.
- **Multi-city itinerary planning**.
- **Voice-enabled** planning.
- **Offline itinerary access**.
- **Multi-language support**.


