# Prompt Chain Documentation  
**Task 1 – AI-Powered YouTube Script & Thumbnail Generator**

---

## 1. Task Overview

**Objective:**  
To design and apply a structured prompt chain that generates a complete YouTube content package (title, script, and thumbnail concept) using AI tools.

**Selected Topic:**  
“I Asked ChatGPT to Run My Day – Here’s What Happened”

**Why Prompt Chaining?**  
Prompt chaining breaks a complex task into smaller, manageable steps where the output of one prompt becomes the input for the next. This improves clarity, consistency, and overall output quality.

---

## 2. Prompt Chain Flow

Prompt 1 → Video Strategy

Prompt 2 → Title Generation

Prompt 3 → Full Script Generation

Prompt 4 → Thumbnail Concept

Each prompt builds on the previous one to maintain narrative consistency and context.

---

## 3. Prompt 1: Video Strategy Prompt

### Purpose  
To define the overall direction of the video, including tone, narrative structure, and key moments.

### Prompt Used
```
You are a YouTube content strategist.

I want to create a first-person YouTube video titled:
“I Asked ChatGPT to Run My Day – Here’s What Happened”.

Target audience:
- College students
- Young professionals
- People curious about AI productivity

Your task:
1. Define the ideal tone for the video.
2. Suggest a clear narrative structure.
3. Identify 4–5 key moments where ChatGPT influences daily decisions.

Keep the output structured and concise.
```

**Output Summary**
- **Tone:** Relatable, honest, slightly humorous
- **Structure:** Morning routine → Workday → Evening → Reflection
- **Key moments:** Planning the day, task prioritization, decision-making, productivity impact, end-of-day evaluation

**Why This Prompt Works**
This prompt sets clear context, audience, and expectations, ensuring all subsequent prompts generate aligned and relevant content.

---

## 4. Prompt 2: Title Generation Prompt

**Purpose**
To generate engaging, curiosity-driven YouTube titles optimized for click-through rate (CTR).

**Prompt Used**
```
Using the video strategy above, generate 10 engaging YouTube titles.

Rules:
- First-person style
- Curiosity-driven
- Under 60 characters
- No misleading clickbait
- Optimized for high CTR

Highlight the top 3 titles and explain why they may perform well.
```

**Selected Title**
“I Let ChatGPT Control My Entire Day”

**Why This Prompt Works**
Clear constraints guide the model to produce platform-appropriate, high-performing titles rather than generic suggestions.

---

## 5. Prompt 3: Full Script Generation Prompt

**Purpose**
To generate a long-form YouTube video script based on the selected title and defined structure.

**Prompt Used**
```
Write a complete YouTube video script (1200–1500 words) for the selected title.

Script requirements:
- Strong hook in the first 10 seconds
- Explain the experiment clearly
- Chronological storytelling (morning to night)
- Conversational and honest tone
- Mention both benefits and limitations of AI
- Clear conclusion with key takeaways

Use headings and short paragraphs.
Do not use emojis.
```

**Why This Prompt Works**
This prompt enforces structure, length, tone, and content balance, which is essential for generating coherent long-form content.

---

## 6. Prompt 4: Thumbnail Concept Prompt

**Purpose**
To design a thumbnail concept that visually communicates curiosity and the human–AI contrast.

**Prompt Used**
```
Create a YouTube thumbnail concept for this video.

Output format:
1. Thumbnail text (3–5 bold words)
2. Visual description
3. AI image generation prompt (for DALL·E or Bing Image Creator)

Thumbnail must:
- Spark curiosity
- Show human vs AI contrast
- Be readable on mobile devices
```

**Why This Prompt Works**
This prompt bridges text-based outputs with visual content creation, demonstrating multi-modal prompt engineering.

---

## 7. Key Prompt Engineering Learnings

- Breaking complex tasks into chained prompts improves output quality
- Assigning roles and constraints reduces ambiguity
- Prompt chaining maintains consistency across multiple AI outputs
- Well-defined prompts reduce the need for manual edits

---

## 8. Tools Used

- ChatGPT (Free) – Prompt execution and content generation
- Bing Image Creator / Canva – Thumbnail creation
- Canva – Video creation and editing

---
