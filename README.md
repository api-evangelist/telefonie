# Telefonie

Telefonie is a cloud communications platform providing programmable telephony, voice, SMS, and number management APIs for developers and businesses. The platform enables developers to embed voice calling, SMS messaging, number provisioning, conferencing, and call recording into their applications via REST APIs.

**Human URL:** [https://www.telefonie.com](https://www.telefonie.com)
**Developer URL:** [https://developers.telefonie.com](https://developers.telefonie.com)

## APIs

### Telefonie Voice API
Make, receive, and control phone calls programmatically. Supports outbound dialing, inbound handling, IVR, conferencing, and call recording.

- **Documentation:** [https://developers.telefonie.com/voice](https://developers.telefonie.com/voice)
- **OpenAPI Spec:** [openapi/telefonie-voice-openapi.yml](openapi/telefonie-voice-openapi.yml)

### Telefonie SMS API
Send and receive SMS and MMS messages globally with delivery receipts and two-way messaging support.

- **Documentation:** [https://developers.telefonie.com/sms](https://developers.telefonie.com/sms)
- **OpenAPI Spec:** [openapi/telefonie-sms-openapi.yml](openapi/telefonie-sms-openapi.yml)

### Telefonie Number Management API
Search, purchase, configure, and manage phone numbers across multiple countries.

- **Documentation:** [https://developers.telefonie.com/numbers](https://developers.telefonie.com/numbers)
- **OpenAPI Spec:** [openapi/telefonie-numbers-openapi.yml](openapi/telefonie-numbers-openapi.yml)

### Telefonie Call Recording API
Record, store, and retrieve call recordings with dual-channel support and transcription.

- **Documentation:** [https://developers.telefonie.com/recording](https://developers.telefonie.com/recording)
- **OpenAPI Spec:** [openapi/telefonie-recording-openapi.yml](openapi/telefonie-recording-openapi.yml)

## Artifacts

### OpenAPI Specifications
| File | Description |
|---|---|
| [openapi/telefonie-voice-openapi.yml](openapi/telefonie-voice-openapi.yml) | Voice API — calls, conferencing, call control |
| [openapi/telefonie-sms-openapi.yml](openapi/telefonie-sms-openapi.yml) | SMS API — send/receive SMS and MMS |
| [openapi/telefonie-numbers-openapi.yml](openapi/telefonie-numbers-openapi.yml) | Number Management API — search, purchase, configure numbers |
| [openapi/telefonie-recording-openapi.yml](openapi/telefonie-recording-openapi.yml) | Call Recording API — record and retrieve call recordings |

### JSON Schemas
| File | Description |
|---|---|
| [json-schema/telefonie-call-schema.json](json-schema/telefonie-call-schema.json) | Voice Call object JSON Schema |
| [json-schema/telefonie-message-schema.json](json-schema/telefonie-message-schema.json) | SMS Message object JSON Schema |

### JSON Structure
| File | Description |
|---|---|
| [json-structure/telefonie-call-structure.json](json-structure/telefonie-call-structure.json) | Call object field structure |

### JSON-LD
| File | Description |
|---|---|
| [json-ld/telefonie-context.jsonld](json-ld/telefonie-context.jsonld) | JSON-LD context for Telefonie data types |

### Examples
| File | Description |
|---|---|
| [examples/telefonie-initiate-call-example.json](examples/telefonie-initiate-call-example.json) | Initiate a voice call |
| [examples/telefonie-send-message-example.json](examples/telefonie-send-message-example.json) | Send an SMS message |

### Spectral Rules
| File | Description |
|---|---|
| [rules/telefonie-rules.yml](rules/telefonie-rules.yml) | Spectral ruleset for Telefonie API conventions |

### Naftiko Capabilities
| File | Description |
|---|---|
| [capabilities/shared/telefonie-voice.yaml](capabilities/shared/telefonie-voice.yaml) | Shared Voice API capability definition |
| [capabilities/shared/telefonie-sms.yaml](capabilities/shared/telefonie-sms.yaml) | Shared SMS API capability definition |
| [capabilities/telephony-communications.yaml](capabilities/telephony-communications.yaml) | Unified communications workflow (REST port 8080, MCP port 9090) |

### Vocabulary
| File | Description |
|---|---|
| [vocabulary/telefonie-vocabulary.yml](vocabulary/telefonie-vocabulary.yml) | Telefonie platform vocabulary |

## Common Properties

| Property | URL |
|---|---|
| Authentication | https://developers.telefonie.com/authentication |
| Getting Started | https://developers.telefonie.com/getting-started |
| Rate Limits | https://developers.telefonie.com/rate-limits |
| SDKs | https://www.telefonie.com/sdks |
| Status | https://status.telefonie.com |
| Terms of Service | https://www.telefonie.com/terms |
| Privacy Policy | https://www.telefonie.com/privacy |
| Pricing | https://www.telefonie.com/pricing |

## Maintainers
- **Telefonie API Team** — api@telefonie.com
