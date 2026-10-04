# Pacman (extended)

An extended version of the Pacman example from [Free Python Games](https://github.com/grantjenks/free-python-games) by Grant Jenks, drawn with Python's `turtle` module. It adds a mode menu, three difficulty levels, a win condition and end screens to the original game.

Demo video: <https://youtu.be/Z0sJjfHg8vM>

## What was added to the original

- **Mode menu** at start-up: `S` unlimited mode (no win condition, 2 extra lives) or `L` limited mode (collect 25 dots to win; one ghost hit ends the game).
- **Three difficulty levels** that set the number of ghosts: `E` easy (4), `M` medium (5), `H` hard (6). The on-screen text says "Press ENTER to Start", but the game actually starts with `E`, `M` or `H`.
- **Score display, win screen and game-over screen**; after either screen the game returns to the mode menu after 3 seconds.
- **Two more ghost start positions** (six instead of the original four).

The mode menu text is in Turkish ("Mod Seçimi").

## Run it

```bash
pip install freegames
python pacman.py
```

Move Pac-Man with the arrow keys.

## Notes

- The game state is kept in module-level variables and the game loop is driven by `turtle` timers, as in the original example.
- No automated tests.

## License

Apache License 2.0, because this project is derived from Apache-licensed code. See [LICENSE](LICENSE) and [NOTICE](NOTICE).

## Türkçe özet

Free Python Games paketindeki Pacman örneğinin genişletilmiş hali (Apache 2.0). Başlangıçta mod seçimi (sınırsız mod: kazanma koşulu yok, 2 ek can; sınırlı mod: 25 noktayı toplayarak kazanılır, tek temasta oyun biter), üç zorluk seviyesi (4, 5 veya 6 hayalet), puan, kazanma ve oyun bitti ekranları eklenmiştir. Orijinal kodun lisansı ve atıfı `LICENSE` ve `NOTICE` dosyalarındadır.
