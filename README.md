# AgentGuard: Preventing Autonomous Backdoors in AI Agents

AgentGuard is a lightweight security layer that prevents LLM agents (e.g., OpenClaw) from silently creating persistent backdoors via unauthorized integrations.

## 🚨 Problem

AI agents can be manipulated via prompt injection to:
- Create new integrations (e.g., Telegram bots)
- Establish external control channels
- Persist beyond enterprise visibility

## 🛡️ Solution

AgentGuard enforces:
- Action interception
- Trust boundary monitoring
- Outbound domain control

## ⚡ Demo

### Attack (without protection)
```bash
python demo/attack_scenario.py
