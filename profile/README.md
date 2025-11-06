# T4U - AI-Powered Autonomous Test Automation

**T4U** is an intelligent test automation platform that creates and executes web tests using natural language. Simply describe what you want to test, and AI agents powered by A.I. models will understand your goals, execute tests in isolated sandboxes, and generate stable, maintainable test scripts.

## Key Highlights

🎯 **Stable & Reliable** - Uses semantic Playwright locators (`by_role`, `by_placeholder`) instead of brittle CSS selectors. Tests survive page structure changes.

🤖 **AI-Driven** - Write tests in plain English like "Login and validate the dashboard". Claude 3.5 Sonnet handles the complexity autonomously.

⚡ **Fast & Scalable** - Custom E2B templates with pre-installed Playwright achieve 6x faster startup (10s vs 60s). Run multiple tests in parallel with full isolation.

🎥 **Real-Time Visibility** - Watch tests execute live with VNC streaming. Get step-by-step updates synced to Firestore in real-time.

🔄 **Zero-Cost Replay** - Record proven test steps once, replay infinitely without AI inference costs. Perfect for regression testing.

🔐 **Enterprise-Ready** - Multi-tenant architecture with Firebase JWT authentication. Secure WebSocket connections with tenant-based validation.

## Technology Stack

FastAPI · Python 3.13+ · Claude 3.5 Sonnet · Playwright · E2B Sandboxes · Firebase · WebSockets (VNC)

## Perfect For

QA teams wanting to accelerate test creation, reduce maintenance burden, and achieve higher test coverage with AI-powered automation.
