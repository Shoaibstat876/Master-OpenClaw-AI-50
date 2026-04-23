# Class 01 — OpenClaw Setup

## Objective
Install OpenClaw, connect a messaging channel, and verify the AI Employee works.

---

## Steps Overview
1. Install OpenClaw  
2. Configure LLM (Google Gemini)  
3. Connect messaging channel (WhatsApp)  
4. Send first message  
5. Verify system  
6. Fix errors if needed  

---

## System Check
Node.js Version: v22.14.0  
npm Version: 10.9.2  
Status: Ready  

---

## Installation & Setup

OpenClaw was installed successfully using terminal.

### Gateway Issue
At first, gateway was not reachable.

Fixed using:
openclaw config set gateway.mode local  
openclaw gateway restart  

Gateway became reachable.

---

## Model Setup

Gemini API configured successfully.

Initial model:
google/gemini-3.1-flash-lite-preview  

System connected and working.

---

## First TUI Test

Prompt: Wake up, my friend!

Result:
- Warning appeared initially
- Agent replied successfully after

Conclusion:
TUI is working and Gemini is connected.

---

## Identity Setup

Agent Name: OpenClaw  
Role: AI Employee  
Style: Professional, helpful  

User: Shoaib  
Goal: Learning agentic AI  

---

## WhatsApp Connection

### Issue
WhatsApp plugin failed due to missing dependency.

### Fix
Installed:
npm install -g @whiskeysockets/baileys  

Then:
openclaw configure --section channels  

Scanned QR → linked successfully.

---

## WhatsApp Testing

Test 1:
Message: Hi  
Result: Bot replied  

Test 2:
Message: What is my name?  
Result:
- First failed
- Then succeeded  

Test 3:
Message: YOU ARE MY BOT NOW REMEMBER  
Result: Bot replied correctly  

---

## Real Behavior

- First response was slow  
- One error occurred  
- System recovered automatically  
- Later responses improved  

---

## Final Result

Everything is working:

- OpenClaw installed  
- Gemini connected  
- Gateway fixed  
- WhatsApp linked  
- Bot replying  

System works end-to-end.

---

## Conclusion

Class 01 completed successfully.

System is real and working, with minor delays which are normal.

---

## Confidence

High ✅