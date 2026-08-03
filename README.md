# Linux System Monitor 

A simple Bash script that monitors the health of a Linux system by displaying important system information such as CPU usage, memory usage, disk usage, uptime, and the most CPU-intensive processes.

## Features

- Displays hostname and current date
- Shows system uptime
- Monitors CPU usage
- Displays memory usage
- Displays disk usage
- Lists the top CPU-consuming processes
- Performs basic system health checks
- Generates warnings when CPU, memory, or disk usage exceeds 80%

### Technologies Used

- Bash
- Linux
- awk
- grep
- top
- free
- df
- ps

## Project Structure

```
linux-system-monitor/
├── system_monitor.sh
└── README.md
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/<your-username>/linux-system-monitor.git
```

2. Go to the project directory:

```bash
cd linux-system-monitor
```

3. Make the script executable:

```bash
chmod +x system_monitor.sh
```

4. Run the script:

```bash
./system_monitor.sh
```

## Sample Output

```
======================================
       LINUX SYSTEM MONITOR
======================================
Hostname: mypc
Date: Mon Aug 3
Uptime: up 2 hours

CPU Usage: 12%
Memory Usage: 48%
Disk Usage: 35%

CPU Status: OK
Memory Status: OK
Disk Status: OK
======================================
```

## Skills Demonstrated

- Bash scripting
- Linux system administration
- Process monitoring
- Resource monitoring
- Command-line automation
- Text processing with awk and grep

## Future Improvements

- Export reports to a log file
- Email alerts for high resource usage
- Colored terminal output
- Real-time monitoring mode
- Support for multiple Linux distributions

