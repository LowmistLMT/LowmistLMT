<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/LowmistLMT/LowmistLMT/main/assets/alpenglow-observatory.webp">
  <img src="./assets/midnight-observatory.webp" alt="Lowmist’s observatory. An orange tabby naps on a glowing computer above a mountain lake.">
</picture>

### Hey, I’m Lowmist 👋

When a training run crashes, I want to know what the logs showed just before it failed. I built **TrainLens** to find those clues and compare the run with the ones that finished.

<a href="https://github.com/LowmistLMT/trainlens">
  <picture>
    <source media="(max-width: 767px)" srcset="https://raw.githubusercontent.com/LowmistLMT/LowmistLMT/main/assets/trainlens-feature-compact.svg">
    <img src="./assets/trainlens-feature.svg" alt="Explore TrainLens. In the bundled SFT example, the gradient norm reached 142.7 at step 200. Loss became NaN at step 250.">
  </picture>
</a>

[Explore TrainLens](https://github.com/LowmistLMT/trainlens) · [Run the offline demo](https://github.com/LowmistLMT/trainlens#30-second-offline-quickstart)

<details>
<summary>Would you keep checkpoint 500 or 600?</summary>

For the baseline run in the demo, I’d keep **checkpoint 500**. Its validation loss was **1.12**. By step 600, training loss had fallen from 0.95 to 0.89, but validation loss had climbed to **1.15**.

</details>

### Open source contributions

I fixed how Pillow handles incomplete PNG color profiles and how GPT Researcher renders Markdown tables split across streamed updates.

<p>
  <a href="https://github.com/python-pillow/Pillow/pull/10646"><img src="./assets/contribution-pillow.svg" width="380" alt="Pillow merged pull request 10646. Handle incomplete PNG color profiles consistently."></a>
  <a href="https://github.com/assafelovic/gpt-researcher/pull/2325"><img src="./assets/contribution-gpt-researcher.svg" width="380" alt="GPT Researcher merged pull request 2325. Keep Markdown tables intact in streamed reports."></a>
</p>
