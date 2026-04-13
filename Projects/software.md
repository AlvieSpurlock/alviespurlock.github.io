<link rel="stylesheet" href="/assets/css/style.css">

<div class="navbar">
  <a href="/index.html" class="nav-brand">Alvie Spurlock</a>
  <div class="nav-right">
    <a href="/Projects/games.html" class="nav-game">Game Development</a>
    <a href="/Projects/software.html" class="nav-soft">Software Engineering</a>
    <a href="/about.html">About</a>
  </div>
</div>

<div class="page-header">
  <p class="page-eyebrow eyebrow-soft">Discipline 02</p>
  <h1>Software Engineering</h1>
  <p class="lead">Developer tools, simulation engines, and utility libraries in C++ and Python. Built for clarity, extensibility, and real problems — not for school.</p>
</div>

<div class="stat-bar">
  <div class="stat">
    <div class="stat-value">6+</div>
    <div class="stat-label">Active Projects</div>
  </div>
  <div class="stat">
    <div class="stat-value">1,364</div>
    <div class="stat-label">MathCore Functions</div>
  </div>
  <div class="stat">
    <div class="stat-value">225k</div>
    <div class="stat-label">Monte Carlo Trials</div>
  </div>
  <div class="stat">
    <div class="stat-value">C++ · Py</div>
    <div class="stat-label">Primary Languages</div>
  </div>
</div>

<div class="section-label">
  <span class="label-tag label-cpp">C++</span> Systems, simulators &amp; desktop tools
</div>

<div class="cards-grid">

  <div class="card card-cpp">
    <img src="../Images/MC.png" alt="TTRPG Combat Balance Simulator">
    <div class="card-body">
      <p class="card-lang cpp">C++ · wxWidgets · MCI/winmm</p>
      <h3>TTRPG Combat Balance Simulator</h3>
      <p>A D&D-themed desktop simulator running 225,000 Monte Carlo trials to estimate party win probability against any enemy configuration. Full GUI, audio engine, sprite VFX, and save/load persistence.</p>
      <ul class="highlights">
        <li>150 batches × 1,500 combats per run, threaded off the UI</li>
        <li>4d6-drop-lowest character creation with per-stat animations</li>
        <li>MCI/winmm audio — looping music and pooled SFX aliases</li>
        <li>Full save/load to %AppData% via structured CSV</li>
      </ul>
      <div class="card-chips">
        <span class="chip">Monte Carlo</span>
        <span class="chip">wxWidgets GUI</span>
        <span class="chip">Simulation</span>
        <span class="chip">D&D</span>
      </div>
      <div class="card-actions">
        <a href="https://github.com/AlvieSpurlock/TTRPGCombatBalanceSimulator" class="btn btn-cpp" target="_blank">GitHub →</a>
      </div>
    </div>
  </div>

  <div class="card card-cpp">
    <img src="../Images/AL.png" alt="Asset Logger">
    <div class="card-body">
      <p class="card-lang cpp">C++ · wxWidgets</p>
      <h3>Asset Logger</h3>
      <p>A desktop tool for indie developers preparing Steam submissions and managing asset inventory. Guides through structured asset entry and exports a clean, Steam-ready CSV.</p>
      <ul class="highlights">
        <li>Form-driven GUI with live validation feedback</li>
        <li>Fields: location, purpose, author, platform, license</li>
        <li>Overwrite protection and multi-asset session support</li>
      </ul>
      <div class="card-chips">
        <span class="chip">wxWidgets GUI</span>
        <span class="chip">Indie Dev Tool</span>
        <span class="chip">Steam</span>
        <span class="chip">CSV Export</span>
      </div>
      <div class="card-actions">
        <a href="https://github.com/AlvieSpurlock/AssetLogger" class="btn btn-cpp" target="_blank">GitHub →</a>
      </div>
    </div>
  </div>

  <div class="card card-cpp">
    <div class="card-placeholder">🧮</div>
    <div class="card-body">
      <p class="card-lang cpp">C++ · wxWidgets</p>
      <h3>Calculator</h3>
      <p>A desktop calculator built on a custom C++ expression engine with a full wxWidgets GUI. Explores event-driven UI design, input parsing, and operator precedence as a proper standalone app.</p>
      <ul class="highlights">
        <li>Custom expression parser with correct operator precedence</li>
        <li>Keyboard and button input via wxWidgets Bind()</li>
        <li>Foundation for future scientific and programmer modes</li>
      </ul>
      <div class="card-chips">
        <span class="chip">wxWidgets</span>
        <span class="chip">Expression Parser</span>
        <span class="chip">Event-Driven</span>
      </div>
      <div class="card-actions">
        <a href="https://github.com/AlvieSpurlock/Calculator_CPP" class="btn btn-cpp" target="_blank">GitHub →</a>
      </div>
    </div>
  </div>

