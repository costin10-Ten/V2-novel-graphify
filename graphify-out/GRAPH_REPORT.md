# Graph Report - my_data  (2026-04-26)

## Corpus Check
- Corpus is ~5,622 words - fits in a single context window. You may not need a graph.

## Summary
- 118 nodes · 194 edges · 19 communities detected
- Extraction: 61% EXTRACTED · 37% INFERRED · 3% AMBIGUOUS · INFERRED: 71 edges (avg confidence: 0.79)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_議題筆記|議題筆記]]
- [[_COMMUNITY_弦音幾何 (String-Tone Geometry)|弦音幾何 (String-Tone Geometry)]]
- [[_COMMUNITY_新竹科學工業園區|新竹科學工業園區]]
- [[_COMMUNITY_洛克頓|洛克頓]]
- [[_COMMUNITY_1983年台海技術危機|1983年台海技術危機]]
- [[_COMMUNITY_1984年大事年表|1984年大事年表]]
- [[_COMMUNITY_1980年大事年表|1980年大事年表]]
- [[_COMMUNITY_1982年台北文化景象|1982年台北文化景象]]
- [[_COMMUNITY_愛因斯坦路線（最低限度防禦原則）|愛因斯坦路線（最低限度防禦原則）]]
- [[_COMMUNITY_AIDS命名（疾管中心正式命名）|AIDS命名（疾管中心正式命名）]]
- [[_COMMUNITY_美國 (2040)|美國 (2040)]]
- [[_COMMUNITY_歐聯 (2040)|歐聯 (2040)]]
- [[_COMMUNITY_日本 (2040)|日本 (2040)]]
- [[_COMMUNITY_韓國 (2040)|韓國 (2040)]]
- [[_COMMUNITY_俄羅斯 (2040)|俄羅斯 (2040)]]
- [[_COMMUNITY_東南亞 (2040)|東南亞 (2040)]]
- [[_COMMUNITY_非洲 (2040)|非洲 (2040)]]
- [[_COMMUNITY_南美洲 (2040)|南美洲 (2040)]]
- [[_COMMUNITY_澳洲與紐西蘭 (2040)|澳洲與紐西蘭 (2040)]]

## God Nodes (most connected - your core abstractions)
1. `弦音幾何 (String-Tone Geometry)` - 13 edges
2. `新竹科學工業園區` - 11 edges
3. `霍予舟` - 11 edges
4. `穩定者（恆）` - 10 edges
5. `1983年台海技術危機` - 10 edges
6. `議題筆記` - 9 edges
7. `夢溪閣` - 8 edges
8. `影集式推理（第二階段）` - 8 edges
9. `1980年大事年表` - 8 edges
10. `1983年大事年表` - 8 edges

## Surprising Connections (you probably didn't know these)
- `地動演算法（萬恩核心方法論）` --semantically_similar_to--> `弦音幾何 (String-Tone Geometry)`  [INFERRED] [semantically similar]
  my_data/隨筆.md → my_data/graphify-out/converted/2040世界概況_2_弦音幾何_4044409e.md
- `弦音幾何 (String-Tone Geometry)` --semantically_similar_to--> `資訊場動力學`  [INFERRED] [semantically similar]
  my_data/graphify-out/converted/2040世界概況_2_弦音幾何_4044409e.md → my_data/graphify-out/converted/2040世界概況_3_資訊場動力學_902bc292.md
- `覺醒者` --semantically_similar_to--> `類比主義`  [INFERRED] [semantically similar]
  my_data/graphify-out/converted/2040世界概況_1_紋質_071092cb.md → my_data/寫作計畫.md
- `「海鷗」秘密工作小組` --conceptually_related_to--> `穩定者（恆）`  [AMBIGUOUS]
  my_data/1982.md → my_data/graphify-out/converted/2040世界概況_中華邦聯_c273fca7.md
- `穩定者（恆）` --references--> `1983年台海技術危機`  [AMBIGUOUS]
  my_data/graphify-out/converted/2040世界概況_中華邦聯_c273fca7.md → my_data/1983.md
- `1980年大事年表` --references--> `1981年大事年表`  [INFERRED]
  my_data/1980.md → my_data/1981.md
- `手稿核心方程式（夢溪閣研析）` --semantically_similar_to--> `弦音幾何 (String-Tone Geometry)`  [INFERRED] [semantically similar]
  my_data/1982.md → my_data/graphify-out/converted/2040世界概況_2_弦音幾何_4044409e.md
- `覺醒者` --references--> `長篇史詩（第三階段）`  [INFERRED]
  my_data/graphify-out/converted/2040世界概況_1_紋質_071092cb.md → my_data/寫作計畫.md
- `拉馬努金1947年弦音幾何遺稿` --semantically_similar_to--> `手稿核心方程式（夢溪閣研析）`  [INFERRED] [semantically similar]
  my_data/graphify-out/converted/2040世界概況_2_弦音幾何_4044409e.md → my_data/1982.md
