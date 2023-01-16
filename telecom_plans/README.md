## Data
 
**The users table (data about users):**
- `user_id` — user id
- `first_name` — username
- `last_name` — last name of the user
- `age` — age of the user (in years)
- `reg_date` — registration date (dd, mm, yy)
- `churn_date` — the date the user stopped using the service (if the value is absent, the plan was in use when this data was generated)
- `city` — user's city of residence
- `plan` — plan name
**The calls table (data about calls):**
- `id` — unique caller ID
- `call_date` — call date
- `duration` — call duration (in minutes)
- `user_id` — the identifier of the calling user
**The messages table (data in text messages):**
- `id` — unique text message identifier
- `message_date` — text message date
- `user_id` — the identifier of the user sending the text message
**The internet table (data about web sessions):**
- `id` — unique session identifier
- `mb_used` — the amount of data spent during the session (in megabytes)
- `session_date` — web session date
- `user_id` — user identifier
**The plans table (data about the plans):**
- `plan_name` — the name of the calling plan
- `usd_monthly_fee` — monthly price in US dollars
- `minutes_included` — monthly package of minutes
- `messages_included` — monthly text message package
- `mb_per_month_included` — data volume package (in megabytes)
- `usd_per_minute` — price per minute after exceeding the package limit (for example, if the package includes 100 minutes, the first excess minute will be charged)
- `usd_per_message` — price per text message after exceeding package limit
- `usd_per_gb` — price per extra gigabyte of data after exceeding the package limit (1 GB = 1024 megabytes)

## Goal
In this project, I carried out an analysis of the behavior of a small selection of customers (500) of a telecommunications company, in relation to the consumption of the year 2018 by the two plans offered by the company.

## Libraries used:

* pandas
* numpy
* seaborn
* matplotlib.pyplot
* scipy.stats