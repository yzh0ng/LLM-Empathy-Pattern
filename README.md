# LLM-Empathy-Pattern

<h1>🤖 AI Empathy Analysis: How LLMs Respond to Breakup Scenarios</h1>

<p>
LLMs have become a trusted resource for individuals seeking support, guidance, and clarity during emotionally difficult moments. This project analyzes how three major language models—<strong>ChatGPT</strong>, <strong>Claude</strong>, and <strong>DeepSeek</strong>—respond to real breakup-related posts sourced from the <a href="https://www.reddit.com/r/BreakUps/" target="_blank">r/BreakUps subreddit</a>. We focus specifically on responses to users who have <em>cheated</em> versus those who have <em>been cheated on</em>.
</p>

<h2>🔍 Research Objectives</h2>
<ul>
  <li>Compare how different LLMs demonstrate empathy in relationship-related scenarios</li>
  <li>Examine whether models differ in emotional tone, language framing, or moral judgment</li>
  <li>Identify patterns in solution-oriented vs. emotionally supportive advice</li>
</ul>

<h2>🧪 Methodology</h2>
<ul>
  <li>Collected 20 real Reddit posts related to cheating (10 from cheaters, 10 from cheated-on users)</li>
  <li>Generated responses from each LLM (60 responses total)</li>
  <li>Processed data using:
    <ul>
      <li><strong>LIWC</strong> (Linguistic Inquiry and Word Count) for psychological and emotional language analysis</li>
      <li><strong>N-gram analysis</strong> to uncover common phrases and tone patterns</li>
    </ul>
  </li>
  <li>Conducted statistical tests (ANOVA, Tukey HSD, Welch’s t-tests) to assess significance</li>
</ul>

<h2>📊 Key Findings</h2>
<ul>
  <li>All models consistently demonstrate empathy, regardless of user role</li>
  <li><strong>ChatGPT</strong> takes a therapist-like tone, offering explanations and rational reflections</li>
  <li><strong>DeepSeek</strong> sounds more like a supportive friend, often validating emotional pain directly</li>
  <li><strong>Claude</strong> maintains a neutral, balanced tone, mirroring the user's language objectively</li>
  <li>Victims of cheating received more moral language across all models</li>
  <li>Cheaters received fewer moral judgments, possibly due to LLMs avoiding offense or maintaining neutrality</li>
</ul>

<h2>📁 Files in This Repository</h2>
<ul>
  <li><code>LIWC Analysis.csv</code> – Raw LIWC output from all LLM responses</li>
  <li><code>main_analysis.ipynb</code> – Python notebook for statistical and linguistic analysis</li>
  <li><code>plots/</code> – Visual comparisons of language use across models</li>
</ul>

<h2>📌 Future Work</h2>
<p>
We hope to expand this project by including a larger dataset and additional LLMs. We’re also exploring ways to include human-written benchmarks and incorporate deeper semantic analysis to capture more nuanced forms of empathy.
</p>

<h2>📜 Citation</h2>
<p>If you use or reference this project, please cite as:</p>
<pre>
"Empathy in AI: A Comparative Analysis of LLM Responses to Relationship Conflict" (2025)
</pre>

<h2>🤝 Contact</h2>
<p>For questions, collaborations, or feedback, feel free to open an issue or
