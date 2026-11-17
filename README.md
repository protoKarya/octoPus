# 🐙 octoPus — Organism Deployment Mesh

The octopus that reaches into every gate.

## What Is octoPus?

`inkFish` is the gaming sovereignty layer — 16 commands for Steam, VR, BT, IoT.
`octoPus` is the **deployment mesh** that pushes inkFish (and everything else) to every gate in the organism.

When Kevin plugs the Steam Frame into eastGate via USB-C, octoPus reaches in:
- Cross-compiles ARM64 binaries on eastGate
- SCPs them through the USB CDC NCM tunnel
- Installs Ollama, pulls models, starts inference
- Deploys inkFish for local mesh scanning and solar panel mode

## Architecture

```
          eastGate (BRAIN)
              │ USB-C CDC NCM
              ▼
         frameGate (FACE)
        Snapdragon 8 Gen 3
         48.4 tok/s Ollama
        Vulkan 1.4.363 GPU
         BT 5.3 + WiFi AP
```

## Gates Reached

| Gate | Arch | Method | Deployed |
|------|------|--------|----------|
| eastGate | x86_64 | local | inkFish, Ollama (38 models) |
| southGate | x86_64 | SSH | inkFish |
| frameGate | aarch64 | USB CDC NCM | inkFish, Ollama (tinyllama), flint-silicon |
| northGate | x86_64 | git push | (game streaming via Sunshine) |
| ironGate | x86_64 | ping only | (SSH auth blocked) |
| milkGate | riscv64 | SSH | (hello_milkgate tested) |
| sporeGate | x86_64 | SSH | (heart-pull active) |

## The Octopus Metaphor

inkFish = ink fish = cephalopod = octopus.
Eight arms reaching into eight gates.
Chromatophore adaptations make every device look like native Steam.
The organism doesn't push — it REACHES.

## First Words on Snapdragon

> "The octopus is a mythical creature with eight arms, which is a metaphorical
> representation of a person or a group of people with different ideas, opinions,
> and perspectives."
>
> — tinyllama on frameGate, 48.4 tok/s, November 16 2026
