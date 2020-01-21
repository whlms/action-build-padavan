# action-build-padavan
build padavan router firmwares with github actions

![](https://github.com/whlms/Padavan-build/workflows/Build%20Padavan/badge.svg)

# Thanks

## Padavan-build by chongshengB

github: <https://github.com/chongshengB/Padavan-build>

right: <https://www.right.com.cn/forum/thread-1673645-1-1.html>

## Actions-OpenWrt by P3TERX

github: <https://github.com/P3TERX/Actions-OpenWrt>

blog: <https://p3terx.com/archives/build-openwrt-with-github-actions.html>

# Github Actions

## Configuring a workflow

Refers:
- [Configuring a workflow](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/configuring-a-workflow)

## trigger events

Refers:
- [Events that trigger workflows](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/events-that-trigger-workflows)
- [Workflow syntax for GitHub Actions#on](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/workflow-syntax-for-github-actions#on)

## checkout action
Refers:
- [Using the checkout action](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/configuring-a-workflow#using-the-checkout-action)
- [the checkout action](https://github.com/actions/checkout)

## Adding a workflow status badge to your repository

![](https://github.com/whlms/actions-test/workflows/actions%20test/badge.svg)

Refers:
- [Adding a workflow status badge to your repository](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/configuring-a-workflow#adding-a-workflow-status-badge-to-your-repository)

Example using a workflow name
```
![](https://github.com/actions/hello-world/workflows/Greet%20Everyone/badge.svg)
```
Example using a workflow file path
```
![](https://github.com/actions/hello-world/workflows/.github/workflows/main.yml/badge.svg)
```