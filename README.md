# IoT-Platforms-Testing


These test scripts are based on the Jmeter load testing application and are used for testing the performance of two platforms Thingsboard and SiteWhere. Scripts simulate several sensors publishing reading to platform server and linked to Prometheus a monitoring platform that collects performance metrics from the IoT platform server. The collected metrics are throughput, response time, CPU load, and memory load. Scripts are used to evaluate the performance of the open-source version of two platforms installed locally in the server. Two protocols are tested HTTP and MQTT.

Results of this evaluation performance test are published in a scientific paper called "Performance Evaluation of Open Source IoT Platforms"

Ismail, Ahmed A., Haitham S. Hamza, and Amira M. Kotb. "Performance evaluation of open source IoT platforms." 2018 IEEE Global Conference on Internet of Things (GCIoT). IEEE, 2018.

https://prometheus.io/docs/introduction/overview/

https://ieeexplore.ieee.org/document/8620130
