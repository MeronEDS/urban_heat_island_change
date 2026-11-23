# urban_heat_island_change
This capstone examines whether the green corridor initiatives in Addis Ababa have changed land use, urban heat and the distribution of green infrastructure.

### Data information 

this data is pretend data just for the practice of this assignment as i am figuring out to access all my real dat from satellite images

### Data Cleaning

What I did:

1. Fixed station IDs so they all use the same format (e.g. `st01` → `ST01`).
2. Reshaped the temperature data (`temperature_raw.csv`) from wide to long format, so each row is one station and month.
3. Reshaped the weather station data (`weather_station_raw.csv`) so each row is one station and year.
4. Replaced missing value codes (`-99` and blanks) with `NA`.
5. Joined the two datasets using `station_id` and `year` to create one tidy dataset.



AI Disclosure 
AI tools (Claude, by Anthropic) were used to correct grammar and improve the clarity of the text, and referred when there were errors in codes
