# Midjourney 配图生成指令

## 使用方法
1. 打开 Discord，进入 Midjourney 频道
2. 输入 `/imagine prompt:` 后跟下面的 prompt
3. 等待生成，选择满意的版本
4. 下载并重命名，保存到 `F:\ClaudeFiles\test\images\` 目录

---

## 图 1：烛光斧影（封面图）

```
/imagine prompt: Ancient Chinese palace bedroom at night, flickering candlelight casting two mysterious silhouettes on the wall, dramatic chiaroscuro lighting, dark moody atmosphere, Song Dynasty imperial interior, cinematic composition, historical drama style, digital illustration, ultra detailed --ar 16:9 --v 6.0 --style raw
```

**保存为**: `01-烛光斧影.jpg`

---

## 图 2：五代十国形势图

```
/imagine prompt: Historical map of Five Dynasties and Ten Kingdoms period China, ancient Chinese scroll map style, five different colored regions marked, hand-painted aesthetic, educational illustration, clean labels, parchment texture, traditional cartography --ar 16:9 --v 6.0
```

**保存为**: `02-五代地图.jpg`

---

## 图 3：陈桥兵变 - 黄袍加身

```
/imagine prompt: Zhao Kuangyin being crowned with yellow imperial robe by soldiers in ancient Chinese military camp, Song Dynasty founding scene, crowd of warriors kneeling and cheering, epic historical painting, dramatic moment, traditional Chinese art style meets cinematic lighting, detailed armor and costumes --ar 16:9 --v 6.0 --style raw
```

**保存为**: `03-黄袍加身.jpg`

---

## 图 4：赵匡胤肖像

```
/imagine prompt: Portrait of Zhao Kuangyin, first emperor of Song Dynasty, wearing black and red imperial dragon robe, majestic and powerful expression, middle-aged Chinese emperor with beard, traditional Chinese imperial portrait style, regal atmosphere, studio lighting, detailed embroidery --ar 3:4 --v 6.0 --style raw
```

**保存为**: `04-赵匡胤.jpg`

---

## 图 5：赵光义肖像

```
/imagine prompt: Portrait of Zhao Guangyi, second emperor of Song Dynasty, wearing imperial robes, complex and slightly sinister expression, cunning eyes, middle-aged Chinese emperor, traditional Chinese portrait style, dramatic side lighting, moody atmosphere --ar 3:4 --v 6.0 --style raw
```

**保存为**: `05-赵光义.jpg`

---

## 图 6：金匮之盟

```
/imagine prompt: Ancient Chinese golden ceremonial box containing imperial edict scroll, Song Dynasty palace interior, mysterious atmosphere, warm candlelight, historical artifact photography style, ornate details, traditional Chinese craftsmanship --ar 16:9 --v 6.0 --style raw
```

**保存为**: `06-金匮之盟.jpg`

---

## 批量生成技巧

### 一次性生成多张
可以用 `--chaos` 参数增加多样性：
```
--chaos 20
```

### 生成后变体
- 选择满意的图后，点击 `V1/V2/V3/V4` 生成变体
- 点击 `U1/U2/U3/U4` 放大高清版本

### 风格统一
所有图都使用了 `--style raw` 参数，保持写实风格统一。

---

## 文件命名

生成后按以下命名保存到 `images/` 目录：

```
images/01-烛光斧影.jpg
images/02-五代地图.jpg
images/03-黄袍加身.jpg
images/04-赵匡胤.jpg
images/05-赵光义.jpg
images/06-金匮之盟.jpg
```

---

## 文章中使用

生成图片后，在文章开头添加：

```markdown
![烛光斧影](images/01-烛光斧影.jpg)
```

其他图片按位置插入对应章节。
