---
theme: seriph
title: "From the Perceptron to Agentic AI"
info: |
  Opening slide for a premium academic presentation on the evolution of Artificial Intelligence.
class: opening-slide
transition: fade
drawings:
  persist: false
colorSchema: light
---

<section class="slide-shell hero-opening">
  <div class="hero-copy">
    <p class="academic-kicker">Master's-level course in Artificial Intelligence, Data Science, and Computer Engineering</p>
    <h1>From the Perceptron to Agentic AI</h1>
    <p class="hero-subtitle">Understanding the Evolution of Artificial Intelligence</p>
    <p class="purpose-line">An intuitive journey from biological neurons and perceptrons to deep learning, transformers, generative AI, agents, and emerging AI frontiers.</p>
  </div>

  <div class="hero-figure">
    <img :src="'/images/slide-1-ai-evolution-hero.png'" alt="Conceptual evolution of AI from neurons to modern agentic systems" />
  </div>

  <div class="evolution-roadmap" aria-label="Course roadmap">
    <div>
      <span>01</span>
      <strong>Foundations</strong>
      <small>Neurons, Perceptrons, Neural Networks</small>
    </div>
    <div>
      <span>02</span>
      <strong>Deep Learning</strong>
      <small>CNNs, Sequence Models, GPUs</small>
    </div>
    <div>
      <span>03</span>
      <strong>Modern AI</strong>
      <small>Transformers, LLMs, Generative AI</small>
    </div>
    <div>
      <span>04</span>
      <strong>Intelligent Systems</strong>
      <small>Agents, World Models, Embodied AI</small>
    </div>
    <div>
      <span>05</span>
      <strong>Emerging Frontiers</strong>
      <small>Federated Learning, Edge AI, AI Safety</small>
    </div>
  </div>
</section>

---
class: roadmap-slide
---

<section class="slide-shell course-roadmap">
  <div class="roadmap-header">
    <h1>The Evolution of AI We Will Explore</h1>
    <p>A structured journey from neural foundations to modern intelligent systems</p>
  </div>

  <div class="roadmap-timeline">
    <div class="roadmap-line"></div>

<div class="roadmap-step">
  <div class="roadmap-number">01</div>
  <div class="roadmap-title">Foundations</div>
  <div class="roadmap-text">Biological neurons · Perceptrons · Neural networks</div>
</div>

<div class="roadmap-step">
  <div class="roadmap-number">02</div>
  <div class="roadmap-title">Deep Learning</div>
  <div class="roadmap-text">Hidden layers · CNNs · GPUs and big data</div>
</div>

<div class="roadmap-step">
  <div class="roadmap-number">03</div>
  <div class="roadmap-title">Transformers & LLMs</div>
  <div class="roadmap-text">Attention · Language models · Reasoning interfaces</div>
</div>

<div class="roadmap-step">
  <div class="roadmap-number">04</div>
  <div class="roadmap-title">Generative & Agentic AI</div>
  <div class="roadmap-text">Multimodal generation · Tools · Memory · Planning</div>
</div>

<div class="roadmap-step">
  <div class="roadmap-number">05</div>
  <div class="roadmap-title">Emerging Frontiers</div>
  <div class="roadmap-text">World models · Embodied AI · Federated learning · Edge AI · Safety</div>
</div>
  </div>
</section>

---
class: ai-meaning-slide
---

<section class="slide-shell ai-meaning">
<div class="ai-meaning-header">
  <h1>What Do We Mean by Artificial Intelligence?</h1>
  <p>AI is the attempt to build systems that transform data into intelligent behavior.</p>
</div>

<div class="ai-system-visual">
  <img :src="'/images/slide-3-ai-capabilities.png'" alt="Abstract AI system connecting perception, learning, reasoning, generation, and action" />
</div>

<div class="capability-grid">
  <div class="capability-card">
    <div class="capability-icon perceive"></div>
    <strong>Perceive</strong>
    <span>Interpret signals from the world</span>
  </div>
  <div class="capability-card">
    <div class="capability-icon learn"></div>
    <strong>Learn</strong>
    <span>Improve from examples and experience</span>
  </div>
  <div class="capability-card">
    <div class="capability-icon reason"></div>
    <strong>Reason</strong>
    <span>Connect information and make decisions</span>
  </div>
  <div class="capability-card">
    <div class="capability-icon generate"></div>
    <strong>Generate</strong>
    <span>Create new text, images, audio, video, and ideas</span>
  </div>
  <div class="capability-card">
    <div class="capability-icon act"></div>
    <strong>Act</strong>
    <span>Use tools, interact with environments, and support humans</span>
  </div>
</div>
</section>

---
class: ai-hierarchy-slide
---

<section class="slide-shell ai-hierarchy">
<div class="ai-hierarchy-header">
  <h1>AI, Machine Learning, and Deep Learning</h1>
  <p>Three terms that are often confused — but they describe different levels of the same evolution.</p>
</div>

<div class="hierarchy-visual">
  <div class="nested-ai-map">
    <div class="ai-layer layer-ai">
      <span>Artificial Intelligence</span>
      <small>systems that perform tasks requiring intelligence</small>
    </div>
    <div class="ai-layer layer-ml">
      <span>Machine Learning</span>
      <small>systems that learn patterns from data</small>
    </div>
    <div class="ai-layer layer-dl">
      <span>Deep Learning</span>
      <small>neural networks with many layers</small>
    </div>
    <div class="ai-layer layer-fm">
      <span>Foundation Models</span>
      <small>large models trained on broad data</small>
    </div>
    <div class="ai-layer layer-agents">
      <span>Generative AI & Agents</span>
      <small>models connected to tools, memory, and actions</small>
    </div>
  </div>

  <div class="hierarchy-note">
    <strong>Modern AI systems are built on layers of abstraction.</strong>
    <span>Each new layer reuses earlier ideas while expanding what systems can learn, generate, and do.</span>
  </div>
</div>
</section>

---
class: neuron-perceptron-slide
---

<section class="slide-shell perceptron-slide neuron-perceptron">
<div class="np-header">
<h1>From Biological Neurons to the Perceptron</h1>
<p>The perceptron was biologically inspired, but it is a mathematical decision unit.</p>
</div>

<div class="perceptron-comparison">
<div class="np-card np-bio-card">
<strong>Biological neuron</strong>
<span>Dendrites receive signals</span>
<span>Cell body integrates signals</span>
<span>Axon sends output</span>
</div>
<div class="np-image-frame">
<img :src="'/images/biological-neuron-vs-perceptron.png'" alt="Public-domain comparison of biological neural organization and a perceptron" />
<div class="np-bridge">Biology <span></span> abstraction <span></span> computation</div>
</div>
<div class="np-card np-math-card">
<strong>Perceptron</strong>
<span>Inputs receive values</span>
<span>Weights control importance</span>
<span>Activation produces output</span>
</div>
</div>

<div class="analogy-row">
<div class="analogy-card">
<strong>Signals</strong>
<span>Inputs</span>
</div>
<div class="analogy-card">
<strong>Synaptic strength</strong>
<span>Weights</span>
</div>
<div class="analogy-card">
<strong>Firing</strong>
<span>Activation / output</span>
</div>
</div>
</section>

---
class: perceptron-decision-slide
---

<section class="slide-shell perceptron-slide perceptron-decision">
<div class="pd-header">
<h1>How a Perceptron Makes a Decision</h1>
<p>Multiple input signals become one binary decision by weighting evidence and applying an activation rule.</p>
</div>

<div class="pd-layout">
<div class="pd-left">
<div class="perceptron-pipeline">
<div class="perceptron-node">
<span>Inputs</span>
<small>measurable features</small>
</div>
<div class="perceptron-arrow"></div>
<div class="perceptron-node">
<span>Weights</span>
<small>importance of each feature</small>
</div>
<div class="perceptron-arrow"></div>
<div class="perceptron-node">
<span>Weighted Sum</span>
<small>combined evidence</small>
</div>
<div class="perceptron-arrow"></div>
<div class="perceptron-node">
<span>Activation</span>
<small>decision threshold</small>
</div>
<div class="perceptron-arrow"></div>
<div class="perceptron-node output-node">
<span>Output</span>
<small>class or decision</small>
</div>
</div>
<div class="formula-pill">y = step(w · x + b)</div>
<div class="decision-boundary">
<div class="boundary-caption">
<strong>Decision boundary</strong>
<span>learned weights define a separating line</span>
</div>
<div class="boundary-plane">
<div class="boundary-line"></div>
<i class="dot blue d1"></i>
<i class="dot blue d2"></i>
<i class="dot blue d3"></i>
<i class="dot cyan d4"></i>
<i class="dot purple d5"></i>
<i class="dot purple d6"></i>
<i class="dot purple d7"></i>
<i class="dot ink d8"></i>
</div>
</div>
</div>
<div class="why-card">
<strong>Why it matters</strong>
<span>Introduced learning as weight adjustment</span>
<span>Connected computation with decision boundaries</span>
<span>Became the conceptual seed of neural networks</span>
</div>
</div>
</section>

---
class: xor-limitation-slide
---

<section class="slide-shell xor-slide">
<div class="xor-header">
<h1>When One Neuron Is Not Enough</h1>
<p>Some patterns cannot be solved with a single linear boundary.</p>
</div>

<div class="xor-layout">
<div class="xor-panels">
<div class="xor-panel">
<strong>Linearly separable</strong>
<div class="xor-plot-frame">
<img :src="'/images/xor-perceptron-limitation.svg'" alt="Linearly separable points separated by a single straight boundary" />
</div>
<span class="success-label">Perceptron works</span>
</div>
<div class="xor-panel">
<strong>XOR pattern</strong>
<div class="xor-plot-frame xor-plot-crop">
<img :src="'/images/xor-perceptron-limitation.svg'" alt="XOR points showing that no single straight boundary can separate diagonal classes" />
</div>
<span class="failure-label">Perceptron fails</span>
</div>
</div>

<div class="xor-side">
<div class="xor-quote">
<strong>The limitation was not learning.</strong>
<span>The limitation was representation.</span>
</div>
<div class="xor-transition">Next step: from one neuron to many neurons.</div>
</div>
</div>
</section>

---
class: many-neurons-slide
---

<section class="slide-shell many-neurons">
<div class="many-neurons-header">
<h1>The Solution: Many Neurons</h1>
<p>A network combines many simple decisions into a more expressive model.</p>
</div>

<div class="many-neurons-layout">
<div class="neuron-transition-visual">
<div class="transition-label one-label">One neuron</div>
<div class="transition-label connect-label">connect</div>
<div class="transition-label many-label">Many neurons</div>
<img :src="'/images/one-neuron-to-network.svg'" alt="Transition from a single perceptron to many connected neurons in layers" />
</div>
<div class="neuron-support-card">
<span>One neuron learns one simple rule.</span>
<span>Many neurons combine simple rules.</span>
<span>A network can model richer patterns.</span>
</div>
</div>

<div class="takeaway-pill">Depth begins when simple units work together.</div>
</section>

---
class: mlp-slide
---

<section class="slide-shell mlp-contained">
<div class="mlp-contained-header">
<h1>Inside a Multilayer Perceptron</h1>
<p>Inputs move through layers of weighted sums, activations, and task-specific outputs.</p>
</div>

<div class="mlp-contained-main">
<div class="mlp-left-panel">
<img :src="'/images/mlp-overview-detailed.svg'" alt="Large clean MLP diagram with input layer, two hidden layers, output layer, and one highlighted path" />
</div>

<div class="mlp-right-column">
<div class="mlp-column-card mlp-neuron-card">
<span class="mlp-column-label">Inside one neuron</span>
<div class="mlp-neuron-flow">
<div class="mlp-input-stack">
<b>x₁</b><small>w₁</small>
<b>x₂</b><small>w₂</small>
<b>x₃</b><small>w₃</small>
</div>
<i class="mlp-flow-arrow"></i>
<div class="mlp-compute-box">
<strong>weighted sum + bias</strong>
<em>z = Σ wᵢxᵢ + b</em>
</div>
<i class="mlp-flow-arrow"></i>
<div class="mlp-activation-box">
<strong>activation</strong>
<em>a = φ(z)</em>
</div>
<i class="mlp-flow-arrow"></i>
<div class="mlp-output-dot">a</div>
</div>
</div>

<div class="mlp-column-card mlp-functions-card">
<span class="mlp-column-label">Activation functions</span>
<p>Nonlinearity makes stacked layers expressive.</p>
<strong>ReLU · sigmoid · tanh</strong>
<div class="mlp-function-plots" aria-hidden="true">
<div>
<svg viewBox="0 0 86 50"><path class="plot-axis" d="M9 38 H78 M24 8 V42" /><path class="plot-line" d="M10 36 H40 L78 12" /></svg>
</div>
<div>
<svg viewBox="0 0 86 50"><path class="plot-axis" d="M9 38 H78 M24 8 V42" /><path class="plot-line" d="M10 37 C26 37 30 29 38 23 C47 15 56 12 78 12" /></svg>
</div>
<div>
<svg viewBox="0 0 86 50"><path class="plot-axis" d="M9 25 H78 M24 8 V42" /><path class="plot-line soft" d="M10 38 C27 38 30 25 43 25 C56 25 59 12 78 12" /></svg>
</div>
</div>
</div>

<div class="mlp-column-card mlp-output-layer-card">
<span class="mlp-column-label">Output layer</span>
<p>Task determines output shape.</p>
<div class="mlp-output-rows">
<div><b>1 neuron</b><span>→ regression</span></div>
<div><b>K neurons</b><span>→ classification</span></div>
</div>
</div>
</div>
</div>
</section>

---
class: representation-slide
---

<section class="slide-shell representation-clarity">
<div class="representation-header">
<h1>From Lines to Representations</h1>
<p>Hidden layers reshape the problem before the final decision is made.</p>
</div>

<div class="representation-clarity-layout">
<div class="representation-story-frame">
<div class="representation-story-labels">
<div>
<strong>Raw data</strong>
<span>XOR-like points</span>
</div>
<div>
<strong>Hidden layers</strong>
<span>Transform the space</span>
</div>
<div>
<strong>Useful representation</strong>
<span>One line separates</span>
</div>
</div>
<div class="representation-story-image">
<img :src="'/images/lines-to-representations.svg'" alt="Pipeline from raw nonlinear data through hidden layers to a useful representation space" />
</div>
</div>
<div class="representation-takeaway-card">
<strong>Hidden layers do not just classify.</strong>
<span>They reshape the problem.</span>
</div>
</div>
</section>

---
class: forward-propagation-slide
---

<section class="slide-shell forward-slide forward-rebuilt">
<div class="forward-header">
<div class="step-badge">STEP 1 — FORWARD PASS</div>
<h1>Forward Propagation</h1>
<p>How information moves from inputs to prediction.</p>
</div>

<div class="forward-layout forward-template-layout">
<div class="forward-visual-frame">
<div class="flow-label input-flow-label">Input</div>
<div class="flow-label layer-one-label">Layer 1</div>
<div class="flow-label layer-two-label">Layer 2</div>
<div class="flow-label output-flow-label">Prediction</div>
<img :src="'/images/forward-propagation-flow.svg'" alt="Input features flowing through two neural network layers to an output prediction" />
</div>
<div class="forward-card">
<span>Each layer transforms the signal.</span>
<span>The final layer produces a prediction.</span>
</div>
</div>

<div class="takeaway-pill forward-pill">Forward propagation is the network’s first guess.</div>
</section>

---
class: loss-intro-step-slide
---

<section class="slide-shell training-slide loss-perfect">
<div class="training-header">
<div class="step-badge">STEP 2 — COMPUTE LOSS</div>
<h1>Learning Means Reducing Error</h1>
<p>After a prediction, the network compares its answer with the correct one.</p>
</div>

<div class="loss-perfect-layout">
<div class="loss-perfect-board">
<svg class="loss-perfect-diagram" viewBox="0 0 1000 380" role="img" aria-label="The network makes a prediction, compares it with the target, computes loss, and sends feedback to update weights">
<defs>
<linearGradient id="lossPerfectGradient" x1="0" x2="1" y1="0" y2="1">
<stop offset="0%" stop-color="#1d4ed8"/>
<stop offset="52%" stop-color="#06b6d4"/>
<stop offset="100%" stop-color="#7c3aed"/>
</linearGradient>
<marker id="lossPerfectArrow" markerHeight="12" markerWidth="14" orient="auto" refX="12" refY="6">
<path d="M0 0 L14 6 L0 12 Z" fill="#7c3aed"/>
</marker>
</defs>

<text class="lp-section-label" x="60" y="28">Forward pass</text>
<rect class="lp-svg-box lp-blue" x="60" y="48" width="165" height="82" rx="16"/>
<text class="lp-svg-label" x="142" y="80">INPUT</text>
<text class="lp-svg-value" x="142" y="113">x</text>

<line class="lp-svg-arrow" x1="255" y1="89" x2="365" y2="89"/>

<rect class="lp-svg-network" x="390" y="38" width="210" height="102" rx="18"/>
<circle class="lp-svg-glow" cx="548" cy="48" r="36"/>
<text class="lp-svg-label white" x="495" y="75">NETWORK</text>
<text class="lp-svg-value white" x="495" y="116">f(x)</text>

<line class="lp-svg-arrow" x1="630" y1="89" x2="740" y2="89"/>

<rect class="lp-svg-box lp-purple" x="765" y="48" width="175" height="82" rx="16"/>
<text class="lp-svg-label" x="852" y="80">PREDICTION</text>
<text class="lp-svg-value" x="852" y="113">ŷ</text>

<text class="lp-section-label" x="60" y="180">Compare with the correct answer</text>
<rect class="lp-svg-box lp-purple" x="60" y="205" width="155" height="82" rx="16"/>
<text class="lp-svg-label" x="137" y="237">PREDICTION</text>
<text class="lp-svg-value" x="137" y="270">ŷ</text>

<text class="lp-svg-plus" x="251" y="258">+</text>

<rect class="lp-svg-box lp-cyan" x="290" y="205" width="155" height="82" rx="16"/>
<text class="lp-svg-label" x="367" y="237">TARGET</text>
<text class="lp-svg-value" x="367" y="270">y</text>

<line class="lp-svg-arrow" x1="475" y1="246" x2="555" y2="246"/>

<rect class="lp-svg-loss" x="585" y="190" width="205" height="112" rx="18"/>
<text class="lp-svg-label white" x="688" y="226">LOSS</text>
<text class="lp-svg-loss-value" x="688" y="263">How wrong?</text>
<text class="lp-svg-small white" x="688" y="286">error signal</text>

<line class="lp-svg-arrow" x1="820" y1="246" x2="880" y2="246"/>

<rect class="lp-svg-box lp-cyan" x="895" y="205" width="82" height="82" rx="16"/>
<text class="lp-svg-label" x="936" y="237">UPDATE</text>
<text class="lp-svg-small" x="936" y="263">weights</text>

<path class="lp-svg-feedback" d="M936 202 C890 148 715 130 600 96"/>
<text class="lp-feedback-label" x="752" y="150">feedback</text>
</svg>
</div>

<div class="loss-perfect-note">
<div class="lp-perfect-mark" aria-hidden="true"></div>
<strong>Loss makes learning measurable.</strong>
<p>The loss tells the network how far the prediction is from the target.</p>
<p>Training means adjusting weights so this value becomes smaller.</p>
</div>
</div>

<div class="loss-perfect-pill">Error becomes feedback for the next update.</div>
</section>

---
class: loss-measure-slide
---

<section class="slide-shell training-slide loss-measure">
<div class="training-header">
<h1>What the Loss Measures</h1>
<p>Loss turns a mismatch between prediction and target into a single training signal.</p>
</div>

<div class="loss-measure-layout">
<div class="measure-example-card regression-example">
<div class="measure-card-header">
<span>Regression</span>
<strong>Distance from the target</strong>
</div>
<div class="number-comparison">
<div><span>Prediction</span><strong>72</strong></div>
<div><span>Target</span><strong>80</strong></div>
</div>
<div class="distance-bar">
<i></i>
</div>
<small>Bigger gap → higher loss</small>
</div>

<div class="measure-example-card classification-example">
<div class="measure-card-header">
<span>Classification</span>
<strong>Confidence on the correct class</strong>
</div>
<div class="class-bars">
<div><span>A</span><i style="--bar: 42%"></i></div>
<div class="correct"><span>B</span><i style="--bar: 68%"></i></div>
<div><span>C</span><i style="--bar: 24%"></i></div>
</div>
<small>More confidence in the target → lower loss</small>
</div>

<div class="loss-signal-card">
<strong>Loss is not a label.</strong>
<span>It is the score that tells learning which direction to improve.</span>
</div>
</div>
</section>

---
class: backpropagation-slide
---

<section class="slide-shell training-slide backprop-slide backprop-clean">
<div class="training-header">
<div class="step-badge">STEP 3 — BACKPROPAGATION</div>
<h1>Backpropagation</h1>
<p>Error information flows backward so the network knows how to change its weights.</p>
</div>

<div class="backprop-clean-layout">
<div class="backprop-visual-frame">
<div class="flow-caption-row">
<div class="flow-caption forward-caption">Forward: input → hidden layers → prediction</div>
<div class="flow-caption backward-caption">Backward: loss → gradients → earlier layers</div>
</div>
<img :src="'/images/backpropagation-online-explanation.png'" alt="Backpropagation diagram showing error signals flowing backward through a neural network" />
</div>

<div class="backprop-card-stack">
<div class="backprop-card">
<span>01</span>
<strong>Prediction</strong>
<p>Compared with the target.</p>
</div>
<div class="backprop-card">
<span>02</span>
<strong>Loss</strong>
<p>Measures the error.</p>
</div>
<div class="backprop-card emphasis">
<span>03</span>
<strong>Gradients</strong>
<p>Tell weights how to change.</p>
</div>
</div>
</div>
</section>

