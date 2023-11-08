# FreeCodeCamp Salon Appointment Scheduler Challenge Solution
The submission for freecodecamp's Salon Appointment Scheduler

## What is the challenge?
Creating the required database `salon`, with 3 tables inside `customers`, `appointments` and `services`.
The main objective of the challenge is to create an interactive bash script that logs Salon appointments for a given service requested by users that stores appointment and customer data.

## The submission requirements
- Creating `salon`, and three tables `customers`, `appointments` and `services` DB within a terminal session using psql
- Populate the `services` table with five columns given in the exemple.txt file.
- Create a `salon.sh` script. The script must display a numbered list of the services you offer before the first prompt for input, each with the format ``#) <service>``
- The script should prompt users to enter a service_id, phone number, a name if they aren’t already a customer, and a time. The script must read informations into variables named `SERVICE_ID_SELECTED`, `CUSTOMER_PHONE`, `CUSTOMER_NAME`, and `SERVICE_TIME`
## Contents of the Repo
- The resulting DB contents dumped in `salon.sql` using `pg_dump` CLI utility
- Bash script used to log the Salon Appointments `salon.sh`.
- exemple.txt file used to populate `services` table and write the text of the script.

