# XML Flashcards

A collection of structured flashcard packs in XML format for interactive study sessions.

Use with the following Claude artifact: 

https://claude.ai/public/artifacts/17b1c1e0-0b99-4d10-811b-5146dc174a60 (v21)

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

---

## Contact
If you want to contact me:
- **LinkedIn:** [jameslunardi](https://www.linkedin.com/in/jameslunardi/)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
