# Fireflies.ai Recent Announcements

## Overview
This wiki page summarizes the key headlines and developments from Fireflies.ai's recent major announcements in June 2025.

## Major Headlines

### 🚀 $1 Billion Valuation Achievement (June 12, 2025)
- **Milestone**: Fireflies.ai reached over $1 billion valuation following first tender offer
- **Profitability**: Company has remained profitable since 2023 (rare among AI startups)
- **Growth**: Sustaining triple-digit year-over-year growth without raising primary capital since 2021
- **Scale**: Serving 20+ million people across 500,000+ organizations globally
- **Enterprise Adoption**: Used by people at 75% of Fortune 500 companies

### 🔍 "Talk to Fireflies" Feature Launch (June 12, 2025)
- **Voice Activation**: Users can engage with "Hey Fireflies!" voice commands during meetings
- **Real-time Web Search**: Partnership with Perplexity enables live internet search during meetings
- **Multi-language Support**: Available in over 60 languages
- **Platform Compatibility**: Works across Zoom, Google Meet, and Microsoft Teams
- **Free Access**: Available to all users, including free plan users

#### Key Use Cases:
- **Meeting Context**: "Hey Fireflies, what key decisions have been made so far?"
- **Industry Research**: "Hey Fireflies, what are the latest market trends in online retail?"
- **Technical Information**: "Hey Fireflies, what's the difference between OAuth and SAML authentication?"
- **Regulatory Information**: "Hey Fireflies, what are the current SEC reporting requirements?"

### 🔧 MCP Server Beta Launch (June 25, 2025)
- **Protocol Integration**: Introduced Model Context Protocol (MCP) Server
- **AI Agent Access**: Direct integration with AI tools and agents
- **Data Access**: Provides transcripts, meeting metadata, speaker information, and summaries
- **Time Savings**: Transforms 2-3 hours of manual transcript review into 5-minute AI analysis
- **Security**: Uses existing API key authentication with same security standards

#### Technical Features:
- **OAuth Integration**: Simple setup with Google/Microsoft OAuth
- **Claude Integration**: Native support for Claude Desktop and Web
- **API Access**: RESTful API for custom integrations
- **Real-time Queries**: Direct access to meeting data for AI analysis

## Partnership Details

### Fireflies + Perplexity Partnership
- **Integration Type**: First-of-its-kind voice-activated web search in meetings
- **Bidirectional Access**: Perplexity users can query Fireflies data from their dashboard
- **Special Offers**:
  - Fireflies Pro/Business: 1 year of Perplexity Pro free
  - Fireflies Enterprise: 3 months of Perplexity Enterprise Pro free
  - Perplexity Pro users: 3 months of Fireflies Business free

## Leadership Quotes

### CEO Krish Ramineni
> "We wanted to recognize our earliest employees who've been vital to Fireflies' journey. Reaching this significant valuation milestone while remaining profitable validates our approach to building an AI company differently from the conventional 'raise big, burn fast' playbook."

> "Talk to Fireflies lets people search the web in real-time and get answers about the current meeting... This turns Fireflies into your most knowledgeable teammate."

### Perplexity's Dmitry Shevelenko (Chief Business Officer)
> "Meetings are where critical decisions happen, but they're often information-poor environments. By integrating Perplexity's search capabilities into Fireflies, we're eliminating the need to switch contexts or postpone decisions."

## Future Roadmap

### Upcoming Features
- **AI Voice Agents**: Agents that can attend meetings entirely on behalf of users
- **Enhanced Search**: Ability to search across user's entire meeting database
- **Regular Tender Offers**: More frequent liquidity events for employees
- **Agentic Capabilities**: Advanced AI automation for meeting workflows

## Company Background
- **Founded**: Remote-first, global organization
- **Team Size**: 100 people across 20+ countries
- **Investors**: Backed by Khosla Ventures and Canaan Partners
- **Processing Scale**: Over 2 billion meeting minutes processed
- **Security**: Enterprise-grade with private storage options
- **Privacy**: Never uses customer meeting data to train AI models

## Technical Implementation

### For Developers
- **MCP Server Setup**: Available via npm package
- **API Integration**: RESTful API with comprehensive documentation
- **Security**: API key and OAuth authentication options
- **Platform Support**: Works with major conferencing platforms

### Getting Started with MCP
```json
{
  "mcpServers": {
    "fireflies": {
      "command": "npx",
      "args": [
        "mcp-remote",
        "https://api.fireflies.ai/mcp"
      ]
    }
  }
}
```

## Resources
- [Official Website](https://fireflies.ai)
- [MCP Server Documentation](https://guide.fireflies.ai)
- [API Documentation](https://fireflies.ai/api)
- [Blog Announcements](https://fireflies.ai/blog)

## How to Use This Wiki
This page serves as a reference for the latest Fireflies.ai developments and can be:
- Updated with new announcements as they're released
- Referenced when planning meeting automation strategies  
- Shared with team members evaluating AI meeting tools

## Contributing
To update this wiki with new Fireflies announcements:
1. Monitor [Fireflies.ai blog](https://fireflies.ai/blog) for updates
2. Add new headlines under appropriate sections
3. Update the "Last Updated" date below

---

*Last Updated: August 2, 2025*
*Source: Fireflies.ai official announcements and press releases*
*Created for: mrjcleaver/test-agentic-meetings-wiki*