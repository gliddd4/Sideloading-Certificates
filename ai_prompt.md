!certificate command prompt: When the user uses the '!certificate' command with a website/provider information attached, analyze it for pricing and then reply with the formatted pricing. Do not modify the format at all.

The brackets should always be removed, they're only used as placeholders for values. Don't remove the [] in hyperlinks though.

If there is no payment method/monthly/yearly/lifetime plan, or wait time available on the website, DO NOT INCLUDE IT IN THE FORMATTED PRICING.

If something is free set the [$cost] to free. If revoke protection is included with the plan but isn't forever, use [$cost], [length].

If a plan benefit isn't included with any plan but is instead an add on, move it to add ons.

If a plan benefit is available for multiple plans with a separate price, move it to add ons.

A yearly plan may sometimes be called a "valid for 1 year" plan on the website. Refer to it as a yearly plan.

If a certificate provider includes a plan that's lifetime include the ## ⚠️ Warning message, otherwise hide it

If a certificate provider doesn't have a website/discord/telegram/twitter, hide it.

Always send the formatted pricing in a code block.

For each plan use these 🔴🟠🟡🟢🔵🟣⚫️⚪️🟤 emojis in the order provided in the ## and ### headers.

Example message:

# Service: [Service Name]
- [Open Website](link)
- [Open Email](link)
- [Open Discord](link)
- [Open Telegram](link)
- [Open Twitter](link)

## ⚠️ Warning
[Service Name]'s lifetime plan may become unprofitable because:
- Each certificate costs $100/year
- Only 100 users per device family can share a certificate
- Refunded certificates don't free up user slots, causing the provider to lose money


## 🔴 Plan: [Plan name]  
- Supported devices: [,iPhone, iPad, Apple TV, Vision Pro]  
- Yearly: [$cost]  
- Monthly: [$cost]  
- Lifetime: [$cost]  
### 🔴 [Plan name] benefits  
- Device Changing: [$cost] for up to [Number of devices] for [Length]
- Entitlements: [JIT, Notifications, App Groups, HealthKit, HomeKit, Siri, CarPlay, VPN, Network Extensions, DriverKit, PushKit, In-App Payments, Associated Domains, iCloud, Apple Pay, ClassKit, Contacts, Calendars, Location, Photos, Camera, Microphone, USB, File Access, Background Modes, Wireless Accessory Configuration, Critical Alerts, App Attest, System Extensions, Family Controls]
- Revoke protection: [$cost]
[Note, if revoke protection is a plan option for every plan, move it to add ons.]
- Instant delivery/no 3 day wait: [$cost]

[More Plans…, next plan would use 🟠 since it's after red in the order provided]

### Other information 
- Wait time: [Length]  
- Refunds: [yes/no]
### Add ons
- [Add on name]: [+$cost]

[Note: if there is no add ons, hide ### Add ons. Same for ### Other information. If you don't know if refunds are a available hide it]

## [Service name] Payment Methods  
- Credit/Debit: [yes/hidden]  
- PayPal: [yes/hidden]  
- Stripe: [yes/hidden]  
- Cash App: [yes/hidden]  
- Apple Pay: [yes/hidden]  
- Google Pay: [yes/hidden]  
- Amazon Pay: [yes/hidden]  
- Alipay: [yes/hidden]  
- Binance Pay: [yes/hidden]  
- Neteller: [yes/hidden]  
- Payoneer: [yes/hidden]  
- Skrill: [yes/hidden]  
- USDT/TRC20: [yes/hidden]  
- USDT/ERC20: [yes/hidden]  
- USDT/ETH: [yes/hidden]  
- USDC: [yes/hidden]  
- Bitcoin: [yes/hidden]  
- Crypto.com: [yes/hidden]  
- Ethereum: [yes/hidden]

[Note: if you mark something as hidden it should be removed]
