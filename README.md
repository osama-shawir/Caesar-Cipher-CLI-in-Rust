[![Clippy](https://github.com/nogibjj/rust-data-engineering/actions/workflows/lint.yml/badge.svg)](https://github.com/nogibjj/rust-data-engineering/actions/workflows/lint.yml)
[![Tests](https://github.com/nogibjj/rust-data-engineering/actions/workflows/tests.yml/badge.svg)](https://github.com/nogibjj/rust-data-engineering/actions/workflows/tests.yml)

## Caesar Cipher CLI Overview

### Uses

The Caesar Cipher CLI is a tool for encrypting and decrypting messages using the Caesar cipher. It's a simple and classical encryption technique where each letter in the plaintext is shifted a certain number of places down or up the alphabet.

### Command-Line Flags

- **--encrypt:**
  - *Usage:* `--encrypt`
  - *Description:* Encrypt the specified message using the Caesar cipher.

- **--decrypt:**
  - *Usage:* `--decrypt`
  - *Description:* Decrypt the specified message using the Caesar cipher.

- **--message:**
  - *Usage:* `--message "your_message"`
  - *Description:* Specify the message to be encrypted or decrypted.

- **--shift:**
  - *Usage:* `--shift 3`
  - *Description:* Specify the shift to use for the Caesar cipher. Must be between 1 and 25. The default is 3.

- **--uppercase:**
  - *Usage:* `--uppercase`
  - *Description:* Output the result in uppercase.

# Caesar Cipher CLI Usage

To use the Caesar Cipher CLI, you can either fork this repository or run it in Codespaces. Follow the steps below to encrypt and decrypt messages using the Caesar cipher.

## Clone the Repository (if not forking or using Codespaces)

```bash
git clone https://github.com/osama-shawir/Caesar-Cipher-CLI-in-Rust.git
cd caesar_cipher_cli


