# Weekly Agent Framework Updates

📊 Weekly digest of what's happening in AI agent frameworks. New releases, trending repos, breaking changes, and deprecations.

[![Weekly Updates](https://img.shields.io/badge/Updated-Weekly-green.svg)](https://www.agentically.sh/ai-agentic-frameworks/updates/)
[![Subscribers](https://img.shields.io/badge/Subscribers-15k+-blue.svg)](https://www.agentically.sh/ai-agentic-frameworks/subscribe/)
[![Frameworks Tracked](https://img.shields.io/badge/Frameworks-40+-orange.svg)](https://www.agentically.sh/ai-agentic-frameworks/all/)

## 📈 This Week's Highlights (Oct 15-22, 2025)

### 🚀 Major Releases

**CrewAI v0.12.0** - Native Memory Management
- ✨ **New**: Built-in conversation memory across tasks
- 🔧 **Improved**: 23% faster task execution  
- 🐛 **Fixed**: Memory leaks in long-running crews
- 📖 [Release Notes](https://github.com/joaomdmoura/crewAI/releases/tag/v0.12.0)
- 🎯 **Migration**: [LangChain → CrewAI guide updated](https://www.agentically.sh/ai-agentic-frameworks/migrate/langchain-to-crewai/)

**AutoGen v0.2.15** - Performance Optimizations  
- ⚡ **Performance**: 18% memory usage reduction
- 🆕 **Feature**: Custom tool registration API
- 🔒 **Security**: Enhanced conversation filtering
- 📖 [Release Notes](https://github.com/microsoft/autogen/releases/tag/v0.2.15)

**LangGraph v0.0.45** - Parallel Processing
- 🔄 **New**: Parallel node execution (31% faster)
- 🛠️ **Tools**: Improved debugging interface
- 📊 **Monitoring**: Built-in performance metrics
- 📖 [Release Notes](https://github.com/langchain-ai/langgraph/releases/tag/v0.0.45)

### 📈 Trending Repositories

1. **SmolAgents** (+2,341 ⭐ this week)
   - Lightweight agent framework for resource-constrained environments
   - [Repository](https://github.com/huggingfaceh4/smolagents) | [Quick Start](https://www.agentically.sh/ai-agentic-frameworks/smolagents/)

2. **OpenAI AgentKit** (+1,892 ⭐ this week)  
   - Official OpenAI framework for building agents
   - [Repository](https://github.com/openai/agentkit) | [Comparison](https://www.agentically.sh/ai-agentic-frameworks/compare/openai-agentkit/)

3. **Anthropic Agent Framework** (+1,456 ⭐ this week)
   - Native Claude integration with tool use
   - [Repository](https://github.com/anthropics/agent-framework) | [Guide](https://www.agentically.sh/ai-agentic-frameworks/anthropic/)

### ⚠️ Breaking Changes & Deprecations

**LangChain Agent Deprecation**
- 🚨 **Breaking**: `initialize_agent` deprecated in favor of `create_react_agent`
- 📅 **Timeline**: Removal in v0.3.0 (estimated Dec 2025)
- 🔧 **Migration**: [Automated migration tool](https://www.agentically.sh/ai-agentic-frameworks/langchain-agent-migration/)

**Haystack Agents API Change**
- 🔄 **Change**: Agent initialization syntax updated
- 📖 **Guide**: [Migration documentation](https://docs.haystack.deepset.ai/v2.0/docs/migrating-from-haystack-1x)
- ⏰ **Action Required**: Update by Nov 15, 2025

[View all breaking changes →](https://www.agentically.sh/ai-agentic-frameworks/breaking-changes/)

## 📊 Framework Performance Updates

### Speed Improvements This Week
- **CrewAI**: 23% faster (v0.12.0 optimizations)
- **LangGraph**: 31% faster (parallel processing)
- **AutoGen**: 12% faster (memory optimizations)

### New Benchmarks
Updated performance benchmarks for all frameworks:
- [Interactive benchmark explorer →](https://www.agentically.sh/ai-agentic-frameworks/benchmarks/)
- [Framework speed comparison →](https://www.agentically.sh/ai-agentic-frameworks/benchmarks/speed/)

## 🆕 New Framework Additions

### OpenAI AgentKit
- **Description**: Official OpenAI framework for building agents
- **Key Features**: Native GPT-4 integration, tool calling, streaming
- **Best For**: OpenAI-first applications
- **Get Started**: [Quick start guide →](https://www.agentically.sh/ai-agentic-frameworks/openai-agentkit/)

### Anthropic Agent Framework  
- **Description**: Claude-native agent development
- **Key Features**: Constitutional AI, tool use, safety controls
- **Best For**: Safety-critical applications
- **Get Started**: [Setup guide →](https://www.agentically.sh/ai-agentic-frameworks/anthropic/)

### SmolAgents
- **Description**: Lightweight agents for edge deployment
- **Key Features**: <50MB memory footprint, edge optimization
- **Best For**: IoT and mobile applications
- **Get Started**: [Installation guide →](https://www.agentically.sh/ai-agentic-frameworks/smolagents/)

## 🔧 Tool & Integration Updates

### New Integrations
- **CrewAI + Zapier**: Workflow automation integration
- **AutoGen + Slack**: Native Slack bot framework
- **LangChain + Notion**: Knowledge base connector

### Updated Tools
- **SerperDevTool**: Enhanced search accuracy (CrewAI)
- **CodeInterpreter**: Python 3.11 support (AutoGen)
- **VectorStore**: Improved embedding search (LangChain)

[View all integrations →](https://www.agentically.sh/ai-agentic-frameworks/integrations/)

## 📝 Community Highlights

### Featured Tutorials
1. **"Building Production Agents with CrewAI"** by @techblogger
   - 45-minute tutorial covering deployment, monitoring, scaling
   - [Watch on YouTube](https://youtube.com/watch?v=example)

2. **"AutoGen for Code Review Automation"** by @devops_guru  
   - Complete guide to PR automation with AutoGen
   - [Read article](https://blog.example.com/autogen-code-review)

3. **"LangGraph State Management Patterns"** by @ai_architect
   - Advanced patterns for stateful agent workflows
   - [GitHub repository](https://github.com/example/langgraph-patterns)

### Community Projects
- **AgentHub**: Community-driven agent marketplace
- **Framework Benchmarks**: Open-source performance testing
- **Migration Tools**: Automated framework migration utilities

## 📈 Market Analysis

### GitHub Stars Growth (Weekly)
```
Framework Growth This Week:
SmolAgents      ████████████████ +2,341
OpenAI AgentKit ████████████     +1,892  
Anthropic       ████████         +1,456
CrewAI         ██████           +1,124
AutoGen        ████             +892
LangChain      ███              +678
LangGraph      ██               +567
```

### Download Statistics
- **CrewAI**: 1.2M downloads (+15% week-over-week)
- **AutoGen**: 890K downloads (+8% week-over-week)
- **LangChain**: 2.8M downloads (+3% week-over-week)

### Developer Survey Results
Recent survey of 5,000 developers:
- 67% plan to adopt AI agents in next 6 months
- CrewAI leads in "most likely to try" (34%)
- AutoGen tops "current usage" (28%)

[Full market report →](https://www.agentically.sh/ai-agentic-frameworks/market-report/)

## 🔮 Next Week Preview

### Expected Releases
- **LangChain v0.1.0**: Major version with agent improvements
- **CrewAI v0.12.1**: Bug fixes and performance patches
- **Haystack v2.0.1**: Post-migration stability improvements

### Events & Webinars
- **Oct 24**: CrewAI Community Call (2 PM EST)
- **Oct 25**: AutoGen Office Hours (11 AM PST)
- **Oct 26**: LangChain Developer Webinar (1 PM EST)

### Framework Conferences
- **AI Agent Summit** (Nov 15-16, SF): All major frameworks presenting
- **LangChain Conference** (Dec 5-6, Virtual): LangGraph deep dive

## 📚 Learning Resources

### New Documentation
- [CrewAI Memory Management Guide](https://docs.crewai.com/memory/)
- [AutoGen Tool Development Tutorial](https://microsoft.github.io/autogen/docs/tutorial/tool-use)
- [LangGraph Parallel Processing Examples](https://langchain-ai.github.io/langgraph/tutorials/parallel/)

### Updated Guides
- [Migration from LangChain to CrewAI](https://www.agentically.sh/ai-agentic-frameworks/migrate/langchain-to-crewai/)
- [Production Deployment Best Practices](https://www.agentically.sh/ai-agentic-frameworks/production/)
- [Cost Optimization Strategies](https://www.agentically.sh/ai-agentic-frameworks/cost-optimization/)

## 🎯 Action Items for Developers

### This Week
- [ ] Update CrewAI to v0.12.0 for memory improvements
- [ ] Review LangChain deprecation warnings in your projects
- [ ] Test AutoGen v0.2.15 performance improvements
- [ ] Explore OpenAI AgentKit for new projects

### This Month  
- [ ] Plan migration from deprecated LangChain agents
- [ ] Evaluate new frameworks for upcoming projects
- [ ] Update production monitoring for performance gains
- [ ] Review and optimize token usage costs

## 📧 Stay Connected

### Subscribe to Updates
- 📧 [Weekly Email Digest](https://www.agentically.sh/ai-agentic-frameworks/subscribe/) - 15,000+ subscribers
- 🐦 [Twitter @agenticallysh](https://twitter.com/agenticallysh) - Real-time updates
- 💬 [Discord Community](https://discord.gg/agentically) - Live discussions
- 📱 [Mobile App](https://app.agentically.sh) - Push notifications

### RSS & API
- 📡 [RSS Feed](https://www.agentically.sh/ai-agentic-frameworks/updates/rss.xml)
- 🔌 [Updates API](https://api.agentically.sh/v1/framework-updates)
- 📊 [Webhook Integration](https://www.agentically.sh/ai-agentic-frameworks/webhooks/)

## 📖 Previous Updates

### Recent Weeks
- [Oct 8-15, 2025](./updates/2025-10-15.md) - LangChain v0.3 beta, CrewAI integrations
- [Oct 1-8, 2025](./updates/2025-10-08.md) - AutoGen multimodal support, new benchmarks
- [Sep 24-Oct 1, 2025](./updates/2025-10-01.md) - Haystack 2.0 release, performance updates

### Archive
- [All 2025 Updates](./archive/2025/)
- [Framework Launch Timeline](./timeline.md)
- [Major Release History](./releases.md)

[Browse update archive →](https://www.agentically.sh/ai-agentic-frameworks/updates/archive/)

## 🤝 Contributing

### Submit News
- [Framework Release](https://github.com/agenticallysh/weekly-agent-updates/issues/new?template=release.md) - New version announcements
- [Breaking Change](https://github.com/agenticallysh/weekly-agent-updates/issues/new?template=breaking-change.md) - Deprecations and changes
- [Community Highlight](https://github.com/agenticallysh/weekly-agent-updates/issues/new?template=community.md) - Tutorials and projects

### Newsletter Sponsorship
Reach 15,000+ AI developers weekly:
- [Sponsorship Information](https://www.agentically.sh/ai-agentic-frameworks/sponsor/)
- [Media Kit](https://www.agentically.sh/ai-agentic-frameworks/media-kit/)

## 🔗 Quick Links

- [All AI Agent Frameworks →](https://github.com/agenticallysh/ai-agentic-frameworks)
- [Framework Comparison Tool →](https://www.agentically.sh/ai-agentic-frameworks/compare/)
- [Performance Benchmarks →](https://github.com/agenticallysh/agent-framework-benchmarks)
- [Migration Guides →](https://github.com/agenticallysh/agentic-framework-migration-guides)
- [Production Templates →](https://github.com/agenticallysh/production-agent-templates)
- [Cost Calculator →](https://github.com/agenticallysh/framework-cost-calculator)

---

Built with ❤️ by [Agentically](https://www.agentically.sh) | [Subscribe for Updates →](https://www.agentically.sh/ai-agentic-frameworks/subscribe/)