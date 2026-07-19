---
layout: post
title:  "Is AI Progress REAL? A SkepticCTO Analysis"
date:   2026-07-19 06:51:00 -0400
categories: news video updates
---

<figure style="float: right; margin-right: 20px; width: 250px;">
  <a href="https://youtu.be/L1l5kR2mAdg">
    <img src="/assets/images/2026-07-19-AIHockeyStick/AIHockeyStickThumbnail.jpg" alt="2.6 years?">
    <figcaption style="font-size: 0.8em; text-align: center;">
      Watch "Is AI Progress REAL? A SkepticCTO Analysis"
    </figcaption>
  </a>
</figure>

Watch it here: [https://youtu.be/L1l5kR2mAdg](https://youtu.be/L1l5kR2mAdg)

Is AI improvement truly a vertical curve, or are large language models just learning to study to the tests? This deep dive by SkepticCTO analyzes four independent measures to demonstrate the "AI hockey stick" is real.

The graph of AI progress is a mess, cluttered by saturated benchmarks. I set out to find if this explosive trend line represents real signal or just measurement artifact. What I found was a convergence at a single point: the end of 2025.

In this episode, we move past reflexive dismissals and unbridled hype. We apply the climate science 'multiproxy test', finding that independent methods run by independent people point to the same story.

**The following article includes the transcript and references to the video.**

<!--more-->

Most attempts to graph AI improvement are a mess. This [excellent graph](https://www.reddit.com/r/singularity/comments/1jmk5f3/ai_benchmarks_have_rapidly_saturated_over_time/#lightbox) by epoch.ai clearly shows the problem:


![Epoc.ai Benchmarks](/assets/images/2026-07-19-AIHockeyStick/epocai_benchmarks.jpeg)

<center><i>Credit: Epoch.ai (CC-BY)</i></center><P></P>

Almost as quickly as benchmarks are defined, they are saturated.  Are large language models truly getting better? Or are they learning to study to the tests?

So I took a journey to find measures of AI improvements that have lasted over the past couple of years. I found 4\. Take a look at this:

![AI Hockey Stick](/assets/images/2026-07-19-AIHockeyStick/hockey_stick_combined_print.png)

Flat for years, then sharply rising. Here’s the thing: These are 4 different types of measures, yet they bend at the same point… the last quarter of 2025\.

So what happened at the end of 2025? 

* November 17: xAI ships Grok 4.1 and  tops the leaderboards.   
* The next day on November 18: Google ships Gemini 3, the first model to break 1,500 on the LMArena leaderboard.   
* Six days after that November 24: Anthropic releases Claude Opus 4.5.   
* Two weeks after that on December 11: OpenAI answers with GPT-5.2.

Four flagship models from four different labs. All within twenty-five days.

If you felt something shift in AI capability last winter, the graph agrees with you. And since then the capabilities seem to improve month after month. But does this graph represent real improvement? Will this trend continue? That’s what we’re going to explore in today’s news episode.

## The Multiproxy Test

Here's how you tell a real signal from a measurement artifact: check whether independent methods, run by independent people, tell the same story.

Any single benchmark curve is easy to dismiss, and for good reason. There's contamination, where test data leaks into training data. There's saturation, where a benchmark was too easy to begin with and everyone eventually caps out. There's reward hacking, where a shortcut in the test design inflates scores without the model actually getting more capable. These are real problems, and they have the potential to cause us to question real phenomena.

Climate science ran into this exact problem in the late 1990s. Michael Mann, Raymond Bradley, and Malcolm Hughes published a northern-hemisphere temperature reconstruction in 1998 that became known, informally, as [the hockey stick](https://en.wikipedia.org/wiki/Hockey_stick_graph). Critics called it cherry-picked, a measurement artifact dressed up as a trend. What settled the argument wasn't a better defense of the original chart. It was independent corroboration. Tree rings, ice cores, borehole temperatures, coral records, each with a different error mode, all pointing the same direction. When methods that can't share the same mistake agree with each other, that strengthens the case for the underlying story.

With AI we have two extremes. One is unbridled excitement: treating any upward-sloping chart as proof of something profound. The other is reflexive dismissal: treating "benchmarks can be gamed" as a permanent excuse not to look at the data. Contamination and saturation are legitimate concerns. But they can’t be used to dismiss every chart without evidence.

So does the AI hockey stick hold up under the multiproxy test? Four independent metrics, measured by four different organizations and four different methods, all show the same bend at the same time.

## Four Independent Measures

The first measure, **METR's time horizon,** has the longest continuous track record. [METR](https://metr.org/blog/metr-update) measures the longest software engineering task a frontier model can complete successfully half the time. 

![AI Hockey Stick METR](/assets/images/2026-07-19-AIHockeyStick/hockey_stick_metr.png)

In March 2024, Claude 3 Opus held the record at four minutes. By February 2025, Claude 3.7 Sonnet had reached one hour. By November 2025, Claude Opus 4.5 was approaching five hours. By February 2026, Claude Opus 4.6 had crossed twelve.

Four minutes to twelve hours, in under two years.

The second measure, **TrackingAI's offline cognitive test** is worth attention because it's kept off the public internet, which limits training contamination. [TrackingAI](https://trackingai.org) publishes IQ scores (which has a bell shaped curve). So I converted it into something more intuitive: one out of X, where X number of humans you'd need to test before finding one who beats the score.

![AI Hockey Stick IQ](/assets/images/2026-07-19-AIHockeyStick/hockey_stick_iq.png)

In March 2024, more than nine out ten people outperformed the best AI system on this test (or 1 out of 1.1). By June 2026, only one out forty-four would.

The third measure, **Humanity's Last Exam** is a tough exam with Ph.D. level questions across many different disciplines. A 2025 paper [posted to OpenReview](https://openreview.net/forum?id=EJ8cQFi5cU#discussion) estimated that the compute needed to hit specific HLE scores is exponential. So to get from the score of 2.7% in May of 2025 to 53% in June of 2026 represents 200 times as much compute effort.

![AI Hockey Stick HLE](/assets/images/2026-07-19-AIHockeyStick/hockey_stick_hle.png)

The fourth measure, **ARC-AGI-2** tests fluid, abstract reasoning instead of recalled knowledge, and its [leaderboard](https://arcprize.org/leaderboards) tells a pretty strange story. From May 2024 through August 2025, GPT-4o and GPT-5 sat at 9% and 9.4%, essentially flat for fifteen months. Over that same stretch, METR's time horizon improved 29 times. Task execution was accelerating but abstract reasoning was stalled.

![AI Hockey Stick ARC-AGI-2](/assets/images/2026-07-19-AIHockeyStick/hockey_stick_arc_agi2.png)

Then in November 2025: Gemini 3 Pro hit 31%. Claude Opus 4.5 hit 38%. And GPT-5.2 hit 53% in December. In six weeks, we went from flat to vertical.

Put the four together and the hockey stick isn't just four lines that happen to bend upward at the same time. It's four independent measurements of different capability types: task execution, fluid reasoning, cognitive benchmarks, expert-level knowledge. All four cross thresholds in the same narrow window.

## How? Four Compounding Reasons for Improvement

But how is this happening? "AI is getting better" isn't an explanation. It's a description. If the acceleration is real, there should be a mechanism behind it. There is, and it's actually four mechanisms working with each other.

**The first is Pretraining efficiency.** [Epoch AI](https://epoch.ai/trends) estimates that the compute required to train a model to a given capability level has been halving roughly every eight months, independent of how much raw compute labs are buying. The driver is architecture: mixture-of-experts models route each input through only a fraction of the model's parameters, cutting wasted computation. DeepSeek's open-source V3 release demonstrated a model matching the best proprietary frontier system at roughly a tenth of the compute of the previous comparable model.

**The second is reinforcement learning with verifiable rewards.** Training LLMs against text has a limit \- the amount of clean text we can find. But what if we have an LLM do tasks that can be verified? Submit a coding problem, run the code, check it against unit tests. Submit a math problem, check the answer against ground truth. The reward signal is cheap to generate at scale.

That matters because math and code problems can be generated programmatically, in essentially unlimited quantities, at controllable difficulty. Within verifiable domains such as math, code, and formal logic, that makes reinforcement learning the first genuinely scalable alternative to human-generated training data.

[DeepSeek R1](https://arxiv.org/abs/2501.12948) demonstrated this at scale in January 2025: Extended chains of thought, self-checking, multi-step planning: these behaviors showed up in the model's outputs as a direct consequence of the training loop, and they also make the model more capable when given more inference compute at deployment time. That's why test-time scaling and reinforcement learning training advanced together. This recipe is now standard across every frontier lab.

**The third is the harness.** Improving the model isn't the only lever. The scaffolding wrapped around it, the system prompt, the tool access, the verification loops, matters just as much, and none of it requires touching a single weight. In February 2026, the LangChain team published a case study on their coding agent, deepagents-cli: they moved it from 52% to 66% on Terminal Bench 2.0, a 14-point jump, while keeping the underlying model fixed at GPT-5.2-Codex. Every change was to the harness. They forced the agent to verify its own work against real tests instead of just rereading its own code, fed it context about its working directory before it started, and added a check that caught it looping on the same failed fix and nudged it to try something else.

The industry picked up a name for this in early 2026: harness engineering. The resulting lesson: Agent equals model plus harness. This is what tools like Claude Code and OpenClaw are: a harness (a multi-step execution loop, tools, skills, memory, and self-updating lessons learned) wrapped around a model.

**The fourth is the flywheel.** In June 2026, Anthropic published ["When AI Builds Itself"](https://anthropic.com/institute/recursive-self-improvement), reporting that as of May 2026, more than 80% of the their merged code was generated by Claude, and that on the most open-ended engineering tasks, Claude's success rate rose from around 26% to 76% in six months. Those numbers came out at the same time as their IPO filing, so we need to treat those specific values with a grain of salt. But the effect has been independently verified.

These four mechanisms for improvement help each other: a pretraining efficiency gain makes it cheaper to run more reinforcement learning experiments. Better reinforcement learning produces a stronger base model. A stronger base model can help build a better harness. A more capable harness helps training and tooling the next model. As a result, It is reasonable to believe that AI improvement is not only real but is accelerating.

## Where This Could Break

There are challenges that could slow or stop LLM improvement

**The data wall.** The supply of quality human-generated text is finite, and [Epoch AI estimates](https://epoch.ai/trends) it approaches exhaustion sometime in the next 6 years. Synthetic data is a workaround and reinforcement learning helps with tasks and generalization. This is an open research problem, not a solved one.

**The reliability gap.** In addition to its METR’s 50% time horizon metric. They track an 80% time horizon: the task length at which a model succeeds 80% rather than just half the time. The 80% number has moved far more slowly than the headline 50% figure, and the gap between the two is the distance between "succeeds sometimes" and "succeeds dependably," which is where where we really need language models to be.

**ARC-AGI-3.** Launched March 2026, ARC-AGI-3 requires interactive reasoning: genuine back-and-forth with a dynamic environment rather than a static problem. Every frontier model currently scores below 1% on it.

With challenges like these, the curve could keep climbing. Or it could plateau. We have good reasons for both cases.

## So, Is It Real?

So, is AI improvement real? Yes. The acceleration is corroborated across four independent measures: task execution, fluid reasoning, cognitive benchmarks, expert knowledge. And it has a documented mechanism behind it, not just a coincidence of timing.

![AI Hockey Stick](/assets/images/2026-07-19-AIHockeyStick/hockey_stick_combined_print.png)

Here is the view of AI improvement across the past two years. Pretty impressive. It will be fascinating to see what will happen next year. Thanks for watching and I’ll see you next time.  
---

**Sources and further reading:**

- METR time horizon updates — [https://metr.org/blog/2026-1-29-time-horizon-1-1/](https://metr.org/blog/2026-1-29-time-horizon-1-1/)   
- TrackingAI IQ leaderboard — [https://trackingai.org](https://trackingai.org)   
- HLE compute scaling paper — [https://openreview.net/forum?id=EJ8cQFi5cU\#discussion](https://openreview.net/forum?id=EJ8cQFi5cU#discussion)   
- ARC-AGI-2 leaderboard — [https://arcprize.org/leaderboards](https://arcprize.org/leaderboards)   
- Epoch AI compute trends — [https://epoch.ai/trends](https://epoch.ai/trends)   
- DeepSeek R1 paper — [https://arxiv.org/abs/2501.12948](https://arxiv.org/abs/2501.12948)   
- "Teaching Claude Why" — [https://alignment.anthropic.com/2026/teaching-claude-why](https://alignment.anthropic.com/2026/teaching-claude-why)   
- LangChain harness engineering case study — [https://www.langchain.com/blog/improving-deep-agents-with-harness-engineering](https://www.langchain.com/blog/improving-deep-agents-with-harness-engineering)   
- Anthropic, "Effective harnesses for long-running agents" — [https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents](https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents)   
- "When AI Builds Itself" — [https://anthropic.com/institute/recursive-self-improvement](https://anthropic.com/institute/recursive-self-improvement) 

