# KiCAD設計TA

回路設計における知識と技能を競いながら学びましょう．

---

## TA_01
ATtiny402でNeoPixelを3つ光らせる基板です．

条件
・配線は1層のみ（リード部品の反転可）
・NeoPixelの電源はUSB typeC
・ATtinyはマイコン間通信用のUARTを用意すること
・基板外形の最大寸法は40x40mm^2
・タイマースタートはプロジェクトのSCHを開いた瞬間
・タイマーストップはJLCPCB用の製造ファイルをZipにまとめた瞬間

### サンプル画像
![サンプル表](./figs/f.png)
![サンプル裏](./figs/b.png)

---

## インストール方法

```bash
git clone https://github.com/Awattson/KiCAD_DTA.git
mkdir username_TA_01
cd username_TA_01
# KiCADのプロジェクトを作成して始めましょう
