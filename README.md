# Ambient Reader

**Turn reading into an immersive experience.**

Ambient Reader is a bilingual web application that combines digital reading with adaptive ambient audio. Instead of listening to the same playlist throughout an entire book, the soundscape evolves as you read, responding to changes in setting, weather, mood, and intensity.

🌐 **Live demo:** https://lector-ambiental.pages.dev

## Features

- **Bilingual interface:** Available in English and Spanish, with support for books in both languages.
- **Multiple book formats:** Import EPUB, PDF, DOCX, TXT, HTML, Markdown, and FB2 files.
- **Adaptive soundscapes:** Ambient sounds, music, and sound effects respond to the content of the book.
- **Multiple visual environments:** Choose from a nighttime library, fantasy forest, space station, zen garden, urban café, or abstract environment.
- **Customizable reading experience:** Choose from multiple fonts, including accessibility-focused options, and adjust the reading paper's appearance.
- **Two-page book view:** Enjoy a realistic page-turning layout alongside a continuous reading mode.
- **Automatic reading:** Advance through the text at an adjustable reading speed.
- **Scene correction:** Manually correct a detected scene to improve the listening experience.
- **Performance settings:** Choose lightweight, balanced, or immersive visual modes, with support for reduced motion.
- **Reading progress persistence:** Return to your book and continue where you left off.
- **Reusable book soundscapes:** Save analyzed scene mappings for reuse with matching books, reducing the need for repeated analysis.

## How It Works

Ambient Reader analyzes the text as you read and determines which sounds best match the current scene.

Its built-in contextual analysis uses keywords, weighted rules, and contextual memory to track elements such as locations, weather, emotions, and intensity. The audio engine combines multiple layers to create a soundscape that evolves with the story.

The audio can include:

- **Environment:** Sounds associated with locations and weather.
- **Music:** Audio that reflects emotions such as calm, sadness, mystery, tension, horror, and action.
- **Intensity cues:** Sounds that respond to sudden or dramatic events.
- **Environmental details:** Additional sounds associated with the current setting, such as a ticking clock.

Readers can also manually correct scenes when the automatic analysis doesn't match the text.

## AI-Powered Scene Analysis

Ambient Reader offers an optional AI-powered analysis mode through **Groq**, currently its only supported AI provider.

- **Built-in analysis:** A free, local, rule-based system that works without an API key.
- **Groq AI analysis:** Uses an AI model through Groq to analyze book content and generate more context-aware scene mappings.

**Using Groq requires your own Groq API key.** Users are responsible for obtaining and configuring their own key and for any applicable usage limits or charges. AI analysis is optional; the built-in system remains available without it.

## Reading Experience

Ambient Reader provides two ways to read:

- **Continuous reading:** Scroll through the book while the ambient audio follows the active paragraph.
- **Two-page view:** Read a book-style layout with facing pages, animated page turns, and a cover when available.

Additional features include adjustable reading speed, keyboard controls, automatic page turning, customizable fonts, and persistent reading progress.

## Visual Environments and Performance

The app includes several atmospheric environments designed to complement the reading experience. Visual effects are built primarily with CSS gradients and canvas-based particles rather than large background images.

Three graphics modes are available:

- **Lightweight:** Minimal animation for lower-powered devices.
- **Balanced:** Moderate particle effects and subtle parallax.
- **Immersive:** More particles and smoother, higher-frame-rate animation.

Automatic mode starts conservatively on mobile devices and less powerful hardware and can reduce visual effects when performance drops. Animations can also be disabled, reduced-motion preferences are respected, and particle effects pause when the browser tab is hidden.

## Supported Languages and Book Formats

**Interface languages**
- English
- Spanish

**Supported book formats**
- EPUB
- PDF
- DOCX
- TXT
- HTML
- Markdown
- FB2

The app can process books in English and Spanish, with language detection helping select the appropriate analysis rules.

## Technology and Engineering

Ambient Reader brings together web application development, document parsing, contextual text analysis, audio playback, browser storage, responsive UI design, and performance-conscious visual effects.

The project includes:

- Rule-based contextual scene analysis.
- Optional AI integration through Groq.
- A layered audio engine with crossfades.
- CSS-based environments and canvas particle effects.
- Multiple reading layouts and accessibility-oriented font options.
- Browser-based storage for reading progress and saved scene corrections.
- Automated test cases for verifying scene detection behavior.

## Roadmap

Future development may focus on:

- Expanding the sound library with higher-quality recordings and more environmental variations.
- Improving scene detection and contextual accuracy.
- Supporting additional AI providers and exploring more capable book-aware AI.
- Expanding compatibility across devices and operating systems.
- Improving performance, scalability, and the overall reading experience.

## Try Ambient Reader

Visit the live demo to explore how ambient audio can accompany your reading.

🌐 **https://lector-ambiental.pages.dev**

**Ambient Reader — You focus on reading. The atmosphere evolves with the story.**
