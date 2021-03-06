# 300 - Recreate Deployment

In this deployment strategy, the dev team shuts down the old version of the application entirely, deploys the new version, and then reboots the whole system. This deployment technique creates a system downtime between shutting down the old software and booting the new one.

It is cheaper and mainly used when the software firm wants to change the application from scratch. It doesn’t require a load balancer as there’s no shifting of traffic from one version to another in the live production environment.

![Recreate-Deployment-Strategy](https://user-images.githubusercontent.com/1499433/177114564-c396c638-e6f4-408a-8674-e803e68e6d92.png)

But this strategy dramatically affects the end users due to the downtime. Users must wait until the application goes live again to use the software. As a result, not many developers use this strategy unless they have no other choice.