- `穩定者（恆）` --references--> `穩定者蘇聯「受控轉型」候選人評估`  [EXTRACTED]
  my_data/graphify-out/converted/2040世界概況_中華邦聯_c273fca7.md → my_data/1984.md

## Hyperedges (group relationships)
- **1983三重危機共振：台海技術危機+KAL007+神弓83同時壓縮決策空間** — tai_hai_wei_ji_1983, kal007_shi_jian, able_archer_83 [INFERRED 0.85]
- **穩定者長線棋局：夢溪閣→弦音幾何→YBCO→C-Score時代** — wen_ding_zhe, wen_ding_zhe_jue_yi, meng_xi_ge, xian_yin_ji_he, ybco_chao_dao, c_score [EXTRACTED 0.95]
- **台灣技術主權弧線：晶片長城→台海危機→香港接觸→《滬台協議》** — jin_pian_chang_cheng, tai_hai_wei_ji_1983, xiang_gang_jie_chu_1983, lu_tai_xie_yi, xin_zhu_yuan_qu [EXTRACTED 0.95]
- **意義危機社會體系：長和平→意義焦慮→夢遊者危機→模擬旅程→類比主義** — chang_he_ping, yi_yi_jiao_lv, meng_you_zhe_wei_ji, mo_ni_lu_cheng, lei_bi_zhu_yi [INFERRED 0.85]
- **數位監控生態系：C-Score+數據資本+默娘AI+Vita手環+安塔神經接口+PRISM** — c_score, shu_ju_zi_ben, mo_niang_ai, vita_shou_huan, an_ta_shen_jing, prism_ping_tai [INFERRED 0.88]
- **第三階段文明崩裂核心：邦聯分裂+鍾悅璟+勒托AGI+長篇史詩** — bang_lian_fen_lie_2051, zhong_yue_jing, le_tuo_agi, chang_pian_shi_shi [INFERRED 0.82]
- **裏層物理體系：紋質+弦音幾何+資訊場動力學+場共鳴運算+R相晶格** — wen_zhi, xian_yin_ji_he, zi_xun_chang_dong_li_xue, chang_gong_ming_yun_suan, r_xiang_jing_ge [EXTRACTED 0.95]
- **霍予舟發現弧線：史丹佛遺稿→H-ALD突破→晶格即語言→弦音幾何** — huo_yu_zhou, la_ma_nu_jin_gao, 1982_h_ald_technology, jing_ge_ji_yu_yan, xian_yin_ji_he [EXTRACTED 0.92]

## Communities

### Community 0 - "議題筆記"
Cohesion: 0.11
Nodes (27): 安塔神經接口, 邦聯分裂2051, C-Score 公民評分, 蒼穹之盾（平流層氣溶膠注射）, 長和平, 長篇史詩（第三階段）, 洞察筆記, 非侵入式神經接口 (+19 more)

### Community 1 - "弦音幾何 (String-Tone Geometry)"
Cohesion: 0.23
Nodes (19): 1987年連結（YBCO高溫超導體、夢溪閣新物理基礎）, 晶格幾何方程式（霍予舟手稿）, 手稿核心方程式（夢溪閣研析）, 夢溪閣無名數學家成員, 場共鳴運算, 高紋質親和度個體 (HSA), 霍予舟, 「晶格即語言」直覺（霍予舟，1984） (+11 more)

### Community 2 - "新竹科學工業園區"
Cohesion: 0.2
Nodes (17): 1985年連結（台灣第一座晶圓廠試產）, 2003年連結（3D晶片技術主流化，霍予舟提案重新發掘）, 《三維積體電路製程可行性初探》提案, 三維NAND技術, H-ALD技術（三維製程遠祖）, 蔣經國, 李國鼎, 有限度政治改革內部評估報告 (+9 more)

### Community 3 - "洛克頓"
Cohesion: 0.2
Nodes (12): 1983年連結（洛克頓倒閉、海鷗香港接觸）, 阿根廷軍政府, 福克蘭群島戰爭, 洛克頓, 雷根衰退, 鐵鏽地帶工廠關閉潮, 柴契爾夫人, 萬恩 (+4 more)

### Community 4 - "1983年台海技術危機"
Cohesion: 0.27
Nodes (11): 中共十二大（鄧小平「有中國特色的社會主義」）, 「海鷗」秘密工作小組, 神弓83演習核戰警報, KAL007客機被擊落事件, 民主化進程延宕（危機正當性壓制）, 1981年大事年表, 1982年大事年表, 1983年大事年表 (+3 more)

### Community 5 - "1984年大事年表"
Cohesion: 0.22
Nodes (9): 戈巴契夫, 1984年大事年表, 1985年大事年表, 1986年大事年表, 1987年大事年表, 1988年大事年表, 1989年大事年表, 1990年大事年表 (+1 more)