---
class: gradient-descent-slide
---

<section class="slide-shell training-slide gradient-descent">
<div class="training-header">
<div class="step-badge">STEP 3 — BACKPROPAGATION</div>
<h1>Gradient Descent</h1>
<p>Backpropagation computes the direction; gradient descent uses it to reduce the loss.</p>
</div>

<div class="gradient-descent-layout">
<div class="gd-visual-frame">
<img :src="'/images/gradient-descent-flow.svg'" alt="Loss curve with gradient descent steps moving toward a lower loss minimum" />
</div>
<div class="gd-card-stack">
<div class="gd-card">
<span>What it is</span>
<strong>An optimization method</strong>
<p>It searches for weights that make the loss smaller.</p>
</div>
<div class="gd-card">
<span>What it is for</span>
<strong>Learning from error</strong>
<p>It turns gradients into concrete parameter updates.</p>
</div>
<div class="gd-card emphasis">
<span>How it works</span>
<strong>Step downhill</strong>
<p>Move weights opposite the gradient, then repeat.</p>
</div>
</div>
</div>

<div class="training-takeaway">Gradient descent is how error becomes improvement.</div>
</section>

---
class: backprop-history-slide
---

<section class="slide-shell training-slide history-slide history-clean">
<div class="training-header">
<h1>Why Backpropagation Changed Neural Networks</h1>
<p>Training hidden layers became practical once error could be assigned backward.</p>
</div>

<div class="history-clean-layout">
<div class="history-photo-frame">
<img :src="'/images/geoffrey-hinton-photo.jpg'" alt="Geoffrey Hinton" />
<div>
<strong>Geoffrey Hinton</strong>
<span>Influential figure in deep learning</span>
</div>
</div>

<div class="history-main-column">
<div class="history-timeline">
<div class="history-event">
<span>1974</span>
<strong>Paul Werbos</strong>
<p>Early formulation of backpropagation ideas.</p>
</div>
<div class="history-event">
<span>1986</span>
<strong>Rumelhart · Hinton · Williams</strong>
<p>Backpropagation for multilayer neural networks.</p>
</div>
<div class="history-event">
<span>2018</span>
<strong>Turing Award</strong>
<p>Deep learning foundations.</p>
</div>
<div class="history-event">
<span>2024</span>
<strong>Nobel Prize in Physics</strong>
<p>Neural networks and statistical physics impact.</p>
</div>
</div>
<div class="history-insight-card">
<span>Backpropagation made hidden layers trainable by solving credit assignment.</span>
</div>
</div>
</div>
</section>

---
class: training-loop-slide
---

<section class="slide-shell training-slide training-loop-slide loop-clean">
<div class="training-header">
<h1>The Training Loop</h1>
<p>Neural networks learn by repeating a simple cycle: predict, measure, correct, repeat.</p>
</div>

<div class="training-loop-layout">
<div class="training-loop-visual">
<img :src="'/images/training-loop.svg'" alt="Four step loop: forward pass, compute loss, backpropagation, update weights, then better prediction" />
</div>
<div class="loop-step-list">
<div class="loop-step">
<span class="step-badge">STEP 1 — FORWARD PASS</span>
<strong>Make a prediction</strong>
</div>
<div class="loop-step">
<span class="step-badge">STEP 2 — COMPUTE LOSS</span>
<strong>Measure error</strong>
</div>
<div class="loop-step">
<span class="step-badge">STEP 3 — BACKPROPAGATION</span>
<strong>Send error backward</strong>
</div>
<div class="loop-step">
<span class="step-badge">STEP 4 — UPDATE WEIGHTS</span>
<strong>Change parameters</strong>
</div>
</div>
</div>
<div class="training-takeaway">Learning is a loop: predict, measure, correct, repeat.</div>
</section>


---
class: nonlinear-slide
---

<section class="slide-shell concept-slide nonlinear-concept">
<div class="concept-header">
<h1>Why Nonlinearity Matters</h1>
<p>Without nonlinear activations, many linear layers collapse into one linear transformation.</p>
</div>

<div class="nonlinear-layout">
<div class="nonlinear-panel">
<div class="concept-panel-heading">
<strong>Linear layers only</strong>
<span>simple straight boundary</span>
</div>
<svg class="boundary-mini-plot" viewBox="0 0 360 220" role="img" aria-label="Linear boundary separating two classes">
<path class="plot-grid" d="M40 30 H330 M40 90 H330 M40 150 H330 M100 20 V195 M180 20 V195 M260 20 V195" />
<path class="linear-boundary-line" d="M78 184 L298 38" />
<circle class="plot-blue" cx="98" cy="72" r="12"/><circle class="plot-blue" cx="142" cy="112" r="12"/><circle class="plot-blue" cx="178" cy="68" r="12"/><circle class="plot-blue" cx="132" cy="158" r="12"/>
<circle class="plot-purple" cx="238" cy="88" r="12"/><circle class="plot-purple" cx="276" cy="132" r="12"/><circle class="plot-purple" cx="216" cy="166" r="12"/><circle class="plot-purple" cx="296" cy="72" r="12"/>
</svg>
</div>

<div class="nonlinear-panel active">
<div class="concept-panel-heading">
<strong>Linear + activation</strong>
<span>flexible nonlinear boundary</span>
</div>
<svg class="boundary-mini-plot" viewBox="0 0 360 220" role="img" aria-label="Nonlinear boundary separating two classes">
<path class="plot-grid" d="M40 30 H330 M40 90 H330 M40 150 H330 M100 20 V195 M180 20 V195 M260 20 V195" />
<path class="nonlinear-boundary-line" d="M52 156 C112 80 152 182 210 114 C252 64 292 104 326 44" />
<circle class="plot-blue" cx="86" cy="62" r="12"/><circle class="plot-blue" cx="124" cy="122" r="12"/><circle class="plot-blue" cx="174" cy="82" r="12"/><circle class="plot-blue" cx="232" cy="62" r="12"/>
<circle class="plot-purple" cx="96" cy="170" r="12"/><circle class="plot-purple" cx="186" cy="160" r="12"/><circle class="plot-purple" cx="260" cy="148" r="12"/><circle class="plot-purple" cx="304" cy="110" r="12"/>
</svg>
</div>

<div class="activation-strip">
<div><strong>ReLU</strong><svg viewBox="0 0 90 54"><path class="mini-axis" d="M10 40 H80 M28 10 V46"/><path class="relu-line" d="M12 39 H40 L78 14"/></svg></div>
<div><strong>sigmoid</strong><svg viewBox="0 0 90 54"><path class="mini-axis" d="M10 40 H80 M28 10 V46"/><path class="sigmoid-line" d="M12 40 C30 40 34 30 44 25 C54 18 62 14 78 14"/></svg></div>
<div><strong>tanh</strong><svg viewBox="0 0 90 54"><path class="mini-axis" d="M10 27 H80 M28 10 V46"/><path class="tanh-line" d="M12 42 C30 42 34 28 45 27 C56 26 60 12 78 12"/></svg></div>
</div>
</div>

<div class="concept-takeaway">Activation functions make deep networks expressive.</div>
</section>

---
class: representation-learning-slide
---

<section class="slide-shell concept-slide rep-learning-premium">
<div class="concept-header">
<h1>Representation Learning</h1>
<p>Hidden layers transform raw inputs into more useful internal features.</p>
</div>

<div class="rep-learning-story">
<div class="rep-learning-pipeline">
<div class="rep-learning-stage">
<em>Input</em>
<strong>Pixels</strong>
<span>raw input</span>
<div class="rep-pixels" aria-hidden="true"><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i></div>
</div>
<div class="rep-learning-arrow" aria-hidden="true"></div>
<div class="rep-learning-stage">
<em>Early layer</em>
<strong>Edges</strong>
<span>early features</span>
<div class="rep-edges" aria-hidden="true"><i></i><i></i><i></i></div>
</div>
<div class="rep-learning-arrow" aria-hidden="true"></div>
<div class="rep-learning-stage">
<em>Deeper layer</em>
<strong>Shapes</strong>
<span>intermediate features</span>
<div class="rep-shapes" aria-hidden="true"><i></i><i></i><i></i></div>
</div>
<div class="rep-learning-arrow" aria-hidden="true"></div>
<div class="rep-learning-stage final">
<em>Final representation</em>
<strong>Object</strong>
<span>high-level concept</span>
<div class="rep-object" aria-hidden="true"></div>
</div>
</div>

<div class="rep-learning-example-card">
<div class="example-badge">Example</div>
<strong>Image recognition</strong>
<span>Pixels → edges → shapes → object</span>
<p>The network builds internal features that make recognition easier.</p>
</div>
</div>

<div class="concept-takeaway">Deep learning works because it learns features, not just decisions.</div>
</section>

---
class: generalization-slide
---

<section class="slide-shell concept-slide gen-premium">
<div class="concept-header">
<h1>Generalization</h1>
<p>A good model does not only work on training data — it must work on new data too.</p>
</div>

<div class="gen-premium-story">
<div class="gen-premium-flow">
<div class="gen-premium-card">
<em>Seen data</em>
<strong>Training examples</strong>
<span>the model studies these cases</span>
<div class="gen-premium-dots seen" aria-hidden="true"><i></i><i></i><i></i><i></i><i></i><i></i></div>
</div>

<div class="gen-premium-arrow" aria-hidden="true"></div>

<div class="gen-premium-card rule">
<em>General rule</em>
<strong>Learned pattern</strong>
<span>the useful structure behind the data</span>
<svg viewBox="0 0 210 116" aria-hidden="true">
<path class="rule-band" d="M24 83 C54 34 86 88 116 55 C146 22 170 37 188 28" />
<path class="rule-line" d="M24 83 C54 34 86 88 116 55 C146 22 170 37 188 28" />
<circle cx="48" cy="66" r="8" /><circle cx="82" cy="58" r="8" /><circle cx="118" cy="56" r="8" /><circle cx="158" cy="40" r="8" />
</svg>
</div>

<div class="gen-premium-arrow" aria-hidden="true"></div>

<div class="gen-premium-card">
<em>Unseen data</em>
<strong>New examples</strong>
<span>the real test of learning</span>
<div class="gen-premium-dots unseen" aria-hidden="true"><i></i><i></i><i></i><i></i><i></i></div>
</div>
</div>

<div class="gen-premium-example">
<div class="example-badge">Real world</div>
<div class="gen-medical-mark" aria-hidden="true"></div>
<strong>Medical AI</strong>
<p>It should work on new patients, not only on patients seen during training.</p>
</div>
</div>

<div class="concept-takeaway">Success is measured on unseen data.</div>
</section>

---
class: overfitting-slide
---

<section class="slide-shell concept-slide overfitting-concept">
<div class="concept-header">
<h1>Overfitting</h1>
<p>When a model memorizes the training data instead of learning the real pattern.</p>
</div>

<div class="rl-overfit-layout">
<div class="rl-fit-frame">
<div class="rl-fit-panel">
<strong>Underfitting</strong>
<svg viewBox="0 0 300 190" role="img" aria-label="Underfitting plot">
<path class="rl-plot-grid" d="M34 42 H270 M34 96 H270 M34 150 H270 M86 24 V166 M154 24 V166 M222 24 V166"/>
<path class="rl-fit-line muted" d="M48 130 L256 72"/>
<circle class="rl-plot-blue" cx="64" cy="118" r="8"/><circle class="rl-plot-blue" cx="104" cy="96" r="8"/><circle class="rl-plot-blue" cx="142" cy="74" r="8"/><circle class="rl-plot-purple" cx="186" cy="108" r="8"/><circle class="rl-plot-purple" cx="224" cy="82" r="8"/><circle class="rl-plot-purple" cx="252" cy="48" r="8"/>
</svg>
</div>
<div class="rl-fit-panel good">
<strong>Good fit</strong>
<svg viewBox="0 0 300 190" role="img" aria-label="Good fit plot">
<path class="rl-plot-grid" d="M34 42 H270 M34 96 H270 M34 150 H270 M86 24 V166 M154 24 V166 M222 24 V166"/>
<path class="rl-fit-line" d="M48 140 C94 96 132 86 170 104 C210 122 232 84 260 46"/>
<circle class="rl-plot-blue" cx="64" cy="122" r="8"/><circle class="rl-plot-blue" cx="104" cy="96" r="8"/><circle class="rl-plot-blue" cx="142" cy="84" r="8"/><circle class="rl-plot-purple" cx="186" cy="108" r="8"/><circle class="rl-plot-purple" cx="224" cy="82" r="8"/><circle class="rl-plot-purple" cx="252" cy="52" r="8"/>
</svg>
</div>
<div class="rl-fit-panel">
<strong>Overfitting</strong>
<svg viewBox="0 0 300 190" role="img" aria-label="Overfitting plot">
<path class="rl-plot-grid" d="M34 42 H270 M34 96 H270 M34 150 H270 M86 24 V166 M154 24 V166 M222 24 V166"/>
<path class="rl-fit-line over" d="M50 138 C78 58 94 152 118 96 C142 40 156 140 186 108 C212 80 218 32 234 84 C244 118 254 74 264 48"/>
<circle class="rl-plot-blue" cx="64" cy="122" r="8"/><circle class="rl-plot-blue" cx="104" cy="96" r="8"/><circle class="rl-plot-blue" cx="142" cy="84" r="8"/><circle class="rl-plot-purple" cx="186" cy="108" r="8"/><circle class="rl-plot-purple" cx="224" cy="82" r="8"/><circle class="rl-plot-purple" cx="252" cy="52" r="8"/>
</svg>
</div>
</div>

<div class="rl-side-list">
<span>Too simple → misses the pattern</span>
<span>Balanced → captures the pattern</span>
<span>Too complex → memorizes noise</span>
</div>
</div>

<div class="concept-takeaway">Too much flexibility can become memorization.</div>
</section>

---
class: fight-overfitting-slide
---

<section class="slide-shell concept-slide fight-overfitting">
<div class="concept-header">
<h1>How We Fight Overfitting</h1>
<p>Good training is not only fitting the data — it is controlling generalization.</p>
</div>

<div class="rl-fight-layout">
<div class="rl-technique-grid">
<div><strong>More data</strong><span>reduce noise</span></div>
<div><strong>Validation set</strong><span>check new data</span></div>
<div><strong>Regularization</strong><span>limit complexity</span></div>
<div><strong>Dropout</strong><span>avoid reliance</span></div>
<div><strong>Early stopping</strong><span>stop in time</span></div>
<div><strong>Data augmentation</strong><span>create variations</span></div>
</div>

<div class="rl-balance-card">
<div class="rl-balance-row">
<div><strong>Model capacity</strong><span>flexibility</span></div>
<i></i>
<div><strong>Data + validation</strong><span>control</span></div>
</div>
<div class="rl-augment-note">
<strong>Image augmentation</strong>
<span>crop · rotate · flip</span>
</div>
</div>
</div>

<div class="concept-takeaway">Generalization improves when model complexity is controlled.</div>
</section>

---
class: dlx-takeoff-slide
---

<section class="slide-shell dlx-slide dlx-takeoff">
<div class="dlx-header">
<h1>Why Deep Learning Took Off</h1>
<p>The ideas were old, but the ecosystem finally became ready.</p>
</div>

<div class="dlx-main dlx-takeoff-stage">
<div class="dlx-factor-grid">
<article class="dlx-factor-card"><span>Data</span><strong>Big Data</strong><p>large datasets became available</p></article>
<article class="dlx-factor-card"><span>Compute</span><strong>GPUs</strong><p>parallel computation made training feasible</p></article>
<article class="dlx-factor-card"><span>Models</span><strong>Architectures</strong><p>CNNs, deeper networks, better designs</p></article>
<article class="dlx-factor-card"><span>Training</span><strong>Optimization</strong><p>initialization, activations, better learning</p></article>
</div>

<div class="dlx-equals-mark">=</div>

<div class="dlx-revolution-panel">
<span>2010s</span>
<strong>Deep Learning Revolution</strong>
<p>Data, compute, and methods aligned.</p>
</div>
</div>

<div class="dlx-takeaway">Deep learning did not win because of one idea. It won because the whole ecosystem aligned.</div>
</section>

---
class: dlx-imagenet-slide
---

<section class="slide-shell dlx-slide dlx-imagenet">
<div class="dlx-header">
<h1>The ImageNet Moment</h1>
<p>2012 showed that deep networks could transform computer vision.</p>
</div>

<div class="dlx-main dlx-imagenet-stage">
<div class="dlx-imagewall-card">
<div class="dlx-imagewall" aria-label="Real natural image examples used to evoke ImageNet-style classes">
<figure><img :src="'/images/imagenet-cat.jpg'" alt="Tabby cat"><figcaption>tabby cat</figcaption></figure>
<figure><img :src="'/images/imagenet-dog.jpg'" alt="Golden retriever"><figcaption>golden retriever</figcaption></figure>
<figure><img :src="'/images/imagenet-duck.jpg'" alt="Mallard duck"><figcaption>mallard</figcaption></figure>
<figure><img :src="'/images/imagenet-sunflower.jpg'" alt="Sunflower"><figcaption>sunflower</figcaption></figure>
<figure><img :src="'/images/imagenet-car.jpg'" alt="Car"><figcaption>car</figcaption></figure>
<figure><img :src="'/images/imagenet-airplane.jpg'" alt="Aircraft"><figcaption>aircraft</figcaption></figure>
</div>
<div class="dlx-caption-row">
<span>ImageNet benchmark</span>
<span>real natural image categories</span>
</div>
</div>

<div class="dlx-turning-card">
<span class="dlx-year">2012</span>
<h2>AlexNet</h2>
<p>A deep CNN trained with GPUs dramatically improved large-scale image classification.</p>
<div class="dlx-mini-flow"><b>Images</b><i></i><b>Deep CNN</b><i></i><b>Classes</b></div>
</div>
</div>

<div class="dlx-takeaway">Computer vision became the first major proof that deep learning could scale.</div>
</section>

---
class: dlx-feature-slide
---

<section class="slide-shell dlx-slide dlx-feature">
<div class="dlx-header">
<h1>From Hand-Crafted Features to Learned Features</h1>
<p>Before deep learning, humans designed features. CNNs learned them.</p>
</div>

<div class="dlx-main dlx-feature-stage">
<article class="dlx-compare-card dlx-traditional">
<span>Traditional vision</span>
<h2>Design features</h2>
<div class="dlx-pipeline">
<b>image</b><i></i><b>edges<br/>corners<br/>SIFT / HOG</b><i></i><b>classifier</b>
</div>
</article>

<article class="dlx-compare-card dlx-learned">
<span>Deep learning</span>
<h2>Learn representations</h2>
<div class="dlx-hierarchy">
<b>pixels</b><i></i><b>edges</b><i></i><b>textures</b><i></i><b>parts</b><i></i><b>object</b>
</div>
</article>
</div>

<div class="dlx-takeaway">The key shift was from designing features to learning representations.</div>
</section>

---
class: dlx-mlp-slide
---

<section class="slide-shell dlx-slide dlx-mlp">
<div class="dlx-header">
<h1>Why Images Are Hard for MLPs</h1>
<p>Images are not just lists of numbers. They have spatial structure.</p>
</div>

<div class="dlx-main dlx-mlp-stage">
<div class="dlx-flatten-card dlx-photo-flatten-card">
<figure class="dlx-real-image-card">
<div><img :src="'/images/imagenet-cat.jpg'" alt="Real cat image used as an image-classification example"><span></span></div>
<figcaption><strong>2D image</strong><small>nearby pixels carry meaning</small></figcaption>
</figure>
<div class="dlx-flow-arrow"></div>
<div class="dlx-vector-card">
<strong>flatten</strong>
<div class="dlx-vector-visual" aria-hidden="true"><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i></div>
<small>150,528 values</small>
</div>
<div class="dlx-flow-arrow"></div>
<div class="dlx-dense-card">
<strong>dense layer</strong>
<svg viewBox="0 0 180 128" role="img" aria-label="Fully connected layer with many connections">
<path d="M42 26 L92 20 M42 26 L92 48 M42 26 L92 78 M42 26 L92 108 M42 64 L92 20 M42 64 L92 48 M42 64 L92 78 M42 64 L92 108 M42 102 L92 20 M42 102 L92 48 M42 102 L92 78 M42 102 L92 108 M92 20 L142 40 M92 48 L142 40 M92 78 L142 88 M92 108 L142 88" />
<circle cx="42" cy="26" r="9"/><circle cx="42" cy="64" r="9"/><circle cx="42" cy="102" r="9"/>
<circle cx="92" cy="20" r="9"/><circle cx="92" cy="48" r="9"/><circle cx="92" cy="78" r="9"/><circle cx="92" cy="108" r="9"/>
<circle cx="142" cy="40" r="10"/><circle cx="142" cy="88" r="10"/>
</svg>
<small>about 150M weights for 1,000 neurons</small>
</div>
</div>

<div class="dlx-mlp-notes">
<article><strong>Flattening</strong><p>nearby pixels become distant vector entries</p></article>
<article><strong>Dense layers</strong><p>ignore local pixel neighborhoods</p></article>
<article><strong>Scale</strong><p>224 x 224 x 3 = 150,528 inputs</p></article>
<article><strong>Cost</strong><p>1,000 neurons means about 150M weights</p></article>
</div>
</div>

<div class="dlx-takeaway">MLPs can process images, but they scale poorly and do not exploit spatial locality.</div>
</section>

---
class: dlx-cnn-needed-slide
---

