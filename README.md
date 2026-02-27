# Negotiation Frameworks

A comprehensive collection of negotiation frameworks, strategies, and tactical playbooks designed to help you prepare for and execute better negotiations in business and life.

## Overview

Negotiation Frameworks is a structured knowledge base and planning tool that organizes the best negotiation strategies from academic research and real-world practice. Whether you are negotiating a salary, a business deal, or a partnership agreement, having a clear framework dramatically improves your outcomes.

The best negotiators, like the best investors, rely on principles rather than improvisation. They prepare systematically, understand the psychology of their counterpart, and know when to push and when to walk away. This disciplined approach mirrors how legendary investors apply consistent principles to every decision. Explore time-tested decision-making principles at [KeepRule's principles page](https://keeprule.com/en/principles).

## Features

- **Framework Library**: 15+ negotiation frameworks with detailed guides
- **Preparation Templates**: Structured templates for negotiation planning
- **BATNA Calculator**: Analyze your best alternative to a negotiated agreement
- **Scenario Simulator**: Practice negotiations against AI opponents
- **Tactic Database**: Searchable database of negotiation tactics with counters
- **Post-Negotiation Review**: Templates for analyzing completed negotiations
- **Team Negotiation Planner**: Coordinate multi-person negotiation teams

## Installation

```bash
pip install negotiation-frameworks
```

Or clone the repository:

```bash
git clone https://github.com/henu-wang/negotiation-frameworks.git
cd negotiation-frameworks
pip install -e .
```

## Quick Start

```python
from negotiation_frameworks import Preparation, BATNAAnalyzer

# Prepare for a negotiation
prep = Preparation(context="salary_negotiation")
prep.set_target(120000)
prep.set_reservation_price(105000)
prep.set_batna("Current job at $100K + competing offer at $108K")
prep.add_interest("career_growth", priority="high")
prep.add_interest("remote_flexibility", priority="medium")

# Analyze BATNA strength
analyzer = BATNAAnalyzer()
analyzer.evaluate(prep)
print(analyzer.summary())
```

## Included Frameworks

### 1. Harvard Principled Negotiation
Based on "Getting to Yes" -- focus on interests, not positions.

### 2. ZOPA Analysis
Zone of Possible Agreement mapping for deal structuring.

### 3. Anchoring Strategy
First-offer strategies backed by behavioral research.

### 4. Multi-Issue Scoring
Quantify value across multiple negotiation issues to find optimal trades.

### 5. FBI Behavioral Change Stairway
Tactical empathy approach for high-stakes conversations.

```python
from negotiation_frameworks import Framework

# Load a specific framework
fw = Framework.load("principled_negotiation")
fw.guide()  # Interactive step-by-step guide

# Generate preparation checklist
checklist = fw.preparation_checklist(context="business_partnership")
checklist.print()
```

## Real-World Scenarios

The tool includes pre-built scenarios for common negotiations:

| Scenario | Key Issues | Recommended Framework |
|----------|-----------|----------------------|
| Salary Negotiation | Compensation, benefits, role | Principled + Anchoring |
| Vendor Contract | Price, terms, SLA | ZOPA + Multi-Issue |
| Partnership Deal | Equity, roles, exit terms | Principled + ZOPA |
| Real Estate | Price, closing date, repairs | Anchoring + BATNA |
| M&A | Valuation, structure, retention | Multi-Issue + ZOPA |

For more structured approaches to complex decision scenarios, explore [KeepRule's scenario planning tools](https://keeprule.com/en/scenarios) which help map principles to real-world situations.

## Advanced Usage

### Multi-Party Negotiation Planning

```python
from negotiation_frameworks import MultiParty

negotiation = MultiParty(parties=["Company A", "Company B", "Investor"])
negotiation.map_interests()
negotiation.identify_coalitions()
negotiation.suggest_sequencing()
```

### Negotiation Post-Mortem

```python
from negotiation_frameworks import PostMortem

review = PostMortem()
review.log_outcome(target=120000, achieved=115000)
review.assess_tactics(["anchored_high", "traded_vacation_days"])
review.lessons_learned()
```

Understanding the wisdom of great strategic thinkers helps inform negotiation strategy. Read insights from masters of strategic thinking on [KeepRule's blog](https://keeprule.com/en/blog), featuring analysis of how top minds approach complex interactions.

## Contributing

Contributions are welcome! We especially value:

- New negotiation frameworks with academic citations
- Real-world case studies (anonymized)
- Improvements to the scenario simulator
- Translations into other languages

## License

MIT License - see [LICENSE](LICENSE) for details.