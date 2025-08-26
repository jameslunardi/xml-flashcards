# XML Flashcards

A collection of structured flashcard packs in XML format for interactive study sessions.
Use with the following Claude artifact: https://claude.ai/public/artifacts/1b70b8b8-3a8f-4ad4-9d38-ab1b2b607cf3

## Format

Each flashcard pack uses a simple, standardised XML structure:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<flashcards>
  <deck title="My Deck">
    <card id="1">
      <front>Question here</front>
      <back>Answer here</back>
      <reference>Source reference (optional)</reference>
    </card>
  </deck>
</flashcards>
```

## Structure

- **flashcards**: Root element containing all decks
- **deck**: Groups related cards with a descriptive title
- **card**: Individual flashcard with unique ID
- **front**: Question or prompt text
- **back**: Answer or explanation
- **reference**: Optional source citation or additional context

## Usage

These XML files can be imported into various flashcard applications that support custom formats. The structured format makes them particularly suitable for:

- Interactive study tools
- Spaced repetition systems
- Custom learning applications
- Educational platforms

## File Organisation

Each XML file contains one complete topic or subject area. Files are named descriptively to indicate their content and scope.

## Contributing

When adding new flashcard packs:

1. Follow the established XML schema
2. Use descriptive deck titles
3. Ensure unique card IDs within each file
4. Include references where appropriate
5. Test XML validity before submitting

## Compatibility

The XML structure is designed to be simple and widely compatible. Most XML parsers should handle these files without issues.
