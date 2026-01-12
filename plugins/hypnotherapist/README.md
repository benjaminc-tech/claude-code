# Hypnotherapist Plugin

A professional hypnotherapy chatbot plugin for Claude Code that provides guided relaxation sessions, stress relief, and therapeutic support through text-based hypnosis techniques.

## Overview

The Hypnotherapist plugin transforms Claude into a calming, compassionate hypnotherapist who can guide you through:
- Deep relaxation and stress reduction
- Sleep improvement techniques
- Confidence building exercises
- Anxiety relief practices
- General wellness and mindfulness

## Features

### Interactive Hypnotherapy Sessions
- **Full guided sessions** following professional hypnotherapy structure
- **7-phase approach**: Connection → Pre-Induction → Induction → Deepening → Therapeutic Work → Awakening → Post-Session
- **Customizable focus areas**: Sleep, anxiety, confidence, pain management, habits, and more
- **Soothing therapeutic language** with proper pacing and rhythm

### Custom Script Creation
- **Therapeutic Script Writer agent** for creating personalized hypnotherapy scripts
- **Multiple therapeutic modalities**: Ericksonian hypnosis, NLP, progressive relaxation, guided imagery
- **Goal-specific techniques** for various therapeutic intentions

## Installation

This plugin is part of the Claude Code plugin ecosystem. If you're viewing this in the repository, it's already available.

To enable the plugin:
1. Ensure you're using Claude Code CLI
2. The plugin should be automatically detected in the `plugins/` directory
3. Access commands using the slash command syntax

## Usage

### Starting a Hypnotherapy Session

```bash
/hypnotherapist:session
```

Or specify a focus area:

```bash
/hypnotherapist:session sleep
/hypnotherapist:session anxiety
/hypnotherapist:session confidence
```

### Example Session Flow

1. **You run**: `/hypnotherapist:session`
2. **Claude asks**: What brings you to this session?
3. **You respond**: "I've been feeling stressed and need to relax"
4. **Claude guides you through**:
   - Initial connection and rapport building
   - Pre-induction (getting comfortable)
   - Induction phase (progressive relaxation)
   - Deepening (going deeper into relaxation)
   - Therapeutic work (addressing stress with techniques and suggestions)
   - Awakening (bringing you back gently)
   - Post-session check-in

### Creating Custom Scripts

Use the Task tool to invoke the therapeutic script writer agent:

```bash
"Can you use the therapeutic-script-writer agent to create a custom sleep script for me?"
```

## Therapeutic Approach

### Evidence-Based Techniques

The plugin incorporates established hypnotherapy methods:
- **Progressive Muscle Relaxation (PMR)**
- **Guided Imagery and Visualization**
- **Breath Awareness and Mindfulness**
- **Ericksonian Hypnosis** (indirect suggestions, metaphors)
- **Neuro-Linguistic Programming (NLP)** patterns
- **Cognitive-Behavioral Techniques**

### Language Patterns

The hypnotherapist uses therapeutic language including:
- Permissive suggestions: "You may notice..." "Allow yourself to..."
- Linkage and pacing: "As you breathe... you relax..."
- Embedded commands for subtle influence
- Sensory-rich descriptions
- Natural rhythm and repetition

### Safety & Ethics

- ✅ You remain in control at all times
- ✅ You can stop or open your eyes anytime
- ✅ All suggestions are positive and safe
- ✅ Focused on wellness and relaxation
- ❌ NOT a replacement for medical or psychological treatment
- ❌ Does not diagnose or treat medical conditions
- ❌ Does not suggest anything harmful

## Common Use Cases

### 😴 Better Sleep
- Progressive relaxation before bed
- Letting go of the day's concerns
- Creating peaceful sleep imagery
- Building healthy sleep associations

### 😰 Stress & Anxiety Relief
- Grounding and centering techniques
- Safe place visualization
- Breath work and calming
- Building inner resources

### 💪 Confidence Building
- Accessing past successes
- Future pacing and rehearsal
- Inner strength building
- Positive self-image work

### 🧘 General Relaxation
- Body scan meditation
- Mindful awareness
- Deep rest and restoration
- Present moment focus

### 🎯 Habit Support
- Strengthening desired behaviors
- Visualizing success
- Managing triggers
- Building motivation

## Tips for Best Results

1. **Find a quiet space** where you won't be disturbed
2. **Get comfortable** - sit or lie down in a relaxed position
3. **Read slowly** - take your time with each suggestion
4. **Engage your imagination** - really visualize the imagery
5. **Be patient with yourself** - hypnosis is a skill that improves with practice
6. **Stay open** - let the experience unfold naturally
7. **Practice regularly** - consistency enhances effectiveness

## Technical Details

### Plugin Structure

```
hypnotherapist/
├── .claude-plugin/
│   └── plugin.json          # Plugin metadata
├── commands/
│   └── session.md           # Main hypnotherapy session command
├── agents/
│   └── therapeutic-script-writer.md  # Script creation agent
└── README.md                # This file
```

### Command Arguments

The `session` command accepts optional focus area arguments:
- `sleep` - Optimized for sleep improvement
- `anxiety` - Focused on anxiety and stress relief
- `confidence` - Building self-confidence
- `pain` - Pain management techniques
- `habits` - Habit change support
- Or any other therapeutic goal (will be adapted accordingly)

## Disclaimers

⚠️ **Important**: This plugin is for relaxation, wellness, and personal development purposes only.

- **Not medical treatment**: Do not use as a substitute for medical or mental health care
- **Serious conditions**: If you have serious anxiety, depression, PTSD, or other mental health conditions, please work with a licensed professional
- **Physical conditions**: For pain management, always consult with a healthcare provider
- **Safety**: Do not use while driving, operating machinery, or in any situation requiring alertness
- **Emergency**: If you're in crisis, contact emergency services or a crisis hotline

## Contributing

Suggestions for improvements are welcome! Potential enhancements:
- Additional specialized scripts for specific conditions
- More therapeutic modalities (EMDR, Somatic, etc.)
- Integration with wellness tracking
- Guided meditation options
- Self-hypnosis training mode

## Resources

To learn more about hypnotherapy:
- American Society of Clinical Hypnosis (ASCH)
- National Board for Certified Clinical Hypnotherapists (NBCCH)
- Books: "Trancework" by Michael Yapko, "My Voice Will Go With You" (Milton Erickson)

## License

Part of the Claude Code project.

---

**Remember**: You have the power to relax, to change, and to grow. This tool is here to support your journey toward greater well-being. 🌟