<section class="slide-shell dlx-slide dlx-cnn-needed">
<div class="dlx-header">
<h1>Why CNNs Were Needed</h1>
<p>CNNs exploit the structure of images.</p>
</div>

<div class="dlx-main dlx-cnn-stage">
<div class="dlx-conv-board">
<div class="dlx-scan-image" aria-hidden="true">
<i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><span></span>
</div>
<div class="dlx-flow-arrow"></div>
<div class="dlx-filter-box"><strong>shared filter</strong><p>same weights scan every position</p></div>
<div class="dlx-flow-arrow"></div>
<div class="dlx-map-box" aria-hidden="true"><i></i><i></i><i></i></div>
</div>

<div class="dlx-cnn-principles">
<article><strong>Locality</strong><p>nearby pixels matter together</p></article>
<article><strong>Weight sharing</strong><p>one filter works across positions</p></article>
<article><strong>Feature maps</strong><p>patterns are detected wherever they appear</p></article>
</div>
</div>

<div class="dlx-takeaway">CNNs are designed for images: local patterns, shared filters, scalable learning.</div>
</section>

---
class: dlx-history-slide
---

<section class="slide-shell dlx-slide dlx-history">
<div class="dlx-header">
<h1>Historical Roots of CNNs</h1>
<p>From biologically inspired vision models to practical image recognition.</p>
</div>

<div class="dlx-main dlx-history-stage">
<div class="dlx-timeline-card">
<article><span>1980</span><strong>Kunihiko Fukushima</strong><p>Neocognitron: a hierarchical vision model inspired by visual cortex.</p></article>
<article><span>1989-1998</span><strong>Yann LeCun and collaborators</strong><p>LeNet: CNNs trained for handwritten digit and document recognition.</p></article>
<article><span>2012</span><strong>AlexNet</strong><p>CNNs scale with GPUs and large visual datasets.</p></article>
</div>

<figure class="dlx-person-card">
<img :src="'/images/yann-lecun-photo.jpg'" alt="Yann LeCun in 2024">
<figcaption><strong>Yann LeCun</strong><span>LeNet and practical CNNs for recognition</span><small>2018 ACM Turing Award recipient</small></figcaption>
</figure>
</div>

<div class="dlx-takeaway">CNNs combined biological inspiration, efficient architecture, and scalable training.</div>
</section>

---
class: dlx-transition-slide
---

<section class="slide-shell dlx-slide dlx-transition">
<div class="dlx-header">
<h1>Next: Convolutional Neural Networks</h1>
<p>How filters learn to see edges, textures, parts, and objects.</p>
</div>

<div class="dlx-main dlx-next-stage">
<div class="dlx-next-step dlx-next-image"><span>image</span></div>
<div class="dlx-flow-arrow"></div>
<div class="dlx-next-step dlx-next-filter"><span>filter</span><i></i></div>
<div class="dlx-flow-arrow"></div>
<div class="dlx-next-step dlx-next-maps"><span>feature maps</span><b></b><b></b><b></b></div>
<div class="dlx-flow-arrow"></div>
<div class="dlx-next-step dlx-next-predict"><span>prediction</span><strong>visual hierarchy</strong></div>
</div>

<div class="dlx-takeaway">Next, we open the CNN black box: filters, feature maps, pooling, and visual hierarchies.</div>
</section>

---
class: cnn-transform-slide
---

<section class="slide-shell cnn-transform">
<div class="cnn-transform-header">
<span>CONVOLUTIONAL NEURAL NETWORKS</span>
<h1>How a CNN Transforms an Image</h1>
<p>Layer by layer, the image becomes a hierarchy of visual evidence: edges, textures, parts, and finally a class score.</p>
</div>

<div class="cnn-transform-stage" aria-label="CNN transformation from image to prediction">
<div class="cnn-flow-ribbon">
<strong>Image evolution</strong>
<span>pixels</span><i></i><span>edges</span><i></i><span>textures</span><i></i><span>parts</span><i></i><span>prediction</span>
</div>

<div class="cnn-transform-flow">
<div class="cnn-input-panel">
<div class="cnn-input-image">
<img :src="'/images/imagenet-cat.jpg'" alt="Real cat image entering a convolutional neural network">
<span class="cnn-kernel-window"></span>
</div>
<strong>Input image</strong>
<small>real pixels arranged in space</small>
</div>

<div class="cnn-stage-arrow"></div>

<div class="cnn-map-stack first">
<span>1st convolution</span>
<div class="cnn-stack-sheets"><i></i><i></i><i></i><i></i><i></i></div>
<small>local filters find edges</small>
</div>

<div class="cnn-pooling-wedge">
<strong>Pooling</strong>
<small>shrinks maps</small>
</div>

<div class="cnn-map-stack second">
<span>2nd convolution</span>
<div class="cnn-stack-sheets"><i></i><i></i><i></i><i></i></div>
<small>combines edges into parts</small>
</div>

<div class="cnn-pooling-wedge compact">
<strong>Pooling</strong>
<small>keeps strong signals</small>
</div>

<div class="cnn-flatten-panel">
<span>Flatten</span>
<div class="cnn-bars"><i></i><i></i><i></i><i></i><i></i><i></i><i></i></div>
<small>maps become a vector</small>
</div>

<div class="cnn-classifier-panel">
<span>Fully<br>connected</span>
<svg viewBox="0 0 220 190" role="img" aria-label="Fully connected classifier">
<path d="M22 24 C74 24 84 28 118 34 S172 36 198 24 M22 50 C76 54 88 80 120 92 S168 116 198 58 M22 76 C74 96 92 134 121 142 S168 150 198 91 M22 102 C70 134 95 36 122 48 S166 45 198 123 M22 128 C70 154 91 82 124 94 S168 98 198 154 M22 154 C74 152 88 158 122 164 S170 165 198 170" />
<g class="cnn-fc-input"><circle cx="22" cy="24" r="6"/><circle cx="22" cy="50" r="6"/><circle cx="22" cy="76" r="6"/><circle cx="22" cy="102" r="6"/><circle cx="22" cy="128" r="6"/><circle cx="22" cy="154" r="6"/></g>
<g class="cnn-fc-hidden"><circle cx="116" cy="34" r="7"/><circle cx="116" cy="72" r="7"/><circle cx="116" cy="110" r="7"/><circle cx="116" cy="148" r="7"/></g>
<g class="cnn-fc-output"><circle cx="198" cy="24" r="5"/><circle cx="198" cy="47" r="5"/><circle cx="198" cy="70" r="5"/><circle cx="198" cy="93" r="5"/><circle cx="198" cy="116" r="5"/><circle cx="198" cy="139" r="5"/><circle cx="198" cy="162" r="5"/></g>
</svg>
<small>scores classes</small>
</div>

<div class="cnn-output-card">
<span>Output</span>
<strong>cat</strong>
<small>highest score</small>
</div>
</div>
</div>

<div class="cnn-transform-takeaway">A CNN learns a visual hierarchy: pixels → edges → textures → parts → prediction.</div>
</section>

---
class: cnn-explainer-slide
---

<section class="slide-shell cnn-explainer-demo">
<div class="cnn-explainer-header">
<span>INTERACTIVE VISUALIZATION</span>
<h1>CNN Explainer</h1>
<p>A browser-based simulator for inspecting feature maps, pooling, activations, and class scores generated inside a CNN.</p>
</div>

<figure class="cnn-explainer-frame">
<img :src="'/images/cnn-explainer-interface.png'" alt="CNN Explainer interface showing convolution, ReLU, pooling, and output activations through a convolutional neural network">
</figure>
</section>

---
class: cnn-convolution-core-slide
---

<section class="slide-shell cnn-topic-slide cnn-convolution-core">
<div class="cnn-topic-header">
<span>CONVOLUTIONAL NEURAL NETWORKS</span>
<h1>Convolution: The Core Idea</h1>
<p>A learned filter looks at one local patch, then scans the whole image to build a feature map.</p>
</div>

<div class="cnn-conv-main">
<div class="cnn-conv-flow">
<figure class="cnn-conv-photo">
<img :src="'/images/cnn-convolution-zebra-stripes.jpg'" alt="Close-up zebra stripe image used to illustrate convolution">
<span class="cnn-conv-window"></span>
<figcaption><strong>Input image</strong><small>spatial pixels</small></figcaption>
</figure>

<figure class="cnn-conv-patch">
<img :src="'/images/cnn-convolution-zebra-patch.jpg'" alt="Exact square crop from the highlighted local image patch">
<figcaption><strong>Local patch</strong><small>small receptive field</small></figcaption>
</figure>

<div class="cnn-conv-arrow" aria-hidden="true"></div>

<div class="cnn-conv-kernel">
<strong>3x3 filter</strong>
<div class="cnn-conv-kernel-values" aria-hidden="true">
<i>-1</i><i>0</i><i>1</i>
<i>-1</i><i>0</i><i>1</i>
<i>-1</i><i>0</i><i>1</i>
</div>
<small>edge detector weights</small>
</div>

<div class="cnn-conv-arrow" aria-hidden="true"></div>

<div class="cnn-conv-map">
<strong>Feature map</strong>
<svg class="cnn-conv-map-visual" viewBox="0 0 480 300" role="img" aria-label="Image-derived edge activation map">
<defs>
<filter id="cnn-slide32-edge-map" color-interpolation-filters="sRGB">
<feColorMatrix type="saturate" values="0"/>
<feConvolveMatrix order="3" kernelMatrix="-1 0 1 -2 0 2 -1 0 1" divisor="1" bias="0.5"/>
<feComponentTransfer>
<feFuncR type="linear" slope="1.85" intercept="-0.34"/>
<feFuncG type="linear" slope="1.85" intercept="-0.34"/>
<feFuncB type="linear" slope="1.85" intercept="-0.34"/>
</feComponentTransfer>
</filter>
<linearGradient id="cnn-slide32-map-tint" x1="0" y1="0" x2="1" y2="1">
<stop offset="0" stop-color="#1d4ed8"/>
<stop offset="0.52" stop-color="#06b6d4"/>
<stop offset="1" stop-color="#7c3aed"/>
</linearGradient>
</defs>
<rect width="480" height="300" rx="12" fill="#f8fbff"/>
<image :href="'/images/cnn-convolution-zebra-stripes.jpg'" x="0" y="0" width="480" height="300" preserveAspectRatio="xMidYMid slice" filter="url(#cnn-slide32-edge-map)"/>
<rect width="480" height="300" rx="12" fill="url(#cnn-slide32-map-tint)" opacity="0.36"/>
<g opacity="0.28">
<path d="M54 48 C138 96 176 34 258 82 S384 152 430 86" fill="none" stroke="#ffffff" stroke-width="5" stroke-linecap="round"/>
<path d="M42 205 C132 150 206 230 282 182 S372 118 432 158" fill="none" stroke="#ffffff" stroke-width="4" stroke-linecap="round"/>
</g>
</svg>
<small>strong response where the pattern appears</small>
</div>
</div>

<div class="cnn-conv-notes">
<article><b>Local region</b><span>the filter sees only nearby pixels at each step</span></article>
<article><b>Shared weights</b><span>the same detector is reused across the image</span></article>
<article><b>Feature map</b><span>the output records where visual evidence is found</span></article>
</div>
</div>

<div class="cnn-topic-takeaway">Convolution detects local patterns wherever they appear.</div>
</section>

---
class: cnn-filters-slide
---

<section class="slide-shell cnn-topic-slide cnn-filters">
<div class="cnn-topic-header">
<span>LEARNED DETECTORS</span>
<h1>Filters Learn Visual Patterns</h1>
<p>During training, different filters specialize in visual evidence that helps prediction.</p>
</div>

<div class="cnn-filter-demo-main">
<figure class="cnn-filter-input-card">
<img :src="'/images/cnn-filters-facade.jpg'" alt="Building facade with repeating geometric windows used to show learned visual filters">
<figcaption>
<strong>Input image</strong>
<span>edges, corners, repeated geometry, local contrast</span>
</figcaption>
</figure>

<div class="cnn-filter-response-grid">
<article class="cnn-filter-response-card">
<svg viewBox="0 0 360 180" role="img" aria-label="Vertical edge response map">
<defs>
<filter id="filter33-vertical" color-interpolation-filters="sRGB">
<feColorMatrix type="saturate" values="0"/>
<feConvolveMatrix order="3" kernelMatrix="-1 0 1 -2 0 2 -1 0 1" divisor="1" bias="0.5"/>
<feComponentTransfer>
<feFuncR type="linear" slope="1.75" intercept="-0.32"/>
<feFuncG type="linear" slope="1.75" intercept="-0.32"/>
<feFuncB type="linear" slope="1.75" intercept="-0.32"/>
</feComponentTransfer>
</filter>
<linearGradient id="filter33-blue-cyan" x1="0" y1="0" x2="1" y2="1">
<stop offset="0" stop-color="#1d4ed8"/>
<stop offset="1" stop-color="#06b6d4"/>
</linearGradient>
</defs>
<rect width="360" height="180" rx="12" fill="#f8fbff"/>
<image :href="'/images/cnn-filters-facade.jpg'" x="0" y="0" width="360" height="180" preserveAspectRatio="xMidYMid slice" filter="url(#filter33-vertical)"/>
<rect width="360" height="180" rx="12" fill="url(#filter33-blue-cyan)" opacity="0.34"/>
</svg>
<div><strong>Vertical edges</strong><span>window bars and facade lines</span></div>
</article>

<article class="cnn-filter-response-card">
<svg viewBox="0 0 360 180" role="img" aria-label="Horizontal edge response map">
<defs>
<filter id="filter33-horizontal" color-interpolation-filters="sRGB">
<feColorMatrix type="saturate" values="0"/>
<feConvolveMatrix order="3" kernelMatrix="-1 -2 -1 0 0 0 1 2 1" divisor="1" bias="0.5"/>
<feComponentTransfer>
<feFuncR type="linear" slope="1.8" intercept="-0.34"/>
<feFuncG type="linear" slope="1.8" intercept="-0.34"/>
<feFuncB type="linear" slope="1.8" intercept="-0.34"/>
</feComponentTransfer>
</filter>
<linearGradient id="filter33-cyan-purple" x1="0" y1="0" x2="1" y2="1">
<stop offset="0" stop-color="#06b6d4"/>
<stop offset="1" stop-color="#7c3aed"/>
</linearGradient>
</defs>
<rect width="360" height="180" rx="12" fill="#f8fbff"/>
<image :href="'/images/cnn-filters-facade.jpg'" x="0" y="0" width="360" height="180" preserveAspectRatio="xMidYMid slice" filter="url(#filter33-horizontal)"/>
<rect width="360" height="180" rx="12" fill="url(#filter33-cyan-purple)" opacity="0.34"/>
</svg>
<div><strong>Horizontal edges</strong><span>floors, ledges, contrast bands</span></div>
</article>

<article class="cnn-filter-response-card">
<svg viewBox="0 0 360 180" role="img" aria-label="Corner and junction response map">
<defs>
<filter id="filter33-corners" color-interpolation-filters="sRGB">
<feColorMatrix type="saturate" values="0"/>
<feConvolveMatrix order="3" kernelMatrix="-1 2 -1 2 -4 2 -1 2 -1" divisor="1" bias="0.55"/>
<feComponentTransfer>
<feFuncR type="linear" slope="1.9" intercept="-0.38"/>
<feFuncG type="linear" slope="1.9" intercept="-0.38"/>
<feFuncB type="linear" slope="1.9" intercept="-0.38"/>
</feComponentTransfer>
</filter>
<linearGradient id="filter33-purple-blue" x1="0" y1="0" x2="1" y2="1">
<stop offset="0" stop-color="#7c3aed"/>
<stop offset="1" stop-color="#1d4ed8"/>
</linearGradient>
</defs>
<rect width="360" height="180" rx="12" fill="#f8fbff"/>
<image :href="'/images/cnn-filters-facade.jpg'" x="0" y="0" width="360" height="180" preserveAspectRatio="xMidYMid slice" filter="url(#filter33-corners)"/>
<rect width="360" height="180" rx="12" fill="url(#filter33-purple-blue)" opacity="0.34"/>
<g fill="#ffffff" opacity="0.72">
<circle cx="74" cy="58" r="4"/>
<circle cx="138" cy="72" r="4"/>
<circle cx="204" cy="55" r="4"/>
<circle cx="285" cy="92" r="4"/>
</g>
</svg>
<div><strong>Corners</strong><span>junctions between local edges</span></div>
</article>

<article class="cnn-filter-response-card">
<svg viewBox="0 0 360 180" role="img" aria-label="Texture and repeated pattern response map">
<defs>
<filter id="filter33-texture" color-interpolation-filters="sRGB">
<feColorMatrix type="saturate" values="0.25"/>
<feConvolveMatrix order="3" kernelMatrix="0 -1 0 -1 5 -1 0 -1 0" divisor="1"/>
<feComponentTransfer>
<feFuncR type="linear" slope="1.45" intercept="-0.10"/>
<feFuncG type="linear" slope="1.45" intercept="-0.10"/>
<feFuncB type="linear" slope="1.45" intercept="-0.10"/>
</feComponentTransfer>
</filter>
<linearGradient id="filter33-texture-grad" x1="0" y1="0" x2="1" y2="1">
<stop offset="0" stop-color="#1d4ed8"/>
<stop offset="0.52" stop-color="#06b6d4"/>
<stop offset="1" stop-color="#7c3aed"/>
</linearGradient>
</defs>
<rect width="360" height="180" rx="12" fill="#f8fbff"/>
<image :href="'/images/cnn-filters-facade.jpg'" x="0" y="0" width="360" height="180" preserveAspectRatio="xMidYMid slice" filter="url(#filter33-texture)"/>
<rect width="360" height="180" rx="12" fill="url(#filter33-texture-grad)" opacity="0.24"/>
</svg>
<div><strong>Textures</strong><span>repeated geometric structure</span></div>
</article>
</div>
</div>

<div class="cnn-topic-takeaway">Filters are not manually designed: the network learns useful detectors.</div>
</section>

---
class: cnn-pooling-slide
---

<section class="slide-shell cnn-topic-slide cnn-pooling">
<div class="cnn-topic-header">
<span>SPATIAL COMPRESSION</span>
<h1>Pooling: Keeping What Matters</h1>
<p>Pooling compresses a feature map by keeping the strongest local activations.</p>
</div>

<div class="cnn-pool-demo-main">
<figure class="cnn-pool-photo-card">
<img :src="'/images/cnn-filters-facade.jpg'" alt="Real building facade used to illustrate pooling on visual activations">
<figcaption><strong>Input image</strong><span>real visual structure</span></figcaption>
</figure>

<div class="cnn-pool-feature-card">
<strong>Feature map</strong>
<svg viewBox="0 0 420 220" role="img" aria-label="Feature map before pooling with pooling windows">
<defs>
<filter id="pool34-feature-filter" color-interpolation-filters="sRGB">
<feColorMatrix type="saturate" values="0"/>
<feConvolveMatrix order="3" kernelMatrix="-1 0 1 -2 0 2 -1 0 1" divisor="1" bias="0.5"/>
<feComponentTransfer>
<feFuncR type="linear" slope="1.8" intercept="-0.34"/>
<feFuncG type="linear" slope="1.8" intercept="-0.34"/>
<feFuncB type="linear" slope="1.8" intercept="-0.34"/>
</feComponentTransfer>
</filter>
<linearGradient id="pool34-feature-tint" x1="0" y1="0" x2="1" y2="1">
<stop offset="0" stop-color="#1d4ed8"/>
<stop offset="0.55" stop-color="#06b6d4"/>
<stop offset="1" stop-color="#7c3aed"/>
</linearGradient>
</defs>
<rect width="420" height="220" rx="12" fill="#f8fbff"/>
<image :href="'/images/cnn-filters-facade.jpg'" x="0" y="0" width="420" height="220" preserveAspectRatio="xMidYMid slice" filter="url(#pool34-feature-filter)"/>
<rect width="420" height="220" rx="12" fill="url(#pool34-feature-tint)" opacity="0.32"/>
<g class="pool-window-marks">
<rect x="54" y="34" width="74" height="58" rx="8"/>
<rect x="244" y="78" width="74" height="58" rx="8"/>
<rect x="134" y="132" width="74" height="58" rx="8"/>
</g>
</svg>
<small>many neighboring activations</small>
</div>

<div class="cnn-pool-operation-card">
<span>2x2 max pooling</span>
<div class="cnn-pool-mini-example" aria-hidden="true">
<i>0.2</i><i>0.7</i>
<i>0.4</i><i>0.9</i>
</div>
<b>max = 0.9</b>
</div>

