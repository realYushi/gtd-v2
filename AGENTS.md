# GTD System Project

This is a comprehensive Getting Things Done (GTD) productivity system built with opencode integration.

## System Overview

The GTD system follows David Allen's methodology with modern automation and AI assistance:

- **Phase 0: Capture** (5 seconds) - Instantly capture any thought or task
- **Phase 1: Daily Planning** (15-20 minutes) - Process inbox and organize tasks  
- **Phase 2: Execution** - Context-aware task execution with focus support
- **Phase 3: Review** (30 minutes weekly) - System maintenance and optimization

## Integration Setup

### Tools & APIs
- **Todoist MCP**: Primary task management system
- **Google Calendar MCP**: Calendar integration for deadlines and time blocking
- **Specialized Agents**: 7 GTD-specific agents for different workflow phases

### File Structure
```
/agents/              # Original agent documentation
/.opencode/agent/     # opencode-compatible agent configs
/newWorkflow.md       # Enhanced GTD workflow specification
/HOW_TO_USE.md        # User guide for the system
/opencode.json        # opencode configuration with GTD modes
```

## Usage Modes

### GTD Mode (Default)
- Full GTD Master Agent system prompt
- All tools enabled for complete workflow management
- Temperature: 0.3 for balanced creativity and focus

### Plan Mode  
- Same GTD Master Agent prompt
- Read-only mode (no file changes or commands)
- Temperature: 0.1 for analytical, focused planning

## Agent Coordination

The **GTD Master Agent** orchestrates specialized agents:

1. **Capture Agent** - Automated task capture from various sources
2. **Daily Planning Agent** - Inbox processing and daily organization
3. **Inbox Review Agent** - Systematic inbox-to-zero processing
4. **Task Selection Agent** - Context-aware task recommendations
5. **Task Organization Agent** - Project management and task structuring
6. **Execution Agent** - Focused work support and interruption handling
7. **Review Phase Agent** - Weekly/monthly reviews and optimization

## Natural Language Commands

The system responds to natural language instructions:

```
"Capture: Call John about project update"
"Plan my day"
"What should I work on? I have 2 hours at home"
"Start weekly review"
"Help me process my inbox"
```

## Automation Features

- **Smart Capture**: Automatic task extraction from emails, calendar events
- **Calendar Sync**: Tasks with deadlines become calendar events
- **Time Blocking**: Important work gets scheduled automatically
- **Context Awareness**: Task suggestions based on location, time, energy
- **Review Insights**: Automated progress summaries and optimization suggestions

## Quick Start

1. Switch to GTD mode: Press Tab key to switch modes
2. Initialize system: `"Initialize my GTD system"`
3. Start capturing: `"Capture: [your first task]"`
4. Begin daily planning: `"Plan my day"`

The Master Agent will guide you through the complete workflow and coordinate all specialized agents automatically.