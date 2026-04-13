# System Design Study Notes

This repository contains structured, browser-friendly system design notes for learning and interview preparation. It focuses on core distributed systems concepts, practical trade-offs, and common architecture patterns.

## Repository Contents

- `index.html` — primary, concise study guide with sectioned notes and references.
- `system-design-comprehensive.html` — expanded companion guide with deeper explanations, frameworks, and tooling references.

## What This Covers

The notes span foundational through advanced topics, including:

1. Fundamentals and estimation
2. Scalability
3. Databases
4. Caching
5. Networking and APIs
6. Message queues and event streaming
7. Distributed systems
8. Storage and CDN
9. Microservices architecture
10. Security and authentication
11. Observability and monitoring
12. Classic design problems
13. Design interview framework
14. Thinking and articulation framework
15. Practice roadmap
16. Tooling ecosystem

The concise guide (`index.html`) provides a focused version of the most important interview topics and links to curated resources.

## How to Use

### Option 1: Open directly
Open `/home/runner/work/SystemDesign/SystemDesign/index.html` in a browser.

### Option 2: Serve locally (recommended)
Run a local static server from the repository root:

```bash
cd /home/runner/work/SystemDesign/SystemDesign
python3 -m http.server 8000
```

Then visit:

- `http://localhost:8000/index.html`
- `http://localhost:8000/system-design-comprehensive.html`

## Suggested Learning Flow

1. Start with `index.html` for high-level coverage.
2. Move to `system-design-comprehensive.html` for depth and interview articulation patterns.
3. Practice by taking one classic system (for example, URL shortener or social feed) and designing it end-to-end:
   - requirements
   - APIs
   - data model
   - high-level architecture
   - scaling and bottlenecks
   - reliability and observability
4. Compare your design decisions against trade-offs discussed in the notes.

## References

The guides include curated references such as:

- Designing Data-Intensive Applications
- ByteByteGo
- System Design Primer
- High Scalability
- Classic papers and engineering blogs

## Contribution Notes

If you update content:

- Keep explanations practical and trade-off driven.
- Maintain section structure and readability.
- Prefer concise language and clear examples.

