# CivicEase Chatbot

**Student:** Aditya Sahani  
**Student ID:** 1000414

---

## 1. Live Chatbot
Access the deployed chatbot here:  
[CivicEase Chatbot](https://console.dialogflow.com/api-client/demo/embedded/628051f6-68ae-4ece-92a7-46606dde7ae8)

---

## 2. Project Overview
CivicEase is an AI-powered chatbot developed using **Google Dialogflow**. It is designed to simplify access to government-related services by providing quick, automated responses to common citizen queries.

The chatbot assists users with:
- **Registering new cases** (e.g., road complaints, electricity issues, water supply problems)
- **Checking case status**
- **General service-related FAQs**

The goal is to reduce confusion, waiting time, and manual workload in government offices.

---

## 3. Target Users
| User Group | Usage Purpose |
|-----------|--------------|
| Citizens | File complaints, track case updates, and get quick information |

---

## 4. Key Features
- Built using **Dialogflow ES**
- **Intent Recognition** to understand user messages
- **Custom Entities** to extract case types and case IDs
- Works **without coding, webhooks, or backend**
- Can be integrated with **Telegram / Web widget**

---

## 5. Intents Implemented
| Intent Name | Function |
|------------|----------|
| Welcome Intent | Greets the user |
| Register Case Intent | Guides user through filing a complaint/case |
| Check Case Status Intent | Allows case status lookup using a case ID |
| General Query Intent | Handles common FAQs |
| Fallback Intent | Handles unclear or unrelated input |

---

## 6. Custom Entities
| Entity Name | Purpose |
|------------|---------|
| `@case_type` | Captures category of case (road, electricity, water, etc.) |
| `@case_id` | Captures case reference numbers for tracking |

---

## 7. Testing Scenarios
| User Input | Expected Intent Triggered |
|-----------|--------------------------|
| "Hi" | Welcome Intent |
| "I want to register a complaint" | Register Case Intent |
| "Check status of case 1045" | Check Case Status Intent |
| "How do I contact the office?" | General Query Intent |
| Random text | Fallback Intent |

All intents responded correctly during testing.

---

## 8. Deployment Steps
1. Open **Dialogflow ES Console**
2. Go to **Settings → Export and Import**
3. Export the agent as **ZIP** (for backup or reuse)
4. To reuse:
   - Create new agent → Import ZIP
5. Verify intents and entities after import
6. Integrate through **Telegram** or **Web Demo** panel

---

## 9. Future Enhancements
- Database integration for real-time case tracking
- Multi-language support
- Voice-enabled chat assistance

---

## License
This project is created for academic and demonstration purposes.
