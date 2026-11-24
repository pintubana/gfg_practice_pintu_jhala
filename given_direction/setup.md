Codex Workshop
Pre-Workshop Setup Checklist (for Participants)
Please complete this setup 1-2 days before the session so there is time to fix any issues. Everything here can be done in advance.
You do NOT need ChatGPT Plus to install or run Codex. Installing Codex is free. You only need a ChatGPT account to sign in. Codex is included across ChatGPT plans, including the free plan (with lower usage limits), so do not let your plan block your setup. If your plan or a promo offer matters, see the optional section at the end.


1. At a glance - what to have ready
Tick each item once done. Details for every step follow below.
❑  A working computer: macOS, Windows, or Ubuntu / Linux
❑  A ChatGPT account you can sign in to (free plan is fine; Plus optional)
❑  Codex installed and signed in (ChatGPT desktop app OR Codex CLI)
❑  Default model left selected in Codex (do not change it)
❑  Git installed (any recent version)
❑  Node.js 22 or newer, with npm (tested on Node 24)
❑  A GitHub account you can sign in to (to fork the repo and open a pull request)
❑  Stable internet, laptop charged, charger handy

2. ChatGPT account (Plus is not mandatory)
Codex is included across ChatGPT plans - free plan, Go, Plus, Pro, Business, Edu and Enterprise. Paid plans mainly give you higher usage limits. For a workshop, a free account is enough to get started; sign in and you are ready.
Two ways to sign in to Codex:
Sign in with ChatGPT (recommended) - run Codex and choose this option; it uses your ChatGPT plan's included usage.
API key (optional, pay-as-you-go) - only if you prefer billing per use through the OpenAI platform. Not needed for this workshop.
Keep it simple: install Codex, then sign in with your ChatGPT account.
3. Install Codex (pick ONE path)
Two main options. Choose the ChatGPT desktop app if you want the simplest setup, or the Codex CLI if you are comfortable in a terminal. The IDE extension is optional.
Option A - ChatGPT desktop app (easiest; includes Codex)
Available for macOS, Windows and Linux. Steps are the same on all three:
Download and install the ChatGPT desktop app (or update it if you already have it).
Open the app and sign in with your ChatGPT account.
Open Codex inside the app, pick a folder to work in, and leave the default model selected.

Option B - Codex CLI (for terminal users)
Prerequisite for the npm path: Node.js 22+ and npm installed first (see section 4). After installing, run codex, choose "Sign in with ChatGPT", and leave the default model.
macOS
Use any one of these:
  npm install -g @openai/codex
or the standalone installer (no Node needed):
  curl -fsSL https://chatgpt.com/codex/install.sh | sh
or Homebrew:
  brew install --cask codex

Windows
Install Node.js 22+ first, then in PowerShell run:
  npm install -g @openai/codex
or use the PowerShell installer:
  powershell -ExecutionPolicy ByPass -c "irm https://chatgpt.com/codex/install.ps1 | iex"
Optional but best-tested: WSL2 (Windows Subsystem for Linux) gives fuller sandbox support. If you already use WSL, install Codex inside it the Ubuntu way below.

Ubuntu / Linux
Use the standalone installer:
  curl -fsSL https://chatgpt.com/codex/install.sh | sh
or npm (needs Node 22+):
  npm install -g @openai/codex

Option C - IDE extension (optional)
If you work in VS Code, Cursor or Windsurf, you can install the Codex IDE extension from your editor's extension marketplace, then sign in with your ChatGPT account. This is optional and can sit alongside the app or CLI.
4. Developer tools to install
Git
Any recent version is fine. Verify in a terminal:
  git --version

Node.js and npm
Node 22 or newer is recommended (tested on Node 24). npm comes bundled with Node. Verify:
  node --version
  npm --version
If Node is older than 22, update it (a version manager such as nvm, or nvm-windows, makes this easy).
GitHub account
You will fork the workshop repository (link shared by your mentor) and open a pull request during the session. Make sure you can sign in at github.com before the workshop.
5. Verify your setup
Run these before the session. Each should return a version or open without errors:
  codex --version
  git --version
  node --version      # should be 22 or higher
  npm --version
Then open Codex, sign in, point it at any small folder, and ask a simple prompt such as "explain this project" to confirm sign-in works. If it responds, you are ready.
6. Optional - getting ChatGPT Plus (not required)
Plus is NOT required for this workshop - a free ChatGPT account is enough to take part. This section is only for anyone who would also like Plus for higher usage limits.
Already have Plus: you are all set - nothing to do.
Claim Free Offer: some ChatGPT accounts show a "Claim Free Offer" option inside ChatGPT that activates one month of Plus. To turn it on, you add a payment method - a card (credit / debit) was needed to proceed; UPI did not work reliably in testing.
Do not see the offer? it does not appear on every account, so just continue with your free account - Plus is optional for this session.
Recommendation: do not block your setup on Plus. Install Codex and sign in with any ChatGPT account first; treat Plus as a separate, optional step.


7. Common issues and quick fixes
codex: command not found - close and reopen your terminal; confirm Node and npm are installed and on your PATH; reinstall if needed.
Node too old - install Node 22+ and run npm install -g @openai/codex again.
Sign-in loops or lost authentication - run codex logout then codex login and sign in again.
Windows sandbox problems - use WSL2 and install Codex inside Ubuntu.
Corporate network, VPN or proxy - these can block installation or sign-in. If something fails, try a personal network.

8. Have these ready when the session starts
❑  Laptop charged, charger nearby
❑  Codex (app or CLI) open and already signed in
❑  GitHub signed in
❑  Stable internet connection
❑  The workshop repository link from your mentor handy
