# Job Hunter – AI Job Search Agent

## Overview

Job Hunter is an AI agent built using the Hermes framework that searches for job opportunities across Saudi Arabia based on user preferences. The agent filters relevant listings and returns organized job results with direct application links.

---

## Features

- AI-powered job search
- User preference filtering
- Job summarization
- Direct application links
- Telegram integration
- Built using Hermes

---


### File Description

- **config.yaml** – Agent configuration.
- **soul.md** – Defines the agent's personality, behavior, and high-level instructions.
- **SKILL.md** – Contains the agent's operational skills and workflow.

---

# Installation (Hermes)

### Step 1

Create a profile inside Hermes.

---

### Step 2

Press

```
Windows + R
```

then type

```
%appdata%
```

---

### Step 3

Navigate to

```
AppData
└── Local
    └── Hermes
        └── Profiles
```

Open your profile folder.

---

### Step 4

Replace

```
config.yaml
```

with the one provided in this repository.

Replace

```
soul.md
```

with the one provided in this repository.

---

### Step 5

Inside your profile folder you'll find

```
skills/
```

Open it.

Create a folder using your profile name.

Example

```
skills/
└── Job_Hunter/
```

Inside that folder create

```
SKILL.md
```

and paste the provided SKILL.md content from this repository.

The final structure should look like

```
Profiles/
└── Job_Hunter/
    ├── config.yaml
    ├── soul.md
    └── skills/
        └── Job_Hunter/
            └── SKILL.md
```

---

## Using Other AI Agent Frameworks

If you are not using Hermes, simply combine the instructions contained in

- config.yaml
- soul.md
- SKILL.md

into a single system prompt (or equivalent instruction file) supported by your preferred AI agent framework.

---

## Demo

Example:

- Agent searching for jobs
- Telegram returning job links

---

## Integration

In order to make your agent work, you have to provide an API key of an AI model.


## Technologies

- Hermes
- Telegram
- AI Agents