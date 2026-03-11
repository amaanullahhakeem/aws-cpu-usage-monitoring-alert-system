# AWS CloudWatch Infrastructure Alerting System: CPU Utilization Monitor

# Descriptio:

This project demonstrates an automated monitoring and alerting pipeline for cloud infrastructure. Using Python, Amazon CloudWatch, and Amazon SNS, the system detects performance bottlenecks and notifies administrators in real-time when system health thresholds are breached.

Key Technical Components:

1. Infrastructure: Deployed an Amazon EC2 instance to host the monitoring script and application environment.

2. Performance Stress Testing: Developed a Python utility (cpu-spike.py) designed to simulate high-compute workloads, pushing CPU utilization beyond an 80% threshold.

3. Automated Monitoring: Configured a CloudWatch Alarm to track real-time metrics, specifically watching for sustained high CPU usage over a 5-minute period.

4. Real-time Notification: Integrated Amazon Simple Notification Service (SNS) to trigger automated email alerts, ensuring immediate visibility into infrastructure status once the threshold is crossed.
