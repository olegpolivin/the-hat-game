# Игра в шляпу

Игра проходит следующим образом:
- Ведущий вытягивает из шляпы слово WORD для команды i.
- Команда i составляет для ведущего список из N_EXLAINING_WORDS слов, которые ведущий будет сообщать другим участникам по одному.
- Игра проходит N_EXPLAINING_WORDS итераций:
    - каждую итерацию j команда добавляет новую подсказку - новое слово,
    - другие игроки (все остальные команды) пытаются отгадать загаданное слово WORD, сообщая N_GUESSING_WORDS слов.
    - Как только слово окажется в этом топ-5, команда получает очки (чем раньше угадала - тем больше, например (N_EXPLAINING_WORDS - j)).
    - Загадывающая команда получает очки за каждую отгадавшую команду (например, столько же очков).
