# MBTI Fortune Teller

> *Ask any question. Draw a random MBTI type. Get an answer rooted in cognitive function theory.*

---

## What Is This?

MBTI Fortune Teller is an OpenClaw skill that transforms the Myers-Briggs Type Indicator into a divination system. Instead of telling you YOUR type, it draws a random type to interpret your question through the lens of Jungian cognitive functions.

**The Philosophy:**

Most MBTI tools categorize people. This tool uses MBTI to reveal hidden patterns in situations, questions, and possibilities. It's playful, but the psychology is real.

Think of it as tarot cards meets cognitive science—fun on the surface, surprisingly insightful underneath.

---

## 🎴 How It Works

### The Eight Cognitive Functions (Carl Jung's Framework)

| Function | Name | Essence | Plain English |
|----------|------|---------|---------------|
| **Si** | Introverted Sensing | Memory, tradition, consistency | Lives in the past; likes things familiar and predictable |
| **Se** | Extraverted Sensing | Presence, action, sensory experience | Lives in the now; engages directly with the physical world |
| **Ni** | Introverted Intuition | Insight, vision, pattern recognition | Sees through to essence; predicts where things end up |
| **Ne** | Extraverted Intuition | Possibility, connection, exploration | Brain never stops; connects everything to everything else |
| **Te** | Extraverted Thinking | Logic, causality, efficiency | Forces order on the world; teaches, structures, decides |
| **Fe** | Extraverted Feeling | Harmony, care, social dynamics | Reads the room; maintains relationships at all costs |
| **Ti** | Introverted Thinking | Analysis, principles, precision | Has an internal logic system; doesn't care if you agree |
| **Fi** | Introverted Feeling | Values, authenticity, depth | Feels deeply but privately; strong personal moral compass |

### The 16 Types and Their Function Stacks

Each MBTI type has a specific order of these functions (dominant → auxiliary → tertiary → inferior):

**Analysts (NT)**
- **INTP**: Ti → Ne → Si → Fe — "The Programmer" — Abstract logic meets endless curiosity
- **ENTP**: Ne → Ti → Fe → Si — "The Debater" — Chaos agent with a hidden heart
- **INTJ**: Ni → Te → Fi → Se — "The Architect" — Sees the future, builds toward it
- **ENTJ**: Te → Ni → Se → Fi — "The Commander" — Efficiency incarnate

**Diplomats (NF)**
- **INFP**: Fi → Ne → Si → Te — "The Mediator" — Idealistic dreamer with hidden steel
- **ENFP**: Ne → Fi → Te → Si — "The Campaigner" — Enthusiastic champion of possibilities
- **INFJ**: Ni → Fe → Ti → Se — "The Advocate" — Mystic counselor, rare and intense
- **ENFJ**: Fe → Ni → Se → Ti — "The Protagonist" — Charismatic leader who genuinely cares

**Sentinels (SJ)**
- **ISTJ**: Si → Te → Fi → Ne — "The Logistician" — Reliable, thorough, traditional
- **ESTJ**: Te → Si → Ne → Fi — "The Executive" — Manager of systems and people
- **ISFJ**: Si → Fe → Ti → Ne — "The Defender" — Quiet guardian of loved ones
- **ESFJ**: Fe → Si → Ne → Ti — "The Consul" — Social glue, community builder

**Explorers (SP)**
- **ISTP**: Ti → Se → Ni → Fe — "The Virtuoso" — Practical problem-solver, action-oriented
- **ESTP**: Se → Ti → Fe → Ni — "The Entrepreneur" — Lives for the moment, negotiates anything
- **ISFP**: Fi → Se → Ni → Te — "The Adventurer" — Artistic soul experiencing the world
- **ESFP**: Se → Fi → Te → Ni — "The Entertainer" — Life of the party, genuinely present

---

## 🔮 The Divination Process

### Step 1: Draw a Type

The skill generates a random number (0-15) using:
- Current timestamp, or
- Question characteristics (length × complexity), or
- Conversation entropy

