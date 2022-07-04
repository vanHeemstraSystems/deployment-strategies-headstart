# 200 - Canary Deployment

In canary deployment, the deployment team sets up the new version and then gradually shifts the production traffic from the older version to the newer version. For example, at a point in time during the deployment process, the older version might retain 90% of all traffic for the software while the newer version hosts 10% of the traffic. This deployment technique helps the DevOps engineers test the stability of the new version. It uses live traffic from a subset of the end-users at different levels that varies as production occurs.

![Canary-Deployment-Strategy](https://user-images.githubusercontent.com/1499433/177113401-e3a7fbab-52fa-436e-906c-aa03aad32f81.png)

Canary deployment enables better performance monitoring. It also aids in a faster and better rollback of the software if the new version fails. However, it has a slow nature and a more time-consuming deployment cycle.
