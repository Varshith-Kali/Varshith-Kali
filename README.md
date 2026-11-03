# Varshith Puli

AI Security Analyst building the security layer for AI agents, LLM applications, and multi-agent systems.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/varshith-puli)
[![Email](https://img.shields.io/badge/Email-pulivarshit%40gmail.com-blue)](mailto:pulivarshit@gmail.com)

## Focus

- **AI red-teaming**: LLM vulnerability assessment, probe development
- **MCP / agentic security**: Model Context Protocol scanning, tool-use safety
- **LLM guardrails**: content safety policy enforcement
- **DevSecOps**: SAST rules, supply-chain and dependency security

## Open source contributions

[![Kestra Contributor](https://img.shields.io/badge/16%20PRs%20MERGED-KESTRA-1F232C?style=for-the-badge&logo=github&logoColor=200062&labelColor=CDC5FE)](https://github.com/search?q=org:kestra-io+author:Varshith-Kali+is:pr+is:merged&type=pullrequests)

**54 pull requests merged** by project maintainers across 14 repositories, and **79 more open** upstream. (Counts verified against GitHub, 3 November 2026.)

### Merged pull requests

| Repository | PR | Work |
|---|---|---|
| kestra-io/blueprints | [#3326](https://github.com/kestra-io/blueprints/pull/3326) | AI agent output safety gate with secrets and PII detection plus LLM-judged triage |
| kestra-io/blueprints | [#4353](https://github.com/kestra-io/blueprints/pull/4353) | AI agent input firewall against prompt injection |
| kestra-io/blueprints | [#4360](https://github.com/kestra-io/blueprints/pull/4360) | AI agent red-team probe harness |
| kestra-io/blueprints | [#4777](https://github.com/kestra-io/blueprints/pull/4777) | AI agent golden prompt regression harness |
| kestra-io/blueprints | [#4779](https://github.com/kestra-io/blueprints/pull/4779) | AI agent tool-call compliance audit |
| kestra-io/blueprints | [#4780](https://github.com/kestra-io/blueprints/pull/4780) | AI agent session leakage scanner |
| kestra-io/blueprints | [#4784](https://github.com/kestra-io/blueprints/pull/4784) | MCP server security regression harness |
| kestra-io/blueprints | [#4805](https://github.com/kestra-io/blueprints/pull/4805) | AI answer grounding and citation guard |
| kestra-io/blueprints | [#4823](https://github.com/kestra-io/blueprints/pull/4823) | Leaver access revocation verification gate |
| kestra-io/blueprints | [#4827](https://github.com/kestra-io/blueprints/pull/4827) | Break-glass privileged account use watchdog |
| kestra-io/blueprints | [#4926](https://github.com/kestra-io/blueprints/pull/4926) | AI agent config change watchdog |
| kestra-io/plugin-elasticsearch | [#147](https://github.com/kestra-io/plugin-elasticsearch/pull/147) | Honor native bulk update bodies in Bulk |
| kestra-io/plugin-elasticsearch | [#151](https://github.com/kestra-io/plugin-elasticsearch/pull/151) | Carry bulk action metadata onto operations |
| kestra-io/plugin-mongodb | [#199](https://github.com/kestra-io/plugin-mongodb/pull/199) | Reject chunk below 1 in Load and Bulk |
| kestra-io/plugin-mongodb | [#204](https://github.com/kestra-io/plugin-mongodb/pull/204) | Keep ObjectId type through Find store then Load copy |
| kestra-io/plugin-serdes | [#458](https://github.com/kestra-io/plugin-serdes/pull/458) | Keep boolean-like strings in string columns with inferAllFields |
| aws-cloudformation/cfn-lint | [#4781](https://github.com/aws-cloudformation/cfn-lint/pull/4781) | Require at least one resource in the Resources section (E1001) |
| aws-cloudformation/cfn-lint | [#4782](https://github.com/aws-cloudformation/cfn-lint/pull/4782) | Stringify E3601 path segments so array indices do not crash message formatting |
| aws-cloudformation/cfn-lint | [#4786](https://github.com/aws-cloudformation/cfn-lint/pull/4786) | Do not crash when a resource or output condition can never be true |
| aws-cloudformation/cfn-lint | [#4787](https://github.com/aws-cloudformation/cfn-lint/pull/4787) | Stop E8001 rejecting condition names CloudFormation accepts |
| aws-cloudformation/cfn-lint | [#4792](https://github.com/aws-cloudformation/cfn-lint/pull/4792) | fix: E3045 flag AccessControl with BucketOwnerEnforced OwnershipControls |
| aws-cloudformation/cfn-lint | [#4793](https://github.com/aws-cloudformation/cfn-lint/pull/4793) | Allow Fn::If and nested Fn::Select as the Fn::Select index |
| aws-cloudformation/cfn-lint | [#4805](https://github.com/aws-cloudformation/cfn-lint/pull/4805) | Extend Fn::Equals mutual-exclusion beyond AllowedValues parameters |
| aws-cloudformation/cfn-lint | [#4806](https://github.com/aws-cloudformation/cfn-lint/pull/4806) | Fix E3688 false positives on IpProtocol "-1", icmpv6 and "ICMP" rules |
| aws-cloudformation/cfn-lint | [#4809](https://github.com/aws-cloudformation/cfn-lint/pull/4809) | Allow array form for AWS::CloudFormation::Init commands |
| aws-cloudformation/cfn-lint | [#4810](https://github.com/aws-cloudformation/cfn-lint/pull/4810) | fix(E1011): skip FindInMap key errors when map name comes from a parameter Default |
| aws-cloudformation/cfn-lint | [#4814](https://github.com/aws-cloudformation/cfn-lint/pull/4814) | Report non-string condition names instead of crashing (E8001) |
| aws-cloudformation/cfn-lint | [#4828](https://github.com/aws-cloudformation/cfn-lint/pull/4828) | Accept resolve:ssm: ImageId on AWS::EC2::Instance (E1152) |
| aws-cloudformation/cfn-lint | [#4830](https://github.com/aws-cloudformation/cfn-lint/pull/4830) | Accept neptune and sqlserver-dev engines in E3690/E3691 |
| aws-cloudformation/cfn-lint | [#4842](https://github.com/aws-cloudformation/cfn-lint/pull/4842) | Do not require StorageEncrypted on RDS read replicas (E3720) |
| aws-cloudformation/cfn-lint | [#4843](https://github.com/aws-cloudformation/cfn-lint/pull/4843) | Skip DependsOn check when target condition is always true (E3005) |
| aws-cloudformation/cfn-lint | [#4844](https://github.com/aws-cloudformation/cfn-lint/pull/4844) | Skip Automation schema for AppConfig SSM document types (E3051) |
| aws-cloudformation/cfn-lint | [#4860](https://github.com/aws-cloudformation/cfn-lint/pull/4860) | Measure Lambda environment size as compact JSON bytes (E3697) |
| aws-cloudformation/cfn-lint | [#4862](https://github.com/aws-cloudformation/cfn-lint/pull/4862) | fix(E3530): flag NotPrincipal, group ARNs, and string "*" in role trust policies |
| aws-cloudformation/cfn-lint | [#4870](https://github.com/aws-cloudformation/cfn-lint/pull/4870) | Scope E3062 DBInstanceClass enum per engine |
| aws-cloudformation/cfn-lint | [#4902](https://github.com/aws-cloudformation/cfn-lint/pull/4902) | fix(E3051): validate SSM Document Content given as a JSON string |
| aws-cloudformation/cfn-lint | [#4917](https://github.com/aws-cloudformation/cfn-lint/pull/4917) | Count subscription filters per condition scenario (E2529) |
| aws-cloudformation/cfn-lint | [#4919](https://github.com/aws-cloudformation/cfn-lint/pull/4919) | Report bad Fn::FindInMap keys in unconstrained positions (E1011) |
| aws-cloudformation/cfn-lint | [#4920](https://github.com/aws-cloudformation/cfn-lint/pull/4920) | Skip NumCacheClusters check for cluster mode groups sized by NodeGroupConfiguration or ReplicasPerNodeGroup (E3026) |
| cisco-ai-defense/mcp-scanner | [#244](https://github.com/cisco-ai-defense/mcp-scanner/pull/244) | Bound wildcard gaps in coercive_injection and credential_harvesting YARA rules |
| cisco-ai-defense/mcp-scanner | [#276](https://github.com/cisco-ai-defense/mcp-scanner/pull/276) | Bind only/must gaps in coercive_injection execution overrides to clause boundaries |
| cisco-ai-defense/mcp-scanner | [#283](https://github.com/cisco-ai-defense/mcp-scanner/pull/283) | Remove local import os that shadowed the module import in main() |
| NVIDIA/SkillSpector | [#893](https://github.com/NVIDIA/SkillSpector/pull/893) | Score writes to agent-memory files as MP3 memory manipulation |
| NVIDIA/SkillSpector | [#898](https://github.com/NVIDIA/SkillSpector/pull/898) | Fix deterministic layer failing closed on ordinary lists of verb names |
| NVIDIA/SkillSpector | [#902](https://github.com/NVIDIA/SkillSpector/pull/902) | Stop backticks/apostrophes in comments and prose from tripping static_parse_limit |
| tester-army/e2e | [#1215](https://github.com/tester-army/e2e/pull/1215) | Map the SDK's NoOutputGeneratedError to MODEL_OUTPUT_INVALID |
| tester-army/e2e | [#1233](https://github.com/tester-army/e2e/pull/1233) | Exit 3 when a passed test's cleanup failed |
| JustVugg/colibri | [#2103](https://github.com/JustVugg/colibri/pull/2103) | Fix COLI_KV_SHARE cross-slot adoption under KV8/KV_TQ |
| JustVugg/colibri | [#2104](https://github.com/JustVugg/colibri/pull/2104) | Refuse over-context prompts with CONTEXT_EXCEEDED instead of silently truncating |
| langflow-ai/langflow | [#14502](https://github.com/langflow-ai/langflow/pull/14502) | Replace eval() with safe literal construction in schema.py |
| thedotmack/claude-mem | [#4777](https://github.com/thedotmack/claude-mem/pull/4777) | Verify the tree-sitter CLI loads, not just exists |
| promptfoo/promptfoo | [#10494](https://github.com/promptfoo/promptfoo/pull/10494) | Tag RAG grader failures so inverse assertions cannot pass |
| GitGuardian/ggshield | [#1562](https://github.com/GitGuardian/ggshield/pull/1562) | Anchor local hook dir to repo root when run from a subdirectory |
| trufflesecurity/trufflehog | [#5445](https://github.com/trufflesecurity/trufflehog/pull/5445) | Add Infisical service token detector |

### Selected work under review

| Repository | Work | Status |
|---|---|---|
| NVIDIA/garak [#1974](https://github.com/NVIDIA/garak/pull/1974) | AART probe for AI-assisted red-teaming | Open |
| BerriAI/litellm [#47846](https://github.com/BerriAI/litellm/pull/47846) | JWKS stale-while-revalidate refresh for JWT validation | Open |
| promptfoo/promptfoo [#11832](https://github.com/promptfoo/promptfoo/pull/11832) | Bounded redirect fetching with guaranteed body cancellation | Open |
| delphisecurity/xaidr [#44](https://github.com/delphisecurity/xaidr/pull/44) | Fix ANSI-C quoting bypass in command scanning (self-found, disclosed to the maintainers first) | Open |
| guardrails-ai/guardrails [#1666](https://github.com/guardrails-ai/guardrails/pull/1666) | Hub auth token expiry hardening | Open |
| trailofbits/mcp-context-protector [#56](https://github.com/trailofbits/mcp-context-protector/pull/56) | Typed exception hierarchy | Open |
| aws-cloudformation/cfn-lint [#4964](https://github.com/aws-cloudformation/cfn-lint/pull/4964) | Pass the whole Fn::Sub value to child rules, restoring W1019 reporting | Open |

## Stack

**Languages:** Python, TypeScript, SQL
**Security:** Garak, Semgrep, Bandit, OWASP Top 10 for LLM & Agentic AI
**AI/Infra:** LangChain, FastAPI, Docker, GitHub Actions, CI/CD

## GitHub Stats

![stats](https://github-readme-stats.vercel.app/api?username=Varshith-Kali&theme=dark&hide_border=false&hide_rank=true&hide=stars&count_private=true&show_icons=true)
![top-langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Varshith-Kali&theme=dark&hide_border=false&layout=donut&hide=HTML&count_private=true)

---

*Open to collaboration on AI security tooling, MCP security research, and multi-agent system hardening.*
