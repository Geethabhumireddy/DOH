# DOH
The main objective of this project is to deploy DoH within an application and capture benign as well as malicious DoH traffic as a two-layered approach to detect and characterize DoH traffic using time-series classifier.

This project uses the following Machine Learning classification algorithms: Naive Bayes, KNN, Decision Tree, Random Forest, Gradient Boost.

The final dataset includes implementing DoH protocol within an application using five different browsers and tools and four servers to capture Benign-DoH, Malicious-DoH and non-DoH traffic. Layer 1 of the proposed two-layered approach is used to classify DoH traffic from non-DoH traffic and layer 2 is used to characterize Benign-Doh from Malicious-DoH traffic. The browsers and tools used to capture traffic include Google Chrome, Mozilla Firefox, dns2tcp, DNSCat2, and Iodine while the servers used to respond to DoH requests are AdGuard, Cloudflare, Google DNS, and Quad9.

![image](https://github.com/user-attachments/assets/30a4c67f-49bf-47e8-b493-0acc261d1c97)
