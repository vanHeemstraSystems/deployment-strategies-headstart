# 500 - Shadow Deployment

In this deployment strategy, developers deploy the new version alongside the old version. However, users can’t access the new version immediately. Just as the name suggests, the latest version hides in the shadows. Developers send a fork or copy of the requests the old version receives to the shadow version to test how the new version will handle the requests when live.

![Shadow-Deployment-Strategy](https://user-images.githubusercontent.com/1499433/177115173-3966ae3b-7e24-4414-8000-8cf03a2076b7.png)

This technique is very complex, and as such, the DevOps engineer should be careful so that the forked traffic does not create a duplicate live request since two versions of the same system are running.

Shadow deployment lets engineers monitor system performance and conduct stability tests. But it’s expensive and complex to set up and can create serious issues.
