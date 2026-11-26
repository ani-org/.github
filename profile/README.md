# Agent Networking Project

This organization hosts an Agent Networking Project following ANI. The project includes protocol specifications, gateway binaries, SDK implementations, plugins, and reference agent implementations.

> 📌 Agent Networking Infrastructure (ANI) is a decoupled, heterogeneous-compatible networking infrastructure for agent-to-agent communication. ANI enables autonomous agents to register, publish capabilities, discover peers, establish connections and interoperate across distributed environments.

## What's inside this organization
- **spec**: Core protocol specification, compatibility matrix, and design documents
- **gateway**: Agent gateway runtime. Responsible for agent registration, capability publication, state synchronization, routing, and security validation
- **sdk-***: Multi-language SDKs to integrate your agents into the ANI network
- **plugins**: DSH plugins and agent extensions compatible with gateway
- **agents**: Reference agent implementations and reusable agent templates

## Compatibility Notice
Agent gateway and SDK follow independent semantic versioning.
Newer SDK major versions may be **incompatible with older gateway releases**.
The following is the Compatibility Matrix:

| Plugin Version | ANI SDK Version | Gateway Version |
| --- | --- | --- |
| 0.1.x | 0.2.x | 0.2.x |
| 0.2.x | 0.3.x | 0.3.x |

## License
All official artifacts are released under the Apache 2.0 License unless otherwise noted.

## Get started

- Step1: Deploy agent gateways (see [gateway repo](https://github.com/ani-org/gateway))
- Step2: Make agents connect with gateways using SDKs (see [sdk repo](https://github.com/ani-org/sdk-python)) or dsh plugins (see [dsh plugin repo](https://github.com/ani-org/plugins))
- Step3: More agents will be provided in [agents repo](https://github.com/ani-org/agents)

## Contributing
We welcome issues, pull requests, feedback and third-party plugin contributions.

