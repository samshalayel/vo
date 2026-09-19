# Task 00: تجهيز البيئة (Environment Setup)

## Manual Setup Steps for Trainees

1. **Create project directory and enter it:**
   ```bash
   mkdir -p ~/my-office && cd ~/my-office
   ```

2. **Initialize git and connect to GitHub repository:**
   ```bash
   git init -b main
   git remote add origin git@github.com:<your-username>/my-office.git
   ```

3. **Set ANTHROPIC API Key:**
   ```bash
   export ANTHROPIC_API_KEY="your-api-key-here"
   ```

4. **Launch Claude Code with Sonnet model:**
   ```bash
   claude --model sonnet
   ```

5. **Success Indicator:**
   Look for "Sonnet 5 · API Usage Billing" at the top of the screen without any login prompt.

6. **Test Claude:**
   Type: "قول مرحبا بجملة واحدة" (Say hello in one sentence)
   If Claude responds, proceed to the next task.

---
**Status:** Task completed
**Date:** 2026-09-19