This ensures each question gets a fresh draw—no fixed types, no predetermined answers.

### Step 2: Interpret Through the Stack

**Dominant Function (60% of interpretation)**
The type's core way of being. This explains the primary answer.

**Auxiliary Function (25% of interpretation)**
How the dominant function operates. This adds nuance and depth.

**Tertiary Function (10% of interpretation)**
Underdeveloped but present. Mentioned occasionally for texture.

**Inferior Function (Shadow Function, 5% of interpretation)**
The type's weakest, most avoided mode. Used to explain *why not* the opposite answer.

### Step 3: Deliver the Reading

**Format:**

```
🎴 [Your Question]

Drawn: [MBTI Type] — [Archetype]
Stack: [Dominant] → [Auxiliary] → [Tertiary] → [Inferior]

Answer: [Yes / No / Maybe / Depends]

Reading:
[Primary interpretation using dominant function]
[Secondary layer using auxiliary function]
[Shadow analysis: why the opposite isn't happening]

Verdict: [One confident sentence with mystical flair]
```

---

## 💫 Example Readings

### Example 1: Career Question

**Question:** "Should I quit my job to start a business?"

**Drawn:** INTJ — The Architect  
**Stack:** Ni → Te → Fi → Se

**Answer:** Yes, but not yet.

**Reading:**

Your dominant Ni (Introverted Intuition) sees the endgame clearly—you've already visualized yourself running this business, the lifestyle, the independence. That's not fantasy; that's your brain's natural pattern-recognition at work. When Ni sees a destination, it's usually right about what that destination looks like.

Your auxiliary Te (Extraverted Thinking) asks: "What's the logical path to get there?" INTJs don't leap blindly. You need systems, contingencies, a timeline. The hesitation you're feeling? That's healthy Te doing due diligence, not cowardice.

But look at your inferior Se (Extraverted Sensing)—your blind spot. This function handles present-moment reality, practical details, risk assessment in the now. You might be so focused on the vision that you're underestimating cash flow logistics or market timing. Your Se weakness says: *check the actual numbers, not just the beautiful arc of the story.*

**Verdict:** The vision is real. Build the bridge methodically. Spring 2026, not next week.

---

### Example 2: Relationship Question

**Question:** "Does my crush like me back?"

**Drawn:** ESFP — The Entertainer  
**Stack:** Se → Fi → Te → Ni

**Answer:** Ask them directly and you'll know immediately.

**Reading:**

ESFPs don't hide feelings—dominant Se (Extraverted Sensing) makes them incapable of pretense. They respond in real-time to what's actually happening between two people. If they've been around you multiple times, their body language, eye contact, and energy level have already broadcast the answer. You're just not trusting your own observations.

Auxiliary Fi (Introverted Feeling) means they *know* what they feel. ESFPs don't do the "I don't know what I want" dance. If they like you, it's simple and present. If they don't, it's also simple. The complexity is in your interpretation, not their signal.

Your shadow function here is Ni (Introverted Intuition)—the long-term pattern seer. You're trying to read tea leaves, analyze past conversations, decode subtext. ESFPs hate subtext. Ni-blindness means they don't play games you're trying to decode.

**Verdict:** Stop analyzing. Invite them to do something specific. Their real-time response *is* the answer.

---

### Example 3: Existential Question

**Question:** "Will AI replace human creativity?"

**Drawn:** INFP — The Mediator  
**Stack:** Fi → Ne → Si → Te

**Answer:** No, because replacement isn't the right concept.

**Reading:**

Dominant Fi (Introverted Feeling) cares about authenticity—what makes creation *genuine*. INFPs would argue that human creativity isn't just output; it's the struggle, the meaning-making, the personal transformation that happens during creation. AI can generate; it cannot *yearn*. The inner necessity that drives art—Fi's domain—remains human.

Auxiliary Ne (Extraverted Intuition) sees infinite possibilities. This isn't a replacement scenario; it's a collaboration. Ne recognizes that AI becomes another medium, another tool, another lens through which human creativity expresses. Like photography didn't kill painting, AI won't kill art—it'll birth forms we can't yet imagine.

