# Project Helping Material 
---

> In the main IP (1X.Y.8.0/23), replace the variable X and Y with the last four digits of the team leader’s student ID (SID)

Leader's ID is **1220175**

Therfore the main IP is **101.75.8.0/23**

---

### Number of Hosts for Each Subnetwork

| Subnetwork | Network     | Number of Hosts |
|------------|-------------|-----------------|
| NET0-A     | Core        | 2               |
| NET0-B     | Core        | 2               |
| NET0-C     | Core        | 2               |
| NET1-A     | University  | 60              |
| NET1-B     | University  | 60              |
| NET2       | Street      | 30              |
| NET3       | Home        | 20              |
| NET4       | Datacenter  | 15              |

---
### 📊 Subnetting Plan Table

| Network      | Subnetwork | Network IP     | CIDR | Broadcast IP   | First Host IP    | Last Host IP     |
|--------------|------------|----------------|------|----------------|------------------|------------------|
| University   | NET1-A     | 101.75.8.0     | /26  | 101.75.8.63    | 101.75.8.1       | 101.75.8.62      |
| University   | NET1-B     | 101.75.8.64    | /26  | 101.75.8.127   | 101.75.8.65      | 101.75.8.126     |
| Street       | NET2       | 101.75.8.128   | /27  | 101.75.8.159   | 101.75.8.127     | 101.75.8.158     |
| Home         | NET3       | 101.75.8.160   | /27  | 101.75.8.191   | 101.75.8.161     | 101.75.8.190     |
| Datacenter   | NET4       | 101.75.8.192   | /27  | 101.75.8.223   | 101.75.8.193     | 101.75.8.222     |
| Core         | NET0-A     | 101.75.8.224   | /30  | 101.75.8.226   | 101.75.8.225     | 101.75.8.226     |
| Core         | NET0-B     | 101.75.8.228   | /30  | 101.75.8.231   | 101.75.8.229     | 101.75.8.230     |
| Core         | NET0-C     | 101.75.8.232   | /30  | 101.75.8.235   | 101.75.8.233     | 101.75.8.234     |
