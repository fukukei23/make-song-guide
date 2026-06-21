# yoen-v3_1 楽譜（MuseScore 4.7.3 / LilyPond 非導入環境で生成）

## 📖 見方

| ファイル | 内容 | 优先度 |
|---|---|---|
| **01_AB_compare.pdf** / **01_AB_compare-1.png** | 上段=Aメロ・下段=サビ の12音対比。**音符の形がほぼ一致＝同じ音程の証拠** | ★★★ 一番見てほしい |
| 02_vocal_24bars.pdf / 02_vocal_24bars-1.png | ボーカル旋律の冒頭96音（24小節）。全体像 | ★★ |
| 03_full_score.pdf | 全555音（ボーカル+伴奏）。長い | ★ |

## 🎵 結論

Aメロとサビは **12音中10音が完全一致**（半音差総和=3）。サビで「高音に跳ね上がる」ことはなく、Aメロ旋律をそのまま継承している。

```
A (A-melody) : G4 F#4 G4 F#4 D5 B4 A4 A#4 A4 A4  G4  F#4
B (Chorus)   : G4 F#4 G4 F#4 D5 B4 A4 A#4 A4 G#4 G4  G#4
```

## 🔧 編集したい場合

`v3_1_AB_compare_v2.musicxml` / `v3_1_vocal_simple.musicxml` / `v3_1.musicxml` を
MuseScore（AppImage: `~/tools/MuseScore-Studio-4.7.3.AppImage`）で開けばGUI編集可能。

## 📍 Windows から見るパス

```
\\wsl.localhost\Ubuntu\home\yn4416\projects\make-song-guide\songs\yoen-night\scores\
```

---

生成日: 2026-06-19 / BPM 85 / music-2.6 生成 MIDI より
