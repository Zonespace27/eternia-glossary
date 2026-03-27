# Eternia Glossary

JSON files for the `/glossary` command in Eternia.

## Contributing

Pull Requests are appreciated and encouraged! For the expected JSON format that entries should follow, see [\_FORMAT.json](_FORMAT.json).

Try to keep entries separated based on their contents—Alessa would go in `plants.json`, not `combat.json`. Bear in mind that the separation of files are purely for editor convenience, the game simply clumps them all together.

### Actions

The repo has two actions enabled, a **spellchecker** and a **JSON validator**.

#### Spellchecker

This helps ensure that spelling mistakes don't make it into the game. If a word is being flagged despite being a real word in Eternia (e.g. "Arcanium"), you can add an exemption to `config/.skipwords.txt`.

#### JSON Validator

This ensures that the JSON files submitted are properly set up, so that the game doesn't throw a fit when trying to load them.
