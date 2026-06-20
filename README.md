# Termii (termii)

Termii is an African multichannel messaging platform whose REST API lets businesses send SMS, voice, WhatsApp, and email; generate and verify one-time passwords (OTP) for customer verification; manage sender IDs, campaigns, and contact phonebooks; and pull insights such as account balance, message reports, and number status. All requests authenticate with an api_key passed in the request body or query string.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/termii/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/termii/refs/heads/main/apis.yml)

## Tags

- Messaging
- SMS
- OTP
- WhatsApp
- Verification

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Termii Messaging API

Send single or bulk messages across SMS, WhatsApp, and voice channels with a registered sender ID, plus send via an auto-generated messaging number that adapts to the recipient's location.

- **Human URL:** [https://developers.termii.com/messaging-api](https://developers.termii.com/messaging-api)
- **Base URL:** `https://api.ng.termii.com/api`

#### Tags

- Messaging
- SMS
- WhatsApp
- Voice

#### Properties

- [Documentation](https://developers.termii.com/messaging-api)
- [API Reference](https://developers.termii.com/)
- [OpenAPI](openapi/termii-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/termii.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/termii.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Termii Token / OTP API

Generate, deliver, and verify one-time passwords across messaging channels (Send Token), as a voice call (Voice Token), or returned in JSON for your own delivery (In-App Token), then confirm codes with Verify Token.

- **Human URL:** [https://developers.termii.com/send-token](https://developers.termii.com/send-token)
- **Base URL:** `https://api.ng.termii.com/api`

#### Tags

- OTP
- Token
- Verification
- Two-Factor

#### Properties

- [Documentation](https://developers.termii.com/send-token)
- [API Reference](https://developers.termii.com/in-app-token)
- [OpenAPI](openapi/termii-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/termii.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/termii.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Termii Sender IDs API

Retrieve the sender IDs on an account (active, pending, or blocked) and submit new alphanumeric sender IDs to Termii for review and approval.

- **Human URL:** [https://developers.termii.com/sender-id](https://developers.termii.com/sender-id)
- **Base URL:** `https://api.ng.termii.com/api`

#### Tags

- Sender ID
- Registration
- Configuration

#### Properties

- [Documentation](https://developers.termii.com/sender-id)
- [OpenAPI](openapi/termii-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/termii.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/termii.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Termii Campaigns API

Launch SMS campaigns to a phonebook with optional scheduling and link tracking, list past campaigns, fetch campaign history, and retry a campaign.

- **Human URL:** [https://developers.termii.com/campaign](https://developers.termii.com/campaign)
- **Base URL:** `https://api.ng.termii.com/api`

#### Tags

- Campaigns
- Bulk
- Scheduling

#### Properties

- [Documentation](https://developers.termii.com/campaign)
- [OpenAPI](openapi/termii-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/termii.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/termii.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Termii Contacts / Phonebooks API

Create, list, update, and delete phonebooks, and manage the contacts within them - add a single contact, bulk upload contacts via CSV, list contacts, and delete a contact.

- **Human URL:** [https://developers.termii.com/phonebook](https://developers.termii.com/phonebook)
- **Base URL:** `https://api.ng.termii.com/api`

#### Tags

- Contacts
- Phonebooks
- Lists

#### Properties

- [Documentation](https://developers.termii.com/phonebook)
- [API Reference](https://developers.termii.com/contacts)
- [OpenAPI](openapi/termii-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/termii.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/termii.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Termii Insights API

Pull account-level insights - current wallet balance and currency, message delivery history and reports, and number status queries that detect fake or ported numbers.

- **Human URL:** [https://developers.termii.com/balance](https://developers.termii.com/balance)
- **Base URL:** `https://api.ng.termii.com/api`

#### Tags

- Insights
- Balance
- Reports
- Status

#### Properties

- [Documentation](https://developers.termii.com/balance)
- [API Reference](https://developers.termii.com/history)
- [OpenAPI](openapi/termii-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/termii.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/termii.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/termii)
- [Website](https://termii.com)
- [Documentation](https://developers.termii.com/)
- [Plans](plans/termii-plans-pricing.yml)
- [Rate Limits](rate-limits/termii-rate-limits.yml)
- [Fin Ops](finops/termii-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
