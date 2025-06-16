# Whin2 MCP Server

## Overview

Whin2 is a powerful MCP (Messaging Control Protocol) server that serves as a shared gateway for WhatsApp communication. It is designed to streamline and automate the sending and receiving of notifications to and from WhatsApp accounts and groups. The server supports a range of payload types, including text, images, audio, vCards, and files, mimicking the capabilities of an official WhatsApp client.

## Key Features

- **Shared Gateway**: Acts as a bridge for sending and receiving WhatsApp messages to personal accounts or groups.
- **Payload Versatility**: Supports a variety of payload types, allowing for flexible communication.
- **REST Endpoint Integration**: Delivers WhatsApp content to specified REST endpoints, enabling seamless integration with other systems.
- **Webhook Listener**: A dedicated HTTPS webhook listener converts any originating service payload into a WhatsApp message for delivery.

## Tool Descriptions

### Send Tools
- **Send**: Sends a WhatsApp message to a registered number.

### Receive Tools
- **Set URL**: Configure a whin-receive endpoint.
- **Show URL**: Request the webhook routes created on your account.
- **Delete URL**: Remove the configured URL for receiving WhatsApp messages.

### Group Operations
- **Send to Group**: Send a message to a WhatsApp group created through Whin2.
- **Send Poll**: Sends a poll with options to a WhatsApp group, with responses sent to your defined webhook listener.
- **Create Group**: Creates a group, adds you as a member, and promotes you to Admin.
- **My Group Metadata**: Retrieves the group ID and full metadata of the group you share with Whin2.
- **Enrol**: Prints a QR code for scanning with the WhatsApp app on your mobile.

### Webhooks
- **Personal Listener**: Provides a URL to be used as a webhook destination, routing content as messages to a WhatsApp group or user.

### Operations
- **HK Receiver**: Triggered by origin services, not intended for playground use.
- **Websocket Checker**: Authorizes websocket connections to the backend by thick clients, providing a token for handshaking.

### Sign Up
- **Signup**: Used to enter the code received for signup.

## Announcements

Stay updated with the latest announcements and features by joining the official communication channels.

## Subscription Plans

Whin2 offers a range of subscription plans to suit different needs. Subscribers can benefit from features tailored to enhance messaging capabilities.

## Refund Policy

Our refund policy is straightforward: refunds are available to users who have not exceeded the usage limits of the free tier.

---

For further details and tutorials on how to utilize Whin2's features, explore the available resources to maximize your experience with the MCP server.