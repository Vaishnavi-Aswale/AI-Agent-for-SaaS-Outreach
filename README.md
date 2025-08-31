# AI Email Agent for SaaS

An intelligent B2B outreach automation tool that helps SaaS companies find potential clients, research them, and generate personalized outreach emails at scale.

## Features

- **Company Discovery**: Find companies that match your ideal customer profile
- **Contact Identification**: Identify key decision makers at target companies
- **Automated Research**: Gather insights about target companies from their websites and Reddit
- **Personalized Email Generation**: Create tailored outreach emails in different styles
- **Streamlit Web Interface**: Easy-to-use interface for managing outreach campaigns

## Prerequisites

- Python 3.8+
- OpenAI API key
- Exa API key (for web search functionality)
- Required Python packages (install via `pip install -r requirements.txt`)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Vaishnavi-Aswale/AI-Agent-for-SaaS-Outreach.git
   cd ai-email-agent-saas
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up environment variables:
   ```bash
   export OPENAI_API_KEY='your-openai-api-key'
   export EXA_API_KEY='your-exa-api-key'
   ```

## Usage

1. Run the Streamlit application:
   ```bash
   streamlit run ai_email_agent_for_saas.py
   ```

2. In the web interface:
   - Enter your target company description
   - Describe your offering
   - Configure email style (Professional, Casual, Cold, or Consultative)
   - Set the number of companies to target
   - Provide sender information
   - Run the pipeline

## Email Styles

- **Professional**: Businesslike and respectful communication
- **Casual**: Friendly and approachable tone
- **Cold**: Direct with strong hooks and clear CTAs
- **Consultative**: Insight-led with tailored solutions

## Configuration

Edit the `ai_email_agent_for_saas.py` file to customize:
- Default email styles
- Target roles for contact finding
- Research parameters
- Email templates and CTAs
