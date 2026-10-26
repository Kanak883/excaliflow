
# Excaliflow — Animated Diagram & Flowchart Maker

**Create hand-drawn diagrams and visualize AI workflows with animated connections.**

Excaliflow is a browser-based diagramming tool for developers who want to sketch AI agent architectures, RAG pipelines, software systems, and flowcharts. Create connected diagrams, animate flows, and export your work as images or video.

**[Open the Live Demo](https://excaliflow.flow-sketch.workers.dev/)**

## Explore Excaliflow

- [Live diagram editor](https://excaliflow.flow-sketch.workers.dev/)
- [About Excaliflow](https://excaliflow.flow-sketch.workers.dev/about.html)
- [RAG pipeline diagram guide](https://excaliflow.flow-sketch.workers.dev/rag-pipeline-diagram.html)
- [AI agent workflow diagram guide](https://excaliflow.flow-sketch.workers.dev/ai-agent-workflow-diagram.html)

## Features

- **Hand-drawn diagrams:** Draw rectangles, circles, decision diamonds, freehand sketches, and sticky notes.
- **Animated connections:** Visualize data flow with animated arrows, pulses, comets, and other flow effects.
- **Quick diagram building:** Use keyboard shortcuts, shape connection ports, and arrow editing to build diagrams faster.
- **AI and software architecture templates:** Start with AI Agent Swarm, RAG Pipeline, How Browsers Work, or Microservices.
- **Multiple canvases:** Organize diagrams in separate tabs, duplicate architectures, and rename canvases.
- **Light and dark canvases:** Choose a visual style for your diagrams.
- **Export and import:** Export cropped 2× PNG images, record WebM videos, copy images to the clipboard, and save or load `.excaliflow` and `.excalidraw` files.
- **Browser-based workspace:** Start drawing without installing a desktop application.

## Try It Online

Open [Excaliflow](https://excaliflow.flow-sketch.workers.dev/) in a modern browser and start creating diagrams.

Your workspace is saved locally in your browser. It is not automatically synchronized across accounts or devices.

## Run Locally

Requirements: Node.js 18 or later.

Clone this standalone repository:

```bash
git clone https://github.com/Kanak883/excaliflow.git
cd excaliflow
npm start
```

Open http://localhost:3000 in your browser.

Excaliflow has no external npm dependencies, so you do not need to run `npm install` for the current project.

## Run Tests

Run the project's verification suite:

```bash
npm test
```

## Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `V` or `1` | Select and move shapes |
| `H` or `Space + Drag` | Pan the canvas |
| `R` or `2` | Rectangle |
| `D` or `3` | Diamond / decision |
| `O` or `4` | Circle / ellipse |
| `A` or `5` | Animated arrow |
| `P` or `7` | Freehand pen |
| `T` or `8` | Text |
| `N` or `9` | Sticky note |
| `K` | Laser pointer |
| `E` or `0` | Eraser |
| `Q` | Keep selected tool active |
| `Tab` | Add and connect the next shape |
| `Alt / Option + Drag` | Duplicate selection while dragging |
| `Alt + T` | Create a new canvas tab |
| `Alt + [` / `Alt + ]` | Switch between canvas tabs |
| `Alt + 1`–`Alt + 9` | Switch directly to a canvas tab |
| `Ctrl/Cmd + Z` | Undo |
| `Ctrl/Cmd + D` | Duplicate selection |

## Project Structure

```text
excaliflow/
├── index.html
├── about.html
├── rag-pipeline-diagram.html
├── ai-agent-workflow-diagram.html
├── favicon.png
├── robots.txt
├── sitemap.xml
├── server.js
├── verify.js
├── package.json
└── README.md
```

The repository also contains deployment configuration and the IndexNow verification file.

## Credits and License

Excaliflow is based on the project originally published in
[Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_llm_apps/excaliflow).

This standalone repository includes additional deployment and documentation work. Please retain the upstream project's copyright notices and applicable attribution.

See the repository's [Apache-2.0 license](LICENSE).
