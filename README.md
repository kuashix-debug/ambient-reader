# Ambient Reader

**Turn reading into an immersive experience.**

Ambient Reader is a bilingual web application that combines digital reading with adaptive ambient audio. Instead of listening to the same playlist throughout an entire book, the soundscape evolves as you read, responding to changes in setting, weather, mood, and intensity.

🌐 **Live demo:** https://lector-ambiental.pages.dev

## Features

- **Multilingual experience:** Interface available in English and Spanish, with support for books in both languages.
- **Multiple book formats:** Import EPUB, PDF, DOCX, TXT, HTML, Markdown, and FB2 files.
- **Adaptive soundscapes:** Ambient environments, music, and sound effects respond to the content of the book.
- **Multiple visual environments:** Choose from atmospheric settings such as a nighttime library, fantasy forest, space station, zen garden, urban café, or abstract space.
- **Customizable reading experience:** Choose fonts, including accessibility-oriented options, and adjust the reading paper's appearance.
- **Two-page book view:** A realistic, page-turning layout alongside a continuous reading mode.
- **Automatic reading:** Let the app advance through the text at an adjustable reading speed.
- **Scene correction:** Manually correct an incorrectly detected scene to improve the listening experience.
- **Performance options:** Lightweight, balanced, and immersive visual modes, with reduced-motion support.
- **Reading progress persistence:** Return to your book and continue where you left off.

## How it works

Ambient Reader analyzes text as the reader progresses and uses contextual rules to determine the appropriate atmosphere. It combines environmental audio, music, intensity cues, and location-specific sound details into a layered soundscape.

The application also supports reusable scene mappings for recognized books, helping avoid repeated analysis when a matching mapping is available.

## Technology and engineering

The project brings together web application development, document parsing, audio playback, contextual text analysis, responsive interfaces, browser storage, and performance-conscious visual effects.

The visual environments use CSS effects and canvas-based particles rather than relying on large background images. This helps keep the experience lightweight while offering different levels of visual detail.

## Languages

- English interface and book support
- Spanish interface and book support

## Roadmap

Future development may focus on expanding the sound library, improving scene recognition, exploring more capable AI-based book analysis, and making the application available across additional devices and platforms.

## Try it

Visit the live demo and explore how ambient audio can accompany your reading.

**Ambient Reader — You focus on reading. The atmosphere evolves with the story.**
