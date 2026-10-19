# Kocks SRB-360/500 spare parts sourcing: full handoff file

Status snapshot: Fri 16.10.2026, ~21:00 (Asia/Shanghai). Compiled Mon 19.10.2026 from the whole chat.
Anything that happened after 16.10 evening is NOT in here. Re-check all 1688 chats and WeChat first.

---

## 1. Project in one paragraph

Source made-to-drawing spare parts for **Kocks SRB-360/500 mill stands** from Chinese factories for the customer **Жасулан** (WhatsApp). The customer's buyer entity is Yiwu Jiali. We buy for him through **East Gate Partners (EGP), Guangzhou**. Delivery is **EXW from the factories**, then trucked by us to **Pavlodar, Kazakhstan** (~4000 km). The user is Mawzik (Project Manager at EGP). Work language: Russian for the customer and boss, Chinese for factories.

The original customer message (paraphrased from the user's first message): AI had already processed all drawings into an RFQ in Chinese+Russian plus drawings so it can be forwarded straight to manufacturers. A contract already exists, the 160-day delivery clock starts the next day (16.10.2026). Average manufacturing time is 100–120 days, but Chinese New Year is approaching, so goods are needed earlier.

## 2. Customer facts and decisions

- **Contract deadline:** arrival in Pavlodar 160 days from 16.10.2026 = **25.03.2027**.
- One consolidated shipment preferred ("лучше собрать все вместе").
- Advance is paid once the factories are chosen.
- **Scope:** only items in the RFQ. Exclude drawing 29564/1c and TIMKEN M272749DV.
- **Bearing (pos 50)** is a separate procurement. The customer will send drawings and other info. Not yet received.
- Customer on price enquiries: "до этого при запросе цен не спрашивали" (he can ask the question if needed).
- **User's approach:** first just ask the factories for their own lead times and don't push our deadline; negotiate later "так как заказ хороший".

### Timeline plan
- Chinese New Year 06.02.2027; factories effectively down ~25.01–20.02.
- Target: all ready by ~20.01; ship by ~01.03; transit ~15–20 days.
- Quotes by **22.10**; choose by **29.10**; contracts and advance by ~**05.11**.

## 3. The seven lots (RFQ positions)

| Lot | Content | Positions |
|---|---|---|
| L1 | Ductile iron castings QT600-3 / QT500-7 + machining + electroless Ni 25 µm (~131 pcs, ~1.7 t) | 15, 16, 19, 22, 24, 26, 27, 28, 31 |
| L2 | 42CrMo4 forged shafts with Hirth face teeth (induction hardened 54±2 HRC) + straight bevel gears/segments m4–4.5, DIN 3965 class 8 (53 pcs, 5 drawings) | 23, 44, 32, 41, 43 |
| L3 | C45/S355 rings/flanges (Ø180–300, 6–19 kg) + pins; QPQ or Ni | 1, 2, 3, 4, 42, 45, 49, 38, 39, 40 |
| L4 | CuSn12 centrifugal bush (pos 25), CuZn35Al1 shims (36, 37, 46, 47, 48), Al EN AW-1050A labyrinth rings (33, 34) | 25, 36, 37, 46, 47, 48, 33, 34 |
| L5 | LAMINUM peelable shim pack, drawing 28074/3b, 18 pcs | 35 |
| L6 | Standard parts | 5–14, 17, 18, 20, 21, 29, 30 |
| L7 | Bearing M263349D/M263310/M263310D (4-row set, 355.6×488.95×317.5). Wafangdian Longfei lists ~13,840 CNY/set | 50 |

### Standard parts detail (L6)
- KMT20 / KMT24 / KMT28 / KMT32 locknuts.
- DIN 471 circlips Ø150 ×21 pcs, Ø180 ×12 pcs (65Mn, 4 mm thick).
- DIN 912 12.9: M8×16, M8×70, M10×25, M10×80, M10×90, M12×25, 300 each.
- DIN 912 10.9: M8×20, 300 pcs.
- Nuts class 8: M10, M12, 300 each.
- O-ring NBR70 265×4, 30 pcs.

### Pos 35 drawing facts (important)
- Material "LAMINIUM"; rev a had TENIFER Q, so it is **steel** (probably carbon steel; factories quote 304 stainless, which is not confirmed).
- **Ø176 is the OUTER diameter**; 6×Ø11 holes on Ø150.
- Section A-A shows 4 mm and 1.5 mm; **total 4 mm** (3 mm is the theoretical fitted size). Weight 0.29 kg is consistent with steel.
- Open question to customer: material (304 vs carbon steel?) and single-layer thickness (0.05 or 0.1 mm).

### Aluminium rings, pos 33/34 (Lot 4)
- Pos 33 outer labyrinth ring, drawing 23916/2; pos 34 inner ring, drawing 23915/2.
- EN AW-1050A (Al99.5), wall 1.6 mm, 0.031 / 0.037 kg, **15 pcs each**.
- Files: `P33_23916-2.pdf`, `P34_23915-2.pdf`.

## 4. Files on the user's computer

Folder: `/Users/guanhzhou/Desktop/EGPC Projects/Tender` (VM path `~/mnt/Tender`).

- `RFQ_SRB_Kocks_RU-CN.xlsx`: original RFQ. Data rows 15–65, header row 13, section rows 14 and 48, totals row 66. Columns K–P are yellow supplier cells. Sheet 2 "Условия 条款" has 16 clauses (EXW; prices CNY incl. 13% VAT with special VAT invoice; 3.1 certs; 120-day target; 30% advance / 70% after inspection; inspection before pickup; confidentiality).
- `RFQ_для_заводов/`: LotN folders (each with its RFQ xlsx and renamed drawings P01_30333-0.pdf … P50_TIMKEN-M263349DV.xlsx) plus a zip per lot:
  - Lot0_全部_Все-позиции
  - Lot1_球铁铸件_Отливки-ВЧ
  - Lot2_锻件齿轮_Валы-шестерни
  - Lot3_钢件机加工_Сталь-мехобработка
  - Lot4_铜铝件_Бронза-латунь-алюминий
  - Lot5_可剥垫片_LAMINUM
  - Lot6_标准件_Стандартные-изделия
  - Lot7_轴承_Подшипник
  - RFQ header per lot: D4 `RFQ-SRB-2026-10-01-Lx`; D6 East Gate Partners (VAT details later); D9 `East Gate Partners · +86 133 4283 4121 · coo@egpgroup.com`; D10 `22.10.2026`. TIMKEN file has the "ПС" sheet removed.
- `SRB_Kocks_план_закупки.xlsx`: tracker. Sheets: Позиции, Заводы, График, Вопросы клиенту, Сообщение заводу. Заводы columns: A Лот, E name, F city, G contact, H source, I Отправлено, J КП получено, K Сумма, L Срок, M До CNY?, N Комментарий.
- `КП_получено/` (created 16.10): `КП_L4_嘉兴荣昌_16.10.xlsx`, `КП_L5_鸿展_16.10.png`, `КП_L5_铧盛_16.10.png`.
- `Чертежи/` (drawings), `_tmp/` (temp render `p35.png`; **I could not delete it, user must delete**).
- Helper scripts (device VM home, not the user's folder): `~/work/make_lots.py`, `tracker.py`, `add1688.py`.

## 5. Customer / boss messages written (Russian)

- Progress overview for the boss was written earlier in the chat (short Russian summary; text not preserved here).
- Questions to the customer were sent; his answers are in section 2.
- **Latest customer status message (draft given 16.10, not confirmed sent):**

> Жасулан, добрый вечер! Коротко по RFQ Kocks SRB:
> • Позиции разбили на 7 лотов по типу производства и разослали запросы с чертежами на заводы.
> • По каждому лоту на связи 2–5 заводов, первые КП уже пришли (бронза/латунь, пакет пластин поз. 35, гайки KMT).
> • По остальным лотам заводы считают, основную часть КП ждём до 22.10.
> • Сроки изготовления запрашиваем с учётом китайского Нового года, чтобы всё было готово до остановки заводов в конце января.
>
> Вопрос по поз. 35 (пакет пластин, черт. 28074/3b):
> 1. Материал: заводы предлагают нержавейку 304. Подходит, или нужна углеродистая сталь?
> 2. Толщина одного слоя: 0,05 или 0,1 мм?
>
> По подшипнику (поз. 50) ждём от вас чертежи.
> Сводку цен и сроков по всем лотам пришлю, как соберём КП.

## 6. Supplier status as of 16.10 evening

Legend: uid = 1688 chat id (`touid=cnalichn` + URL-encoded uid).

### Lot 1: castings
| Supplier | uid / contact | Status |
|---|---|---|
| 宁津利久机械制造有限公司 | uid 宁津利久机械制造有限公司 | Received RFQ + drawings, calculating. WeChat ID (wxid) wasn't addable; asked for a name card; user later said contacted already |
| 硕力机械铸造 (宁津桑工) | WeChat/tel 18506408885 | **DECLINED 16.10**: only grey iron 150–250 and ductile 400–500, can't do QT600 |
| 宁津县伟辰机械有限公司 | uid 宁津县伟辰机械有限公司 | Said "可以做", hasn't received files yet. **User must send Lot 1 zip** |
| 泊头宇天机械 | uid 泊头宇天机械 | OK reply, waiting |
| 南通永威 | uid 南通永威机械有限公司 | Silent ("稍等") |
| 重庆烨烽铸造 | uid 重庆烨烽铸造有限公司 | Not contacted |
| 郑州恒众 | uid zzhzzg | Declined (parts too small) |
| 辉县腾飞 | uid 腾飞大型铸件厂 | Declined (only >1 t) |

→ Need **3–4 more QT600-3 foundries**.

### Lot 2: shafts / gears
| Supplier | uid / contact | Status |
|---|---|---|
| 佛山市奥迪斯传动科技 (叶林) | WeChat/tel **13728565090** | Asks: drawings, quantity, company name. Waiting for us to add WeChat and send Lot 2 zip |
| 沃孚尔传动技术 | uid 沃孚尔传动技术有限公司 | Replied «好»; asked for WeChat/email, no answer |
| 洛阳奥普信 | uid lyapx | Sent, no reply |
| 广州升力 | uid slcl240419798 | Saw QR code (replied 🌹, "稍等"), hasn't added us. Their lot = 5 drawings |
| 河北华谦 | uid 华谦传动配件 | Silent |
| 诸暨麦驰 | uid 诸暨市麦驰齿轮有限公司 | Not contacted |
| LMM Group | info@lmm-rollingmill.com, +86 411 84174804 | Email draft below, user to send |

### Lot 3: steel / QPQ
| Supplier | Contact | Status |
|---|---|---|
| 东莞江序精密 | uid jx202609江序; **email 2315949291@qq.com** | User emailed Lot 3 zip. Also asked (1688) to quote Al rings pos 33/34; they replied "好的。您稍等" |
| 台州黄岩腾飞 | uid hytfjx | Only auto-reply |
| 山东鑫昭 | – | **Declined** |
| 苏州光中 (QPQ heat treatment) | uid 苏州专业热处理 | Silent |

### Lot 4: bronze / brass / Al
| Supplier | Contact | Status |
|---|---|---|
| 嘉兴荣昌 | WeChat/tel **17758253222** | **QUOTED 57,940 CNY incl. VAT, 40 days** (details §7). Do NOT make aluminium |
| 佛山利昌业机械铸造 | uid 利昌业机械铸造; email **120691148@qq.com** | Got Lot 4 via WeChat; user emailed zip 16.10; calculating |
| 广东洪全机械 | uid 洪全机械 | Sent, silent |
| 无锡鑫元辉铜业 | uid 无锡市鑫元辉铜业有限公司 | Sent, silent |
| 江苏双振荣铜业 | uid 江苏双振荣铜业 | Not contacted |

Aluminium rings 33/34: nobody has quoted yet (江序 is the only lead; fallback = aluminium CNC shop in Dongguan).

### Lot 5: peelable shims (pos 35)
| Supplier | Contact | Quote |
|---|---|---|
| 深圳鸿展五金精密 (胡孟浪) | WeChat/tel 13028863481; uid 鸿展五金精密 | 304 stainless Ø176×Ø120, total 4.0 = 1.5 + layers; **0.05 mm×50 layers: 403/pc (7,254); 0.10 mm×25 layers: 343/pc (6,174); EX VAT 13%**, excl. freight (SF), 100% prepayment ("先款后货"), lead time 7–15 days. Quote sheet saved as PNG |
| 深圳铧盛精密 (YDF-雷井香) | WeChat/tel 18098910935; uid 铧盛精密 | 18 pcs, **with VAT: 0.05 mm = 455/pc (8,190); 0.1 mm = 387/pc (6,966)**; ex-VAT 403 / 343. Lead time not stated |
| 深圳精属科技 | uid 精属科技 | Silent |

Note: both quote exactly the same ex-VAT price, so probably the same maker or one reselling. Ask 铧盛 who actually makes it and what material.

### Lot 6: standard parts
| Supplier | Contact | Status |
|---|---|---|
| 凯恩博机械（山东） (KMT) | uid 凯恩博; WeChat added | KMT in stock, incl. VAT: KMT20 176, KMT24 216, KMT28 248, KMT32 319 CNY → **17,388 CNY total**. Don't do rings/screws/O-ring |
| 广州新诺德 (xnd2014) | uid xnd2014 | Silent |
| 苏州威尔捷工业 | uid 苏州威尔捷工业 | Full list sent; they asked VAT/delivery → answered: price incl. 13% special VAT invoice, freight extra, address on order (Jiangsu/Zhejiang or Guangzhou); also asked for 12.9 brand. Waiting |
| 泰州工品金超紧固件 | uid 工品金超紧固件 | Full list sent, "嗯嗯", waiting |
| 瑞安峰泰标准件 | – | **No Ø150/Ø180 circlips** ("没有哦") |
| 乐清智健 (xlh五金) | uid xlh五金 | Circlip request sent, replied "你好" only |

### Lot 7: bearing
Waiting for customer's drawings. Candidates noted: 瓦房店龙飞 (~13,840 CNY/set), 亚代轴承, 山东联宇, LYC/ZWZ/HRB.

## 7. Received quotes: detail

### 嘉兴荣昌 (Lot 4), file `КП_L4_嘉兴荣昌_16.10.xlsx`, total 57,940 CNY incl. VAT, 40 days
| Pos | Part | Qty | Unit CNY | Total |
|---|---|---|---|---|
| 25 | Bearing bush CuSn12, centrifugal | 15 | 2,620 | 39,300 |
| 36 | Thrust washer Ø217 (CuZn35Al1) | 19 | 100 | 1,900 |
| 37 | Thrust washer Ø260 | 18 | 160 | 2,880 |
| 46 | Adjusting disc Ø335 (G-CuZn35Al1) | 18 | 450 | 8,100 |
| 47 | Spacer Ø220 | 18 | 120 | 2,160 |
| 48 | Spacer Ø264 | 18 | 200 | 3,600 |

Pos 25 is 2/3 of the total (~260 CNY/kg). Benchmark it against 利昌业. They state they only make bronze and brass, not aluminium.

### Lot 5 and Lot 6 quotes: see tables above (鸿展, 铧盛, 凯恩博).

## 8. Message templates (Chinese, sent via 1688)

**Lot 2 (shafts/gears):**
您好！我们是广州 East Gate Partners，为海外钢厂采购轧机备件（按图加工）。现有一批询价：42CrMo4锻件轴（带Hirth端面齿，齿面感应淬火54HRC，单重11–69kg）及直齿锥齿轮/扇形齿段（m4–4.5，DIN 3965 8级），5种共约53件。请问贵厂能做吗？如果可以，麻烦留个微信或邮箱，我来加您，把中俄双语询价单和图纸发过去，请报价并告知生产周期和春节放假安排。数量较大，后续还有返单。谢谢！

**Lot 3 (steel/QPQ):**
您好！我们是广州 East Gate Partners，为海外钢厂采购轧机备件（按图加工）。现有一批询价：C45（45#）/S355钢环形件、法兰（外径约Ø180–300mm，单重6–19kg），表面QPQ或化学镀镍，另有几种销轴，共约10种。请问贵厂能做吗（表面处理可外协）？如果可以，麻烦留个微信或邮箱，我来加您，把中俄双语询价单和图纸发过去，请报价并告知生产周期和春节放假安排。后续还有返单。谢谢！

**Lot 4 (bronze/brass):**
… 锡青铜CuSn12离心铸造轴套（Ø194，内螺纹M160×3，单重10kg，15件）及铸造铝黄铜CuZn35Al1垫圈/调整盘（Ø217–335，约90件），按图机加工。请问贵厂能做吗？如果可以，麻烦留个微信或邮箱，我来加您，把中俄双语询价单和图纸发过去，请报价并告知生产周期和春节放假安排。数量较大，后续还有返单。谢谢！

**Lot 6 (screws/nuts/rings):**
您好！我们是广州 East Gate Partners，为海外钢厂采购备件，需要以下标准件报价：①DIN 912 12.9级内六角螺钉 M8×16、M8×70、M10×25、M10×80、M10×90、M12×25 各300件；②DIN 912 10.9级 M8×20 300件；③8级六角螺母 M10、M12 各300件；④如能一起供更好：DIN 471轴用挡圈 Ø150（21件）、Ø180（12件），NBR70 O型圈 265×4（30件）。请报含税价，注明品牌/产地、是否现货及交期，需提供材质证明。方便留个微信或邮箱吗？谢谢！

**Circlip-only:** 需要DIN 471轴用弹性挡圈报价：Ø150（150×4）21件，Ø180（180×4）12件，材质65Mn/弹簧钢。另外如有也请一起报：NBR70 O型圈 265×4 30件。请报含税价，告知是否现货及交期。

**WeChat contact given to suppliers:** wxid_pm8bmshb314h12 (phone/WhatsApp +852 9376 4275), "备注：轧机备件". Caveat: a `wxid_` ID is not searchable. Suppliers should leave their own WeChat, or the user sends a name card/QR.

## 9. LMM Group email draft (for the user to send)

To: info@lmm-rollingmill.com
Subject: RFQ – spare parts for Kocks 3-roll stands SRB-360/500 (made to drawing)

> Dear LMM team,
> We are East Gate Partners (Guangzhou), sourcing spare parts for a steel plant in Kazakhstan. We have an RFQ for parts of Kocks 3-roll reducing/sizing stands SRB-360/500, all made to customer drawings:
> - ductile iron castings (QT600-3 / QT500-7) with machining and electroless nickel plating;
> - 42CrMo4 forged shafts with Hirth face teeth (induction hardened 54 HRC) and straight bevel gears/segments m4–4.5, DIN 3965 class 8;
> - C45/S355 machined rings with QPQ, CuSn12 bushes, CuZn35Al1 shims and standard parts.
>
> About 50 positions in total. We can send the bilingual RFQ (CN/RU) and the full drawing set.
> Could you please confirm whether you can quote the whole package or part of it, and advise your production lead time and Chinese New Year shutdown period? Delivery terms: EXW your factory.
>
> Best regards, [Name] · East Gate Partners · +86 133 4283 4121 · coo@egpgroup.com

Fix before sending: 50 positions includes the bearing, which is bought separately (say ~49 or add one line).

## 10. How the 1688 chat automation worked (for whoever continues)

- Open chat directly: `https://air.1688.com/app/ocms-fusion-components-1688/def_cbu_web_im/index.html?touid=cnalichn<URL-encoded uid>&siteid=cnalichn&status=1`. Wait ~7 s. Frame size is 800x872 in the built-in browser.
- **Reliable typing method (found late):** focus the input via JS, then use the type tool:
  `document.querySelector('iframe').contentDocument.querySelector('[contenteditable="true"]').focus()`
  Then `type` the text, **read the field back via JS to verify it**, then press Return.
  Earlier method (clicking coordinates 450,815 for 800x872) also works but is less safe.
- To clear a draft: select all via `getSelection/createRange` then `execCommand('delete')`.
- Verify a send: read the iframe text and take the slice after the last "进厂"/"暂无更多消息" up to "开启智能".
  `const t=document.querySelector('iframe').contentDocument.body.innerText; t.slice(t.lastIndexOf('进厂'),t.lastIndexOf('开启智能')).slice(-300)`
- Chat list = `t.slice(0,t.indexOf('进厂'))`. Old chats need a visual click in the list (text-click by JS hit the wrong chat once).
- Search: `https://s.1688.com/selloffer/offer_search.htm?charset=utf8&keywords=...` one query per call, wait 5–7 s; read `a[class*="offerCard"]`; uid comes from the IM link `uid=` parameter. Generic keywords return steel traders and nylon shops. Searching by function ("冶金设备配件 机加工 法兰盘") worked better.
- 1688 shows CAPTCHAs; the user must solve them. Screenshots can lag, so verify by iframe text before resending.
- Suppliers on 1688 mostly return **auto-replies**; real answers arrive minutes later. 1688 also shows "off-platform trade risk" banners (ignore).

## 10b. Known uids

| Company | uid |
|---|---|
| 郑州恒众 | zzhzzg |
| 南通永威 | 南通永威机械有限公司 |
| 辉县腾飞 | 腾飞大型铸件厂 |
| 升力 | slcl240419798 |
| 华谦 | 华谦传动配件 |
| 光中 | 苏州专业热处理 |
| 利昌业 | 利昌业机械铸造 |
| 鸿展 | 鸿展五金精密 |
| 精属 | 精属科技 |
| 铧盛 | 铧盛精密 |
| 伟辰 | 宁津县伟辰机械有限公司 |
| 利久 | 宁津利久机械制造有限公司 |
| 硕力 | 硕力机械铸造有限公司 |
| 宇天 | 泊头宇天机械 |
| 新诺德 | xnd2014 |
| 凯恩博 | 凯恩博 |
| 洪全 | 洪全机械 |
| 荣昌 | 嘉兴荣昌轴承 |
| 鑫元辉 | 无锡市鑫元辉铜业有限公司 |
| 双振荣 | 江苏双振荣铜业 |
| 烨烽 | 重庆烨烽铸造有限公司 |
| 洛阳奥普信 | lyapx |
| 沃孚尔 | 沃孚尔传动技术有限公司 |
| 奥迪斯 | 佛山市奥迪斯传动科技 |
| 麦驰 | 诸暨市麦驰齿轮有限公司 |
| 东莞金运来 | jinyunlaikj |
| 江序 | jx202609江序 (touid `jx202609%E6%B1%9F%E5%BA%8F`) |
| 台州腾飞 | hytfjx |
| 鑫昭 | 山东鑫昭金属制品 |
| 威尔捷 | 苏州威尔捷工业 |
| 金超 | 工品金超紧固件 |
| 峰泰 | 瑞安市峰泰标准件有限公司 |
| 智健 | xlh五金 |

## 11. Mistakes made and fixes (so they aren't repeated)

- Told 升力 "共35份左右" drawings; their lot has only 5. Corrected ("贵厂这部分是5份图纸").
- Pos 35: first stated total thickness 3 mm and "内径Ø176". Wrong. Corrected: total 4 mm, Ø176 = OUTER, holes on Ø150.
- Garbled duplicate message to xnd2014 (cmd+a didn't select, texts merged). Sent correction.
- Duplicate tracker row for 铧盛 removed.
- Email draft typo 壁叚 → 壁厚 (told the user).
- 1688 contact-search dropdown clicks failed → use direct `touid` URLs.
- Emulated viewport 1280x900 broke rendering → reset to desktop preset.
- 16.10 typing errors caught before sending: "各95300件" → "各300件"; "壁厄" → "壁厚"; "各150件" → "各15件" (all fixed before the Return key).
- Page wrote to the user's clipboard during input once; the app warned the user.
- Could not delete `Tender/_tmp/p35.png` (rm blocked).

## 12. To-do list

### The user (not me)
1. Add on WeChat **13728565090** (奥迪斯, Lot 2) and **17758253222** (荣昌), send them their lot zips (Lot 2 zip was already delivered to chat; the user can forward it).
2. Email aluminium-ring drawings `P33_23916-2.pdf` and `P34_23915-2.pdf` to **2315949291@qq.com** (江序) if they agreed.
3. Send Lot 1 zip to 伟辰.
4. Send customer the pos 35 question (material, layer thickness) and status message (§5).
5. Send LMM email (§9).
6. Delete `Tender/_tmp`.
7. Wait for bearing drawings from the customer.

### Next steps for the assistant
1. Re-read all 1688 chats and WeChat replies (status changed since 16.10).
2. Find **3–4 more foundries that can do QT600-3** (Lot 1).
3. Chase silent suppliers: Lot 2 (奥迪斯, 沃孚尔, 奥普信, 升力), Lot 3 (江序, 腾飞, 光中), Lot 4 (洪全, 鑫元辉, 利昌业), Lot 6 (威尔捷, 金超, 智健, 新诺德), Lot 1 (利久, 伟辰, 宇天).
4. If 江序 declines the Al rings, find an aluminium CNC shop in Dongguan.
5. Ask 铧盛 who the real maker is and what material; compare with 鸿展.
6. Still need a source for DIN 471 Ø150/Ø180 circlips, DIN 912 screws, nuts and the O-ring if 威尔捷/金超 don't deliver.
7. Build a price/lead-time summary for the customer once quotes are in (due 22.10); factory selection by 29.10.
8. Keep the tracker `SRB_Kocks_план_закупки.xlsx` up to date.

## 13. Open risks

- **QT600-3 foundry shortage** (Lot 1): 硕力 declined; the remaining ones haven't quoted.
- **Pos 35 material mismatch**: factories quote 304 stainless vs. drawing steel; need customer confirmation.
- Pos 25 bush price (2,620/pc) looks high; compare.
- CNY shutdown: lead times must end before ~25.01.
- Tracker is the single source of truth, but the last bulk update was 16.10 ~20:50.
- Don't publish factory names/contacts to the customer (user preference: supplier names, logos and contacts are removed from material sent to clients).
