# WhatsApp Setup — Class 01

## Channel Selection
- Selected: WhatsApp (QR link)

## Setup Steps
1. Opened channel configuration:
   openclaw configure --section channels
2. Selected "Configure/link"
3. Chose "WhatsApp (QR link)"
4. Selected "Yes" to link
5. Chose "This is my personal phone number"
6. Entered phone number
7. Scanned QR code using WhatsApp (Linked Devices)

## Linking Result
- WhatsApp linked successfully
- Message shown: "Linked after restart; web session ready"

## Configuration Mode
- Mode: Personal phone
- DM Policy: allowlist
- Allowed Number: +923333277622

## Verification
Command:
openclaw channels status --probe

Result:
- Gateway reachable
- WhatsApp: enabled, configured, linked, running, connected

## Conclusion
WhatsApp channel successfully connected and operational with OpenClaw.