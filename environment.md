# Development Environment Overview

## System Information
- Host Name: WORKSTATION-XYZ123
- OS: Microsoft Windows 11 Pro (10.0.26100 Build 26100)
- System Type: x64-based PC
- Processor: AMD64 Family 25 Model 33 Stepping 0 AuthenticAMD ~3401 Mhz
- Memory: 32,690 MB Total Physical Memory (17,229 MB Available)
- GPU: NVIDIA GeForce RTX 4080 SUPER
- Network:
  - Ethernet Adapter (Active)
  - Wi-Fi 6 Adapter
- System Manufacturer: Generic Technology Co.
- System Model: X570 GAMING PRO

## AI Development Environment
- GPU Support: NVIDIA RTX 4080 SUPER (Suitable for AI/ML workloads)
- MCP Servers:
  - browser-automation: Browser automation and testing
  - devtools-firefox: Firefox debugging capabilities
  - devtools-chrome: Chrome debugging and automation

## Development Environment
- Node.js: v22.14.0
- npm: v10.9.2
- Global npm Packages:
  - @ai-sdk/core@1.5.0
  - firefox-devtools-server@1.0.0

- Python: 3.13.1
- Python Packages:
  - anyio: 4.8.0
  - playwright: 1.49.1
  - socialmedia-api: 7.0.0
  - requests: 2.32.3
  - httpx: 0.28.1
  - websockets: 15.0
  - psutil: 7.0.0
  - Other utility packages (certifi, charset-normalizer, idna, etc.)

- Git: 2.48.1.windows.1

## Browser Environments
- Google Chrome: 133.0.6943.142
- Mozilla Firefox: Installed (Program Files)
- Browser Automation Tools:
  - Playwright
  - Firefox DevTools Protocol
  - Chrome DevTools Protocol

## IDE Configuration
- VSCode Extensions:
  - AI/ML Support:
    - ai.copilot
    - ai.copilot-chat
  - Language Support:
    - ms-python.python
    - ms-python.vscode-pylance
    - dbaeumer.vscode-eslint
  - Development Tools:
    - devtools-firefox.vscode-firefox-debug
    - npm-intellisense
    - prettier-vscode
  - Remote Development:
    - cloud.codespaces
    - remote-wsl
    - remote-repositories
  - Custom Tools:
    - ai-assistant.userscript

## Workspace Information
- Working Directory: D:/Projects/AI-Tools
- Time Zone: America/Chicago (UTC-6:00)

## Active Projects

### Chrome Debug Tools
- Location: `/projects/chrome-debug-tools`
- Main purpose: Chrome debugging and automation tools
- Key files:
  - src/index.ts
  - src/tool-definitions.ts
  - Documentation in `/docs`
  - Test suite in `/test`

### Firefox Debugger
- Location: `/projects/firefox-debugger`
- Server implementation with TypeScript configuration

### Image Search Tool
- Location: `/projects/image-search`
- Frontend build configuration with Webpack, Babel, and PostCSS
- Comprehensive source structure in `/src`

### Social Media Tools
- Location: `/projects/socialmedia-tools`
- Contains scraper and automation implementations

### Userscripts Collection
- Location: `/projects/userscripts`
- Various userscript implementations

### AI-Assisted Userscripts
- Location: `/projects/ai-userscripts`
- Browser extension project
- Complete development setup with:
  - Webpack configuration
  - Babel setup
  - ESLint configuration
  - Localization support
  - Comprehensive test suite

## Development Tools & Configuration

### Build Tools
- TypeScript (multiple tsconfig.json files present)
- Webpack
- Babel
- PostCSS
- Gulp

### Code Quality
- ESLint
- Prettier (.prettierrc.yml configurations)
- EditorConfig (.editorconfig)

### Package Management
- npm (multiple package.json files)
- yarn (yarn.lock present in ai-userscripts)

### Testing
- Test directories present in multiple projects
- Dedicated test suites and configurations

## Project Organization
- Active projects separated in `/projects`
- Legacy or deprecated code in `/archive`
- Documentation in various README.md files and dedicated doc folders
- Clear separation of source code and build artifacts

## IDE/Editor Setup
Currently open in VSCode with multiple tabs focused on chrome-debug-tools development:
- Types definitions
- Handler implementations
- Tool definitions
- Documentation
- Test files

## Note
This environment overview was auto-generated on 3/7/2025, 6:36:13 PM. Project structure and configurations may change over time.

## How to Update This Environment File

To scan and update this environment information, use the following commands:

1. System Information:
```bash
systeminfo
wmic path win32_VideoController get name
```

2. Node.js Environment:
```bash
node -v
npm -v
npm list -g --depth=0
```

3. Python Environment:
```bash
python --version
pip list
```

4. Git Information:
```bash
git --version
```

5. Browser Versions:
```bash
# For Chrome version
reg query "HKEY_CURRENT_USER\Software\Google\Chrome\BLBeacon" /v version
# For Firefox installation
reg query "HKEY_CURRENT_USER\Software\Mozilla\Firefox\TaskBarIDs"
```

6. VSCode Extensions:
```bash
code --list-extensions
```

7. Project Structure:
```bash
list_files .
list_files . -recursive
list_code_definition_names .
```

To update this file, simply ask the AI assistant to "Scan my dev environment and write it to environment.md".

