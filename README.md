<div align="center">

<img src="assets/banner.svg" alt="Adrian - systems & performance tooling" width="100%"/>

</div>

<div style="border:1px solid #2c3454;border-radius:10px;overflow:hidden;background:#0d1117;">

<!-- window title bar -->
<div style="background:#161b22;border-bottom:1px solid #2c3454;padding:10px 16px;display:flex;align-items:center;gap:8px;">
  <span style="width:12px;height:12px;border-radius:50%;background:#ff5f57;display:inline-block;"></span>
  <span style="width:12px;height:12px;border-radius:50%;background:#febc2e;display:inline-block;"></span>
  <span style="width:12px;height:12px;border-radius:50%;background:#28c840;display:inline-block;"></span>
  <span style="margin-left:8px;font-family:Consolas,Menlo,monospace;font-size:13px;color:#8b949e;">adrian.ts - adrian</span>
</div>

<!-- editor content -->
<pre style="background:#0d1117;margin:0;padding:16px 0;color:#c9d1d9;font-family:Consolas,Menlo,monospace;font-size:13px;line-height:1.55;overflow-x:auto;">
<span style="color:#6e7681;">  1 | // adrian - systems &amp; performance tooling</span>
<span style="color:#6e7681;">  2 | // based in germany</span>
<span style="color:#6e7681;">  3 | </span>
<span style="color:#c9d1d9;">  4 | const</span> <span style="color:#79c0ff;">profile</span> <span style="color:#c9d1d9;">= {</span>
<span style="color:#c9d1d9;">  5 | </span><span style="color:#ff7b72;">  name</span><span style="color:#c9d1d9;">:</span> <span style="color:#a5d6ff;">'Adrian'</span><span style="color:#c9d1d9;">,</span>
<span style="color:#c9d1d9;">  6 | </span><span style="color:#ff7b72;">  focus</span><span style="color:#c9d1d9;">:</span> <span style="color:#a5d6ff;">'performance &amp; system tooling'</span><span style="color:#c9d1d9;">,</span>
<span style="color:#c9d1d9;">  7 | </span><span style="color:#ff7b72;">  platforms</span><span style="color:#c9d1d9;">:</span> <span style="color:#c9d1d9;">[</span><span style="color:#a5d6ff;">'Windows'</span><span style="color:#c9d1d9;">,</span> <span style="color:#a5d6ff;">'Linux'</span><span style="color:#c9d1d9;">],</span>
<span style="color:#c9d1d9;">  8 | </span><span style="color:#ff7b72;">  stack</span><span style="color:#c9d1d9;">:</span> <span style="color:#c9d1d9;">[</span><span style="color:#a5d6ff;">'Rust'</span><span style="color:#c9d1d9;">,</span> <span style="color:#a5d6ff;">'Tauri'</span><span style="color:#c9d1d9;">,</span> <span style="color:#a5d6ff;">'React'</span><span style="color:#c9d1d9;">,</span> <span style="color:#a5d6ff;">'TS'</span><span style="color:#c9d1d9;">,</span> <span style="color:#a5d6ff;">'Bash'</span><span style="color:#c9d1d9;">],</span>
<span style="color:#c9d1d9;">  9 | </span><span style="color:#ff7b72;">  build</span><span style="color:#c9d1d9;">:</span> <span style="color:#a5d6ff;">'tools I couldn't find done the way I wanted'</span><span style="color:#c9d1d9;">,</span>
<span style="color:#c9d1d9;"> 10 | </span><span style="color:#ff7b72;">  license</span><span style="color:#c9d1d9;">:</span> <span style="color:#a5d6ff;">'source-available, non-commercial; check each repo'</span><span style="color:#c9d1d9;">,</span>
<span style="color:#c9d1d9;"> 11 | };</span>
<span style="color:#6e7681;"> 12 | </span>
<span style="color:#6e7681;"> 13 | // -- repos -------------------------------------------------</span>
<span style="color:#c9d1d9;"> 14 | const</span> <span style="color:#79c0ff;">repos</span> <span style="color:#c9d1d9;">= [</span>
<span style="color:#c9d1d9;"> 15 |   {</span>
<span style="color:#c9d1d9;"> 16 |     </span><span style="color:#ff7b72;">name</span><span style="color:#c9d1d9;">:</span> <span style="color:#a5d6ff;">'ad-hyperoptimize'</span><span style="color:#c9d1d9;">,</span>
<span style="color:#c9d1d9;"> 17 |     </span><span style="color:#ff7b72;">what</span><span style="color:#c9d1d9;">:</span> <span style="color:#a5d6ff;">'Windows optimization suite (Tauri 2 + Rust + React)'</span><span style="color:#c9d1d9;">,</span>
<span style="color:#c9d1d9;"> 18 |     </span><span style="color:#ff7b72;">features</span><span style="color:#c9d1d9;">:</span> <span style="color:#a5d6ff;">'health scoring, live metrics, revertible tweaks'</span><span style="color:#c9d1d9;">,</span>
<span style="color:#c9d1d9;"> 19 |     </span><span style="color:#ff7b72;">motto</span><span style="color:#c9d1d9;">:</span> <span style="color:#a5d6ff;">'no snake oil, no telemetry'</span><span style="color:#c9d1d9;">,</span>
<span style="color:#c9d1d9;"> 20 |     </span><span style="color:#ff7b72;">url</span><span style="color:#c9d1d9;">:</span> <span style="color:#a5d6ff;">'https://github.com/zCrxticxl/ad-hyperoptimize'</span><span style="color:#c9d1d9;">,</span>
<span style="color:#c9d1d9;"> 21 |   },</span>
<span style="color:#c9d1d9;"> 22 |   {</span>
<span style="color:#c9d1d9;"> 23 |     </span><span style="color:#ff7b72;">name</span><span style="color:#c9d1d9;">:</span> <span style="color:#a5d6ff;">'adhyper-linux'</span><span style="color:#c9d1d9;">,</span>
<span style="color:#c9d1d9;"> 24 |     </span><span style="color:#ff7b72;">what</span><span style="color:#c9d1d9;">:</span> <span style="color:#a5d6ff;">'Linux updater, cleaner &amp; perf tuner'</span><span style="color:#c9d1d9;">,</span>
<span style="color:#c9d1d9;"> 25 |     </span><span style="color:#ff7b72;">features</span><span style="color:#c9d1d9;">:</span> <span style="color:#a5d6ff;">'15 modules, TUI, dry-run, fully revertible'</span><span style="color:#c9d1d9;">,</span>
<span style="color:#c9d1d9;"> 26 |     </span><span style="color:#ff7b72;">platforms</span><span style="color:#c9d1d9;">:</span> <span style="color:#a5d6ff;">'Arch / Debian / Fedora / openSUSE'</span><span style="color:#c9d1d9;">,</span>
<span style="color:#c9d1d9;"> 27 |     </span><span style="color:#ff7b72;">url</span><span style="color:#c9d1d9;">:</span> <span style="color:#a5d6ff;">'https://github.com/zCrxticxl/adhyper-linux'</span><span style="color:#c9d1d9;">,</span>
<span style="color:#c9d1d9;"> 28 |   },</span>
<span style="color:#c9d1d9;"> 29 |   {</span>
<span style="color:#c9d1d9;"> 30 |     </span><span style="color:#ff7b72;">name</span><span style="color:#c9d1d9;">:</span> <span style="color:#a5d6ff;">'adrice'</span><span style="color:#c9d1d9;">,</span>
<span style="color:#c9d1d9;"> 31 |     </span><span style="color:#ff7b72;">what</span><span style="color:#c9d1d9;">:</span> <span style="color:#a5d6ff;">'full desktop themes from a wallpaper, one-file TUI'</span><span style="color:#c9d1d9;">,</span>
<span style="color:#c9d1d9;"> 32 |     </span><span style="color:#ff7b72;">features</span><span style="color:#c9d1d9;">:</span> <span style="color:#a5d6ff;">'live previews, one-key fixes, day/night'</span><span style="color:#c9d1d9;">,</span>
<span style="color:#c9d1d9;"> 33 |     </span><span style="color:#ff7b72;">platforms</span><span style="color:#c9d1d9;">:</span> <span style="color:#a5d6ff;">'GNOME / KDE / Hyprland'</span><span style="color:#c9d1d9;">,</span>
<span style="color:#c9d1d9;"> 34 |     </span><span style="color:#ff7b72;">url</span><span style="color:#c9d1d9;">:</span> <span style="color:#a5d6ff;">'https://github.com/zCrxticxl/adrice'</span><span style="color:#c9d1d9;">,</span>
<span style="color:#c9d1d9;"> 35 |   },</span>
<span style="color:#c9d1d9;"> 36 | ];</span>
<span style="color:#6e7681;"> 37 | </span>
<span style="color:#6e7681;"> 38 | // also scattered around: R6 strategy planner, Tarkov stash scanner,</span>
<span style="color:#6e7681;"> 39 | // Twitch extension, game settings tools</span>
<span style="color:#6e7681;"> 40 | </span>
<span style="color:#6e7681;"> 41 | // -- outside of code ----------------------------------------</span>
<span style="color:#c9d1d9;"> 42 | const</span> <span style="color:#79c0ff;">personal</span> <span style="color:#c9d1d9;">= {</span>
<span style="color:#c9d1d9;"> 43 | </span><span style="color:#ff7b72;">  game</span><span style="color:#c9d1d9;">:</span> <span style="color:#a5d6ff;">'Rainbow Six Siege (competitive, team mgmt)'</span><span style="color:#c9d1d9;">,</span>
<span style="color:#c9d1d9;"> 44 | </span><span style="color:#ff7b72;">  origin</span><span style="color:#c9d1d9;">:</span> <span style="color:#a5d6ff;">'interest in input latency, frametimes &amp; DPC spikes'</span><span style="color:#c9d1d9;">,</span>
<span style="color:#c9d1d9;"> 45 | </span><span style="color:#ff7b72;">  setup</span><span style="color:#c9d1d9;">:</span> <span style="color:#a5d6ff;">'5800X / RTX 4080'</span><span style="color:#c9d1d9;">,</span>
<span style="color:#c9d1d9;"> 46 | };</span>
<span style="color:#6e7681;"> 47 | </span>
<span style="color:#6e7681;"> 48 | // keep going. build stuff that helps.</span>
</pre>

</div>

<div align="center">

[![X](https://img.shields.io/badge/@zCrxticxl-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/zCrxticxl)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@zcrxticxl)
[![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/vFaKsVuxKP)

</div>
