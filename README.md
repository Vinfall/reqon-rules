# Reqon Ruleset

Reqon is a fork of *[Request Control](https://github.com/tumpio/requestcontrol)*,
an extension to control HTTP requests. Provides front-end for Firefox
[webRequest.onBeforeRequest](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/API/webRequest/onBeforeRequest)
API for HTTP request management.

This repository contains additional rules which you can subscribe in the `Import` tab since (unreleased) version 1.16.0a1 of *Request Control* and all versions of *Reqon*.

You can find a few examples in [rules](./rules/) and the `Import` tab of Reqon extension.
The exported config *per se* is also a valid example, you can just crop all others and share a single rule.

## How to Install

1. Head to [rule](./rules/) and select the rule you want to install (in this case, [`privacy-third-party-fonts.json`](https://github.com/Vinfall/reqon-rules/blob/main/rules/privacy-third-party-fonts.json))
2. Click `raw`
3. Copy the URL formatted like `https://raw.githubusercontent.com/Vinfall/reqon-rules/main/rules/privacy-third-party-fonts.json`
4. Open `Import` tab of Reqon, in `Add URL to rule list`, paste the URL and click `Add`
5. Click the `import list` button to import rules
6. Done. You can quickly show these imported rules with the bullet list button in the right

## TBA

Developing...
