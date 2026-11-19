<!-- ═══════════════════════════════════════════════════════════════
     amriz26 :: autonomous_node v2026.11
     sense → perceive → plan → act
     ═══════════════════════════════════════════════════════════════ -->

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:b8cfd3,25:b4c5ca,42:899297,55:696c70,68:534e4e,82:443936,100:3d2e2c&text=amriz26&fontColor=ffffff&fontSize=60&fontAlignY=38&desc=sense%20%E2%86%92%20perceive%20%E2%86%92%20plan%20%E2%86%92%20act&descAlignY=60&descSize=16&animation=fadeIn" alt="header"/>

<p align="center">
  <a href="https://github.com/amriz26">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=2800&pause=900&color=00FFA3&center=true&vCenter=true&width=640&lines=%5BBOOT%5D+loading+perception+stack...;%5BOK%5D+camera+%E2%86%92+hand+landmarks+%E2%86%92+cursor;%5BOK%5D+fridge+pixels+%E2%86%92+ingredients+%E2%86%92+dinner;%5BOK%5D+tab-switch+entropy+%E2%86%92+procrastination+forecast;%5BIDLE%5D+waiting+for+the+next+weird+sensor..." alt="boot log"/>
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/node-amriz26-00ffa3?style=flat-square&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/status-online-00ffa3?style=flat-square&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/loc-San%20Francisco-8b949e?style=flat-square&labelColor=0d1117" />
  <img src="https://komarev.com/ghpvc/?username=amriz26&style=flat-square&color=0f3d3e&label=pings" />
</p>

---

```python
class Ahmed(Agent):
    location = "San Francisco, CA"
    role     = "Engineering @ Casper Studios"
    school   = "B.S. Computer Science @ SFSU"
    prev     = ["Keplr AI", "Scale AI"]
    focus    = ["AI agents", "autonomous systems", "computer vision"]

    def observe(self):
        return [webcam, fridge_cam, room_scan, typing_cadence]

    def act(self, signal):
        return {
            "hand gesture":  "move the cursor",          # AirMouse
            "fridge photo":  "suggest dinner",           # PantryVision
            "room scan":     "place furniture in AR",    # AR Furniture
            "tab switching": "warn before you drift",    # Procrastination Predictor
        }[signal]

    def loop(self):
        while caffeine > 0:
            self.act(self.observe())
```

> I build things that **look at the world and then do something about it**.
> If it has a camera, a sensor, or a messy behavioral signal, I want to turn it into an action.

---

### 🛰️ System graph

```mermaid
flowchart LR
    subgraph SENSE["📡 sense"]
        CAM([webcam])
        FRIDGE([fridge cam])
        LIDAR([phone camera / room scan])
        BEH([browser + typing telemetry])
    end
    subgraph PERCEIVE["👁️ perceive"]
        HAND[hand landmarks]
        YOLO[YOLO food detection]
        DEPTH[plane + object detection]
        FEAT[behavioral features]
    end
    subgraph ACT["🦾 act"]
        AM[AirMouse<br/>gesture → cursor]
        PV[PantryVision<br/>ingredients → meals]
        AR[AR Furniture<br/>physics-true placement]
        PP[Procrastination Predictor<br/>nudge before you drift]
    end
    CAM --> HAND --> AM
    FRIDGE --> YOLO --> PV
    LIDAR --> DEPTH --> AR
    BEH --> FEAT --> PP
    PV -. bolt-on .-> RME[Recipe Mutation Engine]
```

### 🧪 Active experiments

| node | input → output | stack |
|---|---|---|
| [**AirMouse**](https://github.com/amriz26/AirMouse) | webcam → hand gestures → OS cursor control | `Python` `OpenCV` `MediaPipe` |
| [**PantryVision**](https://github.com/amriz26/PantryVision) | fridge photo → detected ingredients → meal ideas | `TypeScript` `YOLO` |
| [**AR Furniture Placement**](https://github.com/amriz26/AR-Furniture-Placement-Phys-Sim) | room scan → virtual furniture with real physics constraints | `Dart` `Flutter` `CV` |
| [**Procrastination Pattern Predictor**](https://github.com/amriz26/Procrastination-Pattern-Predictor-) | app-switching + typing speed → "you're about to procrastinate" | `Python` `ML` |
| [**Recipe Mutation Engine**](https://github.com/amriz26/-Recipe-Mutation-Engine) | learns *why* recipes work → valid new variations | `Python` |
| [**Cartoon CNN**](https://github.com/amriz26/CNN-Based-Image-Classification-of-Cartoon-Characters) | pixels → which cartoon character is this | `PyTorch` `CNN` |

---

### 🔧 Actuators &amp; firmware

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,ts,js,dart,c,pytorch,tensorflow,opencv,react,nextjs,flutter,nodejs,postgres,sqlite,aws,docker,git,linux&perline=9&theme=dark" alt="stack"/>
</p>

### 📈 Telemetry

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=amriz26&show_icons=true&hide_border=true&bg_color=0d1117&title_color=00ffa3&icon_color=00ffa3&text_color=c9d1d9&rank_icon=github&custom_title=node%20diagnostics" alt="stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=amriz26&layout=compact&hide_border=true&bg_color=0d1117&title_color=00ffa3&text_color=c9d1d9&langs_count=8&custom_title=firmware%20mix" alt="languages"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=amriz26&hide_border=true&background=0d1117&ring=00ffa3&fire=00ffa3&currStreakLabel=00ffa3&sideLabels=c9d1d9&currStreakNum=e6edf3&sideNums=e6edf3&dates=8b949e&stroke=30363d" alt="uptime streak"/>
</p>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=amriz26&bg_color=0d1117&color=c9d1d9&line=00ffa3&point=e6edf3&area=true&area_color=0f3d3e&hide_border=true&title_color=00ffa3&custom_title=signal%20over%20time" alt="activity graph"/>
</p>

---

```diff
+ currently tuning: gesture smoothing so the cursor stops vibrating like it had 4 espressos
+ currently reading: anything about agents that act in the physical world
- known bug: will start a new CV project before finishing the last one
```

<p align="center">
  <sub>📫 ping this node on LinkedIn (link in profile) · ask me about weird sensor inputs</sub>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=110&color=0:b8cfd3,25:b4c5ca,42:899297,55:696c70,68:534e4e,82:443936,100:3d2e2c&section=footer" alt="footer"/>
