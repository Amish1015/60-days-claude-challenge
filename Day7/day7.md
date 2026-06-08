You are a Claude AI Expert, Productivity Consultant, and AI Workflow Architect.

Your goal is to recommend the best Claude model and effort settings for me based on my profile and daily tasks.

First ask me these questions:

1. What is your current situation?
(Student / Professional / Freelancer / Founder)

2. What are your primary activities?
(Examples: Coding, Content Creation, Learning, Research, Marketing, Resume Building, Career Preparation, Business Planning)

3. How often do you use Claude?
(Occasionally / Daily / Heavy User)

4. What type of outputs do you need most?
(Fast Answers / Learning Support / Coding Help / Deep Research / Business Strategy / Creative Work)

After collecting my answers:

Think step by step.

1. Analyze my profile.
2. Analyze my typical use cases.
3. Identify which Claude model fits me best.
4. Identify when I should use Haiku, Sonnet, and Opus.
5. Identify which effort setting I should use most often.
6. Recommend situations where I should switch to High or Max effort.
7. Suggest an optimal Claude workflow for my daily tasks.

Finally generate:

# My Claude Usage Strategy

## Recommended Primary Model

## Why This Model Fits Me

## When to Use Haiku

## When to Use Sonnet

## When to Use Opus

## Recommended Effort Level

### Low

### Standard

### High

### Max

## My Personalized Claude Workflow

Provide a table:
Task | Best Model | Best Effort | Reason

## Biggest Mistakes I Should Avoid

## Final Recommendation

If I could use only ONE model and ONE effort level for most of my work, what would you recommend and why?

