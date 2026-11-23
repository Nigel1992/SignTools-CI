[![Discord](https://img.shields.io/discord/1468295714961494029?color=7289da&label=Join%20Our%20Discord&logo=discord&logoColor=white&style=for-the-badge)](https://discord.gg/UbPRh74PzV)


[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Nigel1992)

# SignTools CI

This is a free and simple builder for [SignTools](https://github.com/SignTools/SignTools). It uses a Continous Integration (CI) provider to pull, sign, and upload any iOS apps to your `SignTools`.

The following providers are supported:

- [GitHub Actions](https://docs.github.com/en/actions)
- [Semaphore CI](https://semaphoreci.com/)

You only need to configure one provider.

## Repository setup

First you need to create your own `SignTools-CI` repository:

1. Create a GitHub account
2. Click on the `Use this template` button at the top of this page
3. Give the new project a name and set the visibility to `Private`
4. Create the new project

Alternatively, you can also manually clone this repo into a new private repository.

## Provider setup

You now need to configure a CI provider. **You only need one**:

> ### :warning: Developer accounts are only supported on GitHub Actions for now!

### GitHub Actions

1. [Open](https://github.com/settings/tokens/new) the Personal access token generation page
2. Select (grant) the `workflow` scope
3. Generate the token

This is the token you need for your `SignTools` service's builder configuration.

### Semaphore CI

1. Register for [SemaphoreCI](https://semaphoreci.com/) and create an organization
2. At the top of the organization dashboard, click on `Create New`
3. On the page that opens, press `Choose repository`
4. Authorize SemaphoreCI's app to access your GitHub private repositories in order to see the builder you just created
5. Back on SemaphoreCI's new project page, you will see your builder repository - click on it
6. Proceed with `Continue to workflow setup`, then click `I will use the existing configuration`
7. Go to `Manage Settings` of that repository
8. At the bottom of the page that opens, set `What to build` to `Do not build this project (Pause project)`

[View](https://me.semaphoreci.com/account) your API Token. This is the token you need for your `SignTools` service's builder configuration.

## 💖 Support the Project

I build this project in my free time and don't need donations for myself. If you'd like to give something back, I'd kindly ask you to donate to a charity of your choice instead — they need it far more than I do. If you still prefer to support me directly in private, thank you so much; it's genuinely appreciated, and I'll be happy to list you as a donor on GitHub and, where applicable, in a donors section of the project, as a small thank you.

[![Ko-Fi](https://img.shields.io/badge/Ko--Fi-Support%20me-FF5E5B?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/nigel1992)
[![PayPal](https://img.shields.io/badge/PayPal-Donate-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.com/donate/?hosted_button_id=KYV9ARF99ZSCE)
