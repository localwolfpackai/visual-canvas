# Visual Canvas

A spatial canvas for organizing ideas, tools, and AI collaborations — built by Lupo Studios.

This is the beginning of something I've wanted for a while: a freeform, infinite board where I can lay out everything I'm working with — tools, models, notes, architecture diagrams — and actually *see* how it all connects. Not a list. Not a dashboard. A space.

## Quick Start

1. Clone or download this repo
2. Open `index.html` in your browser
3. That's it — no build step, no dependencies

## How It Works

- **Pan** the canvas by clicking and dragging the background
- **Zoom** with scroll wheel (zooms toward your cursor)
- **Drag** any card to reposition it — snaps to a 12px grid for alignment
- **Toolbar** at top center to create new elements
- **Keyboard shortcuts**: `Cmd+0` reset view, `Cmd+=` zoom in, `Cmd+-` zoom out

### Card Types

- **Panel** — Glass-style cards with headers, icons, tags, and body text
- **Sticky** — Colored notes with a handmade rotation feel (yellow, green, blue, pink)
- **Label** — Large, faint section headers for organizing regions of the canvas
- **Sticker** — Compact badge-style pills representing AI models, with brand colors and accent borders

### AI Model Stickers

Small draggable badges you can place anywhere on the canvas to attribute which AI model is involved in a workflow or tool. Currently includes: Claude, GPT, Gemini, Llama, Mistral, Grok, Copilot, and Codex. Open the sticker tray from the toolbar to place new ones.

## Features

- Infinite pannable and zoomable canvas
- Draggable cards with grid snapping
- AI model sticker system with brand-accurate colors
- Real-time minimap showing card positions and viewport
- Dot grid background for spatial orientation
- Glass panel aesthetic with backdrop blur throughout
- Entrance animations with staggered delays
- Accessible — respects `prefers-reduced-motion`, keyboard navigable
- Zero dependencies — single HTML file, works offline

## Roadmap

This project is just getting started. Here's where it's headed:

- **Save/load state** — persist card positions and content to localStorage or file export
- **Connector lines** — draw relationships between cards with draggable bezier curves
- **Image cards** — drop images onto the canvas as a new card type
- **Paper MCP integration** — bridge this canvas with Paper for collaborative spatial design
- **More sticker packs** — frameworks, languages, services, custom collections
- **Grouping** — select multiple cards and move them as a cluster
- **Search** — find cards by content across a large canvas
- **Multiplayer** — real-time collaboration on the same board

## License

MIT — Lupo Studios