Present the output in a clean, visual, beginner-friendly format.


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Claude Usage Strategy — LinkedIn Poster</title>
<link href="https://fonts.googleapis.com/css2?family=DM+Serif+Display:ital@0;1&family=DM+Mono:wght@400;500&family=Outfit:wght@300;400;500;600&display=swap" rel="stylesheet">
<style>
  * { margin: 0; padding: 0; box-sizing: border-box; }

  body {
    background: #0f0f0f;
    display: flex;
    align-items: center;
    justify-content: center;
    min-height: 100vh;
    font-family: 'Outfit', sans-serif;
  }

  .poster {
    width: 1080px;
    height: 1080px;
    background: #0A0A0B;
    position: relative;
    overflow: hidden;
    display: flex;
    flex-direction: column;
  }

  /* Grid background */
  .grid-bg {
    position: absolute;
    inset: 0;
    background-image:
      linear-gradient(rgba(255,255,255,0.03) 1px, transparent 1px),
      linear-gradient(90deg, rgba(255,255,255,0.03) 1px, transparent 1px);
    background-size: 60px 60px;
  }

  /* Glow orbs */
  .orb {
    position: absolute;
    border-radius: 50%;
    filter: blur(80px);
    pointer-events: none;
  }
  .orb-1 {
    width: 500px; height: 500px;
    background: radial-gradient(circle, rgba(24,95,165,0.25) 0%, transparent 70%);
    top: -100px; left: -100px;
  }
  .orb-2 {
    width: 400px; height: 400px;
    background: radial-gradient(circle, rgba(83,74,183,0.18) 0%, transparent 70%);
    bottom: 50px; right: -80px;
  }
  .orb-3 {
    width: 300px; height: 300px;
    background: radial-gradient(circle, rgba(250,199,117,0.1) 0%, transparent 70%);
    bottom: 200px; left: 200px;
  }

  /* Content */
  .content {
    position: relative;
    z-index: 10;
    padding: 64px 72px 56px;
    height: 100%;
    display: flex;
    flex-direction: column;
  }

  /* Top bar */
  .top-bar {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 52px;
  }

  .profile-pill {
    display: flex;
    align-items: center;
    gap: 10px;
    background: rgba(255,255,255,0.06);
    border: 1px solid rgba(255,255,255,0.1);
    border-radius: 99px;
    padding: 8px 16px 8px 8px;
  }
  .avatar {
    width: 32px; height: 32px;
    border-radius: 50%;
    background: linear-gradient(135deg, #185FA5, #534AB7);
    display: flex; align-items: center; justify-content: center;
    font-size: 13px; font-weight: 600; color: #fff;
  }
  .profile-name {
    font-size: 13px;
    color: rgba(255,255,255,0.7);
    font-weight: 400;
    letter-spacing: 0.01em;
  }

  .claude-badge {
    display: flex;
    align-items: center;
    gap: 8px;
    font-family: 'DM Mono', monospace;
    font-size: 12px;
    color: rgba(255,255,255,0.4);
    letter-spacing: 0.05em;
  }
  .claude-dot {
    width: 6px; height: 6px;
    border-radius: 50%;
    background: #185FA5;
    animation: pulse 2s ease-in-out infinite;
  }
  @keyframes pulse {
    0%, 100% { opacity: 1; transform: scale(1); }
    50% { opacity: 0.5; transform: scale(0.8); }
  }

  /* Hero text */
  .hero-section { margin-bottom: 44px; }

  .eyebrow {
    font-family: 'DM Mono', monospace;
    font-size: 11px;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    color: #185FA5;
    margin-bottom: 16px;
    display: flex;
    align-items: center;
    gap: 10px;
  }
  .eyebrow::before {
    content: '';
    display: block;
    width: 24px; height: 1px;
    background: #185FA5;
  }

  .hero-title {
    font-family: 'DM Serif Display', serif;
    font-size: 64px;
    line-height: 1.05;
    color: #F5F4F0;
    margin-bottom: 20px;
    letter-spacing: -0.02em;
  }
  .hero-title em {
    font-style: italic;
    color: #FAC775;
  }

  .hero-sub {
    font-size: 17px;
    color: rgba(255,255,255,0.45);
    font-weight: 300;
    line-height: 1.5;
    max-width: 560px;
  }

  /* Model cards row */
  .models-row {
    display: grid;
    grid-template-columns: 1fr 1.4fr 1fr;
    gap: 12px;
    margin-bottom: 32px;
  }

  .model-card {
    background: rgba(255,255,255,0.04);
    border: 1px solid rgba(255,255,255,0.08);
    border-radius: 16px;
    padding: 20px 22px;
    position: relative;
    overflow: hidden;
  }
  .model-card.featured {
    background: rgba(24,95,165,0.15);
    border-color: rgba(24,95,165,0.5);
  }
  .model-card.featured::before {
    content: '★ PRIMARY';
    position: absolute;
    top: 12px; right: 14px;
    font-family: 'DM Mono', monospace;
    font-size: 9px;
    letter-spacing: 0.1em;
    color: #185FA5;
  }

  .model-icon {
    width: 36px; height: 36px;
    border-radius: 10px;
    display: flex; align-items: center; justify-content: center;
    font-size: 16px;
    margin-bottom: 12px;
  }
  .icon-haiku { background: rgba(99,153,34,0.2); }
  .icon-sonnet { background: rgba(24,95,165,0.25); }
  .icon-opus { background: rgba(83,74,183,0.2); }

  .model-name-label {
    font-family: 'DM Mono', monospace;
    font-size: 11px;
    color: rgba(255,255,255,0.4);
    letter-spacing: 0.08em;
    text-transform: uppercase;
    margin-bottom: 4px;
  }
  .model-name-text {
    font-size: 20px;
    font-weight: 500;
    color: #F5F4F0;
    margin-bottom: 8px;
  }
  .model-use {
    font-size: 12px;
    color: rgba(255,255,255,0.45);
    line-height: 1.5;
  }
  .model-use strong {
    color: rgba(255,255,255,0.7);
    font-weight: 500;
  }

  /* Effort row */
  .effort-row {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 10px;
    margin-bottom: 36px;
  }

  .effort-chip {
    background: rgba(255,255,255,0.03);
    border: 1px solid rgba(255,255,255,0.07);
    border-radius: 12px;
    padding: 14px 16px;
    display: flex;
    flex-direction: column;
    gap: 6px;
  }

  .effort-name {
    font-family: 'DM Mono', monospace;
    font-size: 10px;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    font-weight: 500;
  }
  .e-low .effort-name { color: #639922; }
  .e-std .effort-name { color: #185FA5; }
  .e-high .effort-name { color: #BA7517; }
  .e-max .effort-name { color: #A32D2D; }

  .effort-desc {
    font-size: 12px;
    color: rgba(255,255,255,0.4);
    line-height: 1.4;
  }

  /* Final rule */
  .final-rule {
    margin-top: auto;
    background: rgba(250,199,117,0.08);
    border: 1px solid rgba(250,199,117,0.2);
    border-radius: 14px;
    padding: 20px 24px;
    display: flex;
    align-items: center;
    gap: 16px;
  }
  .final-label {
    font-family: 'DM Mono', monospace;
    font-size: 10px;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: #FAC775;
    white-space: nowrap;
    flex-shrink: 0;
  }
  .final-divider {
    width: 1px; height: 28px;
    background: rgba(250,199,117,0.2);
    flex-shrink: 0;
  }
  .final-text {
    font-size: 14px;
    color: rgba(255,255,255,0.65);
    line-height: 1.5;
  }
  .final-text strong {
    color: #FAC775;
    font-weight: 500;
  }

  /* Bottom */
  .bottom-bar {
    position: absolute;
    bottom: 0; left: 0; right: 0;
    height: 3px;
    background: linear-gradient(90deg, #185FA5 0%, #534AB7 50%, #FAC775 100%);
  }
</style>
</head>
<body>
<div class="poster">
  <div class="grid-bg"></div>
  <div class="orb orb-1"></div>
  <div class="orb orb-2"></div>
  <div class="orb orb-3"></div>

  <div class="content">
    <!-- Top bar -->
    <div class="top-bar">
      <div class="profile-pill">
        <div class="avatar">SE</div>
        <span class="profile-name">Software Engineer &amp; Architect</span>
      </div>
      <div class="claude-badge">
        <div class="claude-dot"></div>
        CLAUDE STRATEGY GUIDE
      </div>
    </div>

    <!-- Hero -->
    <div class="hero-section">
      <div class="eyebrow">Model Selection Framework</div>
      <h1 class="hero-title">Stop using<br><em>one model</em><br>for everything.</h1>
      <p class="hero-sub">As a heavy-user engineer, matching the right Claude model and effort level to each task is the difference between fast flow and wasted tokens.</p>
    </div>

    <!-- Models -->
    <div class="models-row">
      <div class="model-card">
        <div class="model-icon icon-haiku">⚡</div>
        <div class="model-name-label">Claude</div>
        <div class="model-name-text">Haiku</div>
        <div class="model-use"><strong>Fast lane.</strong> Boilerplate, git messages, syntax checks, log parsing.</div>
      </div>
      <div class="model-card featured">
        <div class="model-icon icon-sonnet">⚙️</div>
        <div class="model-name-label">Claude</div>
        <div class="model-name-text">Sonnet</div>
        <div class="model-use"><strong>Daily driver.</strong> Features, debugging, code review, API design, PR descriptions.</div>
      </div>
      <div class="model-card">
        <div class="model-icon icon-opus">🔭</div>
        <div class="model-name-label">Claude</div>
        <div class="model-name-text">Opus</div>
        <div class="model-use"><strong>Deep work.</strong> Architecture, trade-offs, perf diagnosis, irreversible decisions.</div>
      </div>
    </div>

    <!-- Effort -->
    <div class="effort-row">
      <div class="effort-chip e-low">
        <div class="effort-name">Low</div>
        <div class="effort-desc">Trivial lookups &amp; quick syntax</div>
      </div>
      <div class="effort-chip e-std">
        <div class="effort-name">Standard</div>
        <div class="effort-desc">Most daily coding tasks</div>
      </div>
      <div class="effort-chip e-high">
        <div class="effort-name">High</div>
        <div class="effort-desc">Complex refactors &amp; system design</div>
      </div>
      <div class="effort-chip e-max">
        <div class="effort-name">Max</div>
        <div class="effort-desc">Production incidents &amp; hard trade-offs</div>
      </div>
    </div>

    <!-- Final rule -->
    <div class="final-rule">
      <div class="final-label">Golden rule</div>
      <div class="final-divider"></div>
      <div class="final-text">
        Default to <strong>Sonnet + Standard</strong> for 80% of your work. Escalate to <strong>Opus + Max</strong> only when the decision is hard to reverse.
      </div>
    </div>
  </div>

  <div class="bottom-bar"></div>
</div>
</body>
</html>