### Community 6 - "1980年大事年表"
Cohesion: 0.5
Nodes (5): 愛因斯坦路線（以色列架空歷史路徑）, 林宅血案（1980）, 美麗島事件審判（1980）, 1980年大事年表, 中東 (2040)

### Community 7 - "1982年台北文化景象"
Cohesion: 0.67
Nodes (4): 《銀翼殺手》, 《E.T.》, 1982年台北文化景象, 《顫慄》（Thriller）—麥可·傑克森

### Community 8 - "愛因斯坦路線（最低限度防禦原則）"
Cohesion: 1.0
Nodes (3): 愛因斯坦路線（最低限度防禦原則）, 以色列出兵黎巴嫩, 薩布拉—夏提拉難民營事件

### Community 9 - "AIDS命名（疾管中心正式命名）"
Cohesion: 1.0
Nodes (2): AIDS命名（疾管中心正式命名）, 雷根政府

### Community 10 - "美國 (2040)"
Cohesion: 1.0
Nodes (1): 美國 (2040)

### Community 11 - "歐聯 (2040)"
Cohesion: 1.0
Nodes (1): 歐聯 (2040)

### Community 12 - "日本 (2040)"
Cohesion: 1.0
Nodes (1): 日本 (2040)

### Community 13 - "韓國 (2040)"
Cohesion: 1.0
Nodes (1): 韓國 (2040)

### Community 14 - "俄羅斯 (2040)"
Cohesion: 1.0
Nodes (1): 俄羅斯 (2040)

### Community 15 - "東南亞 (2040)"
Cohesion: 1.0
Nodes (1): 東南亞 (2040)

### Community 16 - "非洲 (2040)"
Cohesion: 1.0
Nodes (1): 非洲 (2040)

### Community 17 - "南美洲 (2040)"
Cohesion: 1.0
Nodes (1): 南美洲 (2040)

### Community 18 - "澳洲與紐西蘭 (2040)"
Cohesion: 1.0
Nodes (1): 澳洲與紐西蘭 (2040)

## Ambiguous Edges - Review These
- `穩定者（恆）` → `「海鷗」秘密工作小組`  [AMBIGUOUS]
  my_data/1982.md · relation: conceptually_related_to
- `穩定者（恆）` → `1983年台海技術危機`  [AMBIGUOUS]
  my_data/1983.md · relation: references
- `蔣經國` → `阿根廷軍政府`  [AMBIGUOUS]
  my_data/1982.md · relation: semantically_similar_to
- `有限度政治改革內部評估報告` → `愛因斯坦路線（最低限度防禦原則）`  [AMBIGUOUS]
  my_data/1982.md · relation: semantically_similar_to
- `海峽技術整合備忘錄` → `「建國家的另一種主權」（李國鼎語錄）`  [AMBIGUOUS]
  my_data/1982.md · relation: semantically_similar_to

## Knowledge Gaps
- **31 isolated node(s):** `R相晶格`, `美國 (2040)`, `歐聯 (2040)`, `日本 (2040)`, `韓國 (2040)` (+26 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **Thin community `AIDS命名（疾管中心正式命名）`** (2 nodes): `AIDS命名（疾管中心正式命名）`, `雷根政府`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `美國 (2040)`** (1 nodes): `美國 (2040)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `歐聯 (2040)`** (1 nodes): `歐聯 (2040)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `日本 (2040)`** (1 nodes): `日本 (2040)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `韓國 (2040)`** (1 nodes): `韓國 (2040)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `俄羅斯 (2040)`** (1 nodes): `俄羅斯 (2040)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `東南亞 (2040)`** (1 nodes): `東南亞 (2040)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `非洲 (2040)`** (1 nodes): `非洲 (2040)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `南美洲 (2040)`** (1 nodes): `南美洲 (2040)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `澳洲與紐西蘭 (2040)`** (1 nodes): `澳洲與紐西蘭 (2040)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What is the exact relationship between `穩定者（恆）` and `「海鷗」秘密工作小組`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **What is the exact relationship between `穩定者（恆）` and `1983年台海技術危機`?**
  _Edge tagged AMBIGUOUS (relation: references) - confidence is low._
- **What is the exact relationship between `蔣經國` and `阿根廷軍政府`?**
  _Edge tagged AMBIGUOUS (relation: semantically_similar_to) - confidence is low._
- **What is the exact relationship between `有限度政治改革內部評估報告` and `愛因斯坦路線（最低限度防禦原則）`?**
  _Edge tagged AMBIGUOUS (relation: semantically_similar_to) - confidence is low._
- **What is the exact relationship between `海峽技術整合備忘錄` and `「建國家的另一種主權」（李國鼎語錄）`?**
  _Edge tagged AMBIGUOUS (relation: semantically_similar_to) - confidence is low._