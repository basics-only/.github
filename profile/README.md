# bae6

## what is this

I keep hearing the same needs over and over again for large organizations trying to integrate
AI into their work. A lot of this exists elsewhere I'm sure. 

However, the purpose of this codebase is to create a set of lightweight, composable tools 
that organizations can pick and choose between to easily integrate into their workflows. 

## do i need this

Need? No, probably not. But if you're at a large organization and have a few skilled people, this probably helps. 

Who are you? You're not a hyperscaler. You have a relatively fixed set of employees/members and you want to roll out high quality functions to them, but you need flexibility to customize and track stuff. 

## how can i contribute

TBD. If you have expertise in any of these areas, please feel free to reach out!
- Authentication/Authorization
- Security
- Context Harnesses

## what's provided

### bae6-ai

Typical AI Gateway services like invocation, token/cost monitoring and limits, etc.

| Provider | Supported |
| - | :-: |
| AWS Bedrock | ✅ |
| GCP Vertex | ✅ |

### bae6-context

| Type | Supported |
| - | :-: |
| Documents | ✅ |
| Retrieval | ✅ |
| MCP | ✅ |
| Data | ✅ |

### bae6-authz

Uses [OpenFGA](https://openfga.dev/)

