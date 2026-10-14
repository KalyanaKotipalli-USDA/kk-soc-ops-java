<div align="center">

# 🎲 Soc Ops

### Turn introductions into a game.

**Soc Ops** is a fast, friendly social bingo game for in-person mixers. Find people who match the prompts, mark your squares, and make five in a row.

[**▶ Play the live demo**](https://copilot-dev-days.github.io/agent-lab-java/) · [**📚 Explore the lab**](workshop/GUIDE.md)

<br>

🌐 [Português (BR)](README.pt_BR.md) · [Español](README.es.md)

</div>

---

## ✨ Why Soc Ops?

Small talk is easier when there is a mission. Soc Ops gives every guest a reason to move, ask questions, and discover unexpected connections.

| 🔎 Discover | ✅ Connect | 🏆 Celebrate |
| --- | --- | --- |
| Browse prompts such as “has visited three continents.” | Tap a square when you find a match. | Complete a line and trigger a satisfying bingo moment. |

## 🎮 How to play

1. **Start a game** and get a fresh 5×5 board.
2. **Meet people** who match the prompts.
3. **Mark the squares** as you make connections.
4. **Get five in a row**—across, down, or diagonally—to win.

Your board stays available while you play, so you can keep the conversation going after your first bingo.

## 🧰 Built for learning and extending

Soc Ops is a small Spring Boot application with a deliberately approachable codebase:

- **Java 21 + Spring Boot** for the server
- **Thymeleaf + vanilla JavaScript** for the game experience
- **Maven Wrapper** for reproducible local commands
- **GitHub Pages** for automatic deployment on pushes to `main`

Prompts, board assembly, win detection, and the browser game engine are all easy to find and modify.

## 🚀 Run it locally

### Prerequisites

- [Java 21 JDK](https://adoptium.net/) or newer
- [Apache Maven 3.9+](https://maven.apache.org/) — or use the included wrapper

### Start the game

```bash
cd socops
./mvnw spring-boot:run
```

Then open <http://localhost:8080>.

### Build and test

```bash
cd socops
./mvnw clean package
./mvnw test
```

## 📚 Follow the agent lab

Want to see how the project is built and evolved with GitHub Copilot? The lab walks through the process from setup to multi-agent development.

| Part | Focus |
| --- | --- |
| [**00**](workshop/00-overview.md) | Overview & checklist |
| [**01**](workshop/01-setup.md) | Setup & context engineering |
| [**02**](workshop/02-design.md) | Design-first frontend |
| [**03**](workshop/03-quiz-master.md) | Custom Quiz Master |
| [**04**](workshop/04-multi-agent.md) | Multi-agent development |

> 📝 Every guide is also available in the [`workshop/`](workshop/) folder for offline reading.

## 🤝 Contribute

Have a great prompt, a new game mode, or an idea for making mixers more welcoming? Read [CONTRIBUTING.md](CONTRIBUTING.md), then open an issue or pull request.
