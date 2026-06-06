# ✉️ Welcome to VerifiedSMS

[![Website](https://img.shields.io/badge/🌐-verifiedsms.com-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white)](https://verifiedsms.com)
[![Docs](https://img.shields.io/badge/📖-Documentation-4285F4?style=for-the-badge&logo=readthedocs&logoColor=white)](https://docs.verifiedsms.com)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)

**Trust. Security. Simplicity.**  
VerifiedSMS provides enterprise-grade SMS solutions that help businesses communicate with confidence.  
Our SDKs make it easy to integrate powerful messaging features into your application – no matter your stack.

---

## 🚀 Official SDKs – Ready for every language

We maintain official SDKs for all major programming languages. Choose yours and get started in minutes.

| Language     | SDK Repository                                  | Install command                     |
|--------------|-------------------------------------------------|--------------------------------------|
| **Python**   | [`sdk-python`](https://github.com/VerifiedSMS/sdk-python) | `pip install verifiedsms`          |
| **Node.js**  | [`sdk-nodejs`](https://github.com/VerifiedSMS/sdk-nodejs) | `npm install verifiedsms`         |
| **Ruby**     | [`sdk-ruby`](https://github.com/VerifiedSMS/sdk-ruby)   | `gem install verifiedsms`           |
| **Go**       | [`sdk-go`](https://github.com/VerifiedSMS/sdk-go)       | `go get github.com/VerifiedSMS/sdk-go` |
| **PHP**      | [`sdk-php`](https://github.com/VerifiedSMS/sdk-php)     | `composer require verifiedsms/php` |
| **Java**     | [`sdk-java`](https://github.com/VerifiedSMS/sdk-java)   | Maven / Gradle (see repo)           |
| **C#/.NET**  | [`sdk-csharp`](https://github.com/VerifiedSMS/sdk-csharp) | `dotnet add package VerifiedSMS`  |
| **cURL**     | [`sdk-curl`](https://github.com/VerifiedSMS/sdk-curl)   | Copy & paste examples               |

---

## ✨ What makes VerifiedSMS different?

> *[Only Support Sending SMS in Nepal. Organization Presence in Nepal is required to use VerifiedSMS services.]*

- ✅ **Global reach** – Send SMS to all Telcos in Nepal
- ✅ **High deliverability** – Direct carrier connections
- ✅ **Simple API** – RESTful endpoints with clear documentation
- ✅ **Webhook support** – Real-time delivery receipts and replies
- ✅ **Enterprise security** – End-to-end encryption and compliance ready

---

## 🛠️ Quick example (Python)

```python
from verifiedsms import Client

client = Client(api_key="your_api_key")
response = client.send_sms(
    to="+1234567890",
    message="Your verification code is 482035."
)
print(response.message_id)  # 'msg_abc123'