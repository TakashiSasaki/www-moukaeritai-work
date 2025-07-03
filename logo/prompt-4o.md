# ロゴ生成プロンプト仕様書: moukaeritai.work

## 目次
1. 概要
2. ロゴコンセプト
3. 基本プロンプト
4. バリエーション指定子
   - 4.1 色調バリエーション
   - 4.2 構成要素の差分
   - 4.3 スタイルと用途別調整
5. 使用上の注意と再現性のポイント
6. 将来的な拡張例

---

## 1. 概要
このドキュメントは、個人プロジェクト公開用ドメイン "moukaeritai.work" におけるロゴ生成のプロンプト仕様を体系的に記述したものである。目的は、将来的な再生成およびバリエーション展開の再現性確保である。

## 2. ロゴコンセプト
- **モチーフ**：帰宅後にコンテナやシャックで作業する開発者
- **姿勢**：黙々と作業する孤独な人物像
- **象徴性**：非写実的・シンボリックで視認性の高いロゴ
- **雰囲気**：個人的・没入感・ややミステリアス
- **用途**：OAuth同意画面アイコン、ウェブサイトロゴ、ファビコン、SNSアイコン等

## 3. 基本プロンプト
以下は最も基本となる英語の画像生成プロンプトである：

```text
A minimalist flat-style logo featuring a faceless hooded figure working alone on a laptop and a circuit board inside a simple rectangular shelter (e.g., container or shack), under a crescent moon. The figure is in a dark silhouette with no facial features. The design is clean, iconic, and legible at small sizes (as small as 64x64 px). Use a consistent color palette and clear contrast. No text included.
```

## 4. バリエーション指定子

### 4.1 色調バリエーション
- **パステル調**：
  ```text
  with a soft pastel color palette
  ```
- **サイケデリック**：
  ```text
  with psychedelic colors and high contrast vibrant tones
  ```
- **和風（伝統色）**：
  ```text
  using traditional Japanese color schemes like 深緋, 錆浅葱, 藍白
  ```
- **子供向け**：
  ```text
  with friendly cartoon-style colors suitable for children
  ```
- **ダークモード向け**：
  ```text
  with a dark background and neon-style accents
  ```

### 4.2 構成要素の差分
- **測定器を使っているバージョン**：
  ```text
  Replace the circuit board with a simple vector-style electronic measurement device (e.g., oscilloscope or multimeter) next to the laptop.
  ```
- **背景を透明にする**：
  ```text
  on a transparent background for use as a logo icon
  ```

### 4.3 スタイルと用途別調整
- **小サイズ対応強化**：
  ```text
  simplified and bold shapes with strong contrast, suitable for resizing to 64x64 px
  ```
- **テキストを含めたい場合**：
  ```text
  Add the text "moukaeritai.work" beneath the logo in a clean sans-serif font.
  ```

## 5. 使用上の注意と再現性のポイント
- すべてのプロンプトは英語で記述すること（画像生成AIとの互換性を維持）
- モチーフや構図を変える場合でも「faceless hooded figure」「minimalist」「flat-style」の核は維持
- サイズ制約（64x64px対応）のため、細部描写は避け、象徴性重視
- 色指定は抽象的よりも具体名（pastel, navy blue, traditional Japanese colorsなど）を使う
- 背景が必要な場合は明示（e.g., transparent, beige, dark）

## 6. 将来的な拡張例
- アニメーションバージョン（SVGアニメまたはGIF）
- 季節ごとのカラー展開（例：冬：藍×銀、春：桜色×若草）
- 複数人物・動作追加（仲間との作業風景など）
- プロジェクトごとのアイコン分岐（例：app1.moukaeritai.work 用）

---

