# FTP Load Balancer - Group 13
# Overview
This project aims to provide a robust solution for load balancing FTP (File Transfer Protocol) server requests. The system utilizes a load balancer to evenly distribute incoming FTP requests among multiple FTP servers, ensuring optimal performance, scalability, and fault tolerance.

# Design
Our design consists of three main components:
1. **Load Balancer**: Acts as the entry point for incoming FTP requests. It intelligently distributes these requests across multiple FTP servers based on predefined criteria such as server load, availability, or round-robin.
2. **FTP Servers**: Multiple instances of FTP servers are deployed to handle file transfer requests. These servers are identical in configuration and serve the same purpose, allowing for horizontal scaling as traffic increases.
3. **Configuration Management**: The load balancer maintains a dynamic list of available FTP servers and continuously monitors their health and performance. It adjusts the routing of incoming requests based on real-time metrics to ensure efficient resource utilization.


















# Members 
| Student name | ID |
| -- | -- |
| Nguyễn Lê Minh Đức | BI12-092 |
| Thái Trường Giang | BI12-137 |
| Hoàng Việt Phương | BI12-360 |
| Hoàng Vũ Hải Nam | BI12-290 |
| Đặng Quang Nguyên | BI12-331 |

