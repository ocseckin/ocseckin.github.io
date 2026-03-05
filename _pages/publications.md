---
layout: archive
permalink: /research/
author_profile: true
---

<style>
.paper-card {
  display: flex;
  gap: 20px;
  margin: 20px 0;
  padding: 18px 20px;
  border-radius: 10px;
  border: 1px solid #e8e8e8;
  background: #fff;
  box-shadow: 0 2px 8px rgba(0,0,0,0.05);
  transition: box-shadow 0.2s ease, transform 0.2s ease;
  align-items: flex-start;
}
.paper-card:hover {
  box-shadow: 0 6px 20px rgba(0,0,0,0.10);
  transform: translateY(-2px);
}
.paper-thumb {
  width: 150px;
  min-width: 150px;
  height: 110px;
  object-fit: cover;
  border-radius: 7px;
  border: 1px solid #eee;
  background: #f5f5f5;
}
.paper-info {
  flex: 1;
  min-width: 0;
}
.paper-title {
  font-size: 0.97em;
  font-weight: 700;
  margin: 0 0 7px 0;
  line-height: 1.45;
  color: #1a1a1a;
}
.paper-title a {
  color: #1a1a1a;
  text-decoration: none;
  border-bottom: 1px solid transparent;
  transition: border-color 0.15s;
}
.paper-title a:hover {
  border-bottom-color: #0076d1;
  color: #0076d1;
}
.venue-badge {
  display: inline-block;
  font-size: 0.72em;
  font-weight: 600;
  letter-spacing: 0.03em;
  padding: 3px 10px;
  border-radius: 20px;
  margin-bottom: 9px;
  text-transform: uppercase;
}
.badge-ongoing {
  background: #fff8e1;
  color: #b45309;
  border: 1px solid #fcd34d;
}
.badge-preprint {
  background: #eff6ff;
  color: #1d4ed8;
  border: 1px solid #93c5fd;
}
.badge-published {
  background: #f0fdf4;
  color: #166534;
  border: 1px solid #86efac;
}
.paper-desc {
  font-size: 0.875em;
  color: #4b5563;
  line-height: 1.65;
  margin: 0;
}
.research-section-title {
  font-size: 1.4em;
  font-weight: 700;
  margin: 44px 0 18px;
  padding-bottom: 10px;
  border-bottom: 2px solid #f3f4f6;
  color: #111;
}
</style>

<div class="research-section-title">Ongoing Work</div>

<div class="paper-card">
  <img class="paper-thumb" src="/images/ai_polarization.png" alt=""/>
  <div class="paper-info">
    <p class="paper-title">Artificial Intelligence Can Reduce Political Polarization by Challenging Partisan Expectations</p>
    <span class="venue-badge badge-ongoing">Working Paper</span>
    <p class="paper-desc">In a preregistered 2×2 experiment with 1,983 U.S. adults, AI chatbots representing either a disagreeing ingroup member or an agreeing outgroup member both reduced affective and perceived issue polarization.</p>
  </div>
</div>

<div class="paper-card">
  <img class="paper-thumb" src="/images/belief_alignment.png" alt=""/>
  <div class="paper-info">
    <p class="paper-title">Belief Alignment Amplifies Susceptibility of Large Language Models to Manipulation</p>
    <span class="venue-badge badge-ongoing">Working Paper</span>
    <p class="paper-desc">We simulate dialogues between a target LLM (role-playing a human persona) and an influencer LLM. We task the influencer to find an important belief for the target and amplify it. As measured by affective and behavioral metrics, the target LLM becomes more extreme on this belief. Belief reinforcement also propagates to related beliefs, suggesting interconnected belief structures within LLM agents.</p>
  </div>
</div>

<div class="paper-card">
  <img class="paper-thumb" src="/images/stereotypes_polarization.png" alt=""/>
  <div class="paper-info">
    <p class="paper-title">Emergence of Stereotypes and Affective Polarization from Belief Network Dynamics</p>
    <span class="venue-badge badge-ongoing">Working Paper</span>
    <p class="paper-desc">An agent-based model of belief networks shows that two basic mechanisms — social interaction and a drive for internal cognitive coherence — are sufficient to generate stereotypes from insufficient evidence. When coupled with shared group identity, these stereotypes give rise to affective polarization even in the absence of ideological conflict.</p>
  </div>
</div>

