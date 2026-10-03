**Hotel Booking Demand Analysis**

This project supports the 6001CMD Machine Learning assignment. It examines hotel booking data and demonstrates preprocessing for a future cancellation prediction model.

**Dataset**

Source: https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand

The dataset contains 119,390 booking records and 32 columns.

The target is `is_canceled`:
- 0: Not cancelled
- 1: Cancelled

**What the Notebook Does**

- Shows dataset dimensions, hotel counts and arrival dates.
- Examines cancellation counts and percentages.
- Checks missing values and repeated rows.
- Examines numerical distributions, skewness and correlations.
- Checks unusual room rates and guest counts.
- Demonstrates missing-value imputation, feature creation, categorical encoding and numerical standardisation.

Preprocessing settings are calculated from training data only and then applied to test data. No predictive model is trained.

**How to Run**

1. Download hotel_booking_analysis.ipynb from this repository.
2. Open Google Colab: https://colab.research.google.com/
3. Select File → Open notebook → Upload and choose the notebook.
4. Run the cells from top to bottom.
5. When prompted, upload `hotel_bookings.csv`, downloaded from Kaggle.

If the Colab runtime resets, upload the CSV again and rerun the cells.
