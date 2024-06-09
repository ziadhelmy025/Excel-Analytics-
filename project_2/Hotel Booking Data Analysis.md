# Hotel Booking Data Analysis

---

## Introduction
This project aims to analyze the booking data of a mid-sized hotel to understand the financial impacts across different booking channels and improve channel strategy to enhance profitability. The analysis is based on a set of predefined questions to provide deep insights into financial performance and operations.

## Data
The dataset includes the following columns:
- BookingID
- BookingDate
- CheckInDate
- CheckOutDate
- Channel
- RoomType
- RoomRate Per Nights
- Nights
- Revenue
- CommissionPercentage
- CommissionAmount
- Profit

## Analysis Questions
1. How many reservations?
2. How many bookings by the number of nights?
3. What are the total revenues, commissions, and profits?
4. What is the average revenue per reservation?
5. What is the average booking per day?
6. What are the seasonality and trends by quarters and months?
7. What is the profit by channels?
8. What is the profit by room type?

## Analysis Steps
1. **Calculate Revenue for each booking**:
   - Revenue = RoomRate Per Nights * Nights

2. **Calculate Commission for each booking**:
   - CommissionAmount = Revenue * (CommissionPercentage / 100)

3. **Calculate Profit for each booking**:
   - Profit = Revenue - CommissionAmount

4. **Add a new column for Revenue in the dataset**:
   - Add a "Revenue" column using the formula above.

5. **Analyze the number of bookings by the number of nights**:
   - Create a bar chart showing the number of bookings for each number of nights.

6. **Analyze average revenue per reservation**:
   - Calculate the average revenue by dividing the total revenue by the number of bookings.

7. **Analyze average booking per day**:
   - Calculate the average daily bookings by dividing the total number of bookings by the number of days in the specified period.

8. **Analyze revenues and seasonality trends**:
   - Create line and bar charts showing revenues by months and quarters.

9. **Analyze profit by channels**:
   - Create a bar chart showing revenues and profit for each booking channel.

10. **Analyze profit by room type**:
    - Create a bar chart showing revenues and profit for each room type.

## Analysis Results

### Charts:
1. **Revenue by Month**:
   - The chart shows fluctuating revenues throughout the year, with significant peaks in August and February.

2. **Revenue by Quarter**:
   - The chart shows high revenues in Q3, with a notable decline in Q4.

3. **Revenue by Channel**:
   - Travel Agents generate the highest revenue, followed by Direct bookings, and then Online Travel Agents (OTA).

4. **Revenue by Room Type**:
   - Suites generate the highest revenue, followed by Deluxe rooms, and Standard rooms.

## Recommendations
1. **Increase focus on peak months**:
   - Boost marketing and promotional offers in August and February.

2. **Analyze reasons for Q3 peak**:
   - Study seasonal factors and special events contributing to high revenues.

3. **Enhance strategies in Q1 and Q4**:
   - Develop special offers to boost bookings during these periods.

4. **Encourage direct bookings**:
   - Offer exclusive discounts and improved booking experience for direct customers.

5. **Improve relations with Online Travel Agents (OTAs)**:
   - Provide competitive offers and enhance hotel visibility on their platforms.

6. **Focus on Suite rooms**:
   - Market Suites more aggressively and offer premium services to attract customers.

7. **Offer promotional packages for Deluxe rooms**:
   - Provide bundles with additional benefits to attract more customers.

8. **Enhance services in Standard rooms**:
   - Offer additional services at a reasonable price to make these rooms more attractive.

## Summary
This analysis provides deep insights into the hotel's financial performance across different channels, enabling management to make informed decisions to enhance profitability and improve operations.

---

## How to Use the Dataset

1. **Open the file in Excel**.
2. **Add the "Revenue" column**:
   - Use the formula: `=C2 * D2` in the "Revenue" column.
3. **Add the "CommissionAmount" column**:
   - Use the formula: `=E2 * (F2 / 100)` in the "CommissionAmount" column.
4. **Add the "Profit" column**:
   - Use the formula: `=E2 - G2` in the "Profit" column.
5. **Create charts**:
   - Use Excel's chart tools to create the required charts based on the data.

By following these steps, the hotel can effectively analyze its data and make strategic decisions to improve financial performance and operations.
