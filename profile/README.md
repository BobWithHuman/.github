![WithHuman Logo](withhuman_logo_exact.svg "WithHuman Logo")

## Welcome!

**WithHuman** is an execution-time security engine that blocks AI agent actions that deviate from the user's intent. Right before an agent invokes an external tool, WithHuman analyzes the **user's original intent**, the **actual tool call and its arguments**, and the **execution context/trace** together.

While traditional prompt injection defenses focus on detecting malicious prompts at the input stage, WithHuman verifies **whether the action that is about to happen actually matches what the user intended** — not the prompt itself. It hooks into the `before_tool_call` point between the agent and its tools and decides on every request as **ALLOW**, **DENY**, or **REVIEW**. WithHuman aims to control not only Indirect Prompt Injection, Tool Output Injection, and RAG/MCP-based attacks, but also unintended tool calls that occur when an agent misinterprets the user's request, even without any malicious input.

## Project Resources

* [Landing Page](https://github.com/BobWithHuman/bobwithhuman.github.io)
* [Documentation](https://bobwithhuman.github.io/docs/)
* Need help? Open an [Issue](https://github.com/BobWithHuman/withhuman-core/issues)

## Repositories

* **[withhuman-core](https://github.com/BobWithHuman/withhuman-core)**
WithHuman Engine ([Issues](https://github.com/BobWithHuman/withhuman-core/issues) · [Pull Requests](https://github.com/BobWithHuman/withhuman-core/pulls))
* **[docs](https://github.com/BobWithHuman/docs)**
Documentation for the WithHuman project
* **[.github](https://github.com/BobWithHuman/.github)**
Organization profile and community health files

## Code of Conduct

This project follows the [Contributor Covenant Code of Conduct](https://github.com/BobWithHuman/.github/blob/main/CODE_OF_CONDUCT.md). Please report unacceptable behavior to the [organization](https://github.com/BobWithHuman) maintainers.

## Security

If you think you have discovered a security issue in this project, please report it privately via [Security Advisory](https://github.com/BobWithHuman/withhuman-core/security/advisories/new); do **NOT** open a public issue. See [SECURITY](https://github.com/BobWithHuman/.github/blob/main/SECURITY.md).

## License

This project is licensed under the [MIT License](https://github.com/BobWithHuman/.github/blob/main/LICENSE.md).
