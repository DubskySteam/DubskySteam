```
┌─[dubsky@github]─[~]
└──╼ $ tmux new-session -s dev
```

<table>
<tr>
<td width="50%" valign="top">

```bash
┌─[pane 0]─────────────────────────┐
│ $ cat about.sh                   │
└──────────────────────────────────┘

#!/bin/bash
# announcing I use neovim
# upcoming zig enjoyer
# coffee enthusiast

LOCATION="backrooms"
STATUS="probably crashing out"
```

```bash
┌─[pane 1]─────────────────────────┐
│ $ cat stack.conf                 │
└──────────────────────────────────┘

[core]
  zig
  c++
  java
  typescript

[devops]
  teamcity [ci]
  kubernetes/docker
  nginx/caddy

[tools]
  neovim
  gdb/lldb
  perf/flamegraph
```

```bash
┌─[pane 2]─────────────────────────┐
│ $ tail learning.log              │
└──────────────────────────────────┘

[ml/ai]       deep learning optimization
              model architecture tuning
              inference pipeline performance

[systems]     rust driver development  
              embedded zig programming
```

</td>
<td width="50%" valign="top">

```bash
┌─[pane 3]─────────────────────────┐
│ $ ls -la ~/projects              │
└──────────────────────────────────┘

drwxr-xr-x  poe-ai/
  # ML for Path of Exile economy analysis
  # python, pytorch

drwxr-xr-x  WinFlux/
  # Windows optimization GUI
  # zig, win32, system tweaks

drwxr-xr-x  Aiko/
  # Cross-Platform desktop anime app
  # java, gradle, compose

drwxr-xr-x  automata-simulator/
  # automata visualizer with canvas editor
  # react, typescript
```

```bash
┌─[pane 4]─────────────────────────┐
│ $ ps aux | grep interests        │
└──────────────────────────────────┘

→ systems programming
→ machine learning
→ reverse engineering
→ pipeline orchestration
→ performance optimization
```

</td>
</tr>
</table>
