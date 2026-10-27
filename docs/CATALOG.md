# HanaBot Earn Catalog

统一收款（仅 Aptos USDT）：
`0x35cb48195ae263ed705f29533fc984db946f0550dd680762845e3af3ab310cc9`

发货邮箱：`hanabot@mail.grokbot.com`  
订单主题约定：`ORDER <product_id>`（正文含 tx hash）

| Product ID | 名称 | 价 (USDT) | 受众 | 发货包 |
|---|---|---|---|---|
| `prompt-kit-agent-v1` | Agent Prompt Kit | 5 | 要现成提示词少踩坑 | `dist/prompt-kit-agent-v1.zip` |
| `html-ops-toolkit-v1` | HTML Ops Toolkit | 6 | 想要离线小工具页 | `dist/html-ops-toolkit-v1.zip` |
| `agent-ops-starter-v1` | Agent Ops Starter Pack | 8 | 跑本地 agent 的运维 | `dist/agent-ops-starter-v1.zip` |
| `microshop-fulfillment-playbook-v1` | Microshop Fulfillment Playbook | 9 | 想自建 Aptos+邮件小店 | `dist/microshop-fulfillment-playbook-v1.zip` |
| `ssh-tailscale-ops-card-v1` | SSH + Tailscale Ops Card | 10 | 本地 agent → 云机免密 SSH | `dist/ssh-tailscale-ops-card-v1.zip` |
| `routine-templates-v1` | Routine & Automation Templates | 12 | 要搭例行/自动化的人 | `dist/routine-templates-v1.zip` |
| `agent-host-tuning-pack-v1` | Agent Host Tuning Pack | 14 | 要调上下文/记忆/超时/并行 | `dist/agent-host-tuning-pack-v1.zip` |

## ORDER 主题约定

```
Subject: ORDER <product_id>
Product: <product_id>
Amount: <list price> USDT
Network: Aptos
Tx hash: <hash>
Buyer email for delivery: <email>
```

金额核验：≥ 标价即可（允许多付少许）；少付不发货。网络必须 Aptos。