<div class="cnn-pool-output-card">
<strong>Smaller map</strong>
<svg viewBox="0 0 320 220" role="img" aria-label="Downsampled pooled feature map">
<defs>
<linearGradient id="pool34-block-1" x1="0" y1="0" x2="1" y2="1">
<stop offset="0" stop-color="#1d4ed8"/>
<stop offset="1" stop-color="#06b6d4"/>
</linearGradient>
<linearGradient id="pool34-block-2" x1="0" y1="0" x2="1" y2="1">
<stop offset="0" stop-color="#06b6d4"/>
<stop offset="1" stop-color="#7c3aed"/>
</linearGradient>
</defs>
<rect width="320" height="220" rx="12" fill="#f8fbff"/>
<g opacity="0.96">
<rect x="24" y="24" width="62" height="52" rx="8" fill="url(#pool34-block-1)" opacity="0.58"/>
<rect x="94" y="24" width="62" height="52" rx="8" fill="url(#pool34-block-2)" opacity="0.86"/>
<rect x="164" y="24" width="62" height="52" rx="8" fill="url(#pool34-block-1)" opacity="0.50"/>
<rect x="234" y="24" width="62" height="52" rx="8" fill="url(#pool34-block-2)" opacity="0.76"/>
<rect x="24" y="84" width="62" height="52" rx="8" fill="url(#pool34-block-2)" opacity="0.65"/>
<rect x="94" y="84" width="62" height="52" rx="8" fill="url(#pool34-block-1)" opacity="0.92"/>
<rect x="164" y="84" width="62" height="52" rx="8" fill="url(#pool34-block-2)" opacity="0.82"/>
<rect x="234" y="84" width="62" height="52" rx="8" fill="url(#pool34-block-1)" opacity="0.48"/>
<rect x="24" y="144" width="62" height="52" rx="8" fill="url(#pool34-block-1)" opacity="0.45"/>
<rect x="94" y="144" width="62" height="52" rx="8" fill="url(#pool34-block-2)" opacity="0.70"/>
<rect x="164" y="144" width="62" height="52" rx="8" fill="url(#pool34-block-1)" opacity="0.80"/>
<rect x="234" y="144" width="62" height="52" rx="8" fill="url(#pool34-block-2)" opacity="0.58"/>
</g>
</svg>
<small>lower resolution, strongest evidence kept</small>
</div>
</div>

<div class="cnn-pool-principles">
<article><b>Less computation</b><span>fewer spatial values move forward</span></article>
<article><b>Strong evidence survives</b><span>max pooling keeps the strongest response</span></article>
<article><b>More stable features</b><span>small shifts change less downstream</span></article>
</div>

<div class="cnn-topic-takeaway">Pooling compresses information while preserving strong evidence.</div>
</section>

---
class: cnn-visual-hierarchy-slide
---

<section class="slide-shell cnn-topic-slide cnn-visual-hierarchy">
<div class="cnn-topic-header">
<span>FEATURE HIERARCHY</span>
<h1>Visual Hierarchies in CNNs</h1>
<p>Early layers detect simple signals; deeper layers combine them into object-level evidence.</p>
</div>

<div class="cnn-hierarchy-demo-main">
<figure class="cnn-hierarchy-input-card">
<img :src="'/images/imagenet-dog.jpg'" alt="Golden retriever image used to explain visual feature hierarchy">
<figcaption><strong>Input image</strong><span>pixels arranged in space</span></figcaption>
</figure>

<div class="cnn-hierarchy-stage-grid">
<article class="cnn-hierarchy-stage-card">
<svg viewBox="0 0 340 170" role="img" aria-label="Early CNN edge response">
<defs>
<filter id="hier35-edges" color-interpolation-filters="sRGB">
<feColorMatrix type="saturate" values="0"/>
<feConvolveMatrix order="3" kernelMatrix="-1 0 1 -2 0 2 -1 0 1" divisor="1" bias="0.5"/>
<feComponentTransfer>
<feFuncR type="linear" slope="1.75" intercept="-0.32"/>
<feFuncG type="linear" slope="1.75" intercept="-0.32"/>
<feFuncB type="linear" slope="1.75" intercept="-0.32"/>
</feComponentTransfer>
</filter>
<linearGradient id="hier35-edge-tint" x1="0" y1="0" x2="1" y2="1">
<stop offset="0" stop-color="#1d4ed8"/>
<stop offset="1" stop-color="#06b6d4"/>
</linearGradient>
</defs>
<rect width="340" height="170" rx="12" fill="#f8fbff"/>
<image :href="'/images/imagenet-dog.jpg'" x="0" y="0" width="340" height="170" preserveAspectRatio="xMidYMid slice" filter="url(#hier35-edges)"/>
<rect width="340" height="170" rx="12" fill="url(#hier35-edge-tint)" opacity="0.34"/>
</svg>
<div><strong>Edges</strong><span>contours, contrast, orientation</span></div>
</article>

<article class="cnn-hierarchy-stage-card">
<svg viewBox="0 0 340 170" role="img" aria-label="Middle CNN texture response">
<defs>
<filter id="hier35-textures" color-interpolation-filters="sRGB">
<feColorMatrix type="saturate" values="0.45"/>
<feConvolveMatrix order="3" kernelMatrix="0 -1 0 -1 5 -1 0 -1 0" divisor="1"/>
<feComponentTransfer>
<feFuncR type="linear" slope="1.45" intercept="-0.10"/>
<feFuncG type="linear" slope="1.45" intercept="-0.10"/>
<feFuncB type="linear" slope="1.45" intercept="-0.10"/>
</feComponentTransfer>
</filter>
<linearGradient id="hier35-texture-tint" x1="0" y1="0" x2="1" y2="1">
<stop offset="0" stop-color="#06b6d4"/>
<stop offset="1" stop-color="#7c3aed"/>
</linearGradient>
</defs>
<rect width="340" height="170" rx="12" fill="#f8fbff"/>
<image :href="'/images/imagenet-dog.jpg'" x="0" y="0" width="340" height="170" preserveAspectRatio="xMidYMid slice" filter="url(#hier35-textures)"/>
<rect width="340" height="170" rx="12" fill="url(#hier35-texture-tint)" opacity="0.22"/>
</svg>
<div><strong>Textures</strong><span>fur, leaves, repeated local patterns</span></div>
</article>

<article class="cnn-hierarchy-stage-card">
<svg viewBox="0 0 340 170" role="img" aria-label="Deep CNN part response">
<defs>
<linearGradient id="hier35-part-glow" x1="0" y1="0" x2="1" y2="1">
<stop offset="0" stop-color="#1d4ed8"/>
<stop offset="0.5" stop-color="#06b6d4"/>
<stop offset="1" stop-color="#7c3aed"/>
</linearGradient>
</defs>
<rect width="340" height="170" rx="12" fill="#f8fbff"/>
<image :href="'/images/imagenet-dog.jpg'" x="0" y="0" width="340" height="170" preserveAspectRatio="xMidYMid slice" opacity="0.88"/>
<rect width="340" height="170" rx="12" fill="#0f172a" opacity="0.22"/>
<g fill="none" stroke="url(#hier35-part-glow)" stroke-width="5">
<rect x="74" y="27" width="70" height="58" rx="12"/>
<rect x="135" y="70" width="115" height="52" rx="16"/>
<rect x="92" y="107" width="48" height="42" rx="12"/>
</g>
<g fill="#ffffff" opacity="0.92">
<circle cx="143" cy="58" r="4"/>
<circle cx="250" cy="94" r="4"/>
<circle cx="140" cy="128" r="4"/>
</g>
</svg>
<div><strong>Parts</strong><span>head, body, legs, local object structure</span></div>
</article>

<article class="cnn-hierarchy-stage-card object">
<div class="cnn-hierarchy-object-panel">
<span>prediction</span>
<strong>dog</strong>
<div class="cnn-score-bars" aria-hidden="true">
<i style="--score: 92%"></i>
<i style="--score: 42%"></i>
<i style="--score: 18%"></i>
</div>
</div>
<div><strong>Object</strong><span>semantic concept assembled by deep layers</span></div>
</article>
</div>
</div>

<div class="cnn-topic-takeaway">CNNs learn visual hierarchies from simple patterns to semantic concepts.</div>
</section>

---
class: cnn-real-world-slide
---

<section class="slide-shell cnn-topic-slide cnn-real-world">
<div class="cnn-topic-header">
<span>APPLICATIONS</span>
<h1>CNNs in the Real World</h1>
<p>The same visual machinery scales from images and sensors to high-stakes decision support.</p>
</div>

<div class="cnn-real-app-grid">
<article class="medical">
<img :src="'/images/cnn-medical-xray.jpg'" alt="Chest X-ray used as an example of medical imaging">
<div><span>medical imaging</span><strong>X-rays and scans</strong><p>detect subtle structures for clinical decision support</p></div>
</article>
<article class="driving">
<img :src="'/images/cnn-autonomous-car.jpg'" alt="Autonomous vehicle used as an example of vision perception">
<div><span>autonomous driving</span><strong>road perception</strong><p>recognize lanes, signs, vehicles, and pedestrians</p></div>
</article>
<article class="industrial">
<img :src="'/images/cnn-industrial-quality-control.png'" alt="Quality-control inspection station for printed circuit board assembly">
<div><span>industrial inspection</span><strong>quality control</strong><p>find defects in manufactured parts and electronics</p></div>
</article>
<article class="remote">
<img :src="'/images/cnn-satellite-imagery.jpg'" alt="Aerial city image used as an example of satellite and remote sensing">
<div><span>remote sensing</span><strong>Earth observation</strong><p>map roads, buildings, land use, and damage</p></div>
</article>
</div>

<div class="cnn-topic-takeaway">CNNs became the visual engine of modern AI systems.</div>
</section>

---
class: cnn-evolution-slide
---

<section class="slide-shell cnn-evolution">
<div class="cnn-evolution-header">
<span>COMPUTER VISION</span>
<h1>The Evolution of CNNs</h1>
<p>From LeNet to modern deep vision architectures.</p>
</div>

<div class="cnn-evolution-map" aria-label="Historical evolution of convolutional neural networks">
<article class="cnn-evolution-card lenet">
<div class="cnn-evolution-card-head">
<span>1998</span>
<h2>LeNet-5</h2>
<small>Yann LeCun</small>
</div>
<figure class="cnn-evolution-visual wide">
<img :src="'/images/cnn-history-lenet.svg'" alt="LeNet-5 architecture diagram">
</figure>
<div class="cnn-evolution-note">
<strong>Practical CNNs</strong>
<p>Convolution + pooling for digit recognition.</p>
</div>
</article>

<article class="cnn-evolution-card alexnet">
<div class="cnn-evolution-card-head">
<span>2012</span>
<h2>AlexNet</h2>
<small>Krizhevsky · Sutskever · Hinton</small>
</div>
<figure class="cnn-evolution-visual tall">
<img :src="'/images/cnn-history-alexnet-commons.svg'" alt="AlexNet architecture block diagram">
</figure>
<div class="cnn-evolution-note">
<strong>ImageNet breakthrough</strong>
<p>Deep CNNs + GPUs made large-scale vision practical.</p>
</div>
</article>

<article class="cnn-evolution-card vgg">
<div class="cnn-evolution-card-head">
<span>2014</span>
<h2>VGG</h2>
<small>Simonyan · Zisserman</small>
</div>
<figure class="cnn-evolution-visual tall">
<img :src="'/images/cnn-history-vgg-commons.svg'" alt="VGG architecture comparison diagram">
</figure>
<div class="cnn-evolution-note">
<strong>Simple depth</strong>
<p>Repeated small 3x3 convolutions scale cleanly.</p>
</div>
</article>

<article class="cnn-evolution-card inception">
<div class="cnn-evolution-card-head">
<span>2014</span>
<h2>GoogLeNet</h2>
<small>Inception modules</small>
</div>
<figure class="cnn-evolution-visual wide">
<img :src="'/images/cnn-history-inception.svg'" alt="Inception module diagram">
</figure>
<div class="cnn-evolution-note">
<strong>Multi-scale features</strong>
<p>Parallel filters process several spatial scales efficiently.</p>
</div>
</article>

<article class="cnn-evolution-card resnet">
<div class="cnn-evolution-card-head">
<span>2015</span>
<h2>ResNet</h2>
<small>He et al.</small>
</div>
<figure class="cnn-evolution-visual wide">
<img :src="'/images/cnn-history-resnet.svg'" alt="ResNet residual block diagram">
</figure>
<div class="cnn-evolution-note">
<strong>Residual learning</strong>
<p>Skip connections make very deep networks trainable.</p>
</div>
</article>
</div>

<div class="cnn-evolution-insight">
<span>KEY LEGACY</span>
<strong>Not just deeper networks:</strong>
<p>CNNs made hierarchical features, parameter sharing, multi-scale design, and residual learning reusable ideas.</p>
</div>
</section>

---
class: nlp-sequence-intro-slide
---

<section class="slide-shell nlp-slide nlp-language-different nlp-language-redone">
<div class="nlp-header">
<span>SEQUENCE MODELS</span>
<h1>Why Language Is Different</h1>
<p>Images have spatial structure; language has order, context, ambiguity, and memory.</p>
</div>

<div class="nlp-redone-language-main">
<article class="nlp-redone-domain-card vision">
<div class="nlp-domain-topline">
<span>Images</span>
<strong>CNNs read space</strong>
</div>
<div class="nlp-redone-image-frame">
<img :src="'/images/cnn-convolution-zebra-stripes.jpg'" alt="Zebra stripes showing spatial visual patterns">
<div class="nlp-local-patch"></div>
</div>
<div class="nlp-redone-caption">
<b>Local neighborhoods</b>
<span>pixels near each other form reusable patterns</span>
</div>
</article>

<div class="nlp-redone-bridge">
<span>2D space</span>
<i></i>
<span>ordered time</span>
</div>

<article class="nlp-redone-domain-card language">
<div class="nlp-domain-topline">
<span>Language</span>
<strong>RNNs read sequences</strong>
</div>
<div class="nlp-redone-sequence-frame">
<img :src="'/images/nlp-sequence-model.svg'" alt="Sequence model diagram from Dive into Deep Learning">
</div>
<div class="nlp-redone-token-timeline">
<b>The</b><b>student</b><b>understands</b><b>the</b><b>concept</b>
</div>
<div class="nlp-redone-caption">
<b>Context over time</b>
<span>each word changes the meaning of what comes next</span>
</div>
</article>
</div>

<div class="nlp-takeaway">Language is not just data — it is ordered context.</div>
</section>

---
class: nlp-embedding-slide
---

<section class="slide-shell nlp-slide nlp-embeddings nlp-embeddings-redone">
<div class="nlp-header">
<span>LANGUAGE REPRESENTATION</span>
<h1>Tokens and Embeddings</h1>
<p>Words and subwords become numerical vectors that models can compare, combine, and learn from.</p>
</div>

<div class="nlp-embed-redone-main">
<div class="nlp-embed-process-card embed-left-perfect">
<div class="embed-left-header">
<span>Embedding pipeline</span>
<strong>Language becomes geometry</strong>
</div>

<div class="embed-flow-card sentence">
<div class="embed-flow-label">
<span>01</span>
<strong>Sentence</strong>
</div>
<p>The student understands neural networks.</p>
</div>

<div class="embed-flow-card tokens">
<div class="embed-flow-label">
<span>02</span>
<strong>Tokens</strong>
</div>
<div class="embed-token-chips">
<b>The</b><b>student</b><b>understands</b><b>neural</b><b>networks</b>
</div>
</div>

<div class="embed-flow-card vectors">
<div class="embed-flow-label">
<span>03</span>
<strong>Embedding vectors</strong>
</div>
<div class="embed-vector-stack">
<i>student</i><em>[0.61, 0.09, -0.31, ...]</em>
<i>neural</i><em>[0.58, 0.12, -0.28, ...]</em>
</div>
</div>

<div class="embed-context-visual">
<div>
<span>learned from context</span>
<strong>Nearby words shape the vector</strong>
</div>
<img :src="'/images/nlp-skip-gram.svg'" alt="Skip-gram word embedding diagram from Dive into Deep Learning">
</div>
</div>

<figure class="nlp-embedding-map-card">
<figcaption>
<span>Semantic space</span>
<strong>Similar words cluster together</strong>
</figcaption>
<div class="nlp-embedding-map-image">
<img :src="'/images/nlp-word-embeddings-colah.png'" alt="Two-dimensional visualization of word embedding clusters">
</div>
<p>Each point is a word vector; nearby regions tend to represent related meanings.</p>
</figure>
</div>

<div class="nlp-takeaway">Embeddings turn language into geometry.</div>
</section>

---
class: nlp-rnn-slide
---

<section class="slide-shell nlp-slide nlp-rnn nlp-rnn-redone">
<div class="nlp-header">
<span>RECURRENT MODELS</span>
<h1>Recurrent Neural Networks</h1>
<p>RNNs process sequences one step at a time while carrying a hidden state forward.</p>
</div>

<div class="rnn-redone-main">
<div class="rnn-redone-visual-card">
<div class="rnn-redone-card-head">
<span>Unrolled through time</span>
<strong>One recurrent cell is reused at every position.</strong>
</div>
<div class="rnn-redone-image-frame">
<img :src="'/images/nlp-colah-rnn-unrolled.png'" alt="Unrolled recurrent neural network through time from colah's LSTM explanation">
</div>
<div class="rnn-token-strip">
<b>x₀</b><span>The</span>
<b>x₁</b><span>model</span>
<b>x₂</b><span>reads</span>
<b>xₜ</b><span>context</span>
</div>
</div>

<aside class="rnn-redone-side">
<div class="rnn-hidden-card">
<span>hidden state</span>
<strong>h<sub>t</sub></strong>
<p>A compact memory of the tokens seen so far.</p>
</div>

<div class="rnn-redone-steps">
<div><b>01</b><span>read current input token</span></div>
<div><b>02</b><span>combine it with previous memory</span></div>
<div><b>03</b><span>produce a new hidden state</span></div>
</div>

<div class="rnn-rolled-mini">
<img :src="'/images/nlp-rnn-rolled.svg'" alt="Compact recurrent neural network with loop from Dive into Deep Learning">
<span>Loop = information can persist across time.</span>
</div>
</aside>
</div>

<div class="nlp-takeaway">RNNs introduced memory into neural networks.</div>
</section>

---
class: nlp-memory-problem-slide
---

<section class="slide-shell nlp-slide nlp-memory-problem nlp-memory-redone">
<div class="nlp-header">
<span>LIMITATION</span>
<h1>The Memory Problem</h1>
<p>Simple RNNs struggle when useful context is far away from the word being predicted.</p>
</div>

<div class="memory-redone-main">
<div class="memory-redone-visual-card">
<div class="memory-sentence-card">
<span>Long-range dependency</span>
<p>I grew up in <mark>France</mark> ... after many words ... I speak fluent <mark>French</mark>.</p>
</div>

<div class="memory-longterm-frame">
<img :src="'/images/nlp-colah-rnn-longtermdependencies.png'" alt="RNN long-term dependency diagram from colah's LSTM explanation">
</div>

<div class="memory-fade-meter">
<b>near context</b>
<i></i>
<b>distant context</b>
</div>
</div>

<aside class="memory-redone-side">
<div class="memory-redone-card">
<span>Why it fails</span>
<strong>Signal fades with distance.</strong>
<p>The model must carry information through many repeated steps.</p>
</div>

<div class="memory-redone-card gradient">
<span>Training issue</span>
<strong>Vanishing gradients</strong>
<p>Error signals can become too small to update early tokens effectively.</p>
</div>

<div class="memory-bptt-card">
<img :src="'/images/nlp-rnn-bptt.svg'" alt="Backpropagation through time diagram from Dive into Deep Learning">
<p>Learning sends error backward through the unrolled sequence.</p>
</div>
</aside>
</div>

<div class="nlp-takeaway">Remembering nearby words is easy. Remembering distant context is hard.</div>
</section>

---
class: nlp-gates-slide
---

<section class="slide-shell nlp-slide nlp-gates-redone">
<div class="nlp-header">
<span>GATED MEMORY</span>
<h1>LSTMs and GRUs</h1>
<p>Gates help recurrent models decide what to keep, update, and forget.</p>
</div>

<div class="gates-redone-layout">
<article class="gates-redone-hero">
<div class="gates-redone-heading">
<span>Long short-term memory</span>
<strong>A recurrent cell with controlled memory flow</strong>
</div>
<div class="gates-redone-image">
<img :src="'/images/nlp-colah-lstm-chain.png'" alt="Unrolled LSTM cell diagram showing gates and memory flow">
</div>
<div class="gates-redone-legend">
<b>cell state</b>
<b>gates</b>
<b>hidden state</b>
</div>
</article>

<aside class="gates-redone-side">
<article class="gates-redone-card gates-lstm-card">
<span>1997 · Hochreiter & Schmidhuber</span>
<strong>LSTM</strong>
<p>Uses forget, input, and output gates to protect useful long-range information.</p>
</article>

<article class="gates-redone-card gates-gru-card">
<div>
<span>2014 · Cho et al.</span>
<strong>GRU</strong>
<p>A simpler gated unit with update and reset gates.</p>
</div>
<div class="gates-gru-image">
<img :src="'/images/nlp-colah-gru.png'" alt="GRU gate diagram from Christopher Olah">
</div>
</article>

<article class="gates-redone-insight">
<span>Core mechanism</span>
<strong>remember · update · forget</strong>
<p>Gates decide which signal survives across time.</p>
</article>
</aside>
</div>

<div class="nlp-takeaway">Gates made sequence memory more controllable.</div>
</section>

---
class: nlp-attention-bridge-slide
---

<section class="slide-shell nlp-slide nlp-attention-redone">
<div class="nlp-header">
<span>BRIDGE TO TRANSFORMERS</span>
<h1>From Recurrence to Attention</h1>
<p>RNNs read sequentially; attention lets models look directly at relevant tokens.</p>
</div>

<div class="attention-redone-layout">
<article class="attention-redone-hero">
<div class="attention-redone-heading">
<span>Conceptual shift</span>
<strong>From sequential memory to direct context selection</strong>
</div>

<div class="attention-redone-compare attention-balanced-compare">
<article class="attention-balanced-card recurrence-mode">
<div class="attention-balanced-head">
<span>Recurrence</span>
<strong>Sequential path</strong>
</div>
<div class="attention-balanced-image">
<img :src="'/images/nlp-unfolded-rnn.svg'" alt="Unrolled recurrent neural network diagram from Dive into Deep Learning">
</div>
<p>Context is carried from one hidden state to the next.</p>
</article>

