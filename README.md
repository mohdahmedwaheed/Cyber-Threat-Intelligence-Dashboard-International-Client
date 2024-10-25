# AI/ML Threat Classification and Incident Response Dashboard
### Author: Mohd Ahmed Waheed
### Tools: Power BI, SQL
### Industry: Cybersecurity
### Client: International Client (Saudi Arabia)
# Overview
This repository showcases a Power BI dashboard created for an international cybersecurity client based in Saudi Arabia. The primary goal of this project was to provide real-time monitoring and threat classification to help the client's security teams swiftly identify and respond to cyber threats. Due to privacy and client confidentiality, the actual dataset cannot be shared; however, this README will provide an in-depth explanation of the dashboard's structure and its key components.

## The insights provided by this dashboard allow the client to:

## Classify attack types
Identify top attacking IP addresses
Track traffic volume during attacks
Respond proactively to potential threats

## Problem Statement
With the increasing number of cyber threats globally, the client required a robust system to monitor and analyze attacks on their infrastructure. This dashboard was designed to offer real-time insights into:

### The types of attacks detected.
The volume and pattern of network traffic during these attacks.
The key attackers (IPs) targeting the client’s network.
How often and when these attacks occur.

The project provides a centralized interface where cybersecurity teams can make data-driven decisions to protect their systems from threats.

## Dashboard Structure
### 1. Attack Type Slicer
This slicer allows users to filter between different types of attacks, including:

DoS (Denial of Service): Helps identify attacks intended to disrupt service by overwhelming the network with traffic.
Generic: Detects more generalized attack patterns.
Normal: Represents typical, non-malicious traffic.
Worms: Tracks worm-based attacks, which self-replicate and spread across systems.
The slicer allows the cybersecurity team to analyze specific attack types in greater detail.

### 2. KPIs (Key Performance Indicators)
Total Logs: Displays the total number of logs processed by the system. This metric provides a snapshot of network activity over the period.

Attack Type Percentages: The dashboard highlights the percentages of different attack types (DoS, Generic, Worms, and Normal) present in the logs, offering a quick view of the most prevalent threats.

### 3. Top 3 Attacker IPs
This table presents the top 3 IP addresses associated with the highest number of attack logs. These IPs are flagged for further investigation, enabling the cybersecurity team to focus on potential high-risk actors.

### 4. Traffic Volume During Attack (Area Chart)
The total bytes and packets exchanged during attacks are visualized over time. These trends help the client:

Analyze how network traffic fluctuates during attack periods.
Detect unusual spikes in traffic that could indicate malicious activities.

### 5. Attack Distribution by Type (Pie Chart)
This pie chart shows the proportion of different attack types, allowing quick identification of the most common threats. This breakdown gives insights into the overall security environment, allowing the client to allocate resources to address the most frequent threats.

### 6. Attack Type by Protocol (Bar Chart)
The bar chart illustrates the connection between attack types and network protocols. It shows which protocols (e.g., TCP or UDP) are commonly used in the detected attacks, helping the team focus on securing vulnerable protocols.

# Insights and Business Value
## Key Business Outcomes:
### 1. Proactive Threat Detection:

The dashboard allows the client's security team to detect threats early by classifying attacks in real-time.
The ability to visualize top attackers and identify patterns enables faster response times and reduces the impact of security incidents.

### 2. Network Traffic Monitoring:

By tracking traffic volume during attacks, the client can understand how malicious actors interact with their systems.
This helps the team pinpoint the intensity of attacks and manage network resources efficiently.

### 3. Enhanced Security Strategy:

Insights from the dashboard guide the client in improving firewall rules, blocking malicious IPs, and securing commonly attacked network protocols.

### 4. Data-Driven Incident Response:

The ability to drill down into specific attack types and protocols allows security teams to prioritize their responses based on the severity and type of threat.

# Challenges and Solutions

## Challenges Faced

1. Data Sensitivity: Client data was highly sensitive, requiring robust privacy measures and restricting data sharing.
2. SQL Server Connectivity: Initial connection issues hindered efficient data access.

## Solutions Implemented

1. Python-Powered SQL Server Integration: Overcame connectivity issues using Python scripting, enabling direct data connection to Power BI.
2. Real-Time Monitoring and Threat Detection: Configured dashboard to pull logs at regular intervals, providing instant insights into cybersecurity threats.
# Technologies Used

## 1. Power BI
    1. Data Connection: Established direct connection to client's SQL server using Python scripting.
    2. Data Visualization: Designed customized dashboards with multiple visuals for:
        1. Attack type analysis
        2. Traffic volume monitoring
        3. Attacker detail insights
        
## 2. SQL and Python
    1. Data Extraction: Utilized Python to extract data from client's SQL database.
    2. Data Transformation: Preprocessed data for analysis and visualization in Power BI.

# Limitations and Future Scope
Data Sharing Restrictions: Due to client privacy concerns, the actual dataset and dashboard files cannot be shared publicly.
Future Enhancements: The dashboard can be expanded to include:
Real-time alerts when certain thresholds (e.g., traffic spikes or specific attack patterns) are reached.
Anomaly detection using machine learning to identify outliers in attack data.

# Conclusion
This AI/ML Threat Classification and Incident Response Dashboard has proven invaluable in helping the client enhance their cybersecurity efforts. The dashboard allows for real-time threat monitoring, detailed analysis of attack patterns, and quick response to mitigate risks.

Feel free to explore the screenshot provided to get an idea of the design and structure of the dashboard. While I cannot share the data, I’m happy to discuss the approach and methodologies used to create this powerful tool for improving cybersecurity defenses.

# Contact Information
For any queries or collaborations, feel free to reach out via LinkedIn or GitHub.
### Your LinkedIn Profile: https://www.linkedin.com/in/mohd-ahmed-waheed-3b1b90175/

