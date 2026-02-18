# AI-Business-Alliance
AI Business Alliance (AIBA) is a student organization at Ohio University dedicated to bridging the gap between emerging AI technologies and real-world business applications. Our mission is to equip students with AI literacy, hands-on experience, and professional connections to thrive in an AI-driven economy.

## Fraternity ERP Module
This site now includes a **Fraternity ERP** workflow for cabinet and executive members:
- Shared-password login (no individual accounts required).
- Structured form submission for operations records.
- Automatic conversion of submissions into templated documents with clean PDF export (plus TXT fallback).
- Local archive grouped by folder/department so current and future members can reference past resources.

### Shared password configuration
The default shared password is configured in `index.html` as `ERP_SHARED_PASSWORD`.
Update this value before production deployment.


### Document templates
Members can choose from multiple templates (Meeting Minutes, Event Recap, Budget Summary, Incident Follow-Up, and General Ops Memo) before saving a record.