<article class="attention-balanced-card attention-mode">
<div class="attention-balanced-head">
<span>Attention</span>
<strong>Direct links</strong>
</div>
<div class="attention-balanced-image">
<img :src="'/images/nlp-self-attention.svg'" alt="Self-attention diagram from Dive into Deep Learning">
</div>
<p>Relevant tokens can be selected without waiting through the chain.</p>
</article>
</div>

<div class="attention-shift-note">
<b>Key shift</b>
<span>Attention replaces a single compressed memory path with learned relevance weights across the sequence.</span>
</div>
</article>

<aside class="attention-redone-side">
<article class="attention-source-card">
<div class="attention-source-heading">
<span>Self-attention</span>
<strong>direct token-to-token links</strong>
</div>
<div class="attention-source-image attention-self-image">
<img :src="'/images/nlp-self-attention.svg'" alt="Self-attention diagram from Dive into Deep Learning">
</div>
</article>

<article class="attention-source-card">
<div class="attention-source-heading">
<span>Translation</span>
<strong>align source and target words</strong>
</div>
<div class="attention-source-image attention-seq-image">
<img :src="'/images/nlp-seq2seq-attention.svg'" alt="Sequence-to-sequence attention diagram from Dive into Deep Learning">
</div>
</article>
</aside>
</div>

<div class="nlp-takeaway">Attention was the bridge from sequence models to Transformers.</div>
</section>

---
class: transformer-attention-breakthrough-slide
---

<section class="slide-shell transformer-section attention-breakthrough attn44-redone">
<div class="ts-header">
<span>ATTENTION MECHANISM</span>
<h1>The Attention Breakthrough</h1>
<p>Instead of compressing everything into one memory state, a model can focus on the most relevant parts.</p>
</div>

<div class="attn44-main">
<div class="attn44-comparison">
<article class="ts-panel attn44-card before">
<div class="attn44-card-head">
<span>Before attention</span>
<strong>Context is squeezed through time</strong>
</div>
<div class="attn44-image-frame">
<img :src="'/images/nlp-colah-rnn-longtermdependencies.png'" alt="Long-term dependency example from Christopher Olah">
</div>
<p>RNNs and LSTMs still pass information step by step through hidden states.</p>
</article>

<article class="ts-panel attn44-card after">
<div class="attn44-card-head">
<span>With attention</span>
<strong>Relevant tokens get direct routes</strong>
</div>
<div class="attn44-image-frame">
<img :src="'/images/seq2seq-attention-details-d2l.svg'" alt="Attention details diagram from Dive into Deep Learning">
</div>
<p>Attention lets the model retrieve the useful context directly when it is needed.</p>
</article>
</div>

<article class="attn44-sentence ts-panel">
<div class="attn44-sentence-text">
<span>The</span><strong>animal</strong><span>did not cross the street because</span><strong>it</strong><span>was too tired.</span>
</div>
<div class="attn44-sentence-note">
<b>Direct focus</b>
<span>“it” can attend back to the relevant earlier concept instead of relying on a single compressed memory.</span>
</div>
</article>
</div>

<div class="ts-takeaway">Attention reduces the memory bottleneck of recurrent models.</div>
</section>

---
class: transformer-paper-slide
---

<section class="slide-shell transformer-section paper-slide paper45-redone paper45-hero-redesign">
<div class="ts-header">
<span>HISTORICAL TURNING POINT</span>
<h1>Attention Is All You Need</h1>
<p>The 2017 paper that changed the future of AI.</p>
</div>

<div class="paper45-hero-main">
<article class="ts-panel paper45-transformer-hero">
<div class="paper45-panel-head">
<span>Transformer architecture</span>
<strong>Attention becomes the central computation</strong>
</div>
<div class="paper45-transformer-frame">
<img :src="'/images/transformer-full-d2l.svg'" alt="Transformer architecture diagram from Dive into Deep Learning">
</div>
</article>

<aside class="paper45-hero-side">
<article class="ts-panel paper45-paper-card">
<figure class="paper45-cover-mini">
<img :src="'/images/attention-paper-first-page.png'" alt="First page of the Attention Is All You Need paper from arXiv">
</figure>
<div class="paper45-paper-meta">
<b>2017</b>
<strong>Vaswani et al.</strong>
<p>Introduced the Transformer and showed attention could replace recurrence in sequence modeling.</p>
</div>
</article>

<article class="ts-panel paper45-google-card">
<div class="paper45-google">
<img :src="'/images/google-logo-official.png'" alt="Official Google logo">
<span>Google Brain / Google Research</span>
</div>
</article>

<article class="ts-panel paper45-core-card">
<span>Core idea</span>
<strong>Attention replaces recurrence</strong>
<p>Parallel, scalable, and reusable sequence modeling.</p>
</article>

<div class="paper45-hero-impact">Foundation for BERT, GPT, LLMs, and modern generative AI.</div>
</aside>
</div>
</section>

---
class: what-is-attention-slide
---

<section class="slide-shell transformer-section what-attention attn46-redone">
<div class="ts-header">
<span>ATTENTION INTUITION</span>
<h1>What Is Attention?</h1>
<p>A token builds its representation by looking at the most relevant other tokens.</p>
</div>

<div class="attn46-main">
<article class="ts-panel attn46-visual-card">
<div class="attn46-card-head">
<span>Online educational figure</span>
<strong>Attention computes a weighted context vector</strong>
</div>
<div class="attn46-image-frame">
<img :src="'/images/attention-output-d2l.svg'" alt="Attention output diagram from Dive into Deep Learning">
</div>
</article>

<aside class="attn46-side">
<article class="ts-panel attn46-token-card">
<span>Target token</span>
<strong>“it” asks where to look</strong>
<div class="attn46-sentence">
<b>The</b><b>cat</b><b>sat</b><b>on</b><b>the</b><b class="focus">mat</b><b>because</b><b class="target">it</b><b>was</b><b>soft</b>
</div>
</article>

<article class="ts-panel attn46-weight-card">
<span>Relevance weights</span>
<div class="attn46-weight-row high">
<b>mat</b><i></i><strong>0.62</strong>
</div>
<div class="attn46-weight-row medium">
<b>cat</b><i></i><strong>0.24</strong>
</div>
<div class="attn46-weight-row low">
<b>street</b><i></i><strong>0.08</strong>
</div>
</article>

<article class="ts-panel attn46-message-card">
<strong>Attention is selective context.</strong>
<p>The representation of one token becomes a weighted mixture of information from other tokens.</p>
</article>
</aside>
</div>

<div class="ts-takeaway">Attention turns context into weighted relevance.</div>
</section>

---
class: self-attention-step-slide
---

<section class="slide-shell transformer-section self-attention-step attn47-redone">
<div class="ts-header">
<span>SELF-ATTENTION</span>
<h1>Self-Attention Step by Step</h1>
<p>Each token creates queries, keys, and values to decide where to look.</p>
</div>

<div class="attn47-main">
<div class="attn47-flow ts-panel">
<span>Token embeddings</span>
<i></i>
<span>Linear projections</span>
<i></i>
<span>Q · K · V</span>
<i></i>
<span>Attention weights</span>
<i></i>
<span>Updated token</span>
</div>

<div class="attn47-visual-grid">
<article class="ts-panel attn47-visual-card">
<div class="attn47-card-head">
<span>Online figure</span>
<strong>Query, key, value projections</strong>
</div>
<div class="attn47-image-frame">
<img :src="'/images/qkv-d2l.svg'" alt="Query key value attention diagram from Dive into Deep Learning">
</div>
</article>

<article class="ts-panel attn47-visual-card">
<div class="attn47-card-head">
<span>Online figure</span>
<strong>Multi-head attention combines several views</strong>
</div>
<div class="attn47-image-frame">
<img :src="'/images/multi-head-attention-d2l.svg'" alt="Multi-head attention diagram from Dive into Deep Learning">
</div>
</article>
</div>

<div class="attn47-explain-row">
<article class="ts-panel attn47-mini-card">
<span>Query</span>
<strong>asks what to find</strong>
</article>
<article class="ts-panel attn47-mini-card">
<span>Keys</span>
<strong>describe available tokens</strong>
</article>
<article class="ts-panel attn47-mini-card">
<span>Values</span>
<strong>carry the information</strong>
</article>
<article class="ts-panel attn47-mini-card result">
<span>Output</span>
<strong>a context-aware token representation</strong>
</article>
</div>
</div>

<div class="ts-takeaway">Self-attention lets every token gather information from the whole sequence.</div>
</section>

---
class: rnn-to-transformer-slide
---

<section class="slide-shell transformer-section rnn-transformer-compare attn48-final">
<div class="ts-header">
<span>ARCHITECTURAL SHIFT</span>
<h1>From RNNs to Transformers</h1>
<p>Sequential recurrence gave way to attention-based parallel processing.</p>
</div>

<div class="attn48-final-main">
<article class="ts-panel attn48-final-figure">
<div class="attn48-final-head">
<span>Online comparison figure</span>
<strong>Sequential recurrence versus direct self-attention</strong>
</div>
<div class="attn48-final-frame">
<img :src="'/images/nlp-cnn-rnn-self-attention.svg'" alt="CNN RNN self-attention comparison diagram from Dive into Deep Learning">
</div>
</article>

<div class="attn48-final-cards">
<article class="ts-panel attn48-final-card rnn">
<span>RNN / LSTM</span>
<strong>Sequential path</strong>
<p>Tokens are processed one after another through a hidden state.</p>
</article>

<article class="ts-panel attn48-final-card transformer">
<span>Transformer</span>
<strong>Direct interaction</strong>
<p>Self-attention lets every token look at every other token.</p>
</article>

<article class="ts-panel attn48-final-card result">
<span>Result</span>
<strong>More scalable context</strong>
<p>Parallel processing makes long-range dependencies easier to model.</p>
</article>
</div>
</div>

<div class="ts-takeaway">Transformers replaced recurrence with scalable contextual interaction.</div>
</section>

---
class: transformer-block-slide
---

<section class="slide-shell transformer-section transformer-block attn49-redone">
<div class="ts-header">
<span>TRANSFORMER ANATOMY</span>
<h1>Inside a Transformer Block</h1>
<p>Self-attention is combined with feed-forward layers, normalization, and residual paths.</p>
</div>

<div class="attn49-main">
<article class="ts-panel attn49-block-card">
<div class="attn49-card-head">
<span>Block anatomy</span>
<strong>Context mixing plus feature transformation</strong>
</div>

<div class="attn49-block-diagram">
<div class="attn49-signal input">token representations</div>
<i></i>
<div class="attn49-layer attention">
<span>Multi-head self-attention</span>
<b>mix context across tokens</b>
</div>
<div class="attn49-residual first">residual + norm</div>
<i></i>
<div class="attn49-layer ffn">
<span>Feed-forward network</span>
<b>transform each token</b>
</div>
<div class="attn49-residual second">residual + norm</div>
<i></i>
<div class="attn49-signal output">updated representations</div>
</div>
</article>

<aside class="attn49-side">
<article class="ts-panel attn49-reference-card">
<div class="attn49-card-head">
<span>Online reference</span>
<strong>Original Transformer architecture</strong>
</div>
<div class="attn49-reference-frame">
<img :src="'/images/transformer-full-d2l.svg'" alt="Transformer architecture diagram from Dive into Deep Learning">
</div>
</article>

<div class="attn49-component-grid">
<article class="ts-panel attn49-mini"><span>attention</span><strong>context mixing</strong></article>
<article class="ts-panel attn49-mini"><span>norm</span><strong>stable activations</strong></article>
<article class="ts-panel attn49-mini"><span>ffn</span><strong>nonlinear transform</strong></article>
<article class="ts-panel attn49-mini"><span>skip</span><strong>train deep stacks</strong></article>
</div>
</aside>
</div>

<div class="ts-takeaway">The Transformer block combines context mixing and nonlinear feature transformation.</div>
</section>

---
class: transformer-scale-slide
---

<section class="slide-shell transformer-section transformer-scale attn50-redone">
<div class="ts-header">
<span>SCALING PRINCIPLE</span>
<h1>Why Transformers Scale So Well</h1>
<p>Parallel attention made context modeling hardware-friendly and reusable.</p>
</div>

<div class="attn50-main">
<article class="ts-panel attn50-hero-card">
<div class="attn50-head">
<span>Online figure</span>
<strong>Multi-head attention reads context through several learned views</strong>
</div>
<div class="attn50-image-frame">
<img :src="'/images/multi-head-attention-d2l.svg'" alt="Multi-head attention diagram from Dive into Deep Learning">
</div>
</article>

<aside class="attn50-side-grid">
<article class="ts-panel attn50-factor">
<span>01</span>
<strong>Parallel tokens</strong>
<p>Sequences can be processed together instead of strictly step by step.</p>
</article>
<article class="ts-panel attn50-factor">
<span>02</span>
<strong>Long context</strong>
<p>Any token can directly attend to distant information.</p>
</article>
<article class="ts-panel attn50-factor">
<span>03</span>
<strong>Data + compute</strong>
<p>Large pretraining benefits from bigger models and datasets.</p>
</article>
<article class="ts-panel attn50-factor">
<span>04</span>
<strong>Reusable models</strong>
<p>One pretrained backbone can support many downstream tasks.</p>
</article>
</aside>
</div>

<div class="ts-takeaway">Scaling works because attention combines parallel computation with flexible context.</div>
</section>

---
class: transformer-llm-transition-slide
---

<section class="slide-shell transformer-section transformer-llm-transition attn51-redone">
<div class="ts-header">
<span>TRANSITION TO LLMs</span>
<h1>From Transformers to Large Language Models</h1>
<p>The Transformer became the engine behind GPT, BERT, and modern foundation models.</p>
</div>

<div class="attn51-main">
<article class="ts-panel attn51-family-card">
<div class="attn51-head">
<span>Online figure</span>
<strong>Transformer language models reuse the same attention backbone in different ways</strong>
</div>
<div class="attn51-image-frame">
<img :src="'/images/elmo-gpt-bert-d2l.svg'" alt="ELMo GPT BERT comparison diagram from Dive into Deep Learning">
</div>
</article>

<aside class="attn51-model-grid">
<article class="ts-panel attn51-model-card">
<span>Encoder</span>
<strong>BERT</strong>
<p>Builds bidirectional representations for understanding.</p>
</article>
<article class="ts-panel attn51-model-card">
<span>Decoder</span>
<strong>GPT</strong>
<p>Predicts the next token for fluent generation.</p>
</article>
<article class="ts-panel attn51-model-card">
<span>Encoder-decoder</span>
<strong>T5</strong>
<p>Frames language tasks as text-to-text transformation.</p>
</article>
</aside>
</div>

<div class="ts-takeaway">Large language models are Transformers scaled through pretraining, data, and compute.</div>
</section>

---
class: llm-definition-slide
---

<section class="slide-shell transformer-section llm-section llm-what-slide llm52-redone">
<div class="ts-header">
<span>LARGE LANGUAGE MODELS</span>
<h1>What Is a Large Language Model?</h1>
<p>A Transformer trained at scale to model language from massive text corpora.</p>
</div>

<div class="llm52-main">
<article class="ts-panel llm52-architecture">
<div class="llm52-head">
<span>Online figure</span>
<strong>LLMs use Transformer blocks as a scalable language engine</strong>
</div>
<div class="llm52-architecture-frame">
<img :src="'/images/gpt-decoder-only-d2l.svg'" alt="GPT decoder-only Transformer diagram from Dive into Deep Learning">
</div>
</article>

<aside class="llm52-side">
<article class="ts-panel llm52-formula">
<span>definition</span>
<div>
<b>Transformer</b>
<i>+</i>
<b>scale</b>
<i>+</i>
<b>pretraining</b>
</div>
<strong>Large Language Model</strong>
</article>

<article class="ts-panel llm52-flow">
<span>training signal</span>
<div class="llm52-flow-row">
<b>text</b><i></i><b>tokens</b><i></i><b>probabilities</b>
</div>
<p>The model learns statistical structure by repeatedly predicting language.</p>
</article>

<article class="ts-panel llm52-key">
<span>what becomes large</span>
<strong>data · parameters · compute</strong>
<p>Scale gives the model broad linguistic and task knowledge.</p>
</article>
</aside>
</div>

<div class="ts-takeaway">An LLM is a Transformer trained at scale to model language.</div>
</section>

---
class: llm-next-token-slide
---

<section class="slide-shell transformer-section llm-section llm-next-token-slide llm53-redone">
<div class="ts-header">
<span>TRAINING OBJECTIVE</span>
<h1>Next-Token Prediction</h1>
<p>A simple objective becomes powerful when repeated across enormous text collections.</p>
</div>

<div class="llm53-main">
<article class="ts-panel llm53-objective">
<div class="llm53-head">
<span>objective</span>
<strong>Given the previous tokens, predict what comes next</strong>
</div>

<div class="llm53-sentence-card">
<p>The model learns to predict the next</p>
<div>
<span>large</span>
<span>language</span>
<span>models</span>
<span>predict</span>
<b>?</b>
</div>
</div>

<div class="llm53-distribution">
<div class="winner"><span>token</span><i style="--w:86%"></i><b>0.46</b></div>
<div><span>word</span><i style="--w:54%"></i><b>0.24</b></div>
<div><span>text</span><i style="--w:33%"></i><b>0.15</b></div>
<div><span>answer</span><i style="--w:18%"></i><b>0.08</b></div>
</div>
</article>

<article class="ts-panel llm53-reference">
<div class="llm53-head">
<span>Online figure</span>
<strong>Language modeling turns text into repeated prediction examples</strong>
</div>
<div class="llm53-reference-frame">
<img :src="'/images/nlp-lang-model-data.svg'" alt="Language model data diagram from Dive into Deep Learning">
</div>
<p>Every position in a text sequence can become a training example.</p>
</article>
</div>

<div class="ts-takeaway">Predicting the next token becomes a powerful learning signal.</div>
</section>

---
class: llm-pretraining-scale-slide
---

<section class="slide-shell transformer-section llm-section llm-scale-slide llm54-redone">
<div class="ts-header">
<span>PRETRAINING</span>
<h1>Pretraining at Scale</h1>
<p>Broad capabilities emerge from data, compute, parameters, and long optimization.</p>
</div>

<div class="llm54-main">
<article class="ts-panel llm54-hero">
<img :src="'/images/llm-datacenter-server-racks.jpg'" alt="Data center server racks from Wikimedia Commons">
<div class="llm54-overlay">
<span>Online image · compute infrastructure</span>
<strong>Pretraining is language modeling at industrial scale</strong>
<p>Huge corpora are processed for weeks or months across specialized accelerators.</p>
</div>
</article>

<aside class="llm54-side">
<article class="ts-panel llm54-equation">
<span>scaling recipe</span>
<div><b>data</b><i>+</i><b>compute</b><i>+</i><b>parameters</b></div>
<strong>broad capabilities</strong>
</article>

<div class="llm54-factor-grid">
<article class="ts-panel llm54-factor"><span>datasets</span><strong>curated text + code</strong><p>Examples teach language, facts, style, and structure.</p></article>
<article class="ts-panel llm54-factor"><span>accelerators</span><strong>GPUs / TPUs</strong><p>Parallel hardware makes large training runs feasible.</p></article>
<article class="ts-panel llm54-factor"><span>parameters</span><strong>capacity to store patterns</strong><p>Weights encode distributed statistical regularities.</p></article>
<article class="ts-panel llm54-factor"><span>optimization</span><strong>many prediction steps</strong><p>Repeated next-token loss gradually shapes behavior.</p></article>
</div>
</aside>
</div>

<div class="ts-takeaway">Scale turns a simple objective into broad capabilities.</div>
</section>

---
class: llm-assistant-slide
---

<section class="slide-shell transformer-section llm-section llm-assistant-slide llm55-redone">
<div class="ts-header">
<span>ALIGNMENT PIPELINE</span>
<h1>From Pretrained Model to Assistant</h1>
<p>Instruction and preference tuning shape a raw model into conversational behavior.</p>
</div>

<div class="llm55-main">
<article class="ts-panel llm55-pipeline">
<div class="llm55-head">
<span>training pipeline</span>
<strong>The same model is tuned to follow instructions and prefer better answers</strong>
</div>

<div class="llm55-flow">
<div class="raw"><span>01</span><b>Pretrain</b><em>language patterns</em></div>
<i></i>
<div class="instruction"><span>02</span><b>Instruct</b><em>follow tasks</em></div>
<i></i>
<div class="preference"><span>03</span><b>Prefer</b><em>ranked answers</em></div>
<i></i>
<div class="assistant"><span>04</span><b>Assistant</b><em>useful dialogue</em></div>
</div>

<div class="llm55-behavior-strip">
<b>raw language model</b>
<i></i>
<b>instruction-following assistant</b>
</div>
</article>

<aside class="llm55-side">
<article class="ts-panel llm55-reference">
<div class="llm55-head">
<span>Online figure</span>
<strong>Transformer language model reference</strong>
</div>
<div class="llm55-reference-frame">
<img :src="'/images/t5-encoder-decoder-d2l.svg'" alt="T5 encoder-decoder diagram from Dive into Deep Learning">
</div>
</article>

<article class="ts-panel llm55-note">
<span>key distinction</span>
<strong>Pretraining gives capability. Alignment shapes behavior.</strong>
<p>The assistant layer is learned from instructions, examples, and preference feedback.</p>
</article>
</aside>
</div>

<div class="ts-takeaway">Alignment turns a raw language model into a useful assistant.</div>
</section>

---
class: llm-capabilities-slide
---

