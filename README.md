**Edmunds Forum Car Discussion Scraper & Brand Analysis**

This project scrapes and analyzes consumer discussions from the Edmunds automotive forums to understand brand perception, competitive dynamics, and consumer preferences within the entry-level luxury performance sedan market.

Using Selenium for web scraping and a combination of NLP and statistical techniques, the project extracts thousands of user comments and analyzes:

- Word frequency patterns

- Brand mention popularity

- Brand co-mentions and competitive relationships

- Attribute associations (e.g., performance, luxury)

- Aspirational sentiment toward different car brands

The goal is to simulate how an automotive company or analyst might use unstructured online discussion data to inform marketing strategy, positioning, and product decisions.


**Data Source**

Website: Edmunds Forums

Forum Topic: Entry-Level Luxury Performance Sedans

Content: User-generated forum posts including usernames, timestamps, and comment text

Volume: ~8,000 scraped comments across multiple forum pages

Project Structure
```
├── project1-1.ipynb          # Main notebook (scraping + analysis)
├── car_models_and_brands.csv # Mapping of car models to brands
├── sample data.csv           # Sample forum data (for testing)
├── car_data.csv              # Scraped forum data (optional export)
└── README.md                 # Project documentation
```

**Key Takeaways**

Online forum data can reveal real consumer perceptions not captured by surveys.

Lift and co-mention analysis are powerful tools for competitive intelligence.

Performance and luxury dominate buyer conversations in this segment.

Aspirational sentiment provides a lens into brand equity and future demand.

