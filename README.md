# ČVUT Container

A fork of [github.com/filip2cz/better-contain-microsoft.git](https://github.com/filip2cz/better-contain-microsoft.git), a fork of [Microsoft Container](https://github.com/jschenke488/contain-microsoft), a fork of [Facebook Container](https://github.com/mozilla/contain-facebook).

**Note:** To learn more about Containers in general, see [Firefox Multi-Account Containers](https://support.mozilla.org/kb/containers).

## How does ČVUT Container work?

The Add-on keeps ČVUT sites in a separate Container, so you do not mix up your personal cookies with ČVUT cookies. When you first install the add-on, it signs you out of Microsoft and deletes the cookies that Microsoft uses to track you on other websites.

Every time you visit ČVUT sites, it will open in its own container, separate from other websites you visit. You can login to ČVUT within its container.

## How do I enable ČVUT Container?

We’ve made it easy to take steps to protect your privacy so you can go on with your day.

1. [Install ČVUT Container](https://addons.mozilla.org/cs/firefox/addon/better-microsoft-container/). This will log you out of ČVUT and delete the cookies.
2. Open ČVUT site and use it like you normally would. Firefox will automatically switch to the ČVUT Container tab for you.

To learn more about how Mult-Account Containers work, see our support page at [Firefox Multi-Account Containers](https://addons.mozilla.org/firefox/addon/multi-account-containers/).

## Building

### Install web-ext
```bash
npm install --global web-ext
```

### Build
```bash
web-ext build
```

Build is now in `.\web-ext-artifacts\`
