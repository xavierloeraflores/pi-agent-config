# Pi Setup

My personal Pi setup.

## Installation

Install Pi first by following the [Pi docs](https://pi.dev).

Clone this repo into `~/.pi/agent`

Set up Pi by running `pi` and using `/login`, or configure a provider API key such as `ANTHROPIC_API_KEY`.

## Grok Subscription Support

Install the xAI OAuth provider:

```sh
pi install npm:pi-xai-oauth
```

Then start Pi and authenticate/select the Grok model:

```sh
pi
/login xai-auth
/model grok-build
```
