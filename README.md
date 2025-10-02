# Alfred OTP Keychain Workflow

Alfred workflow to generate OTP secured in keychain. Secrets are stored in your keychain "local items", suffixed with the label "-otp".

## Install

- Install `oathtool` via `brew install oath-toolkit`

## Usage

- Add a new OTP service and token: `otp+ [service] [token]`
![add new token](/doc/otp+.png)

- Generate OTP for a service: `otp [service]`. OTP is pasted at cursor and copied to clipboard
![generate otp](/doc/otp.png)

## Credits
- Forked from https://github.com/caalberts/alfred-otp
- Inspired by https://github.com/MyDeity/OTP-Generator