<section class="slide-shell transformer-section llm-section llm-capabilities-slide llm56-redone">
<div class="ts-header">
<span>CAPABILITIES</span>
<h1>What LLMs Can Do</h1>
<p>LLMs became general-purpose interfaces for language-heavy work.</p>
</div>

<div class="llm56-main">
<article class="ts-panel llm56-hero">
<div class="llm56-head">
<span>Online figure</span>
<strong>A reusable language backbone can support many interfaces</strong>
</div>
<div class="llm56-model-frame">
<img :src="'/images/elmo-gpt-bert-d2l.svg'" alt="ELMo GPT BERT comparison diagram from Dive into Deep Learning">
</div>
<div class="llm56-prompt-strip">
<b>prompt</b><i></i><b>language model</b><i></i><b>task output</b>
</div>
</article>

<aside class="llm56-task-grid">
<article class="ts-panel llm56-task-card"><span>writing</span><strong>draft, rewrite, adapt tone</strong></article>
<article class="ts-panel llm56-task-card"><span>coding</span><strong>generate, explain, debug</strong></article>
<article class="ts-panel llm56-task-card"><span>summaries</span><strong>compress long documents</strong></article>
<article class="ts-panel llm56-task-card"><span>translation</span><strong>move between languages</strong></article>
<article class="ts-panel llm56-task-card"><span>reasoning support</span><strong>structure analysis steps</strong></article>
<article class="ts-panel llm56-task-card"><span>RAG</span><strong>answer with retrieved context</strong></article>
</aside>
</div>

<div class="ts-takeaway">LLMs became general-purpose language interfaces.</div>
</section>

---
class: llm-limits-slide
---

<section class="slide-shell transformer-section llm-section llm-limits-slide llm57-redone">
<div class="ts-header">
<span>LIMITS</span>
<h1>Limits and Failure Modes</h1>
<p>Fluent output can still be wrong, biased, stale, or insufficiently grounded.</p>
</div>

<div class="llm57-main">
<article class="ts-panel llm57-warning">
<div class="llm57-warning-visual">
<img :src="'/images/llm-caution-warning-sign.svg'" alt="Public-domain caution warning sign from Wikimedia Commons">
</div>
<strong>Language fluency is not reliability</strong>
<p>LLMs generate plausible continuations. Reliability requires grounding, checks, and careful use.</p>
</article>

<aside class="llm57-risks">
<article class="ts-panel llm57-risk-card"><span>hallucination</span><strong>confident falsehoods</strong><p>Plausible wording can hide incorrect facts.</p></article>
<article class="ts-panel llm57-risk-card"><span>bias</span><strong>data-shaped behavior</strong><p>Models can reproduce patterns from training data.</p></article>
<article class="ts-panel llm57-risk-card"><span>privacy</span><strong>sensitive input risk</strong><p>Prompts may contain information that should not be shared.</p></article>
<article class="ts-panel llm57-risk-card"><span>stale knowledge</span><strong>training has a date</strong><p>Recent events may require external verification.</p></article>
<article class="ts-panel llm57-risk-card wide"><span>grounding</span><strong>check claims against evidence</strong><p>For high-stakes work, retrieval, citations, and human review are part of the system.</p></article>
</aside>
</div>

<div class="ts-takeaway">Fluent language is not the same as reliable knowledge.</div>
</section>

---
class: genai-overview-slide
---

<section class="slide-shell transformer-section genai-section genai-overview-slide genai58">
<div class="ts-header">
<span>GENERATIVE AI</span>
<h1>From LLMs to Generative AI</h1>
<p>Text generation is one part of a broader family of models that create new artifacts.</p>
</div>

<div class="genai58-composed">
<article class="ts-panel genai58-hero-image">
<img :src="'/images/genai-stable-astronaut-horse.webp'" alt="Stable Diffusion generated astronaut riding a horse image from Wikimedia Commons">
<div class="genai58-hero-copy">
<span>online generated image</span>
<strong>Language becomes a creative control surface.</strong>
</div>
</article>

<aside class="genai58-story">
<article class="ts-panel genai58-thesis">
<div class="genai58-route">
<b>LLMs</b>
<i></i>
<b>Generative AI</b>
</div>
<strong>From predicting words to producing artifacts.</strong>
<p>Text is no longer only the output. It becomes the interface for creating media.</p>
</article>

<div class="genai58-four-modes">
<article class="ts-panel"><img :src="'/images/genai-dalle-sample-grid.png'" alt="DALL-E generated image sample grid from Wikimedia Commons"><span>images</span><strong>visual creation</strong></article>
<article class="ts-panel"><img :src="'/images/genai-dalle-teddy-research.jpg'" alt="DALL-E generated teddy bears researching AI underwater image from Wikimedia Commons"><span>text + image</span><strong>prompted scenes</strong></article>
<article class="ts-panel"><img :src="'/images/genai-stable-shrine-landscape.png'" alt="Stable Diffusion generated shrine landscape from Wikimedia Commons"><span>worlds</span><strong>style and space</strong></article>
<article class="ts-panel"><img :src="'/images/genai-taskmatrix-ai.jpg'" alt="TaskMatrix.AI overview diagram from Wikimedia Commons"><span>systems</span><strong>multimodal tools</strong></article>
</div>
</aside>
</div>

<div class="ts-takeaway">Generative AI turns models into creative engines.</div>
</section>

---
class: genai-diffusion-slide
---

<section class="slide-shell transformer-section genai-section genai-diffusion-slide genai59">
<div class="ts-header">
<span>IMAGE GENERATION</span>
<h1>How Image Generation Works</h1>
<p>Diffusion models learn to turn random noise into coherent visual structure.</p>
</div>

<div class="genai59-composed">
<article class="ts-panel genai59-process">
<div class="genai-card-head">
<span>online diffusion trace</span>
<strong>Noise becomes structure through repeated denoising.</strong>
</div>
<div class="genai59-process-frame">
<img :src="'/images/genai-ddim-castle-steps.png'" alt="DDIM diffusion denoising steps image from Wikimedia Commons">
</div>
</article>

<aside class="genai59-clear-explainer">
<article class="ts-panel genai59-sample">
<img :src="'/images/genai-stable-shrine-landscape.png'" alt="Stable Diffusion generated shrine landscape from Wikimedia Commons">
<div>
<span>sample</span>
<strong>Generated, not retrieved.</strong>
</div>
</article>

<div class="genai59-step-list">
<article class="ts-panel"><span>01</span><strong>Noise</strong><p>start from randomness in latent space</p></article>
<article class="ts-panel"><span>02</span><strong>Denoise</strong><p>predict what noise should be removed</p></article>
<article class="ts-panel"><span>03</span><strong>Structure</strong><p>shapes, textures, and layout emerge</p></article>
<article class="ts-panel"><span>04</span><strong>Image</strong><p>decode the final latent into pixels</p></article>
</div>
</aside>
</div>

<div class="ts-takeaway">Diffusion models learn to reverse noise into structure.</div>
</section>

---
class: genai-text-image-slide
---

<section class="slide-shell transformer-section genai-section genai-text-image-slide genai60">
<div class="ts-header">
<span>PROMPT TO IMAGE</span>
<h1>Text-to-Image Generation</h1>
<p>Language becomes a control signal for visual synthesis.</p>
</div>

<div class="genai60-showcase">
<article class="ts-panel genai60-command">
<div class="genai60-prompt-box">
<span>prompt</span>
<strong>“Astronaut riding a horse, cinematic light, high detail.”</strong>
<p>The sentence becomes a conditioning signal that guides the image generator.</p>
</div>

<div class="genai60-pipeline">
<b>text</b><i></i><b>latent plan</b><i></i><b>pixels</b>
</div>

<div class="genai60-controls">
<div><span>objects</span><b>astronaut · horse</b></div>
<div><span>style</span><b>cinematic</b></div>
<div><span>composition</span><b>subject + scene</b></div>
<div><span>detail</span><b>lighting · texture</b></div>
</div>
</article>

<article class="ts-panel genai60-hero">
<img :src="'/images/genai-stable-astronaut-horse.webp'" alt="Stable Diffusion generated astronaut riding a horse image from Wikimedia Commons">
<div class="genai60-hero-label">
<span>online generated image</span>
<strong>prompt becomes image</strong>
</div>
</article>

<aside class="genai60-variants">
<figure class="ts-panel"><img :src="'/images/genai-dalle-teddy-research.jpg'" alt="DALL-E generated teddy bears researching AI underwater image from Wikimedia Commons"><figcaption>new scene</figcaption></figure>
<figure class="ts-panel"><img :src="'/images/genai-stable-shrine-landscape.png'" alt="Stable Diffusion generated shrine landscape from Wikimedia Commons"><figcaption>new world</figcaption></figure>
<figure class="ts-panel"><img :src="'/images/genai-dalle-radish.jpg'" alt="DALL-E generated radish image from Wikimedia Commons"><figcaption>new object</figcaption></figure>
</aside>
</div>

<div class="ts-takeaway">Language becomes a control interface for visual creation.</div>
</section>

---
class: genai-multimodal-slide
---

<section class="slide-shell transformer-section genai-section genai-multimodal-slide genai61">
<div class="ts-header">
<span>MULTIMODAL AI</span>
<h1>Multimodal AI</h1>
<p>Modern systems connect language with perception, sound, motion, and action.</p>
</div>

<div class="genai61-showcase">
<article class="ts-panel genai61-stage">
<div class="genai61-inputs">
<div class="genai61-mode-card text"><span>text</span><b>“What should I notice?”</b></div>
<div class="genai61-mode-card image"><img :src="'/images/imagenet-cat.jpg'" alt="Cat photo from Wikimedia Commons"><span>image</span></div>
<div class="genai61-mode-card audio"><div class="genai61-wave"><i></i><i></i><i></i><i></i><i></i></div><span>audio</span></div>
<div class="genai61-mode-card video"><img :src="'/images/genai-stable-shrine-landscape.png'" alt="Stable Diffusion generated shrine landscape from Wikimedia Commons"><span>video</span></div>
</div>

<div class="genai61-model">
<em>shared</em>
<strong>multimodal<br>representation</strong>
<p>different signals become one reasoning space</p>
</div>

<div class="genai61-outputs">
<div class="genai61-output-card"><span>caption</span><b>describe what is seen</b></div>
<div class="genai61-output-card visual"><img :src="'/images/genai-stable-astronaut-horse.webp'" alt="Stable Diffusion generated astronaut riding a horse image from Wikimedia Commons"><span>generate</span></div>
<div class="genai61-output-card"><span>action</span><b>retrieve · explain · use tools</b></div>
</div>
</article>

<aside class="genai61-reference-column">
<article class="ts-panel genai61-reference">
<div class="genai-card-head">
<span>online systems diagram</span>
<strong>Multimodal models become useful when connected to tools, data, and interfaces.</strong>
</div>
<div class="genai61-reference-frame">
<img :src="'/images/genai-taskmatrix-ai.jpg'" alt="TaskMatrix.AI overview diagram from Wikimedia Commons">
</div>
</article>

<article class="ts-panel genai61-principle">
<span>core idea</span>
<strong>One model interface, many forms of context.</strong>
</article>
</aside>
</div>

<div class="ts-takeaway">Modern AI increasingly understands and generates across modalities.</div>
</section>

---
class: genai-vlm-slide
---

<section class="slide-shell transformer-section genai-section genai-vlm-slide genai62">
<div class="ts-header">
<span>VISION + LANGUAGE</span>
<h1>Vision-Language Models</h1>
<p>These models connect visual perception with natural language.</p>
</div>

<div class="genai62-showcase">
<article class="ts-panel genai62-scene">
<img :src="'/images/cnn-autonomous-car.jpg'" alt="Autonomous vehicle photo from Wikimedia Commons">
<div class="genai62-scene-overlay">
<span>image input</span>
<strong>Perception becomes language-ready context.</strong>
</div>
</article>

<aside class="genai62-dialogue">
<article class="ts-panel genai62-question-card">
<span>visual question</span>
<strong>“What is happening in this scene?”</strong>
</article>
<article class="ts-panel genai62-answer-card">
<span>grounded answer</span>
<strong>A vehicle is navigating a real street environment.</strong>
<p>The answer is grounded in the pixels, not only in text.</p>
</article>
<div class="genai62-task-row">
<article class="ts-panel"><img :src="'/images/imagenet-cat.jpg'" alt="Cat photo from Wikimedia Commons"><b>caption</b></article>
<article class="ts-panel"><img :src="'/images/cnn-medical-xray.jpg'" alt="Chest X-ray image from Wikimedia Commons"><b>inspect</b></article>
<article class="ts-panel"><img :src="'/images/cnn-satellite-imagery.jpg'" alt="Satellite imagery from Wikimedia Commons"><b>reason</b></article>
</div>
</aside>
</div>

<div class="ts-takeaway">Vision-language models connect perception with language.</div>
</section>

---
class: genai-practice-slide
---

<section class="slide-shell transformer-section genai-section genai-practice-slide genai63">
<div class="ts-header">
<span>APPLICATIONS</span>
<h1>Generative AI in Practice</h1>
<p>The impact is less about one output and more about changing workflows.</p>
</div>

<div class="genai63-showcase">
<article class="ts-panel genai63-workflow-hero">
<img :src="'/images/genai-dalle-teddy-research.jpg'" alt="DALL-E generated teddy bears researching AI underwater image from Wikimedia Commons">
<div class="genai63-hero-copy">
<span>workflow shift</span>
<strong>Generate, critique, revise, deploy.</strong>
<p>Generative AI becomes a collaborator inside creative, technical, scientific, and industrial processes.</p>
</div>
<div class="genai63-pipeline">
<b>idea</b><i></i><b>draft</b><i></i><b>review</b><i></i><b>iteration</b>
</div>
</article>

<aside class="genai63-usecases">
<article class="ts-panel genai63-use"><img :src="'/images/genai-stable-astronaut-horse.webp'" alt="Stable Diffusion generated astronaut riding a horse image"><span>design</span><strong>concept exploration</strong></article>
<article class="ts-panel genai63-use"><img :src="'/images/gpt-decoder-only-d2l.svg'" alt="GPT decoder-only diagram from Dive into Deep Learning"><span>coding</span><strong>assist development</strong></article>
<article class="ts-panel genai63-use"><img :src="'/images/nlp-lang-model-data.svg'" alt="Language model data diagram from Dive into Deep Learning"><span>education</span><strong>adaptive explanation</strong></article>
<article class="ts-panel genai63-use"><img :src="'/images/genai-dalle-sample-grid.png'" alt="DALL-E generated image sample grid from Wikimedia Commons"><span>marketing</span><strong>campaign variants</strong></article>
<article class="ts-panel genai63-use"><img :src="'/images/cnn-medical-xray.jpg'" alt="Chest X-ray image from Wikimedia Commons"><span>science</span><strong>research support</strong></article>
<article class="ts-panel genai63-use"><img :src="'/images/cnn-industrial-quality-control.png'" alt="Industrial quality-control inspection photo from Wikimedia Commons"><span>industry</span><strong>prototype faster</strong></article>
</aside>
</div>

<div class="ts-takeaway">Generative AI changes workflows, not only content creation.</div>
</section>

---
class: genai-risks-slide
---

<section class="slide-shell transformer-section genai-section genai-risks-slide genai64">
<div class="ts-header">
<span>RISKS</span>
<h1>Limits and Risks of Generative AI</h1>
<p>Generation is powerful, but fluent or realistic output still requires verification.</p>
</div>

<div class="genai64-showcase">
<article class="ts-panel genai64-evidence-wall">
<figure class="genai64-risk-shot primary">
<img :src="'/images/genai-stable-astronaut-horse.webp'" alt="Stable Diffusion generated astronaut riding a horse image from Wikimedia Commons">
<figcaption>synthetic but convincing</figcaption>
</figure>
<figure class="genai64-risk-shot">
<img :src="'/images/genai-dalle-sample-grid.png'" alt="DALL-E generated image sample grid from Wikimedia Commons">
<figcaption>variation at scale</figcaption>
</figure>
<figure class="genai64-risk-shot">
<img :src="'/images/genai-ddim-castle-steps.png'" alt="DDIM diffusion generation steps from Wikimedia Commons">
<figcaption>opaque process</figcaption>
</figure>
<div class="genai64-stamp">
<img :src="'/images/llm-caution-warning-sign.svg'" alt="Public-domain caution warning sign from Wikimedia Commons">
<strong>verify before trust</strong>
</div>
</article>

<aside class="genai64-governance">
<article class="ts-panel genai64-core-risk">
<span>central risk</span>
<strong>Realistic does not mean reliable.</strong>
<p>Generated media can be persuasive, biased, copyrighted, manipulated, or simply wrong.</p>
</article>

<div class="genai64-checklist">
<article class="ts-panel"><span>provenance</span><strong>Where did it come from?</strong></article>
<article class="ts-panel"><span>rights</span><strong>Who owns or can reuse it?</strong></article>
<article class="ts-panel"><span>harm</span><strong>Could it deceive or target people?</strong></article>
<article class="ts-panel"><span>review</span><strong>Who verifies before release?</strong></article>
</div>
</aside>
</div>

<div class="ts-takeaway">Generation needs verification, governance, and human judgment.</div>
</section>

---
class: genai-agentic-bridge-slide
---

<section class="slide-shell transformer-section genai-section genai-agentic-bridge-slide genai65">
<div class="ts-header">
<span>BRIDGE TO AGENTS</span>
<h1>Bridge to Agentic AI</h1>
<p>Generation becomes more powerful when models can use tools, memory, and plans.</p>
</div>

<div class="genai65-showcase">
<article class="ts-panel genai65-map">
<div class="genai-card-head">
<span>online systems diagram</span>
<strong>Agentic AI connects foundation models to tools, APIs, memory, and external systems.</strong>
</div>
<div class="genai65-map-frame">
<img :src="'/images/genai-taskmatrix-ai.jpg'" alt="TaskMatrix.AI overview diagram from Wikimedia Commons">
</div>
</article>

<aside class="genai65-agent-card">
<article class="ts-panel genai65-agent-idea">
<span>conceptual leap</span>
<strong>From content generator to goal-directed system.</strong>
<p>The model no longer only produces an answer; it chooses steps, calls tools, observes results, and updates the plan.</p>
</article>

<div class="genai65-agent-loop">
<article class="ts-panel"><span>01</span><strong>Plan</strong><p>break the goal into steps</p></article>
<i></i>
<article class="ts-panel"><span>02</span><strong>Act</strong><p>use tools and APIs</p></article>
<i></i>
<article class="ts-panel"><span>03</span><strong>Observe</strong><p>read outputs and state</p></article>
<i></i>
<article class="ts-panel"><span>04</span><strong>Adapt</strong><p>revise the next move</p></article>
</div>
</aside>
</div>

<div class="ts-takeaway">The next step is AI systems that act, not only generate.</div>
</section>

---
class: agentic-overview-slide
---

<section class="slide-shell transformer-section agentic-section agentic-overview-slide agent66">
<div class="ts-header">
<span>AGENTIC AI</span>
<h1>From Generation to Action</h1>
<p>Generation creates an artifact. Agentic AI turns model outputs into goal-directed action loops.</p>
</div>

<div class="agent66-layout">
<article class="ts-panel agent66-generation">
<img :src="'/images/agent-robonaut-working.jpg'" alt="NASA Robonaut 2 working, sourced from Wikimedia Commons">
<div class="agent66-generation-copy">
<span>agentic system</span>
<strong>turns goals into work</strong>
<p>tools, APIs, environments, feedback</p>
</div>
</article>

<div class="agent66-transition">
<span>goal</span>
<i></i>
<strong>control loop</strong>
</div>

<article class="ts-panel agent66-action">
<div class="agent66-action-head">
<span>control loop</span>
<strong>Decide the next step from feedback.</strong>
</div>
<div class="agent66-loop-steps">
<article><span>01</span><strong>Plan</strong><p>break the goal into steps</p></article>
<article><span>02</span><strong>Use tool</strong><p>call APIs, code, files, web</p></article>
<article><span>03</span><strong>Observe</strong><p>read results and state</p></article>
<article><span>04</span><strong>Adapt</strong><p>revise the next move</p></article>
</div>
<div class="agent66-systems-strip">
<img :src="'/images/genai-taskmatrix-ai.jpg'" alt="TaskMatrix.AI overview diagram from Wikimedia Commons">
<div>
<span>online systems diagram</span>
<strong>Tools and APIs turn language into executable work.</strong>
</div>
</div>
</article>
</div>

<div class="ts-takeaway">The key shift is from producing an answer to managing an action loop.</div>
</section>

---
class: agentic-definition-slide
---

<section class="slide-shell transformer-section agentic-section agentic-definition-slide agent67">
<div class="ts-header">
<span>DEFINITION</span>
<h1>What Is an AI Agent?</h1>
<p>An agent perceives context, chooses an action, observes the result, and updates what it does next.</p>
</div>

<div class="agent67-layout">
<article class="ts-panel agent67-core-loop">
<div class="agent67-rebuilt-canvas">
<div class="agent67-loop-title">
<span>control loop</span>
<strong>LLM inside a decision cycle</strong>
</div>
<div class="agent67-cycle-steps">
<article><span>01 perceive</span><strong>Context</strong><p>task, state, intent</p></article>
<i></i>
<article class="agent67-llm-step"><span>02 reason</span><strong>Choose action</strong><p>model selects the next move</p></article>
<i></i>
<article><span>03 act</span><strong>Tool or reply</strong><p>execute, search, write, call API</p></article>
<i></i>
<article><span>04 observe</span><strong>Feedback</strong><p>result updates state</p></article>
</div>
<div class="agent67-feedback-note">
<span>feedback loop</span>
<strong>Observation changes the next decision.</strong>
</div>
</div>
<div class="agent67-formula">
<b>LLM</b><i></i><b>tools</b><i></i><b>memory</b><i></i><b>rules</b>
</div>
</article>

