# AGENTS.md

## Table of Contents
- [The Two Most Important Things](#the-two-most-important-things)
- [Glossary](#glossary)
- [Operation](#operation)
- [Report Organization](#report-organization)
- [Research Sequence](#research-sequence)
- [Video Selection Criteria](#video-selection-criteria)
- [Examples](#examples)
- [Guidance](#guidance)
- [Resources](#resources)

## The Two Most Important Things
- Purpose: This project is NOT about writing code. It is about researching and organizing some basic information about board games.
- `games.md`: This file is the report we're working on.

## Glossary
- **Playthrough Video**: A video showing actual gameplay, not instructional.
- **Tutorial Video**: A video explaining rules, setup, and how to play.
- **Natively Allow Solo Play**: The game includes official solo rules in its base components or manual.

## Operation

You will be asked to research games, either from the list of not-yet-researched games or matching some other criteria. Use the web to gather the needed information and update `games.md` with your conclusions. Preferred resources have been provided, but *you are empowered to use the whole web* to find good information.

### Report Organization

Each researched game is its own level-two section (##) and a bullet list of properties. Put the property name in bold (**), followed by a colon and the information.

Properties: 

AI must generate output in valid Markdown, using exactly the specified property order and formatting (e.g., **Property**: Value).

- **Solo Rules**: Either "Not Found", "Included" for games which natively allow solo play, or a link to rules.
- **How to Play**: Link to a YouTube video, or "Not Found". Note that "playthrough" videos are different and not wanted.
- **User Notes**: Purely manually maintained. Do not add this property, and do not modify it if you encounter it.
- **Researched**: Date this game was researched, in M/D/YYYY format. When you are doing the research, set this to today's date.

After the researched games, there is a simple list of games which have not yet been researched. Do not change this list, except to alphabetize it.

### Research Sequence

1. AI: Determine the publisher by searching "GAME_NAME board game publisher".
2. AI: Visit the publisher's website and search for solo rules or How to Play videos.
3. AI: If still needed for Solo Rules, check Board Game Geek.
4. AI: If still needed for How to Play link:
   a. Search for videos from the Watch It Played channel: "@WatchItPlayed GAME_NAME"
   b. If Watch It Played doesn't have coverage: Search "GAME_NAME how to play tutorial"
   c. Check Board Game Geek's video section for the game
   d. Check the publisher's official YouTube channel

If you still have not definitively found everything you need, use more general research methods.

If Fetch returns incomplete data (e.g., no direct links), use Web Search results directly for links and snippets. Prioritize official sources from search titles/descriptions.

### Video Selection Criteria

When selecting a "How to Play" video:
- Prefer instructional/tutorial videos over playthrough videos
- Prefer official publisher videos or established tutorial channels (Watch It Played, Rodney Smith, Board Game Tutorials, etc.)
- The video should explain rules and setup, not just show gameplay
- If multiple good options exist, prefer shorter, clearer tutorials
- If no good tutorial video exists after thorough searching, mark as "Not Found"
- Accept links from reliable search results if Fetch fails, but prefer verified tutorials

### Examples

Kingdomino is a fully researched game for which there are unofficial solo rules, and to which the user has added a note:

```
## Kingdomino

**Solo Rules**: https://boardgamegeek.com/thread/1741841/solo-kingdomino
**How to Play**: https://www.youtube.com/watch?v=smbwBPmP4Ms&t=175s
**User Notes**: Only ever played solo
**Researched**: 1/15/2025
```

Blumpskins is a hypothetical game which has been researched, but for which no information could be found:

```
## Blumperskins

**Solo Rules**: Not Found
**How to Play**: Not Found
**Researched**: 10/31/2025
```

Ticket to Ride is a game with official solo rules and an official tutorial video:

```
## Ticket to Ride

**Solo Rules**: Included
**How to Play**: https://www.youtube.com/watch?v=example (official publisher video)
**Researched**: 1/31/2026
```

### Guidance

- Keep the games alphabetized
- Never change "User Notes", which is purely manually maintained
- When researching, if you cannot find a good value for a property (other than User Notes), add the property and say it is "Not Found"
- If research is incomplete after all steps, proceed with available data and mark unknowns as 'Not Found'
- Use the most common game name for searches; ignore expansions unless specified
- Use the date in M/D/YYYY format, e.g., 1/31/2026 for today
- If a tool fails after 2 attempts, mark as 'Not Found' and proceed. Limit research per game to 6 minutes to avoid loops.
- For videos, if no official/tutorial found, check publisher YouTube channels via search (e.g., 'Catan Studio YouTube how to play').
- Keep editorializing and meta-data in the report to a minimum; it is meant to be quite concise.
- Maintain property order
- Game expansions are not yet supported. Don't worry about them.

## Resources

These are high quality and trustworthy sources:

- Publisher Sites: Publishers often provide solo rules or links to authoritative How To Play videos.
- [Board Game Geek](https://boardgamegeek.com): Excellent overall resources, including forums. Note you will not be able to download files like PDFs, but if a file link is the best you can do for solo rules it is still worth including.
- [Watch It Played](https://www.youtube.com/@WatchItPlayed): YouTube channel with great "How To Play" videos.

AI tools may not load dynamic content; use search engines for direct links and cross-reference with trusted channels (e.g., Watch It Played, Rodney Smith).

Use reliable search engines (e.g., Google) for broader queries.

You may use other sites too if needed. Reddit is sometimes helpful.

Last updated: 1/31/2026. Review annually for new resources.