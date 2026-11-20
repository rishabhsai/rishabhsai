# Hi, I'm Rishabh

I like building things, mostly projects and dev tools for the AI era. I study computer science at Penn State, I'm one of 140 students in the first [OpenAI Campus Leads](https://openai.com/student-collective/) cohort, and I spent summer 2026 at Cisco in San Francisco working on AI infrastructure.

More about me at **[rishabhsai.com](https://rishabhsai.com)**.

## Wins

- 🏆 **$10,000, 2nd place** at the AI Strike Team PA Housing Hackathon for [ByRight PGH](https://byright-pgh.vercel.app), which finds which of Pittsburgh's vacant city lots could fit small homes. ([Technical.ly](https://technical.ly/entrepreneurship/easescore-ai-wins-allegheny-county-housing-hackathon-pittsburgh-money-moves/))
- ☁️ **$20K in AWS credits** to build [Atrax](https://atrax.run)
- 📈 **Ran a business doing about $30K a year** with TrendFlip, which used AI to spot underpriced trading cards and collectibles to resell
- 🥇 **1st place** at the University of West London national science fair for AURA, a mental health chatbot for students
- 💸 **Built, raised money for, and sold** [SharePen](https://share-pen.com), an AI writing product

## Tools for building with AI

- **[Atrax](https://atrax.run)**: tell your coding agent what to build, and Atrax deploys it, sets up the database, and shows you what's running.
- **[Glance](https://github.com/rishabhsai/glance)**: lets AI apps read what's on your Mac screen without taking screenshots.
- **[BYOA](https://github.com/rishabhsai/byoa)**: gives every user their own Codex agent in a private sandbox, signed in with their own ChatGPT account.
- **[Mandate Protocol](https://mandate.lol)**: permission slips for AI agents acting on someone's behalf.
- **[NotionBench](https://github.com/rishabhsai/notionbench)**: a test of how well coding agents can build on Notion.
- **[Yap for Cursor](https://github.com/rishabhsai/yap-for-cursor-extension_Voice-To-Text)**: talk instead of type in Cursor and VS Code, all on your own machine. **12,000+ users.**

## Other things I've made

- **[PDFSpacer](https://pdfspacer.com)**: add blank space to any PDF so you have room to write your answers. **2,000+ monthly users.**
- **[mdbar](https://github.com/rishabhsai/mdbar)**: a notes app that lives in your Mac menu bar.
- **[Vrishn](https://github.com/rishabhsai/vrishn-quick-tab-switcher)**: faster tab switching for Chrome-style browsers.

There are more than 35 others on [my projects page](https://rishabhsai.com/projects).

## Open source

I fix bugs in the open source projects that AI runs on. I've had **36 pull requests merged** so far, in projects from:

**Google DeepMind** (MuJoCo, Optax) · **Kubeflow** · **Kubernetes** · **Hugging Face** · **Apple** · **MLX** · **Google** (ADK, Gemini Cookbook) · **vLLM** · **llm-d** · **Model Context Protocol** · and more

A few I'm proud of:

- [ogx#6704](https://github.com/ogx-ai/ogx/pull/6704) and [ogx#6716](https://github.com/ogx-ai/ogx/pull/6716): in OGX, the open source Llama Stack, one conversation's chat messages could be written into someone else's. The maintainer called it a real data-corruption fix, and I followed up by rebuilding how messages are stored so it can't happen again.
- [kueue#15575](https://github.com/kubernetes-sigs/kueue/pull/15575): Kubernetes Kueue looked up failed machines by the wrong name, so it could miss jobs sitting on a dead one. The fix shipped in two releases.
- [trainer#4489](https://github.com/kubeflow/trainer/pull/4489): in Kubeflow Trainer, one empty option could keep an AI hyperparameter search running forever. I found it, the maintainer asked me to fix it, and it merged the same day.
- [kgateway#14712](https://github.com/kgateway-dev/kgateway/pull/14712): calls to AWS Lambda through kgateway failed because requests were signed for the wrong address.
- [mujoco#3573](https://github.com/google-deepmind/mujoco/pull/3573): my first one. Google DeepMind's MuJoCo physics engine used a different default than its own docs promised.

[See all of them](https://github.com/pulls?q=is%3Apr+author%3Arishabhsai+is%3Amerged+-user%3Arishabhsai).

## Say hi

[rishabhsai.com](https://rishabhsai.com) · [X](https://x.com/rishabhsaiv) · [LinkedIn](https://linkedin.com/in/rishabh-sai) · [Hugging Face](https://huggingface.co/rishabhsai)
