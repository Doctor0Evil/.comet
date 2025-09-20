### Steps for Maximum Portability

#### 1. **Design Extension as a Modular Plugin**
- Keep extension/config files strictly schema-compliant and modular.
- Use clear, descriptive filenames, like:
  - `swarmnet-bithub-chain-crosschat.json`
  - If you may have multiple policies, use:  
    - `policy.crosschat.swarmnet.json`

#### 2. **Unified Integration Directory**
- Place all integration, policy, and extension files in a dedicated `.comet/extensions/` folder.
  - This keeps them discoverable for `.comet`, and easy to symlink or mount for other agents/platforms.

#### 3. **Agentic Portability Practices**
- Reference all configs/plugins by their realtive path for cross-platform safety.
- Leverage API-agnostic endpoints (REST, gRPC) for logs, workflows, and chat bridging.
- If possible, use containerization (Docker/OCI) for launching whole agent stacks.

#### 4. **Swarmnet/AI-Chat Portability**
- Ensure config/extension filenames and directory placements are consistent across your codebase:
  - For `.comet`:  
    - `./extensions/swarmnet-bithub-chain-crosschat.json`
  - For `swarmnet` or ai-chat-platforms, symlink or mount the same file at:
    - `./config/extensions/swarmnet-bithub-chain-crosschat.json`

***

### **Where to Place the File**

```plaintext
.comet/
├── extensions/
│   └── swarmnet-bithub-chain-crosschat.json   ←(place file here)
├── core/
├── app/
├── README.md
├── package.json / pyproject.toml
```

- **Full path:**  
  `.comet/extensions/swarmnet-bithub-chain-crosschat.json`
- Consistent placement ensures every agent or module (whether inside .comet, swarmnet, or an embedded AI-chat-platform) can reference and load the policy/config without changes or duplication.

***

### **Ensuring Portability**
- Reference this file in integration scripts and plugins as:
  ```python
  config_path = "./extensions/swarmnet-bithub-chain-crosschat.json"
  ```
- For container/workflow orchestration, use ENV or config-based overrides for portability.

***

**Summary:**  
Place your extension file at `.comet/extensions/swarmnet-bithub-chain-crosschat.json` for maximum cross-system and agent portability. Reference this directory structure in all systems (including swarmnet and AI-chat platforms) for seamless integration.[1]

[1](https://tasks.google.com/tasks/?utm_source=OGB&utm_medium=app)