<aside class="agent67-reference">
<article class="ts-panel agent67-classic">
<div class="agent67-reference-copy">
<span>classic model</span>
<strong>Perception → decision → action</strong>
<p>Agent theory has always centered on feedback from an environment.</p>
</div>
<div class="agent67-classic-frame">
<img :src="'/images/agent-artificial-intelligent-agent.png'" alt="Artificial intelligent agent perception-action loop diagram from Wikimedia Commons">
</div>
</article>

<article class="ts-panel agent67-modern">
<img :src="'/images/agent-genai-agent.png'" alt="GenAI agent architecture diagram from Wikimedia Commons">
<div>
<span>modern stack</span>
<strong>LLM plus tools, data, memory, and control rules.</strong>
</div>
</article>
</aside>
</div>

<div class="ts-takeaway">An agent is not just a model. It is a model embedded in perception, action, and feedback.</div>
</section>

---
class: agentic-history-slide
---

<section class="slide-shell transformer-section agentic-section agentic-history-slide agent68">
<div class="ts-header">
<span>HISTORY</span>
<h1>A Brief History of Agents</h1>
<p>Agentic AI is the latest version of a much older dream: software that can respond, decide, and act.</p>
</div>

<div class="agent68-layout">
<article class="ts-panel agent68-hero">
<img :src="'/images/agent-eliza-conversation.png'" alt="ELIZA conversation screenshot from Wikimedia Commons">
<div class="agent68-hero-caption">
<span>1960s</span>
<strong>ELIZA showed how little language behavior can feel intelligent.</strong>
<p>A rule-based therapist illusion, created by Joseph Weizenbaum, exposed how easily people attribute understanding to software.</p>
</div>
</article>

<article class="ts-panel agent68-timeline">
<div class="agent68-line"></div>
<article class="agent68-era first"><span>1966</span><strong>ELIZA</strong><p>conversation as illusion</p></article>
<article class="agent68-era second"><span>1970s-80s</span><strong>Expert systems</strong><p>rules encode expertise</p></article>
<article class="agent68-era third"><span>1990s</span><strong>Software agents</strong><p>programs act for users</p></article>
<article class="agent68-era fourth"><span>2023</span><strong>AutoGPT</strong><p>LLM loops go viral</p></article>
<article class="agent68-era fifth"><span>today</span><strong>LLM agents</strong><p>tools, memory, control</p></article>
</article>

<article class="ts-panel agent68-context">
<figure>
<img :src="'/images/agent-virtual-agent-diagram.jpg'" alt="Virtual agent diagram from Wikimedia Commons">
<figcaption>1990s-style software agent idea</figcaption>
</figure>
<figure>
<img :src="'/images/agent-genai-agent.png'" alt="GenAI agent architecture diagram from Wikimedia Commons">
<figcaption>modern LLM agent stack</figcaption>
</figure>
<div class="agent68-context-copy">
<span>continuity</span>
<strong>Same ambition, new substrate.</strong>
<p>Rules became models. Menus became tools. Scripts became adaptive loops.</p>
</div>
</article>
</div>

<div class="ts-takeaway">Agents evolved from scripted behavior to systems that can use models, tools, memory, and feedback.</div>
</section>

---
class: agentic-tools-slide
---

<section class="slide-shell transformer-section agentic-section agentic-tools-slide agent69">
<div class="ts-header">
<span>TOOLS</span>
<h1>Tool Use and Function Calling</h1>
<p>Function calling gives the model a disciplined way to turn intent into external action.</p>
</div>

<div class="agent69-layout">
<article class="ts-panel agent69-systems">
<div class="genai-card-head">
<span>online systems diagram</span>
<strong>Tool-using agents connect foundation models to APIs, services, databases, and other models.</strong>
</div>
<div class="agent-frame">
<img :src="'/images/genai-taskmatrix-ai.jpg'" alt="TaskMatrix.AI overview diagram from Wikimedia Commons">
</div>
</article>

<article class="ts-panel agent69-workflow">
<div class="agent69-example">
<span>user goal</span>
<strong>“Find flights for Friday and compare options.”</strong>
</div>

<div class="agent69-tool-flow">
<article><span>01</span><strong>choose tool</strong><p>flight search API</p></article>
<i></i>
<article><span>02</span><strong>call function</strong><p>structured arguments</p></article>
<i></i>
<article><span>03</span><strong>observe result</strong><p>prices, times, constraints</p></article>
</div>

<div class="agent69-contract">
<article><span>schema</span><strong>name · inputs · output type</strong></article>
<article><span>safety</span><strong>confirm before irreversible actions</strong></article>
</div>

<div class="agent69-result">
<span>agent response</span>
<strong>“Here are the best options. Do you want me to book one?”</strong>
</div>
</article>
</div>

<div class="ts-takeaway">Tools let agents go beyond narration and actually change something.</div>
</section>

---
class: agentic-memory-slide
---

<section class="slide-shell transformer-section agentic-section agentic-memory-slide agent70">
<div class="ts-header">
<span>MEMORY</span>
<h1>Memory: Why Agents Need Context</h1>
<p>Memory turns isolated model calls into a coherent interaction over time.</p>
</div>

<div class="agent70-layout">
<article class="ts-panel agent70-memory-hero">
<div class="genai-card-head">
<span>online research figure</span>
<strong>Generative agents use memory streams, retrieval, reflection, and planning before acting.</strong>
</div>
<div class="agent70-memory-frame">
<img :src="'/images/agent-generative-architecture.png'" alt="Generative agent architecture figure from Wikimedia Commons">
</div>
</article>

<aside class="agent70-memory-stack">
<article class="ts-panel agent70-memory-card active"><span>working memory</span><strong>current task state</strong><p>goal, constraints, recent tool results, open questions</p></article>
<article class="ts-panel agent70-memory-card"><span>retrieved memory</span><strong>relevant past context</strong><p>notes, files, prior decisions, user preferences</p></article>
<article class="ts-panel agent70-memory-card"><span>reflection</span><strong>lessons for the next step</strong><p>what worked, what failed, what should change</p></article>
<article class="ts-panel agent70-memory-example">
<span>why it matters</span>
<strong>Without memory, the agent repeats itself. With memory, it can continue.</strong>
</article>
</aside>
</div>

<div class="ts-takeaway">Memory lets agents maintain continuity, personalize behavior, and avoid repeating mistakes.</div>
</section>

---
class: agentic-planning-slide
---

<section class="slide-shell transformer-section agentic-section agentic-planning-slide agent71">
<div class="ts-header">
<span>PLANNING</span>
<h1>Planning: Breaking Goals into Steps</h1>
<p>Planning is how an agent turns an ambiguous goal into a sequence of concrete, checkable actions.</p>
</div>

<div class="agent71-layout">
<article class="ts-panel agent71-planning-board">
<div class="agent71-goal-card">
<span>goal</span>
<strong>“Prepare a competitive travel itinerary.”</strong>
<p>The agent must decide what to do first, what evidence it needs, and when to ask the user.</p>
</div>

<div class="agent71-plan-flow">
<article><span>01</span><strong>Decompose</strong><p>destination, dates, budget, constraints</p></article>
<i></i>
<article><span>02</span><strong>Gather</strong><p>search APIs, documents, live data</p></article>
<i></i>
<article><span>03</span><strong>Evaluate</strong><p>compare options against the goal</p></article>
<i></i>
<article><span>04</span><strong>Decide</strong><p>answer, act, ask, or re-plan</p></article>
</div>

<div class="agent71-check-row">
<article><span>stop</span><strong>goal satisfied</strong></article>
<article><span>ask</span><strong>missing preference</strong></article>
<article><span>verify</span><strong>high-stakes action</strong></article>
</div>
</article>

<aside class="agent71-reference-stack">
<article class="ts-panel agent71-reference-figure">
<div class="genai-card-head">
<span>online agent loop</span>
<strong>Planning works because it is connected to perception, memory, and action.</strong>
</div>
<div class="agent71-reference-frame">
<img :src="'/images/agent-generative-architecture.png'" alt="Generative agent architecture figure from Wikimedia Commons">
</div>
</article>

<article class="ts-panel agent71-classic-loop">
<img :src="'/images/agent-artificial-intelligent-agent.png'" alt="Artificial intelligent agent perception-action loop diagram from Wikimedia Commons">
<div>
<span>classic idea</span>
<strong>percepts become actions through a decision process</strong>
</div>
</article>
</aside>
</div>

<div class="ts-takeaway">Good planning is not a fixed script. It is decomposition plus feedback-aware revision.</div>
</section>

---
class: agentic-multi-slide
---

<section class="slide-shell transformer-section agentic-section agentic-multi-slide agent72">
<div class="ts-header">
<span>COORDINATION</span>
<h1>Multi-Agent Systems</h1>
<p>Multiple agents can divide work, but the real challenge is coordination: shared state, roles, messages, and review.</p>
</div>

<div class="agent72-layout">
<article class="ts-panel agent72-coordination-board">
<div class="agent72-workspace">
<span>shared workspace</span>
<strong>task state · evidence · tool results · decisions</strong>
</div>

<div class="agent72-agent-card planner"><span>planner</span><strong>sets strategy</strong><p>breaks goal into subtasks</p></div>
<div class="agent72-agent-card researcher"><span>researcher</span><strong>finds evidence</strong><p>retrieves data and sources</p></div>
<div class="agent72-agent-card executor"><span>executor</span><strong>uses tools</strong><p>runs actions and APIs</p></div>
<div class="agent72-agent-card critic"><span>critic</span><strong>checks quality</strong><p>tests, verifies, challenges</p></div>
<div class="agent72-connector a"></div>
<div class="agent72-connector b"></div>
<div class="agent72-connector c"></div>
<div class="agent72-connector d"></div>
</article>

<aside class="agent72-reference-stack">
<article class="ts-panel agent72-architecture-card">
<div class="genai-card-head">
<span>online architecture</span>
<strong>Classic multi-agent architectures already combined memory, roles, communication, and environment.</strong>
</div>
<div class="agent72-architecture-frame">
<img :src="'/images/agent-janus-architecture.png'" alt="Agent organizational architecture diagram from Wikimedia Commons">
</div>
</article>

<article class="ts-panel agent72-principle">
<span>design lesson</span>
<strong>More agents are useful only when coordination is explicit.</strong>
<p>Without shared state and review, multi-agent systems become noisy parallel guessing.</p>
</article>
</aside>
</div>

<div class="ts-takeaway">Multi-agent AI is not just more agents. It is structured collaboration around shared state.</div>
</section>

---
class: agentic-practice-slide
---

<section class="slide-shell transformer-section agentic-section agentic-practice-slide agent73">
<div class="ts-header">
<span>APPLICATIONS</span>
<h1>Agentic AI in Practice</h1>
<p>Agents become useful when they sit inside real workflows: observe state, choose tools, make updates, and report back.</p>
</div>

<div class="agent73-layout">
<article class="ts-panel agent73-command-center">
<div class="genai-card-head">
<span>online systems map</span>
<strong>Practical agents connect foundation models to APIs, domain data, and operational systems.</strong>
</div>
<div class="agent73-command-frame">
<img :src="'/images/genai-taskmatrix-ai.jpg'" alt="TaskMatrix.AI overview diagram from Wikimedia Commons">
</div>
<div class="agent73-loop-strip">
<b>observe</b><i></i><b>decide</b><i></i><b>act</b><i></i><b>report</b>
</div>
</article>

<aside class="agent73-usecases">
<article class="ts-panel agent73-usecase">
<img :src="'/images/llm-datacenter-server-racks.jpg'" alt="Datacenter server racks photo from Wikimedia Commons">
<div><span>operations</span><strong>triage incidents and monitor systems</strong></div>
</article>
<article class="ts-panel agent73-usecase">
<img :src="'/images/cnn-industrial-quality-control.png'" alt="Industrial quality control photo from Wikimedia Commons">
<div><span>industry</span><strong>inspect processes and coordinate actions</strong></div>
</article>
<article class="ts-panel agent73-usecase">
<img :src="'/images/cnn-medical-xray.jpg'" alt="Chest X-ray image from Wikimedia Commons">
<div><span>healthcare</span><strong>retrieve evidence and prepare reviews</strong></div>
</article>
<article class="ts-panel agent73-usecase">
<img :src="'/images/cnn-autonomous-car.jpg'" alt="Autonomous vehicle photo from Wikimedia Commons">
<div><span>embodied AI</span><strong>connect perception with real-world actions</strong></div>
</article>
</aside>
</div>

<div class="ts-takeaway">The value of agents is measured by completed workflow steps, not by fluent descriptions.</div>
</section>

---
class: agentic-failure-slide
---

<section class="slide-shell transformer-section agentic-section agentic-failure-slide agent74">
<div class="ts-header">
<span>FAILURE MODES</span>
<h1>Why Agents Fail</h1>
<p>Failures happen when an agent acts faster than it can verify, recover, or ask for help.</p>
</div>

<div class="agent74-rebuilt-layout">
<article class="ts-panel agent74-risk-visual">
<img class="agent74-risk-photo" :src="'/images/agent-ai-artifact-failure.png'" alt="AI-generated image with a visible artifact, sourced from Wikimedia Commons">
<div class="agent74-risk-overlay">
<img :src="'/images/llm-caution-warning-sign.svg'" alt="Public-domain caution warning sign from Wikimedia Commons">
<div>
<span>central risk</span>
<strong>Autonomy makes small errors operational.</strong>
</div>
</div>
</article>

<aside class="agent74-control-panel">
<article class="ts-panel agent74-thesis-card">
<span>failure is a loop problem</span>
<strong>The agent must decide whether to act, stop, ask, or verify.</strong>
</article>

<div class="agent74-failure-grid">
<article class="ts-panel agent74-failure-card"><span>goal</span><strong>unclear objective</strong><p>Optimizes the wrong success condition.</p></article>
<article class="ts-panel agent74-failure-card"><span>tools</span><strong>wrong action</strong><p>Calls the wrong API or parameters.</p></article>
<article class="ts-panel agent74-failure-card"><span>memory</span><strong>stale context</strong><p>Uses irrelevant or outdated information.</p></article>
<article class="ts-panel agent74-failure-card"><span>planning</span><strong>weak decomposition</strong><p>Chooses steps that do not converge.</p></article>
</div>

<article class="ts-panel agent74-gate-card">
<span>control gate</span>
<div class="agent74-gate-row">
<strong>act</strong>
<strong>stop</strong>
<strong>ask</strong>
<strong>verify</strong>
</div>
<p>The safest agents make this decision explicit before each consequential step.</p>
</article>
</aside>
</div>

<div class="ts-takeaway">Reliable agents need guardrails around the loop, not just a stronger model.</div>
</section>

---
class: agentic-future-slide
---

<section class="slide-shell transformer-section agentic-section agentic-future-slide agent75">
<div class="ts-header">
<span>FUTURE SYSTEMS</span>
<h1>Bridge to Future AI Systems</h1>
<p>Agentic AI points toward systems that combine perception, memory, planning, tools, and action in richer environments.</p>
</div>

<div class="agent75-rebuilt-layout">
<article class="ts-panel agent75-future-hero">
<img :src="'/images/cnn-autonomous-car.jpg'" alt="Autonomous vehicle photo from Wikimedia Commons">
<div class="agent75-future-overlay">
<span>toward embodied intelligence</span>
<strong>From browser agents to systems that perceive and act in the world.</strong>
</div>
</article>

<aside class="agent75-future-stack">
<article class="ts-panel agent75-trajectory">
<div class="agent75-trajectory-head">
<span>trajectory</span>
<strong>From language interfaces to situated systems</strong>
</div>
<div class="agent75-trajectory-grid">
<div><b>01</b><strong>tool agents</strong><p>APIs, files, web actions</p></div>
<div><b>02</b><strong>teams</strong><p>specialized agents coordinate</p></div>
<div><b>03</b><strong>world models</strong><p>simulate outcomes before acting</p></div>
<div><b>04</b><strong>embodied AI</strong><p>sensors, environments, action</p></div>
</div>
</article>

<article class="ts-panel agent75-system-card">
<img :src="'/images/agent-generative-architecture.png'" alt="Generative agent architecture figure from Wikimedia Commons">
<div>
<span>through-line</span>
<strong>Future systems keep the same loop: perceive, remember, plan, act, reflect.</strong>
</div>
</article>
</aside>
</div>

<div class="ts-takeaway">Agentic AI is the bridge from generative models to broader intelligent systems.</div>
</section>

---
class: future-world-models-slide
---

<section class="slide-shell transformer-section frontier-section future76">
<div class="ts-header">
<span>FUTURE AI FRONTIERS</span>
<h1>World Models</h1>
<p>AI systems that learn internal representations of how the world changes over time.</p>
</div>

<div class="ff76-redesign-layout">
<article class="ts-panel ff76-world-panel">
<img :src="'/images/future-earth-apollo17.jpg'" alt="NASA Apollo 17 image of Earth from Wikimedia Commons">
<div class="ff76-world-copy">
<span>observed world</span>
<strong>The model learns a compact mental map of reality.</strong>
</div>
</article>

<article class="ts-panel ff76-simulator-panel">
<div class="ff76-simulator-head">
<span>internal simulator</span>
<strong>Observation becomes prediction.</strong>
<p>A world model compresses experience into a representation that can be rolled forward in time.</p>
</div>

<div class="ff76-simulator-flow">
<article class="observe"><span>01</span><strong>Observe</strong><p>state, objects, context</p></article>
<i></i>
<article class="latent"><span>02</span><strong>Latent model</strong><p>hidden dynamics</p></article>
<i></i>
<article class="future"><span>03</span><strong>Imagine</strong><p>possible futures</p></article>
</div>

<div class="ff76-futures">
<article><span>t + 1</span><strong>likely next state</strong></article>
<article><span>t + 2</span><strong>change in motion</strong></article>
<article><span>t + 3</span><strong>risk or opportunity</strong></article>
</div>

<article class="ff76-bottom-note">
<span>why it matters</span>
<strong>Prediction becomes the substrate for planning.</strong>
</article>
</article>
</div>

<div class="ts-takeaway">A world model lets AI imagine what may happen next.</div>
</section>

---
class: frontier-case-study-slide
---

<section class="slide-shell transformer-section frontier-section frontier-case-study">
<div class="ts-header">
<span>CASE STUDY</span>
<h1>Case Study — NVIDIA Cosmos</h1>
<p>World foundation models for synthetic data, simulation, and physical AI training.</p>
</div>

<div class="case-study-layout">
<article class="ts-panel case-study-visual">
<div class="case-study-visual-image logo">
<img :src="'/images/case-nvidia-logo.svg'" alt="NVIDIA logo">
</div>
<div class="case-study-image-label">
<span>world foundation models</span>
<strong>Synthetic worlds for training physical AI.</strong>
</div>
</article>

<aside class="case-study-cards">
<article class="ts-panel"><span>technology used</span><strong>World models</strong><p>Cosmos provides foundation models and tools for generating realistic world states and video-like sensor scenarios.</p></article>
<article class="ts-panel"><span>how it is used</span><strong>Simulation before deployment</strong><p>Robotics and autonomous-system teams can expand training data with synthetic scenes, rare events, and controlled variations.</p></article>
<article class="ts-panel"><span>why it matters</span><strong>Safer physical AI training</strong><p>Systems can practice risky or expensive situations in simulation before meeting the real world.</p></article>
</aside>
</div>

<div class="ts-takeaway">Synthetic worlds let robots learn before they enter the real world.</div>
</section>

---
class: future-world-rl-slide
---

<section class="slide-shell transformer-section frontier-section future77">
<div class="ts-header">
<span>MODEL-BASED RL</span>
<h1>World Models and Reinforcement Learning</h1>
<p>Reinforcement learning matters because an intelligent system must choose actions, not only predict outcomes.</p>
</div>

<div class="ff77-redesign-layout">
<article class="ts-panel ff77-image-panel">
<div class="ff77-image-head">
<span>reinforcement loop</span>
<strong>Actions are judged by consequences.</strong>
</div>
<div class="ff77-image-frame">
<img :src="'/images/future-rl-diagram.svg'" alt="Reinforcement learning diagram from Wikimedia Commons">
</div>
</article>

<article class="ts-panel ff77-planning-panel">
<div class="ff77-planning-head">
<span>model-based RL</span>
<strong>Use the world model to plan before acting.</strong>
</div>

<div class="ff77-planning-steps">
<article><span>01 observe</span><strong>Read current state</strong><p>What is true now?</p></article>
<article><span>02 simulate</span><strong>Roll out futures</strong><p>What could happen?</p></article>
<article><span>03 evaluate</span><strong>Estimate reward</strong><p>Which future is better?</p></article>
<article><span>04 act</span><strong>Choose an action</strong><p>Try the best move.</p></article>
<article><span>05 learn</span><strong>Update from feedback</strong><p>Correct the model.</p></article>
</div>

<article class="ff77-bottom-note">
<span>planning advantage</span>
<strong>The agent can test actions in imagination before testing them in the world.</strong>
</article>
</article>
</div>

<div class="ts-takeaway">World models make planning possible before acting.</div>
</section>

---
class: frontier-case-study-slide
---

<section class="slide-shell transformer-section frontier-section frontier-case-study">
<div class="ts-header">
<span>CASE STUDY</span>
<h1>Case Study — DeepMind Planning</h1>
<p>Dreamer and AlphaGo-style systems show how models can evaluate futures before acting.</p>
</div>

