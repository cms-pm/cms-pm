### Chris Slothouber

I build embedded systems because I'm passionate about the process and seeing the thing become reality from imagination. 
My adventures include taking boards from schematic
through fabrication and bring-up, and I've spent enough overheated evenings with a scope on
an SPI or I2C bus to trust the wire over the status line.

When AI coding agents turned up at my bench, I started writing rules for them,
then wrote more every time an agent got around the last batch. A heartbeat LED I
insisted on once caught an agent testing the wrong firmware. The rules grew into
the projects below.

My earlier jobs mostly didn't have titles yet. I ran bare-metal hosting across
several points of presence, streamed live concerts from the venue before anyone
had heard of YouTube, picked up ISO 9001 discipline at BlackBerry, kept remote
facilities running in Northern Canada, and sat on the board of a community
nonprofit ISP. I live in Seattle.

I'm writing [*AI-Assisted Embedded Development*](https://failclosed.dev).
Chapter 1 is out now as an early release.

**What I'm building**

- [**ai-dev-governance**](https://github.com/cms-pm/ai-dev-governance). The rules
  from my bench, grown into a versioned framework for working with AI coding
  agents. It requires a plan before code and evidence before a change counts,
  and the agent never grades its own work. An embedded profile covers firmware
  and bench work.
- [**brontes-probe-mcp**](https://github.com/cms-pm/brontes-probe-mcp). An MCP
  server that lets an AI assistant operate a debug probe. It flashes, halts, reads
  memory, and streams ITM/SWO trace on Cortex-M targets.
- [**astaire**](https://github.com/cms-pm/astaire). A SQLite knowledge store that
  hands an agent small, token-budgeted context in place of whole files.

**Also**

- [zydeco-profiler-mcp](https://github.com/cms-pm/zydeco-profiler-mcp). Code-size
  and cycle measurements for embedded A/B comparisons, judged by a decision rule
  fixed before the numbers come in.
- [kv4-edge-inference](https://github.com/cms-pm/kv4-edge-inference). The
  reproduction package for my study of 4-bit KV-cache quantization on a 4 GB GPU
  ([paper](https://ssrn.com/abstract=6941538)).
