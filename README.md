## Requirements

- [Node.js](https://nodejs.org/en/)
- [PubNub Account](#pubnub-account) (*Free*) 

<a href="https://dashboard.pubnub.com/signup">
    <img alt="PubNub Signup" src="https://i.imgur.com/og5DDjf.png" width=260 height=97/>
</a>

## PubNub Account and App Setup

1. You’ll first need to sign up for a [PubNub account](https://dashboard.pubnub.com/signup/). Once you sign up, you can get your unique PubNub keys from the [PubNub Developer Portal](https://admin.pubnub.com/).

1. Sign in to your [PubNub Dashboard](https://dashboard.pubnub.com/).

1. Click **Create New App**.

1. Give your app a name, and select **Chat App** as the app type.

1. Click **Create**.

1. Click your new app to open its settings, then click its keyset.

1. [Enable the Channel Presence feature](https://support.pubnub.com/support/solutions/articles/14000043562-how-do-i-enable-the-channel-presence-feature-/) for your keyset.

1. [Enable the Storage and Playback feature](https://support.pubnub.com/support/solutions/articles/14000043644-how-do-i-enable-the-message-history-feature-) for your keyset.

1. [Enable the Stream Controller feature](https://support.pubnub.com/support/solutions/articles/14000043662-how-do-i-enable-wildcard-subscribe-for-my-pubnub-keys-) for your keyset.

1. Copy the Publish and Subscribe keys for the next step.

## Building and Running

1. You'll need to run the following commands from your terminal.

1. Clone the GitHub repository.

    ```bash
    git clone https
    ```

1. Navigate into the repository.

    ```bash
    cd chat-app
    ```

1. Open src/config/pubnub-keys.json. **Replace YOUR_PUBLISH_KEY_HERE and YOUR_SUBSCRIBE_KEY_HERE** with your keyset from your [PubNub Dashboard](https://dashboard.pubnub.com/).

1. Install the node modules.

    ```bash
    npm install
    ```

1. Run the project in your local environment.

    ```bash
    npm start
    ```

