# 🌍 GastroGlobe – Weather-Aware Foodie Tour Generator

## 🚀 Overview
**GastroGlobe** is a delightful workflow built on **Julep** that generates a foodie tour for any list of cities by:
- Checking today’s weather to decide indoor/outdoor dining
- Selecting 3 iconic local dishes per city
- Finding top-rated restaurants serving those dishes
- Crafting a breakfast-lunch-dinner story to enjoy in each city

## 💡 How It Works
1. **Weather Fetch**: Uses Open-Meteo API to get weather for each city.
2. **Dining Decision**: Decides indoor or outdoor dining based on weather code.
3. **Dish Selector**: Looks up 3 iconic dishes from a static database.
4. **Restaurant Finder**: Uses mock restaurant data (Yelp can be integrated if needed).
5. **Narrative Generator**: Produces a human-friendly foodie tour.

## 🔨 Built With
- **Julep** workflows
- **Open-Meteo API** (no key needed)
- **Static JSON** for local dishes and restaurant data

## 📂 Files Included
| File | Description |
|------|-------------|
| `gastroglobe_workflow.json` | Full Julep workflow definition |
| `dishes_db.json` | City → Dishes mapping |
| `mock_restaurant_data.json` | Dish → Restaurant mapping |
| `example_output.json` | Sample foodie tours |
| `README.md` | Project explanation |

## ✨ Creative Touches
- Emoji-enhanced meal descriptions 🍽️
- Indoor/outdoor contextual dining modes 🏡☀️
- Modular: easily extendable to real APIs or dietary filters

## 🧪 Try It On Julep
1. Sign into your [Julep Dashboard](https://julep.ai)
2. Import `gastroglobe_workflow.json`
3. Set input cities (e.g. `['Mumbai', 'Paris']`)
4. Run and explore the foodie journey!

## 📝 Submission
Submit this project by uploading:
- Your GitHub link (with this repo)
- Your Julep API key (if needed for workflow demo)

👉 [Submit Here](https://julep.ai)

## 🧠 Bonus Ideas
- Add Google Maps links to restaurants 📍
- Add vegetarian/vegan filter 🌱
- Integrate real Yelp/Foursquare APIs 🔎

## 🤝 Support
Got stuck? Ask in [Julep Discord](https://discord.gg/julep) or [Book a 1:1 with Anas](https://cal.com/anas)

---
Made with 🍜 by Aditya Singh
