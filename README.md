<img src="imgs/wso2.jpg" width="250">

# Running WSO2 Products on Containerization Platforms
The Guide of Best Practices and Recommendations

## Table of Contents
- ### [1. Building a container image](https://github.com/wso2/container-guide)
    * [1.1. Why should you choose Docker as your container runtime ?](https://github.com/wso2/container-guide)
    * [1.2. Using WSO2 images](https://github.com/wso2/container-guide)
    * [1.3. Building from source](https://github.com/wso2/container-guide)
    * [1.4. Tips to harden your image](https://github.com/wso2/container-guide)
    * [1.5. Tips on Tagging](https://github.com/wso2/container-guide)
    * [1.6. Vulnerability scanning and container security check](https://github.com/wso2/container-guide)
    * [1.7. Image signing and Verification](https://github.com/wso2/container-guide)

- ### [2. Pushing your image to a container registry](https://github.com/wso2/container-guide)
    * [2.1. Why should you have your own private registry ?](https://github.com/wso2/container-guide)
    * [2.2. How to secure your private registry ?](https://github.com/wso2/container-guide)
    * [2.3. Scanning and Auditing](https://github.com/wso2/container-guide) 

- ### [3. Deploying into production](https://github.com/wso2/container-guide)
    * [3.1. Why do you need a container orchestrator ?](https://github.com/wso2/container-guide)
    * [3.2. Why should you choose Kubernetes ?](https://github.com/wso2/container-guide)
    * [3.3. Kubernetes Vs. OpenShift ?](https://github.com/wso2/container-guide)
    * [3.4. Helm as package manager](https://github.com/wso2/container-guide) 
    * [3.5. Supporting Infrastructure](https://github.com/wso2/container-guide)
    * [3.6. Resource Allocation](https://github.com/wso2/container-guide)
    * [3.7. Deployment definition tips](https://github.com/wso2/container-guide) 
    * [3.8. Managing configurations](https://github.com/wso2/container-guide)  
    * [3.9. Managing keystores, certificates and other artifacts](https://github.com/wso2/container-guide/blob/master/deploy/Managing_Keystores_And_Truststores.md)
    * [3.10. Managing databases](https://github.com/wso2/container-guide)
    * [3.11. Production deployment tips](https://github.com/wso2/container-guide)
    * [3.12. Managing security](https://github.com/wso2/container-guide)

- ### [4. Storage](https://github.com/wso2/container-guide)
    * [4.1. Why do we need storage for WSO2 products ?](https://github.com/wso2/container-guide)
    * [4.2. Recommended storage options for WSO2 products](https://github.com/wso2/container-guide)
    * [4.3. Storage binding tips](https://github.com/wso2/container-guide)
    * [4.4. Storage type and size](https://github.com/wso2/container-guide)

- ### [5. Routing](https://github.com/wso2/container-guide/README.md)
    * [5.1. Exposing your application to outside](https://github.com/wso2/container-guide/blob/master/route/Routing.md#exposing-your-application-to-outside)
    * [5.2. Configuring hostnames](https://github.com/wso2/container-guide/blob/master/route/Routing.md#configuring-hostname)
    * [5.3. Configuring SSL](https://github.com/wso2/container-guide/blob/master/route/Routing.md#configuring-ssl)
    * [5.4. DNS mapping](https://github.com/wso2/container-guide/blob/master/route/Routing.md#dns-mapping)
    * [5.5. Tips on Session Affinity](https://github.com/wso2/container-guide/blob/master/route/Routing.md#tips-on-session-affinity)

- ### [6. Scaling your deployment](https://github.com/wso2/container-guide)
    * [6.1. What is scaling ?](https://github.com/wso2/container-guide/blob/master/scale/Scaling_Deployments.md#what-is-scaling?)
    * [6.2. When do we need to scale ?](https://github.com/wso2/container-guide/blob/master/scale/Scaling_Deployments.md#when-do-we-need-to-scale?)
    * [6.3. Scaling metrics](https://github.com/wso2/container-guide/blob/master/scale/Scaling_Deployments.md#scaling-metrics)
    * [6.4. Scaling strategies](https://github.com/wso2/container-guide/blob/master/scale/Scaling_Deployments.md#scaling-strategies)
    * [6.5. Scaling WSO2 product profiles](https://github.com/wso2/container-guide/blob/master/scale/Scaling_Deployments.md#scaling-wso2-product-profiles)

- ### [7. Propagating Updates](https://github.com/wso2/container-guide)
    * [7.1. When do we need to update ?](https://github.com/wso2/container-guide/blob/master/update/Propagating_Updates.md#when-do-we-need-to-update?)
    * [7.2. Simplest way to perform an update](https://github.com/wso2/container-guide/blob/master/update/Propagating_Updates.md#simplest-way-to-perform-an-update)
    * [7.3. Achieve zero downtime](https://github.com/wso2/container-guide/blob/master/update/Propagating_Updates.md#achieve-zero-downtime)

- ### [8. Publishing Logs](https://github.com/wso2/container-guide)
    * [8.1. Why do we need centralized logging ?](https://github.com/wso2/container-guide)
    * [8.2. Centralized logging with EFK](https://github.com/wso2/container-guide)
    * [8.3. Logging storage and Backup](https://github.com/wso2/container-guide)  

- ### [9. Monitoring and Alerting](https://github.com/wso2/container-guide)
    * [9.1. Why do we need metrics monitoring](https://github.com/wso2/container-guide)
    * [9.2. Metrics monitoring with Prometheus and Kibana](https://github.com/wso2/container-guide)
    * [9.3. Prometheus operator and exporters](https://github.com/wso2/container-guide)
    * [9.4. Alertmanager Integration with Prometheus](https://github.com/wso2/container-guide)
    * [9.5. Monitoring storage and Backup](https://github.com/wso2/container-guide)

- ### [10. Development and Testing](https://github.com/wso2/container-guide)
    * [10.1. Planning your non-production environments](https://github.com/wso2/container-guide)
    * [10.2. Kubernetes Vs. Openshift way of execution](https://github.com/wso2/container-guide)

- ### [11. Maintenance](https://github.com/wso2/container-guide)
    * [11.1. Importance of CI/CD](https://github.com/wso2/container-guide)
    * [11.2. WSO2 Kubernetes Pipeline](https://github.com/wso2/container-guide)

- ### [12. A deployment checklist in summary](https://github.com/wso2/container-guide)
    * [12.1. Building a container image](https://github.com/wso2/container-guide)
    * [12.2. Pushing your image to a container registry](https://github.com/wso2/container-guide)
    * [12.3. Deploying into production](https://github.com/wso2/container-guide)
    * [12.4. Scaling your deployment](https://github.com/wso2/container-guide)
    * [12.5. Propagating updates](https://github.com/wso2/container-guide)
    * [12.6. Publishing and analysing logs](https://github.com/wso2/container-guide)
    * [12.7. Monitoring and Alerting](https://github.com/wso2/container-guide)
    * [12.8. Disaster Recovery](https://github.com/wso2/container-guide)
    * [12.9. Development and Testing](https://github.com/wso2/container-guide)
    * [12.10. Maintenance](https://github.com/wso2/container-guide)

- ### [13. Appendix](https://github.com/wso2/container-guide)