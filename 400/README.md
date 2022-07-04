# 400 - Ramped Deployment

The ramped deployment strategy gradually changes the older version to the new version. Unlike canary deployment, the ramped deployment strategy makes its switch by replacing instances of the old application version with the instances from the new application version one instance at a time. You can also call this method the **rolling upgrade deployment strategy**.

When developers replace all instances of the older version, they shut down the older version. The new version then controls the whole production traffic.

![Ramped-Deployment-Strategy](https://user-images.githubusercontent.com/1499433/177114733-20e6b62a-196f-4435-99d1-046e848c2fff.png)

This strategy gives zero downtime and also enables performance monitoring. Nevertheless, the rollback duration is long in case there is an unexpected event. This is because the downgrading process to the initial version follows the same cycle, one instance at a time.
