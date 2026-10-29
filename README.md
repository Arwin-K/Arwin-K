<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Arwin-K/Arwin-K/main/assets/terminal-hero.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Arwin-K/Arwin-K/main/assets/terminal-hero-light.svg" />
    <img src="https://raw.githubusercontent.com/Arwin-K/Arwin-K/main/assets/terminal-hero-light.svg" alt="Terminal introduction: Arwin Karir, Computer Engineering at U of T, software engineer at SellStatic, interested in AI and ML infrastructure, GPU systems, and useful products" width="960" />
  </picture>
</div>

```text
Last login: 2026-10-29
arwin@macbook ~ % sw_vers
ProductName: macOS
```

---

## `arwin@macbook ~ % cat ~/about/profile.toml`

```toml
name      = "Arwin Karir"
location  = "Toronto, Canada"
education = "Computer Engineering, University of Toronto"
focus     = ["AI/ML infrastructure", "GPU performance", "computer vision", "product engineering"]
```

I like building across the stack, especially where an idea has to leave the notebook and survive real use. I care about the path from **data and inference** to **backend and interface**, including what happens when things fail and how to tell whether a change actually helped.

---

## `arwin@macbook ~ % ls -lh ~/experience`

<table>
  <tr>
    <td align="center" width="100"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Arwin-K/Arwin-K/main/assets/sellstatic-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Arwin-K/arwin-personal-website/main/public/logos/sellstatic.png" /><img src="https://raw.githubusercontent.com/Arwin-K/arwin-personal-website/main/public/logos/sellstatic.png" alt="SellStatic logo" width="76" /></picture></td>
    <td><strong>SellStatic</strong><br/>Software Engineer<br/><sub>May 2026 – present · Toronto</sub></td>
  </tr>
</table>

- Ship AI ad creation workflows with **React, C# / ASP.NET Core, AWS, and Azure**.
- Built an asynchronous video completion path with **SNS, SQS, Lambda, SES, and Azure Blob Storage** so finished renders still reach users who leave mid-render.
- Shipped brand onboarding and ad revision history, with validation, recovery paths, and tests.
- Added GA4 instrumentation across **27 product surfaces** to make user behavior measurable.

<br/>

<table>
  <tr>
    <td align="center" width="100"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Arwin-K/Arwin-K/main/assets/amazon-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Arwin-K/arwin-personal-website/main/public/logos/amazon.png" /><img src="https://raw.githubusercontent.com/Arwin-K/arwin-personal-website/main/public/logos/amazon.png" alt="Amazon logo" width="76" /></picture></td>
    <td><strong>Amazon Work Experience Program</strong><br/>Artificial Intelligence Intern<br/><sub>June – August 2023 · Remote</sub></td>
  </tr>
</table>

- Built a forest cover classification pipeline using **Python, pandas, scikit-learn, Optuna, and AWS SageMaker**.
- Worked with **464,811 records**, seven classes, and a substantial class imbalance.
- Compared a tuned decision tree with neural network and logistic regression baselines. The decision tree reached **93.4% accuracy** in that experiment.
- Measured training time and discussed accuracy versus compute cost with AWS engineers.

---

## `arwin@macbook ~ % ls ~/projects`

### GPU systems & applied ML

- **[CUDA fused causal softmax](https://github.com/Arwin-K/cuda-attention-softmax)** — A PyTorch/CUDA operator for transformer attention, with correctness checks, profiler output, and reproducible Tesla T4 benchmarks. The full-attention comparison also records where PyTorch SDPA wins.
- **[LumiSense](https://github.com/Arwin-K/lumisense)** — Camera-based lighting analysis for the U of T Sustainability Office, connecting computer vision with Raspberry Pi edge inference.
- **[Fake news detection](https://github.com/Arwin-K/fake-news-detection)** — An NLP pipeline comparing TF-IDF and classical models with contextual embeddings.

### Products & research

- **[ArwinOS](https://github.com/Arwin-K/arwin-personal-website)** — My [portfolio](https://arwink.me) as a desktop you can explore, built with React and TypeScript.
- **[Stock volatility research](https://github.com/Arwin-K/stock-price-volatility-comparison)** — Python and statistical modeling to compare volatility and predictability across penny stocks and large caps.
- **FinanceU** — A financial literacy app concept that won first prize at the ASPIRE 2030 Global Hackathon.
- **Stock prediction research** — Earlier research with Morgan State University using Python, MATLAB, and linear regression.

### In progress

```text
arwin@macbook ~ % cat ~/projects/jev/STATUS
Jev — an LLM gateway research project exploring routing, verification,
      calibration, caching, and comparisons between decision models.
Status: in progress. Results belong in the project record.
```

---

## `arwin@macbook ~ % ls ~/stack`

```text
product    ml-systems    infrastructure
```

**Product — interfaces, APIs, databases**  
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=ts,js,react,vite,cs,dotnet,postgres,mongodb&amp;theme=dark" />
  <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=ts,js,react,vite,cs,dotnet,postgres,mongodb&amp;theme=light" />
  <img src="https://skillicons.dev/icons?i=ts,js,react,vite,cs,dotnet,postgres,mongodb&amp;theme=light" alt="TypeScript, JavaScript, React, Vite, C sharp, .NET, PostgreSQL, MongoDB" />
</picture>

**ML & systems — training, inference, vision, GPU work**  
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=python,cpp,pytorch,opencv,raspberrypi,linux&amp;theme=dark" />
  <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=python,cpp,pytorch,opencv,raspberrypi,linux&amp;theme=light" />
  <img src="https://skillicons.dev/icons?i=python,cpp,pytorch,opencv,raspberrypi,linux&amp;theme=light" alt="Python, C plus plus, PyTorch, OpenCV, Raspberry Pi, Linux" />
</picture>  
<sub>CUDA · ONNX · scikit-learn · NumPy · pandas</sub>

**Infrastructure — cloud, containers, tooling**  
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=aws,azure,docker,git,github&amp;theme=dark" />
  <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=aws,azure,docker,git,github&amp;theme=light" />
  <img src="https://skillicons.dev/icons?i=aws,azure,docker,git,github&amp;theme=light" alt="AWS, Azure, Docker, Git, GitHub" />
</picture>  
<sub>SNS/SQS · Lambda · SageMaker · CI · profiling and benchmarks</sub>

---

## `arwin@macbook ~ % cat ~/interests.txt`

Photography, comics, a good sunset, and making the details of a project feel intentional. Some of my photos live on [ArwinOS](https://arwink.me).

```zsh
arwin@macbook ~ % open https://arwink.me
```

[portfolio](https://arwink.me) · [LinkedIn](https://www.linkedin.com/in/arwin-karir/) · [email](mailto:karirarwin@gmail.com) · [photography](https://www.instagram.com/karir.visuals/)

```text
arwin@macbook ~ % _
```
