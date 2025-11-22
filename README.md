# Network Traffic / Anomaly Detection Dashboard

This project is a **SOC Analyst portfolio dashboard** built in Splunk to monitor network traffic events and detect anomalies such as unusual host activity, event spikes, and total event counts.

## Panels Included

1. **All Network Events**  
   Displays all network events captured for monitoring unusual activity.

2. **Top Hosts by Event Count**  
   Highlights hosts generating the most network events. Useful for spotting high-activity or suspicious machines.

3. **Host vs Event Count Heatmap**  
   Visualizes host activity over time, helping to identify unusual patterns or spikes.

4. **Recent Events Timeline**  
   Shows event trends over time, useful for detecting spikes or abnormal activity periods.

5. **Total Event Count (KPI)**  
   Quick KPI displaying the total number of events captured for monitoring purposes.

## Tools Used

- **Splunk**  
- **Windows / Web / Network Logs**

## How to Use

1. Download or clone this repository.  
2. Import the `network_traffic_dashboard.xml` file into Splunk to view the dashboard.  
3. Screenshots are included below for reference.

---

### Screenshots

#### First Three

<img width="1907" height="1075" alt="All Panels Screenshot" src="https://github.com/user-attachments/assets/0a286120-1b88-47eb-b369-b66a270b4e1a" />

#### Last Two

<img width="1915" height="1072" alt="Panel Detail Screenshot" src="https://github.com/user-attachments/assets/4ce828f5-6aef-416d-a24d-8bc204337ebf" />

---

**Portfolio Tip:**  
Even with small datasets, combining table, chart, heatmap, timeline, and KPI panels creates a **professional-looking SOC dashboard** suitable for a GitHub portfolio showcase.
