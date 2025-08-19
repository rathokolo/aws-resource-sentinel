# AWS Resource Sentinel

A Python-based monitoring tool that simulates AWS resource usage, triggers alerts, and logs system health. Built for learning and philosophical exploration of fairness, thresholds, and system integrity.

## Features
- Usage threshold detection
- Critical alert simulation
- Auto-scaling trigger logic
- Ethical imbalance detection

## How to Run
bash
# Clone the repository
git clone https://github.com/rathokolo/aws-resource-sentinel.git
cd aws-resource-sentinel

# Run the main script
python sentinel.py
⚙️ Configuration
You can adjust thresholds, scaling logic, and ethical parameters in config.py. Example:

python
THRESHOLD_CPU = 80  # percent
THRESHOLD_MEMORY = 75  # percent
ENABLE_ETHICAL_CHECKS = True

Sample Output
Code
[INFO] CPU usage: 82% — Threshold breached
[ALERT] Auto-scaling triggered
[ETHICS] Detected imbalance: Resource allocation favors Node A disproportionately

Philosophy Behind the Code:
This project isn't just about simulating AWS—it’s about interrogating the assumptions behind system design. What counts as “fair” in resource allocation? How do thresholds reflect human bias? Can a dashboard tell the truth?

Technologies Used:
Python 3.10+

Logging module

Simulated AWS-like logic (no actual cloud resources used)

📁 Folder Structure
Code
aws-resource-sentinel/
├── sentinel.py          # Main simulation logic
├── config.py            # Thresholds and ethical parameters
├── utils.py             # Helper functions
├── logs/                # Output logs
└── README.md            # You're reading it!

Future Enhancements:
Real-time dashboard with Power BI or Streamlit

Integration with AWS CloudWatch (for real deployments)

Peer-reviewed fairness metrics

GitHub Actions for automated testing

Contributing
Pull requests are welcome! If you have ideas for improving the simulation logic or philosophical framing, let’s collaborate.

License:
MIT License. Use freely, reflect deeply.
