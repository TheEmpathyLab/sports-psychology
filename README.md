# The Weight Format
### Internal Framework — Not for Public Distribution

---

## What this is

A repeatable talk architecture for presentations that need to land with people who are distracted, skeptical, or under pressure. Built from a single talk (*Sports & Psychology*, March 2026) and extracted into a reusable system.

The format has 7 slides. Each slide has a specific job. The jobs don't change. The content does.

---

## The 7-Slide Arc

### Slide 1 — The Object
**Job:** Create weight before words.

Bring something into the room — physical, tangible, or visceral — that the audience can feel before you explain it. Don't introduce yourself first. Don't explain the object. Say one line and let silence do the work.

The object is not a metaphor you explain. It's a metaphor they complete.

> *Reference: shot put in Sports & Psychology.*
> *Could be: a worn tool, a blank form, a broken thing, a heavy object, an empty chair.*

**Slide should show:** The object (drawn or photographed). One provocation line. Your name small at the bottom.

---

### Slide 2 — The Question
**Job:** Make them realize they're already inside the subject.

Don't explain what you're going to talk about. Ask the question that reveals they already have skin in the game. Take 2–3 answers from the room. You're already doing the work.

> *Reference: "What would you need to know about yourself before you threw this?"*

**Slide should show:** The question, large. The object again if useful. Minimal copy.

---

### Slide 3 — Who's Asking
**Job:** Establish why you're the one in the room — briefly.

One honest sentence about your path. Not credentials. The thread that connects your work to the question on slide 2. If it takes more than 30 seconds to say out loud, cut it.

> *Reference: "I study how humans perform when things get hard."*

**Slide should show:** Your one-sentence through-line. A simple visual that represents your work, not your bio.

---

### Slide 4 — The Science
**Job:** Borrow authority from an unexpected discipline.

Find one quote from outside your field that reframes everything. Translate it into the room's language immediately after. The gap between the source and the application is where the insight lives.

> *Reference: Dan Siegel — "Where attention goes, neural firing occurs..."*
> *Translated to: mental reps are real reps.*

**Slide should show:** The quote, large enough to read from the back. The source, small. Two plain sentences of translation below or alongside.

---

### Slide 5 — The Design Principle
**Job:** Show there's a system, not just a feeling.

A second borrowed lens — ideally from a completely different field than slide 4. Brief. It should make the audience feel like the insight is inevitable, not invented.

> *Reference: Louis Sullivan — "Form ever follows function."*
> *Applied to: prep must fit the actual pressure, not a generic version of it.*

**Slide should show:** The principle. A simple before/after or contrast that applies it to your context.

---

### Slide 6 — The Body
**Job:** Make the abstract felt.

This is your highest-risk, highest-reward slide. Something physical happens — a volunteer, a demo, an exercise, an object passed around. The audience stops watching and starts experiencing. If you skip this slide, the talk is forgettable.

Plan for it to take longer than you expect. Budget 7–10 minutes.

> *Reference: arthritis simulation glove — volunteer writes their name, room watches what changes.*

**Slide should show:** The prop or activity. A simple prompt for the volunteer. One key question to ask the room afterward.

---

### Slide 7 — The Leave-Behind
**Job:** Three things. One unanswered question. No bow.

State the three takeaways plainly. Don't over-explain them — you've already done the work. Then land one final question and stop. Don't answer it. Don't wrap up. Don't invite applause. Let them carry it out.

The discomfort of an unanswered question is the neural firing happening in real time.

> *Reference: "What's one thing the pressure in your life is trying to teach you that you keep avoiding?"*

**Slide should show:** The three takeaways, numbered. The closing question in a different visual register — italicized, colored, set apart.

---

## How to Use the Template

1. Open `template/index.html`
2. Read the speaker notes on every slide first — they tell you what kind of content goes there
3. Replace placeholder content with your own
4. The visual style (Sketch/Zine) is the default — don't change it unless you have a strong reason
5. Keep the 7-slide structure. Resist adding slides. Every addition dilutes the arc.

---

## What Not to Change

- **The order.** The arc is load-bearing. Slides 1–2 must create weight before slide 3 earns credibility. Slide 6 must come after the two intellectual frames, not before.
- **Slide 7's ending.** Do not close with a summary or a thank-you. The open question is intentional.
- **The Object on slide 1.** It must be real, specific, and physically present if possible. Abstract metaphors don't work here.

---

## File Structure

```
the-weight-format/
├── README.md                        ← you are here
├── template/
│   └── index.html                   ← blank deck, build from this
└── examples/
    └── sports-psychology/
        └── index.html               ← reference implementation (March 2026)
```

---

## Adding a New Example

When you build a new talk using this format:
1. Duplicate `template/index.html`
2. Build your talk in that copy
3. Move the finished file to `examples/your-talk-name/index.html`
4. The template stays untouched

---

*Framework extracted by Shelton Davis, March 2026.*
*Built from one talk. Intended for many.*
