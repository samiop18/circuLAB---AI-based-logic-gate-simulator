<p>
  <strong>CircuLab</strong> is an innovative, web-based digital circuit simulator designed to transform the way students and engineers design and learn digital logic. Unlike traditional simulators, CircuLab features an integrated Artificial Intelligence engine that provides <strong>predictive optimization</strong> and <strong>automatic circuit generation</strong>, all accessible instantly in a single browser file.
</p>

<h2>Project Innovation & Purpose</h2>
<p>
  The traditional digital design workflow involves tedious manual simplification and verification, often resulting in inefficient circuits. CircuLab solves the guidance gap by placing an optimization engine directly at the user's fingertips. The project's core purpose is to offer a professional-grade, glitch-free interactive canvas combined with AI to enforce efficiency and provide instant solutions.
</p>

<h2>Key Features (Proteus-Grade Experience)</h2>
<p>CircuLab is built as a Single-Page Application (SPA) prioritizing performance and usability, replicating core features found in high-end tools:</p>

<h3>Canvas Interactivity</h3>
<ul>
  <li>
    <strong>Select/Copy/Paste:</strong> Fully functional component manipulation, including **Ctrl+C / Ctrl+V** keyboard shortcuts for efficiency.
  </li>
  <li>
    <strong>Action History:</strong> Functional **Undo/Redo** system powered by a JavaScript Action History Stack.
  </li>
  <li>
    <strong>Glitch-Free Wiring:</strong> Implements robust logic for creating reliable, **90° angle wires** with proper grid alignment.
  </li>
  <li>
    <strong>Real-Time Simulation:</strong> Instantaneous, event-driven logic propagation upon input change, with **Neon Green** visual feedback.
  </li>
</ul>

<h3>AI & Analysis Tools</h3>
<ul>
  <li>
    <strong>Predictive Optimization:</strong> Integrates the **Quine-McCluskey Algorithm** to analyze the circuit and suggest the minimum gate equivalent.
  </li>
  <li>
    <strong>Text-to-Circuit Generator:</strong> Users input natural language prompts (e.g., "Design a half adder") to **automatically generate and draw the schematic** onto the canvas.
  </li>
  <li>
    <strong>Comprehensive Analysis:</strong> Includes a <strong>"RUN/ANALYZE"</strong> feature to instantly generate the **complete Truth Table**.
  </li>
</ul>

<h3>Design & Structure</h3>
<ul>
  <li>
    <strong>Single-File Application:</strong> The entire project is self-contained within **one <code>index.html</code> file** for ultimate portability and zero external dependencies.
  </li>
  <li>
    <strong>Export Functionality:</strong> Ability to download the circuit design in a standardized format, analogous to a **Proteus export file format**.
  </li>
</ul>

<h2>Technology Stack</h2>
<p>The project utilizes an efficient and modern stack:</p>
<ul>
  <li>
    <strong>Frontend/UI:</strong> Pure **HTML5/CSS3/JavaScript** for core logic and interactivity.
  </li>
  <li>
    <strong>Drawing/Graphics:</strong> **Canvas API** for high-performance, smooth rendering of all components and wires.
  </li>
  <li>
    <strong>Simulation Core:</strong> JavaScript implementation of **Topological Sort** on the circuit's DAG (Directed Acyclic Graph) for accurate evaluation.
  </li>
  <li>
    <strong>Optimization Core:</strong> JavaScript implementation of the **Quine-McCluskey Algorithm**.
  </li>
</ul>

<h2>Quick Start</h2>
<p>1. <strong>Clone the repository.</strong></p>
<p>2. <strong>Open the file:</strong> Simply open the <code>index.html</code> file in any modern web browser.</p>

<p>***</p>
<p>Created by Samitesh Panda</p>
