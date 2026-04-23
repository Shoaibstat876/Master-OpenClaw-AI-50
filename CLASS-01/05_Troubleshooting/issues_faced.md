# Issues Faced — Class 01

## Issue 1: Gateway Not Reachable
Error:
- Gateway not reachable / timeout

Solution:
- Set gateway mode to local:
  openclaw config set gateway.mode local
- Restarted gateway

---

## Issue 2: WhatsApp Plugin Failed
Error:
- WhatsApp plugin not available
- Missing @whiskeysockets/baileys

Solution:
- Installed dependency:
  npm install -g @whiskeysockets/baileys
- Reconfigured channels

---

## Issue 3: WhatsApp Not Connected
Error:
- WhatsApp showed "not linked / disconnected"

Solution:
- Re-ran:
  openclaw configure --section channels
- Scanned QR again
- Completed linking successfully

---

## Issue 4: Device Approval Required
Error:
- scope upgrade pending approval

Solution:
- Approved device using:
  openclaw devices approve <requestId>

---

## Issue 5: Slow or Failed Responses
Error:
- "Agent couldn't generate a response"

Solution:
- Retried message
- Observed automatic recovery
- Switched to stable model if needed

---

## Final Conclusion
All issues were identified and resolved successfully.
System is now working and stable for Class-01 requirements.
