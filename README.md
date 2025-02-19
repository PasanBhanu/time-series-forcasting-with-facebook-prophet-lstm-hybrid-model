# Code Repository of Journal Article - Time series forecasting-based Kubernetes autoscaling using Facebook Prophet and Long Short-Term Memory

This repository contain the python codes created for the work of the journal article "Time series forecasting-based Kubernetes autoscaling using Facebook Prophet and Long Short-Term Memory" by Pasan Bhanu Guruge ([@PasanBhanu](https://github.com/PasanBhanu)) and Y.H.P.P. Priyadarshana ([@CyraxSector](https://github.com/CyraxSector)).

Read Paper: https://www.frontiersin.org/journals/computer-science/articles/10.3389/fcomp.2025.1509165/full

## Abstract

The advancement of cloud computing technologies has led to increased usage in application deployment in recent years. Kubernetes, a widely used container orchestration platform for deploying applications on cloud systems, provides benefits such as autoscaling to adapt to fluctuating workload while maintaining quality of service and availability. In this research, we designed and evaluated a proactive Kubernetes autoscaling using Facebook Prophet and Long Short-Term Memory (LSTM) hybrid model to predict the HTTP requests and calculate required pod counts based on the Monitor-Analyze-Plan-Execute loop. The proposed model not only captures seasonal data patterns effectively but also proactively predicts the pod requirements for timely and efficient resource allocation to reduce resource wastage while enhancing cloud computing applications. The proposed hybrid model was evaluated using real-world datasets from NASA and the Federation Internationale de Football Association (FIFA) World Cup to benchmark and compare with existing literature. Evaluation results indicate that the proposed novel hybrid model outperforms single-model proactive autoscaling by a maximum margin of 65–90% accuracy when compared to NASA and FIFA World Cup datasets. This study contributes to the fields of cloud computing and container orchestration by providing a refined proactive autoscaling mechanism that enhances application availability, efficient resource usage, and reduced costs and paves the way for further exploration in increased prediction speed, integrated with vertical scaling and implementations using Kubernetes.

## Citation

Guruge PB and Priyadarshana YHPP (2025) Time series forecasting-based Kubernetes autoscaling using Facebook Prophet and Long Short-Term Memory. Front. Comput. Sci. 7:1509165. doi: 10.3389/fcomp.2025.1509165

## Other Related Repositories

The used datasets, NASA-HTTP and WorldCup98 datasets were preprocessed and shared in,
https://github.com/PasanBhanu/time-series-forcasting-benchmark-dataset-preprocessing

Integration of the models to Kubernetes via KEDA development is available in,
https://github.com/PasanBhanu/proactive-autoscaler-for-keda-kubernetes

Sample application used for API testing in Kubernetes is available in,
https://github.com/PasanBhanu/springboot-sample-api-with-prometheus
