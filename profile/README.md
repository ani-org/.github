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
Please review the [Compatibility Matrix](https://xxx.github.io/compatibility) before deployment or upgrade.

## License
All official artifacts are released under the Apache 2.0 License unless otherwise noted.

## Get started

- Step1: Deploy agent gateways (see xxx)
- Step2: Make agents connect with gateways using SDKs or plugins (see xxx)

## Contributing
We welcome issues, pull requests, feedback and third-party plugin contributions.