<div class="paper-card">
  <img class="paper-thumb" src="/images/rise_of_bluesky.png" alt=""/>
  <div class="paper-info">
    <p class="paper-title"><a href="https://arxiv.org/abs/2504.12902">The Rise of Bluesky</a></p>
    <span class="venue-badge badge-preprint">arXiv Preprint</span>
    <p class="paper-desc">Bluesky grew through four major user migration waves between August 2023 and February 2025, reaching 30 million accounts. The platform has developed a dense follower network with clustering and hub features that favor viral information diffusion, with structural similarities to established platforms like X (Twitter).</p>
  </div>
</div>

<div class="paper-card">
  <div class="paper-info">
    <p class="paper-title">Language Style and Emotion Matching in Chatbot Conversations</p>
    <span class="venue-badge badge-ongoing">IC2S2 2026</span>
    <p class="paper-desc">We measure language style and emotional convergence in conversations between two LLM-based chatbots. Chatbots converge in reply length, emotional expression, and linguistic features across conversation turns.</p>
  </div>
</div>

<div class="research-section-title">Published Papers</div>

<div class="paper-card">
  <img class="paper-thumb" src="/images/constructive_conflict.png" alt=""/>
  <div class="paper-info">
    <p class="paper-title"><a href="https://arxiv.org/abs/2509.18303">Identifying Constructive Conflict in Online Discussions through Controversial yet Toxicity Resilient Posts</a></p>
    <span class="venue-badge badge-published">AAAI ICWSM 2025</span>
    <p class="paper-desc">We propose <em>constructive conflict</em> as a criterion for algorithmic curation: posts that are controversial (challenging dialogue) yet toxicity resilient (respectful). High-accuracy models capturing both dimensions show that political posts are often controversial and attract toxic responses — but some remain resilient to toxicity despite their controversy, tending to use politeness cues such as gratitude and hedging.</p>
  </div>
</div>

<div class="paper-card">
  <img class="paper-thumb" src="/images/info_operations.png" alt=""/>
  <div class="paper-info">
    <p class="paper-title"><a href="https://ojs.aaai.org/index.php/ICWSM/article/view/35958">Labeled Datasets for Research on Information Operations</a></p>
    <span class="venue-badge badge-published">AAAI ICWSM 2025</span>
    <p class="paper-desc">We release labeled datasets covering 26 information operation campaigns, pairing IO posts verified by social media platforms with over 13M posts by 303k organic accounts discussing the same topics. The datasets enable development and benchmarking of IO detection algorithms by providing the control data that has been missing from prior work.</p>
  </div>
</div>

<div class="paper-card">
  <img class="paper-thumb" src="/images/loneliness_twitter.png" alt=""/>
  <div class="paper-info">
    <p class="paper-title"><a href="https://escholarship.org/uc/item/2r3874sx">Quantifying the Digital Phenotype of Loneliness on Twitter</a></p>
    <span class="venue-badge badge-published">CogSci 2024</span>
    <p class="paper-desc">We characterize loneliness on Twitter using text embeddings and social features. Lonely users are spatially separable from controls in embedding space, exhibiting self-referential language (e.g., "I should", "but I"), fewer social connections, and lower-valence posts. Results provide a starting point for computational diagnostics of loneliness from social media behavior.</p>
  </div>
</div>

<div class="paper-card">
  <img class="paper-thumb" src="/images/vaccine_debate.png" alt=""/>
  <div class="paper-info">
    <p class="paper-title"><a href="https://doi.org/10.1177/20563051241229657">Mechanisms Driving Online Vaccine Debate During the COVID-19 Pandemic</a></p>
    <span class="venue-badge badge-published">Social Media + Society 2024</span>
    <p class="paper-desc">We study the mechanisms behind vaccine debate on social media during the COVID-19 pandemic, examining how anti-vaccine misinformation spread and the role of inauthentic accounts in shaping public perception. The paper highlights how platform dynamics amplified vaccine skepticism and identifies key drivers of engagement with misleading narratives.</p>
  </div>
</div>

<div class="paper-card">
  <img class="paper-thumb" src="/images/academic_network_new.png" alt=""/>
  <div class="paper-info">
    <p class="paper-title"><a href="https://journals.sagepub.com/doi/10.1177/20563051241229657">Academic Support Network Reflects Doctoral Experience and Productivity</a></p>
    <span class="venue-badge badge-published">EPJ Data Science 2022</span>
    <p class="paper-desc">We analyze 26,236 dissertation acknowledgments to build an "academic support network" revealing five communities that support PhD students: Academic, Administration, Family, Friends &amp; Colleagues, and Spiritual. Female students mention fewer people across most communities, and the total number of acknowledgments predicts whether a discipline operates as individual or team science. University rankings and the size of academic support networks are positively correlated with productivity.</p>
  </div>
</div>