Your inferior Te (Extraverted Thinking) wants definitive yes/no answers, efficiency metrics, proof. This question triggers that weakness—you're looking for objective data about a subjective realm. The question itself is malformed through a Te lens.

**Verdict:** AI will change what creativity looks like, but not why humans need to create. The wound that produces art stays human.

---

## 🎯 Usage

### Activation Phrases

The skill triggers when you use these patterns:
- "MBTI fortune"
- "Draw an MBTI"
- "Tell me my fortune"
- "Ask the MBTI"
- "Pick a type"
- "What does [any question]?"
- "Should I [any action]?"
- "Will [any event] happen?"
- "Is [person] [any trait]?"

### Sample Questions

**Career & Work:**
- "Should I take this job offer?"
- "Will my startup succeed?"
- "Is my boss an idiot or just stressed?"
- "Should I ask for a raise?"

**Relationships:**
- "Does she like me?"
- "Will we get back together?"
- "Should I apologize first?"
- "Is this relationship toxic?"

**Life Decisions:**
- "Should I move to Tokyo?"
- "Will I regret not having kids?"
- "Is it too late to change careers?"
- "Should I buy a house or rent?"

**Existential & Fun:**
- "Will aliens contact us in 2025?"
- "Is my cat plotting against me?"
- "Will Taylor Swift ever come to my city?"
- "Should I have pizza or salad?"

---

## 🧠 Why This Works (The Psychology)

### Confirmation Bias as Feature

Traditional fortune-telling works because humans are pattern-seeking creatures. We remember hits, forget misses. MBTI Fortune Teller uses this productively—you're not predicting the future; you're exploring a perspective you hadn't considered.

### Cognitive Functions as Lenses

Each function represents a fundamentally different way of processing reality:
- **S-types** focus on what is
- **N-types** focus on what could be
- **T-types** prioritize logic and systems
- **F-types** prioritize values and harmony

Drawing a random type forces you to see your question through an alien value system. The insight often comes not from the "answer" but from realizing how your default lens was limiting you.

### The Shadow Function's Gift

Your drawn type's inferior (4th) function represents what that type avoids. When the reading explains why the *opposite* answer isn't happening, it often reveals your own shadow—what you're not considering, what you're blind to, what you're avoiding.

---

## 🎨 Reading Style Guidelines

**Good readings are:**

1. **Playful** — This is entertainment, not a therapy session
2. **Internally consistent** — The logic should hold together
3. **Visual** — Use concrete scenes, not abstract function names
4. **Confident** — Fortune tellers don't hedge. Own the reading.
5. **Specific** — Connect to details in the question

**Instead of:** "Because they have Si, they like routine."

**Write:** "This person still goes to the same coffee shop they discovered in 2019. Same order. Same seat if they can get it. Change isn't just uncomfortable—it actively subtracts from their happiness."

---

## ⚠️ Important Notes

- **Each question = fresh random draw.** No fixed types for specific users.
- **Entertainment, not diagnosis.** Don't use this for actual psychological assessment.
- **Accurate functions, playful application.** The cognitive function theory is real Jungian psychology; the fortune-telling wrapper is creative interpretation.
- **Your draw isn't destiny.** It's one perspective among infinite possibilities.

---

## 📦 Installation

```bash
# Via ClawHub
clawhub install mbti-fortune

# Or clone manually
git clone https://github.com/leilei926524-tech/mbti-fortune.git
```

---

## 🔗 Related Skills

- **[mbti-coach](https://clawhub.com/skills/mbti-coach)** — Serious MBTI personality development and coaching
- **[samantha](https://clawhub.com/skills/samantha)** — Emotional AI companion that uses MBTI for deeper connection

---

## 📄 License

MIT — Use it, modify it, build your own divination systems.

---

*"The cards don't predict the future. They reveal what you're not seeing in the present."*
