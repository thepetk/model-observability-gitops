# RobotHeus Metrics Contract (v1)

All metrics are Prometheus counters unless noted.

## OpenAI

- robotheus_openai_requests_total{model,project,api_key}
- robotheus_openai_tokens_total{model,project,api_key,direction="input|output"}
- robotheus_openai_cost_usd_total{project} # counter, USD

## Gemini

- robotheus_gemini_requests_total{model,project,api_key}
- robotheus_gemini_tokens_total{model,project,api_key,direction="input|output"}
- robotheus_gemini_cost_usd_total{project} # counter, USD
