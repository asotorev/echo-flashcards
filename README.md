# Echo Flashcards

Curated flashcard decks for software engineering interview preparation. Use with [EchoStudy](https://github.com/asotorev/echo-flashcards) or any spaced repetition app that supports JSON imports.

## Categories

### Backend (6 decks, 255 cards)
- **Node.js Core** - Node.js fundamentals and core concepts (25 cards)
- **Express.js** - Express.js web framework (20 cards)
- **MongoDB** - MongoDB database and queries (50 cards)
- **PostgreSQL** - PostgreSQL database and SQL (50 cards)
- **AWS** - Amazon Web Services fundamentals (100 cards)
- **Full-Stack Concepts** - Full-stack development patterns (10 cards)

### Frontend (7 decks, 245 cards)
- **JavaScript Fundamentals** - Core JavaScript concepts (40 cards)
- **JavaScript Advanced** - Advanced JavaScript patterns (35 cards)
- **TypeScript** - TypeScript type system and features (30 cards)
- **Async JavaScript** - Promises, async/await, event loop (25 cards)
- **React Fundamentals** - React basics and hooks (40 cards)
- **React Advanced** - Advanced React patterns (40 cards)
- **Redux** - Redux state management (35 cards)

### AI & ML (25 decks, 618 cards)
Comprehensive AI/ML interview preparation covering:
- Fundamentals (linear algebra, statistics, probability)
- Machine learning algorithms (supervised, unsupervised, deep learning)
- Neural networks and architectures
- NLP and computer vision
- MLOps and production deployment
- Advanced topics (transformers, RAG, fine-tuning)

## Usage with EchoStudy

### Import from URL
1. Open EchoStudy app
2. Tap Import → From URL
3. Enter the raw GitHub URL for any deck:
```
https://raw.githubusercontent.com/asotorev/echo-flashcards/main/Backend/expressjs.json
```

### Import via Files App
1. Download deck files to your device
2. Open Files app → locate the JSON file
3. Tap and select "Open in EchoStudy"

### Import from Clipboard
1. Copy the raw JSON content
2. Open EchoStudy → Import → From Clipboard

## JSON Format

Each deck file follows this structure:

```json
{
  "decks": [
    {
      "name": "Deck Name",
      "description": "Deck description",
      "cards": [
        {
          "id": "1",
          "question": "Question text",
          "answer": "Answer with markdown support\n\n```javascript\ncode examples\n```",
          "tags": ["tag1", "tag2"],
          "nextReviewDate": null,
          "reviewCount": 0,
          "easeFactor": 2.5,
          "consecutiveCorrect": 0
        }
      ]
    }
  ]
}
```

## Spaced Repetition

All cards include SM-2 algorithm metadata:
- `easeFactor` - Card difficulty factor (default: 2.5)
- `reviewCount` - Number of times reviewed
- `consecutiveCorrect` - Streak of correct answers
- `nextReviewDate` - Next scheduled review

## Contributing

Found an error or want to add more decks? Open an issue or submit a pull request!

## License

MIT License - Feel free to use these decks for interview preparation.
