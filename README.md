🏥 Healthcare Appointment No-Show Analysis


📌 Overview
Analysis of 110,000+ medical appointment records from Brazil to identify key drivers of patient no-shows and recommend strategies to improve attendance rates.


🎯 Business Problem
Hospital no-shows waste clinical resources and delay patient care. This project identifies which patients are most likely to miss appointments — enabling smarter reminder strategies and scheduling optimization.


📊 Dataset
Source: Kaggle — Medical Appointment No Shows
Size: 110,000+ records × 14 features
Target: No-show flag (1 = missed, 0 = attended)


🔧 Tools
Python | Pandas | Matplotlib | Seaborn | Scikit-learn | Jupyter
⚙️ Features Engineered
waiting_days, age_group, waiting_bucket, same_day flag,
has_chronic flag, is_returning flag, appointment_weekday,
scheduled_month, total_visits


📈 Key Findings
Overall no-show rate: ~20%
Waiting 30+ days = highest no-show risk
Young Adults (18-35) miss appointments most
Same-day appointments = lowest no-show rate
SMS reminders show paradoxical effect — needs redesign


💡 Recommendations
Multi-touch reminders for patients waiting 30+ days
WhatsApp/app reminders for 18-35 age group
Priority slots for returning patients
Redesign SMS strategy based on patient risk score
Flag first-time patients for extra follow-up

👤 Author
Shivakumar V K | shivakumarkadagad25@gmail.com
