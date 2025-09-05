<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=180&text=Vinícius%20C.%20Chelli&fontAlign=50&fontSize=40&desc=Game%20AI%20•%20Unity%20•%20Godot%20•%20Rob%C3%B3tica&color=gradient" />
</p>

# Olá! Eu sou o Vinícius Chelli 👋
NPCs autônomos (LLM + DQL + TTS), Unity/Godot e robótica. Ciência pra transformar o jogo. ⚔️

<p>
  <img src="https://img.shields.io/badge/Unity-2022%20LTS-black?logo=unity&style=flat-square"/>
  <img src="https://img.shields.io/badge/Godot-4.x-478CBF?logo=godot-engine&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/C%23-239120?logo=csharp&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/R-Expert-276DC3?logo=r&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/ESP32-WiFi%2FBT-000?logo=espressif&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/Arduino-Nano-00979D?logo=arduino&logoColor=white&style=flat-square"/>
</p>

---

## 🎮 Jogos

### Dawn Forest 🌲 (Godot • 2D Sidescroller)
**Pitch:** plataformas 2D em floresta ao amanhecer, foco em precisão de pulo e coleta de sementes mágicas.  
**Tech:** Godot 4 • GDScript • Tilemap • Parallax • State machine  
**Jogar:** _HTML5 no itch_ • **[Jogar](https://SEU_USUARIO.itch.io/dawn-forest)** • **[Repo](https://github.com/SEU_USUARIO/dawn-forest-godot)**  
**Windows:** releases no GitHub  
**Roadmap:** chefes por bioma • power-ups (dash/duplo pulo) • música dinâmica

---

### Infinity Runner Omega ⚡ (Unity • Endless Runner)
**Pitch:** runner infinito com obstáculos procedurais e power-ups de velocidade.  
**Tech:** Unity 2022 LTS • C# • Object Pooling • ScriptableObjects • Cinemachine  
**Jogar:** **[WebGL](https://SEU_USUARIO.itch.io/infinity-runner-omega)** • **[Repo](https://github.com/SEU_USUARIO/infinity-runner-omega)**  
**Próximos passos:** leaderboard online • skins • missões diárias

---

### Advanced Platformer 2D 🎯 (Unity)
**Pitch:** plataforma 2D com física polida, **coyote time**, **input buffer** e inimigos com FSM.  
**Tech:** Unity 2022 LTS • New Input System • URP 2D • Cinemachine  
**Jogar:** **[WebGL](https://SEU_USUARIO.itch.io/advanced-platformer-2d)** • **[Repo](https://github.com/SEU_USUARIO/advanced-platformer-2d)**  
**Destaques:** tilemap + rule tiles • checkpoints • collectibles

---

### Start Game Dev 🧱 (Unity • Template)
**Pitch:** template de protótipo com **menu**, **opções (áudio/daltonismo)**, HUD e save simples.  
**Tech:** Unity 2022 LTS • UI Toolkit/Canvas • JSON save  
**Repo:** **[Start Game Dev](https://github.com/SEU_USUARIO/start-game-dev)**  
**Use assim:** clone → abra no Unity → troque a cena e comece o protótipo

---

### 3D Game Adventurer 🗺️ (Unity • 3D)
**Pitch:** aventura 3D terceira pessoa com movimento, combate leve e coleta.  
**Tech:** CharacterController • Cinemachine FreeLook • NavMesh  
**Repo:** **[3D Game Adventurer](https://github.com/SEU_USUARIO/3d-game-adventurer)**  
**Roadmap:** quests (fetch/kill/escort) • minimapa • BT simples para inimigos

---

## 🤖 Robótica

### “Gol Quadrado” RC (ESP32)
**Ideia:** carrinho **RC** inspirado em “Gol Quadrado”, controlado por **DualShock 4** via **Bluetooth**, direção/tração com ponte H.  
**Stack:** ESP32 • Bluepad32 • L298N (ou ponte H compatível) • LiPo 2S/3S • (opcional) LEDs e buzina  
**Repo:** **[gol-quadrado-esp32](https://github.com/SEU_USUARIO/gol-quadrado-esp32)**

**Features**
- Pareamento do controle PS4 (sticks → PWM motor/esquerda/direita)
- Mapeamento de botões (buzina/luzes)
- Fail-safe (corta motores se perder BT)
- Calibração rápida (deadzone, ganho)

**Como rodar (resumo)**
1. Instale **ESP32** na IDE Arduino e a **lib Bluepad32**  
2. Configure pinos do L298N (ENA/IN1/IN2/ENB/IN3/IN4)  
3. Compile e grave no ESP32  
4. Pareie o DualShock (segure **Share + PS**) e divirta-se

> Dica: se preferir PID de velocidade, adicione encoders e calcule RPM na interrupção.

---

### Robô Quadrúpede 🐾 (Arduino Nano)
**Ideia:** quadrúpede educativo com **8–12 servos**, gaits básicos (trote/andar), controle simples por joystick/serial.  
**Stack:** Arduino Nano • PWM (direto ou **PCA9685**) • MG90S/SG90 • pack 6V • (opcional) IMU **MPU6050**  
**Repo:** **[quadrupede-arduino-nano](https://github.com/SEU_USUARIO/quadrupede-arduino-nano)**

**Features**
- Gaits prontos (crawl/trot) com offsets por perna
- Perfil de **calibração** (zero mecânico e amplitude)
- Modo demo (sequências coreografadas)
- (Opcional) equilíbrio com IMU (pitch/roll → correção)

**Como rodar (resumo)**
1. Monte as pernas (coxo/joelho) e **zerar** posição dos servos em 90°  
2. Edite `config.h` (pinos/offsets/limites)  
3. Grave via IDE Arduino  
4. Use **Serial Monitor** ou joystick para comandos

> Dica: se usar **PCA9685**, alimente servos separadamente e ligue **GND comum** com o Nano.

---

## 🗂️ Mapa dos Repositórios

- Godot: **[dawn-forest-godot](https://github.com/SEU_USUARIO/dawn-forest-godot)**
- Unity: **[infinity-runner-omega](https://github.com/SEU_USUARIO/infinity-runner-omega)** • **[advanced-platformer-2d](https://github.com/SEU_USUARIO/advanced-platformer-2d)** • **[start-game-dev](https://github.com/SEU_USUARIO/start-game-dev)** • **[3d-game-adventurer](https://github.com/SEU_USUARIO/3d-game-adventurer)**
- Robótica: **[gol-quadrado-esp32](https://github.com/SEU_USUARIO/gol-quadrado-esp32)** • **[quadrupede-arduino-nano](https://github.com/SEU_USUARIO/quadrupede-arduino-nano)**

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=SEU_USUARIO&show_icons=true&theme=tokyonight" height="160"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SEU_USUARIO&layout=compact&theme=tokyonight" height="160"/>
  ## 📚 Aulas de R (materiais)
Repositório com scripts, datasets e notebooks das minhas aulas e monitorias de R:
- **[ensino-codigos](https://github.com/SEU_USUARIO/ensino-codigos)**  
  <sub>fundamentos da linguagem, limpeza de dados, EDA, visualização, modelagem com `tidymodels`/`caret`.</sub>

<p align="center">
  <a href="https://github.com/SEU_USUARIO/ensino-codigos">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=SEU_USUARIO&repo=ensino-codigos&theme=tokyonight" />
  </a>
</p>

## 🧪 Projetinhos de ML (R)
Mini-projetos didáticos (dados clássicos, pipeline completo: limpeza → EDA → treino → métricas):
- 🍷 **Classificador de Vinhos** (quality) — [código](https://github.com/SEU_USUARIO/ensino-codigos/tree/main/R/ml_vinhos)  
  `tidymodels` (logístico/árvore/rf), grid search, matriz de confusão, ROC.
- 🎗️ **Câncer de Mama (Wisconsin)** — [código](https://github.com/SEU_USUARIO/ensino-codigos/tree/main/R/ml_cancer_mama)  
  seleção de features, comparação SVM vs. Random Forest, explicabilidade simples.
- 🩺 **Diabetes (Pima)** — [código](https://github.com/SEU_USUARIO/ensino-codigos/tree/main/R/ml_diabetes)  
  validação estratificada, métricas macro, curva PR.
- 🧹 **Limpeza + EDA** — [código](https://github.com/SEU_USUARIO/ensino-codigos/tree/main/R/eda_limpeza)  
  tratamento de NA/outliers, encoding, `ggplot2` (distribuições, correlações).

</p>

---

## 📬 Contato
[LinkedIn](https://linkedin.com/in/SEU_LINK) • theongatechelli@gmail.com
