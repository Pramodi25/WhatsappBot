# WhatsApp Bot using Python

## Overview

This project demonstrates how to create a WhatsApp bot using Python, Flask, and Twilio. The bot is designed to respond to user queries and provide relevant articles from GeeksforGeeks.

## System Requirements

- Twilio account and a smartphone with WhatsApp installed
- Python 3.9 or newer
- Flask
- ngrok

## Getting Started

### Step 1: Set up Twilio account using Twilio WhatsApp API

1. Sign up for a Twilio account [here](https://www.twilio.com/try-twilio).
2. Follow the instructions to set up the Twilio WhatsApp API.

### Step 2: Configure Twilio WhatsApp Sandbox

1. Send the secret code to the WhatsApp number provided by Twilio to set up the WhatsApp Sandbox.

### Step 3: Set up the Python environment

```bash
mkdir geek-bot && cd geek-bot
python3 -m venv geek-bot-env && source geek-bot-env/bin/activate
pip3 install twilio flask requests
