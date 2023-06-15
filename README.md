# VALR Restaking
A simple scheduled script for restaking rewards on VALR.com

When run, this script will use the [VALR.com](https://www.valr.com/invite/VARVXA5D) [API](https://docs.valr.com/) to get the account balance for SOL and AVAX, and stake the full available amount.

# Why?
VALR staking rewards are paid out immediately and not automatically restaked. To benefit from compound growth you have to restake your rewards. This script, when deployed to Netlify, automates that.

# Deploy scheduled task on Netlify
When deployed on Netlify, the script will execute at 5 minutes past every hour.

## Recommended setup
It is strongly recommended to use a dedicated [sub-account](https://support.valr.com/hc/en-us/articles/4409820263186) for staking.

## VALR API key
In your sub-account, create a new API key with "View" and "Trade" permissions. DO NOT grant withdrawal permissions.
Note the API key and secret.

## Deploy on Netlify
Use this button to deploy on Netlify. Provide the API key and secret in the API_KEY and API_SECRET environment variables, respectively.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/nieldw/valr-restaking-serverless)

## Tip the Developer 🫶
Like this? Please show your gratitude by sending me a tip with VALR Pay.

VALR Pay me here: https://www.valr.com/payments/send?payId=DQ87EY5LUF94HA8YUBJZ