# 🚍 Transjakarta Passenger Data Analysis

This project explores, analyzes, and visualizes customer journey data from the Transjakarta Bus Rapid Transit system in Jakarta, Indonesia. The dataset contains anonymized tap-in and tap-out records, including user demographics, travel behavior, and revenue data. It aims to uncover insights about peak hour traffic, route popularity, user segmentation, and more, to support better operational and marketing strategies.

## 📁 Dataset Overview

The dataset consists of 22 fields that capture the essential details of each passenger transaction. Here's a description of each column:

| Column Name         | Description |
|---------------------|-------------|
| **transID**         | Unique transaction ID for every ride taken by a customer. |
| **payCardID**       | Unique identifier for a customer’s transit card (used for both entry and exit). |
| **payCardBank**     | The name of the bank that issued the customer’s transit card. |
| **payCardName**     | The name embedded on the customer’s card (anonymized). |
| **payCardSex**      | Gender information derived from the card (e.g., Male, Female). |
| **payCardBirthDate**| Customer's birth year (used to calculate age). |
| **corridorID**      | Unique ID representing a specific Transjakarta route or corridor. |
| **corridorName**    | Full name of the route/corridor, showing origin and destination stops. |
| **direction**       | Route direction: `0` = Go (outbound), `1` = Back (inbound). |
| **tapInStops**      | Stop ID where the passenger tapped in (entry). |
| **tapInStopsName**  | Stop name where the passenger tapped in. |
| **tapInStopsLat**   | Latitude coordinate of the entry stop. |
| **tapInStopsLon**   | Longitude coordinate of the entry stop. |
| **stopStartSeq**    | Stop sequence number based on the direction of the route. |
| **tapInTime**       | Date and time the passenger tapped in (entered the system). |
| **tapOutStops**     | Stop ID where the passenger tapped out (exit). |
| **tapOutStopsName** | Stop name where the passenger tapped out. |
| **tapOutStopsLat**  | Latitude coordinate of the exit stop. |
| **tapOutStopsLon**  | Longitude coordinate of the exit stop. |
| **stopEndSeq**      | Stop sequence number on exit. |
| **tapOutTime**      | Date and time the passenger tapped out (exited the system). |
| **payAmount**       | Fare paid by the passenger. Some rides may be free due to discounts or passes. |

Dashboard Link : https://public.tableau.com/views/Transjakarta_17536689726740/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link 
