DS SAT 2 - EduSpace Campus Facility Utilization Dataset

Files:
facilities.csv  -> facility, type, capacity, block
bookings.csv    -> facility, date, start, end, purpose
occupancy.csv   -> timestamp, facility, count
calendar.csv    -> date, working_day, event, exam_period
maintenance.csv -> facility, issue, downtime

INTENTIONALLY INCLUDED DATA QUALITY CONDITIONS:
1. Missing occupancy readings
2. Duplicate bookings
3. Inconsistent facility names
4. Occupancy above capacity
5. Incomplete maintenance records

Suggested KPI:
Utilization % = Occupancy / Capacity * 100