<div class="case-study-layout">
<article class="ts-panel case-study-visual">
<div class="case-study-visual-image logo">
<img :src="'/images/case-deepmind-logo.svg'" alt="Google DeepMind logo">
</div>
<div class="case-study-image-label">
<span>model-based learning</span>
<strong>Imagine rollouts, score actions, improve policy.</strong>
</div>
</article>

<aside class="case-study-cards">
<article class="ts-panel"><span>technology used</span><strong>World models + RL</strong><p>Dreamer learns compact dynamics and trains behavior from imagined trajectories; AlphaGo combined search, value estimates, and policy learning.</p></article>
<article class="ts-panel"><span>how it is used</span><strong>Plan in latent futures</strong><p>The agent simulates possible outcomes, compares expected rewards, and updates the policy before or between real actions.</p></article>
<article class="ts-panel"><span>why it matters</span><strong>Fewer costly trials</strong><p>Planning reduces blind trial-and-error by testing decisions in an internal model first.</p></article>
</aside>
</div>

<div class="ts-takeaway">Planning is learning to test actions in imagination before acting.</div>
</section>

---
class: future-embodied-ai-slide
---

<section class="slide-shell transformer-section frontier-section future78">
<div class="ts-header">
<span>PHYSICAL INTELLIGENCE</span>
<h1>Embodied AI</h1>
<p>AI inside robots and physical systems must connect perception, action, environment, and feedback.</p>
</div>

<div class="ff78-redesign-layout">
<article class="ts-panel ff78-embodied-hero">
<img :src="'/images/agent-robonaut-working.jpg'" alt="NASA Robonaut 2 working image from Wikimedia Commons">
<div class="ff78-hero-overlay">
<span>embodied agent</span>
<strong>Intelligence must pass through a body.</strong>
</div>
</article>

<article class="ts-panel ff78-control-loop">
<div class="ff78-loop-head">
<span>perception-action loop</span>
<strong>Embodied AI closes the loop with the physical world.</strong>
</div>

<div class="ff78-loop-steps">
<article><span>01 sensors</span><strong>Perceive</strong><p>vision, touch, position, spatial context</p></article>
<article><span>02 world state</span><strong>Understand</strong><p>estimate what is happening now</p></article>
<article><span>03 controller</span><strong>Decide</strong><p>choose a safe next action</p></article>
<article><span>04 actuators</span><strong>Act</strong><p>move, grasp, navigate, manipulate</p></article>
</div>

<article class="ff78-constraint-strip">
<span>real-world constraints</span>
<strong>Delay, uncertainty, friction, and safety make embodiment harder than software.</strong>
</article>
</article>
</div>

<div class="ts-takeaway">Embodied AI connects intelligence to the physical world.</div>
</section>

---
class: frontier-case-study-slide
---

<section class="slide-shell transformer-section frontier-section frontier-case-study">
<div class="ts-header">
<span>CASE STUDY</span>
<h1>Case Study — Tesla Optimus</h1>
<p>Humanoid robotics frames AI as perception, control, feedback, and safe physical action.</p>
</div>

<div class="case-study-layout">
<article class="ts-panel case-study-visual">
<div class="case-study-visual-image logo">
<img :src="'/images/case-tesla-logo.svg'" alt="Tesla logo">
</div>
<div class="case-study-image-label">
<span>embodied robotics</span>
<strong>AI must turn perception into motion.</strong>
</div>
</article>

<aside class="case-study-cards">
<article class="ts-panel"><span>technology used</span><strong>Vision + control policies</strong><p>Optimus is presented as a humanoid platform using perception, learned control, and robotics data to perform physical tasks.</p></article>
<article class="ts-panel"><span>how it is used</span><strong>Perceive, move, correct</strong><p>The robot estimates the scene, selects motions, observes results, and adjusts behavior through continuous feedback.</p></article>
<article class="ts-panel"><span>why it matters</span><strong>General-purpose physical work</strong><p>Humanoid robots test whether AI can operate in spaces designed for people, tools, and everyday tasks.</p></article>
</aside>
</div>

<div class="ts-takeaway">Embodied AI turns predictions into physical movement.</div>
</section>

---
class: future-physical-intelligence-slide
---

<section class="slide-shell transformer-section frontier-section future79">
<div class="ts-header">
<span>AGENTS TO ROBOTS</span>
<h1>From Agents to Physical Intelligence</h1>
<p>Software agents use tools. Embodied agents use bodies, sensors, actuators, and safety constraints.</p>
</div>

<div class="ff79-redesign-layout">
<article class="ts-panel ff79-compare-card ff79-digital">
<div class="ff79-card-image">
<img :src="'/images/genai-taskmatrix-ai.jpg'" alt="TaskMatrix.AI systems diagram from Wikimedia Commons">
</div>
<div class="ff79-card-copy">
<span>digital agent</span>
<strong>Acts through software tools</strong>
<p>Searches, writes, calls APIs, modifies files, and coordinates workflows.</p>
<div class="ff79-chip-row"><b>APIs</b><b>files</b><b>web</b></div>
</div>
</article>

<div class="ff79-bridge-redesign">
<span>same control logic</span>
<strong>goal</strong>
<i></i>
<strong>action</strong>
<i></i>
<strong>feedback</strong>
</div>

<article class="ts-panel ff79-compare-card ff79-physical">
<div class="ff79-card-image">
<img :src="'/images/cnn-autonomous-car.jpg'" alt="Autonomous vehicle photo from Wikimedia Commons">
</div>
<div class="ff79-card-copy">
<span>physical agent</span>
<strong>Acts through sensors and actuators</strong>
<p>Moves through space, reacts to obstacles, and manages physical risk.</p>
<div class="ff79-chip-row"><b>sensors</b><b>motion</b><b>safety</b></div>
</div>
</article>
</div>

<div class="ts-takeaway">The next frontier is not only thinking, but acting safely in the world.</div>
</section>

---
class: frontier-case-study-slide
---

<section class="slide-shell transformer-section frontier-section frontier-case-study">
<div class="ts-header">
<span>CASE STUDY</span>
<h1>Case Study — Waymo</h1>
<p>Autonomous driving is embodied AI under strict safety and real-world constraints.</p>
</div>

<div class="case-study-layout">
<article class="ts-panel case-study-visual photo">
<div class="case-study-visual-image">
<img :src="'/images/cnn-autonomous-car.jpg'" alt="Waymo autonomous vehicle photo from Wikimedia Commons">
</div>
<div class="case-study-image-label">
<span>autonomous driving</span>
<strong>Perception, prediction, planning, validation.</strong>
</div>
</article>

<aside class="case-study-cards">
<article class="ts-panel"><span>technology used</span><strong>Sensor-rich autonomy</strong><p>Cameras, lidar, radar, maps, and learned perception help the vehicle understand road users and scene geometry.</p></article>
<article class="ts-panel"><span>how it is used</span><strong>Plan safe maneuvers</strong><p>The system predicts how traffic may evolve, chooses a trajectory, and continuously checks the result against the environment.</p></article>
<article class="ts-panel"><span>why it matters</span><strong>Safety at physical scale</strong><p>Driving shows why embodied AI needs validation, redundancy, monitoring, and conservative decision-making.</p></article>
</aside>
</div>

<div class="ts-takeaway">Autonomous driving turns AI decisions into accountable physical behavior.</div>
</section>

---
class: future-federated-edge-slide
---

<section class="slide-shell transformer-section frontier-section future80">
<div class="ts-header">
<span>DISTRIBUTED INTELLIGENCE</span>
<h1>Federated & Edge AI</h1>
<p>AI can run or learn near the data, instead of sending every signal back to a central cloud.</p>
</div>

<div class="ff80-redesign-layout">
<article class="ts-panel ff80-federated-panel">
<div class="ff80-panel-head">
<span>federated learning</span>
<strong>Train together without centralizing raw data.</strong>
<p>Devices keep private examples locally and share model updates instead.</p>
</div>
<div class="ff80-diagram-frame">
<img :src="'/images/future-federated-learning.png'" alt="Federated learning process diagram from Wikimedia Commons">
</div>
<div class="ff80-data-strip">
<b>local data</b><i></i><b>model update</b><i></i><b>shared model</b>
</div>
</article>

<aside class="ff80-edge-panel">
<article class="ts-panel ff80-edge-visual">
<img :src="'/images/future-edge-computing.png'" alt="Edge computing and IoT diagram from Wikimedia Commons">
<div>
<span>edge AI</span>
<strong>Intelligence moves closer to sensors.</strong>
<p>Inference can happen on phones, cameras, vehicles, and industrial devices.</p>
</div>
</article>

<div class="ff80-benefit-grid">
<article class="ts-panel"><span>privacy</span><strong>keep data local</strong></article>
<article class="ts-panel"><span>latency</span><strong>respond in real time</strong></article>
<article class="ts-panel"><span>personalization</span><strong>adapt to context</strong></article>
<article class="ts-panel"><span>resilience</span><strong>work with weak connectivity</strong></article>
</div>
</aside>
</div>

<div class="ts-takeaway">Not all intelligence will live in the cloud.</div>
</section>

---
class: frontier-case-study-slide
---

<section class="slide-shell transformer-section frontier-section frontier-case-study">
<div class="ts-header">
<span>CASE STUDY</span>
<h1>Case Study — Google Gboard</h1>
<p>Federated learning improves keyboard models while keeping raw typing data on devices.</p>
</div>

<div class="case-study-layout">
<article class="ts-panel case-study-visual">
<div class="case-study-visual-image logo">
<img :src="'/images/google-logo-official.png'" alt="Google logo">
</div>
<div class="case-study-image-label">
<span>federated learning</span>
<strong>On-device updates for better suggestions.</strong>
</div>
</article>

<aside class="case-study-cards">
<article class="ts-panel"><span>technology used</span><strong>Local training</strong><p>Phones compute small model updates from local interactions instead of uploading raw personal typing data.</p></article>
<article class="ts-panel"><span>how it is used</span><strong>Aggregate improvements</strong><p>Updates from many devices are combined to improve shared prediction and suggestion models.</p></article>
<article class="ts-panel"><span>why it matters</span><strong>Privacy-aware personalization</strong><p>The product can learn from usage patterns while reducing the need to centralize sensitive text.</p></article>
</aside>
</div>

<div class="ts-takeaway">Edge learning improves products while keeping raw data closer to users.</div>
</section>

---
class: future-safety-slide
---

<section class="slide-shell transformer-section frontier-section future81">
<div class="ts-header">
<span>SAFETY LAYER</span>
<h1>AI Safety and Guardrails</h1>
<p>More autonomous systems need explicit control layers around models, tools, memory, and actions.</p>
</div>

<div class="ff81-redesign-layout">
<article class="ts-panel ff81-safety-panel">
<div class="ff81-safety-head">
<img :src="'/images/llm-caution-warning-sign.svg'" alt="Public-domain caution warning sign from Wikimedia Commons">
<div>
<span>guardrail system</span>
<strong>Autonomy needs checkpoints before action.</strong>
<p>Safety is a control layer around the model, not a paragraph after the model.</p>
</div>
</div>

<div class="ff81-pipeline">
<article><span>01 model</span><strong>Propose</strong><p>answer, plan, or action</p></article>
<i></i>
<article><span>02 policy</span><strong>Filter</strong><p>allowed, blocked, or ask</p></article>
<i></i>
<article><span>03 verify</span><strong>Check</strong><p>facts, code, side effects</p></article>
<i></i>
<article><span>04 action</span><strong>Monitor</strong><p>tool use with audit trail</p></article>
</div>
</article>

<aside class="ts-panel ff81-control-panel">
<div class="ff81-control-head">
<span>control layers</span>
<strong>Guardrails reduce risk before, during, and after execution.</strong>
</div>
<div class="ff81-control-grid">
<article><strong>Policies</strong><p>clear boundaries for allowed actions</p></article>
<article><strong>Verification</strong><p>evidence checks before trust</p></article>
<article><strong>Human oversight</strong><p>approval for consequential choices</p></article>
<article><strong>Monitoring</strong><p>detect drift, misuse, and failures</p></article>
</div>
</aside>
</div>

<div class="ts-takeaway">Powerful AI systems need boundaries, feedback, and accountability.</div>
</section>

---
class: frontier-case-study-slide
---

<section class="slide-shell transformer-section frontier-section frontier-case-study">
<div class="ts-header">
<span>CASE STUDY</span>
<h1>Case Study — AWS Bedrock Guardrails</h1>
<p>Enterprise guardrails add configurable policy and monitoring around foundation-model applications.</p>
</div>

<div class="case-study-layout">
<article class="ts-panel case-study-visual">
<div class="case-study-visual-image logo">
<img :src="'/images/case-aws-logo.svg'" alt="AWS logo">
</div>
<div class="case-study-image-label">
<span>safety controls</span>
<strong>Policy boundaries for model-powered apps.</strong>
</div>
</article>

<aside class="case-study-cards">
<article class="ts-panel"><span>technology used</span><strong>Guardrail policies</strong><p>Bedrock Guardrails lets teams configure content filters, denied topics, and sensitive-information handling.</p></article>
<article class="ts-panel"><span>how it is used</span><strong>Filter and monitor</strong><p>Controls can be applied around prompts and responses so applications follow organization-specific rules.</p></article>
<article class="ts-panel"><span>why it matters</span><strong>Operational trust</strong><p>Autonomous systems need repeatable safety controls, logging, and human oversight before production use.</p></article>
</aside>
</div>

<div class="ts-takeaway">Guardrails turn model behavior into an operational control surface.</div>
</section>

---
class: future-stack-slide
---

<section class="slide-shell transformer-section frontier-section future82">
<div class="ts-header">
<span>SYSTEM ARCHITECTURE</span>
<h1>The Future AI Stack</h1>
<p>Future AI will combine models, tools, memory, world models, edge deployment, and safety into layered systems.</p>
</div>

<div class="ff82-redesign-layout">
<article class="ts-panel ff82-stack-redesign">
<div class="ff82-stack-head">
<span>layered system</span>
<strong>Future AI is an architecture, not a single model.</strong>
</div>
<div class="ff82-stack-layers">
<div class="ff82-system-layer safety"><b>Safety + human oversight</b><small>policies, audit, approval</small></div>
<div class="ff82-system-layer edge"><b>Edge / federated deployment</b><small>privacy, latency, local adaptation</small></div>
<div class="ff82-system-layer world"><b>World models + planning</b><small>simulate futures before acting</small></div>
<div class="ff82-system-layer agents"><b>Agents + tools + memory</b><small>action loops around the model</small></div>
<div class="ff82-system-layer foundation"><b>Foundation models</b><small>language, vision, multimodal reasoning</small></div>
</div>
</article>

<aside class="ff82-system-panel">
<div class="ts-panel ff82-system-image">
<img :src="'/images/agent-genai-agent.png'" alt="GenAI agent architecture diagram from Wikimedia Commons">
</div>
<article class="ts-panel ff82-system-note">
<span>systems view</span>
<strong>Capabilities emerge from how models connect to tools, memory, deployment, and control.</strong>
</article>
</aside>
</div>

<div class="ts-takeaway">Future AI will be a system, not a single model.</div>
</section>

---
class: frontier-case-study-slide
---

<section class="slide-shell transformer-section frontier-section frontier-case-study">
<div class="ts-header">
<span>CASE STUDY</span>
<h1>Case Study — GitHub Copilot</h1>
<p>A deployed AI stack combines foundation models, code context, tools, workflow integration, and controls.</p>
</div>

<div class="case-study-layout">
<article class="ts-panel case-study-visual">
<div class="case-study-visual-image logo dark-logo">
<img :src="'/images/case-github-logo.svg'" alt="GitHub logo">
</div>
<div class="case-study-image-label">
<span>developer assistant</span>
<strong>Foundation model embedded in the coding workflow.</strong>
</div>
</article>

<aside class="case-study-cards">
<article class="ts-panel"><span>technology used</span><strong>LLM + code context</strong><p>Copilot uses editor, repository, and conversational context to generate suggestions, explanations, and code changes.</p></article>
<article class="ts-panel"><span>how it is used</span><strong>Assist the workflow</strong><p>The assistant supports completion, chat, review, documentation, and increasingly agentic coding tasks.</p></article>
<article class="ts-panel"><span>why it matters</span><strong>Stack, not just model</strong><p>Usefulness comes from connecting the model to tools, files, permissions, feedback, and safety settings.</p></article>
</aside>
</div>

<div class="ts-takeaway">Copilot shows how AI becomes useful when embedded in the work system.</div>
</section>

---
class: future-next-slide
---

<section class="slide-shell transformer-section frontier-section future83">
<div class="ts-header">
<span>WHAT COMES NEXT?</span>
<h1>Capability Plus Control</h1>
<p>The frontier is not only bigger models. It is the balance between autonomy, grounding, deployment, and governance.</p>
</div>

<div class="ff83-redesign-layout">
<article class="ts-panel ff83-frontier-hero">
<img :src="'/images/future-earth-apollo17.jpg'" alt="NASA Apollo 17 image of Earth from Wikimedia Commons">
<div class="ff83-hero-copy">
<span>frontier map</span>
<strong>Capability matters only when it is grounded, deployed, and governed.</strong>
</div>
</article>

<div class="ff83-quadrants">
<article class="ts-panel ff83-quadrant">
<img :src="'/images/llm-datacenter-server-racks.jpg'" alt="Datacenter server racks photo from Wikimedia Commons">
<div><span>models</span><strong>More capable</strong><p>scale, reasoning support, long context</p></div>
</article>
<article class="ts-panel ff83-quadrant">
<img :src="'/images/agent-generative-architecture.png'" alt="Generative agent architecture figure from Wikimedia Commons">
<div><span>agents</span><strong>More autonomous</strong><p>tools, memory, planning, collaboration</p></div>
</article>
<article class="ts-panel ff83-quadrant">
<img :src="'/images/agent-robonaut-working.jpg'" alt="NASA Robonaut 2 working image from Wikimedia Commons">
<div><span>embodied</span><strong>More physical</strong><p>robots, vehicles, labs, factories</p></div>
</article>
<article class="ts-panel ff83-quadrant">
<img :src="'/images/llm-caution-warning-sign.svg'" alt="Public-domain caution warning sign from Wikimedia Commons">
<div><span>governance</span><strong>More controlled</strong><p>verification, oversight, monitoring</p></div>
</article>
</div>
</div>

<div class="ts-takeaway">The future of AI is capability plus control.</div>
</section>

---
class: frontier-case-study-slide
---

<section class="slide-shell transformer-section frontier-section frontier-case-study">
<div class="ts-header">
<span>CASE STUDY</span>
<h1>Case Study — Morgan Stanley + OpenAI</h1>
<p>Enterprise assistants connect models to governed internal knowledge and expert workflows.</p>
</div>

<div class="case-study-layout">
<article class="ts-panel case-study-visual">
<div class="case-study-visual-image logo">
<img :src="'/images/case-morganstanley-logo.svg'" alt="Morgan Stanley logo">
</div>
<div class="case-study-image-label">
<span>enterprise assistant</span>
<strong>Retrieval, governance, and advisor support.</strong>
</div>
</article>

<aside class="case-study-cards">
<article class="ts-panel"><span>technology used</span><strong>LLM + retrieval</strong><p>The assistant connects language-model interaction to internal research, documents, and knowledge bases.</p></article>
<article class="ts-panel"><span>how it is used</span><strong>Support expert work</strong><p>Advisors can ask questions, search institutional knowledge, and surface relevant material faster.</p></article>
<article class="ts-panel"><span>why it matters</span><strong>Governed knowledge access</strong><p>Enterprise AI succeeds when it combines useful answers with permissioning, auditability, and human judgment.</p></article>
</aside>
</div>

<div class="ts-takeaway">Enterprise assistants combine retrieval, governance, and human expertise.</div>
</section>

---
class: future-synthesis-slide
---

<section class="slide-shell transformer-section frontier-section future84">
<div class="ts-header">
<span>FINAL SYNTHESIS</span>
<h1>From Perceptron to Agentic Systems</h1>
<p>AI evolved from simple decision boundaries to systems that perceive, generate, plan, and act.</p>
</div>

<div class="ff84-redesign-layout">
<article class="ts-panel ff84-image-band">
<figure><img :src="'/images/biological-neuron-vs-perceptron.png'" alt="Biological neuron and perceptron image from Wikimedia Commons"><figcaption>early neural ideas</figcaption></figure>
<figure><img :src="'/images/attention-paper-first-page.png'" alt="Attention Is All You Need paper first page"><figcaption>transformer era</figcaption></figure>
<figure><img :src="'/images/genai-dalle-sample-grid.png'" alt="DALL-E sample grid from Wikimedia Commons"><figcaption>generative systems</figcaption></figure>
<figure><img :src="'/images/agent-robonaut-working.jpg'" alt="NASA Robonaut 2 working image from Wikimedia Commons"><figcaption>action in the world</figcaption></figure>
</article>

<article class="ts-panel ff84-synthesis-roadmap">
<div class="ff84-milestone"><span>01</span><strong>Perceptrons</strong><p>linear decision boundaries</p></div>
<i></i>
<div class="ff84-milestone"><span>02</span><strong>Deep learning</strong><p>learned representations</p></div>
<i></i>
<div class="ff84-milestone"><span>03</span><strong>Transformers</strong><p>attention and scale</p></div>
<i></i>
<div class="ff84-milestone"><span>04</span><strong>Generative agents</strong><p>create, use tools, remember</p></div>
<i></i>
<div class="ff84-milestone"><span>05</span><strong>World systems</strong><p>simulate, plan, act safely</p></div>
</article>
</div>

<div class="ts-takeaway">AI evolved from simple decision boundaries to systems that perceive, generate, plan, and act.</div>
</section>
