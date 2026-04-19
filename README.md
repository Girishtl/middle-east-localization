# 🌍 Middle East Localization Skill

A Sample  GitHub Copilot AI skill for localizing products and services for Middle Eastern markets with cultural sensitivity, compliance, and market-specific guidelines.

## 📋 Overview

This skill provides expert guidance for localizing digital products and services for Middle Eastern markets, particularly **Saudi Arabia** . It ensures that content, terminology, tone, and behavior align with local cultural norms, compliance requirements, and brand safety guidelines.

Instead of relying on ad-hoc prompts, the desired tone (formal, professional, neutral) and cultural guidelines are defined as part of the skill contract, ensuring **consistent, policy-aligned output** across teams and use cases.

### ✨ Key Features

- **Tone Control**: Enforces formal, professional, and neutral communication standards
- **Terminology Mapping**: Automatically handles culturally sensitive terms (e.g., wine → juice)
- **Compliance Validation**: Ensures content meets local regulations and cultural norms
- **Brand Safety**: Maintains brand consistency while adapting to local context
- **Cultural Respect**: Prevents offensive language and stereotypes
- **Market-Specific Guidelines**: Tailored rules for each Middle Eastern market

## 🎯 Supported Markets

### 🇸🇦 Saudi Arabia (SA)

**Description**: Complete localization services for Saudi Arabia, including translation, cultural adaptation, and market research.

#### Tone Guidelines
- **Allowed**: Formal, professional, neutral
- **Example**: "We welcome your inquiry" (not casual language)

#### Terminology Mapping
| Term | Mapped To | Rationale |
|------|-----------|-----------|
| Wine glasses | Juice glasses | Aligns with Islamic cultural norms |
| Wine goblet | Goblet | Respects local sensitivities |
| Alcohol | Non-alcoholic alternatives | Compliance with local practices |

#### Behavior Standards
- ✅ **Allowed**: Respectful, culturally sensitive, brand-safe messaging
- ❌ **Forbidden**: Offensive language, stereotypes, gender stereotypes, inappropriate content

#### Compliance Requirements
- Adhere to local regulations and cultural norms
- Ensure all content is appropriate for the Saudi Arabian market
- Obtain necessary approvals for culturally sensitive content
- Reference local laws in content decisions

## 🚀 Quick Start: Adding to Copilot CLI

### Prerequisites
- GitHub Copilot CLI installed ([install guide](https://docs.github.com/en/copilot/quickstart-copilot))
- Git installed
- Local development environment configured

### Step 1: Clone the Repository

```bash
git clone https://github.com/Girishtl/middle-east-localization.git


### Step 2: Add the Skill to Copilot CLI

Use the `copilot add --skill` command with the cloned path:

```bash
copilot add --skill ./
```

**Or**, if cloned to a different location:

```bash
copilot add --skill /path/to/middle-east-localization
```

### Step 3: Reload Skills

Reload your Copilot CLI to activate the newly added skill:

```bash
copilot /skills reload
```

### Step 4: Verify Installation

Confirm the skill is installed and ready:

```bash
copilot /skills info middle-east-localization
```

#### Testing in cli
<img width="1097" height="329" alt="image" src="https://github.com/user-attachments/assets/1a16dfd4-87b0-4cc0-a3f3-600fa209a774" />
