---
outdated_translation: true
outdated_since: b0afe186b01a363a31211b349e4d83c15033890e
---

# Нестандартные хитсаунды

В настоящее время можно использовать свои файлы для звуков и скинов. Именно про первое здесь и пойдёт речь.

Следующие файлы могут быть заменены:

## Обычный («громкий») сет

- normal-hitnormal
- normal-hitwhistle
- normal-hitfinish
- normal-hitclap

*Заметка:* Последние 3 сэмпла будут проигрываться вместе с обычным хитсаундом. То есть, в случае свистка будут при попадании в ноту будут проиграны и hitnormal и hitwhistle звуки.

- normal-sliderslide (проигрывается непрерывно)
- normal-sliderwhistle (проигрывается непрерывно)
- normal-slidertick

## Тихий сет

- soft-hitnormal
- soft-hitwhistle
- soft-hitfinish
- soft-hitclap

*Заметка:* Последние 3 сэмпла будут проигрываться вместе с обычным хитсаундом.

- soft-sliderslide (проигрывается непрерывно)
- soft-sliderwhistle (проигрывается непрерывно)
- soft-slidertick

## Звуки спиннеров

- spinnerspin (Это звук имеет разную высоту в зависимости от того, как быстро игрок крутит спиннер. Варьируется от ~500hz to 80000hz при оригинальном звучании сэмпла на 44100hz)
- spinnerbonus (Дзынь)

## Формат файлы

В качестве сэмпла вы можете использовать как mp3, так и Wav файлы, но учтите, что Wav'ы для этой цели подходят лучше: мптришки имеют небольшую (0-20 мс) задержку перед воспроизведением, и поэтому некорректно зацикливаются.

Достаточно только поместить файлы с нужными названиями в папку с картой, переоткрыть её (Ctrl+Shift+L) и звуки появятся!
