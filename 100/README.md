# 100 - Blue/Green Deployment

In this type of deployment strategy, the new version of the software runs alongside the old version. Note that you can also refer to this as **red/black deployment strategy** in some cases.

Here, the stable or the older version of the application is always **blue or red**, while the newer version is **green or black**.

After the new version has been tested and certified to meet all the requirements, the load balancer automatically switches the traffic from the older version to the newer version.

![Blue-Green-Deployment-Strategy](https://user-images.githubusercontent.com/1499433/177112882-eb503542-48f9-4419-b54a-c2d2f5a5b956.png)

The major advantage of this strategy is that it avails a quick update or rollout of a new application version. However, its main disadvantage is that it is costly because you must run both the new and old versions concurrently. Engineers mostly use this method in mobile app development and deployment.
