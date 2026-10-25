# BedrockPulse CDS (`AWSCDS_OmniAgent2026`)

**Autonomous Omnichannel AI War-Room built on AWS End User Messaging Social (WhatsApp), AWS End User Messaging RCS/SMS v2, Amazon SES v2, and Amazon Bedrock AgentCore.**

## Repository Structure
- `index.html` — Self-contained interactive Omnichannel Simulator & Live AWS Boto3 SDK Inspector (WhatsApp EUM Social + RCS/SMS + Amazon SES v2 + Bedrock AgentCore Memory Graph).
- `aws_cds_agentcore_server.py` — Production Python Boto3 orchestrator implementing `socialmessaging`, `pinpoint-sms-voice-v2`, `sesv2`, and `bedrock-agent-runtime` with EventBridge automatic cross-channel failover.
- `template.yaml` — AWS SAM / CloudFormation serverless infrastructure template.
- `DEVPOST_SUBMISSION.md` — Complete Devpost writeup, Mermaid architecture diagram, and judging rubric alignment.

## Quick Verification
```bash
python aws_cds_agentcore_server.py
```