</div>

<div class="section-label">
  <span class="label-tag label-soft">Python</span> Libraries, tools &amp; automation
</div>

<div class="cards-grid">

  <div class="card card-soft">
    <img src="../Images/P_MC.png" alt="MathCore">
    <div class="card-body">
      <p class="card-lang soft">Python · Tkinter · Pillow</p>
      <h3>MathCore</h3>
      <p>A modular math computation library covering 23 domains and 1,364 callable functions — and a generative art engine that turns every calculation into a unique 3000×3000px artwork.</p>
      <ul class="highlights">
        <li>23 modules: Algebra, Calculus, Topology, Physics, and more</li>
        <li>Art engine maps function class and results to visual parameters</li>
        <li>8 visual profiles, rarity system from Common to Legendary</li>
        <li>Full Tkinter UI with searchable sidebar and session history</li>
      </ul>
      <div class="card-chips">
        <span class="chip">1,364 Functions</span>
        <span class="chip">Generative Art</span>
        <span class="chip">23 Modules</span>
        <span class="chip">Tkinter</span>
      </div>
      <div class="card-actions">
        <a href="https://github.com/AlvieSpurlock/MathCore" class="btn btn-soft" target="_blank">GitHub →</a>
      </div>
    </div>
  </div>

  <div class="card card-soft">
    <img src="../Images/SA_UI.jpg" alt="SocialsAgent">
    <div class="card-body">
      <p class="card-lang soft">Python · ML · Open Source</p>
      <h3>SocialsAgent</h3>
      <p>An intelligent social automation tool that creates, optimizes, and posts content across multiple platforms with minimal input. Entirely free and open source.</p>
      <ul class="highlights">
        <li>Multi-platform auto-posting and listing</li>
        <li>ML-trained AI-generated captions, tags, and descriptions</li>
        <li>Engagement-aware scheduling and optimization</li>
      </ul>
      <div class="card-chips">
        <span class="chip">ML / AI</span>
        <span class="chip">Automation</span>
        <span class="chip">Multi-Platform</span>
        <span class="chip">Open Source</span>
      </div>
      <div class="card-actions">
        <a href="https://github.com/AlvieSpurlock/SocialsAgent" class="btn btn-soft" target="_blank">GitHub →</a>
      </div>
    </div>
  </div>

</div>

<div class="section-label">
  <span class="label-tag label-soft">Python Utilities</span> Lightweight standalone tools
</div>

<div class="util-grid">

  <div class="util-card">
    <p class="util-lang py">Python</p>
    <h3>PyCommand</h3>
    <p>A lightweight command routing system. Clean, simple, and built for extensibility.</p>
    <a href="https://github.com/AlvieSpurlock/PyCommand" target="_blank">GitHub →</a>
  </div>

  <div class="util-card">
    <p class="util-lang py">Python</p>
    <h3>PyError</h3>
    <p>Structured error-logging that captures exceptions with timestamps, file paths, and line numbers.</p>
    <a href="https://github.com/AlvieSpurlock/PyError" target="_blank">GitHub →</a>
  </div>

</div>

<div class="section-label">
  <span class="label-tag label-dim">Planned</span> Upcoming C++ projects
</div>

<div class="future-grid">
  <div class="future-item">
    <h4>File I/O Helper</h4>
    <p>Heavily simplified File I/O operations in C++.</p>
  </div>
  <div class="future-item">
    <h4>cRNG</h4>
    <p>RNG from simple dice rolls to a full Monte Carlo framework.</p>
  </div>
  <div class="future-item">
    <h4>cPhysics</h4>
    <p>Physics as easy as a few method calls.</p>
  </div>
  <div class="future-item">
    <h4>RPG Tool</h4>
    <p>Inventory, dialogue, quests, and AI as a reusable C++ framework.</p>
  </div>
</div>

<div class="site-footer">
  <p><a href="/index.html">← Back to Portfolio</a></p>
  <p><a href="https://github.com/AlvieSpurlock" target="_blank">github.com/AlvieSpurlock</a></p>
</div>
