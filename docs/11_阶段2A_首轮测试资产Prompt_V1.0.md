# 阶段2A｜《千年寻缘・珠定团圆》首轮测试资产Prompt V1.0

执行方式：GPT Image 2内置生成路径。每条Prompt只服务一个稳定生产资产ID；全部为阶段2A静态测试资产，不是正式分镜，不包含Seedance2.0镜头Prompt、镜头运动、时长、剪辑、字幕或音乐指令。

读取风格：`docs/08_阶段2A_风格锁定包_V1.0-DRAFT.md`、`docs/10_阶段2A_风格圣经短执行版_V1.0-DRAFT.md`。

## QNXY-2A-TST-001｜苏珏人物剧照验证图

```text
Prompt编号：QNXY-2A-TST-001
Prompt版本：V1.0
关联生产资产ID：QNXY-CHR-P0-001-苏珏
上游生产包：QNXY-PKG-01
风格锁定包：V1.0-DRAFT
生成目的：确认演员锁脸、真实肤质、南宋束发适配、书生气质和常服A色材方向；不替代人物基础多视图
参考素材：Image 1=QNXY-REF-014身份主参考；Image 2=QNXY-REF-011身份/三分之四角度辅助；Image 3=QNXY-REF-007常服A服装发型配饰整体参考
必须继承：同一真人演员骨相五官发际线；185厘米生产尺度观感；温润克制书生气
允许补充：自然肤质；按Image 3整体继承服装、发型及配饰
禁止改变：唯一禁止从Image 3继承的是参考人物脸部五官、骨相与身份信息；苏珏脸必须只取Image 1/2
输出规格：横向16:9，胸部以上人物剧照，约85mm等效，眼平，中性低反差结构光
确认状态：2026-07-15用户提供候选已登记；服饰参考发型与配饰允许整体继承；机器有条件通过；待主创确认身份相似度和肤质
```

Prompt正文：

```text
Use case: photorealistic-natural
Asset type: Stage 2A P0 actor-identity casting still for QNXY-CHR-P0-001-苏珏; static asset validation, not a film shot
Input images: Image 1 is the only main face and identity reference for the actor; preserve its facial bone structure, eye-nose-mouth proportions, hairline and real skin identity. Image 2 is the same authorized actor from a three-quarter angle and supplements cheek, jaw, upper-body and visible-hand proportions only. Image 3 is the complete clothing, hairstyle and accessory reference: inherit its outfit, garment construction, colors, hairstyle and worn/carried accessories together unless the creator later excludes a specific element. The ONLY forbidden inheritance from Image 3 is its person's face, facial bone structure and identity; Su Jue's face must come only from Images 1 and 2.
Primary request: portray the same authorized actor as Su Jue, a young Southern Song lake-dwelling scholar in Sichuan/Chongqing, warm, restrained and observant, credible as a real live-action person rather than a costume model
Scene/backdrop: seamless warm gray-green neutral studio backdrop with a faint soft tonal gradient; no lake set and no architecture
Subject: chest-up portrait, natural straight posture, shoulders relaxed, head turned only a few degrees from the lens, calm low-amplitude expression, no smile for camera; authentic Chinese male facial anatomy and the exact same identity as Images 1 and 2
Hair: inherit the hairstyle and hair accessories shown in Image 3 while fitting them to the real actor hairline from Images 1 and 2; preserve a few natural flyaway hairs
Wardrobe: inherit the complete outfit and accessories shown in Image 3, including garment layers, colors, patterns, belt, sleeve structure and worn/carried matching accessories; do not simplify or independently delete details unless the creator explicitly requests it
Style/medium: photorealistic professional casting photograph, live-action historical drama realism, subtle sensor texture, not concept art and not beauty advertising
Composition/framing: horizontal 16:9 with 4:5 portrait safety area, chest-up, eye-level, 85mm portrait perspective, face fully visible and not distorted
Lighting/mood: neutral 5000K low-contrast structure light; large soft key 45 degrees from front-side, weak fill only to preserve eye sockets and jaw, no rim light; quiet, sincere, grounded
Color palette: natural warm skin, muted blue-gray, pale blue-green, gray-beige and warm neutral background
Materials/textures: real pores, slight under-eye structure, fine facial hair, individual eyebrow and hair strands, visible ramie/hemp weave and soft fabric folds
Constraints: preserve actor identity aggressively; correct human anatomy; no text, no logo, no watermark; this is an identity proof and wardrobe-direction test only
Avoid: unfamiliar face, Image 3 person's face, celebrity reinterpretation, idol styling, wax skin, poreless beauty retouching, heavy makeup, heroic pose, dramatic backlight, teal-orange grade, interface text
```

检查：身份相似度；发际线；真实肤质；束发不改头型；常服A低饱和且非仙侠；无现代/参考图脸污染。

## QNXY-2A-TST-002｜林如蔚人物剧照验证图

```text
Prompt编号：QNXY-2A-TST-002
Prompt版本：V1.0
关联生产资产ID：QNXY-CHR-P0-002-林如蔚
上游生产包：QNXY-PKG-01
风格锁定包：V1.0-DRAFT
生成目的：确认演员锁脸、真实肤质、湖居女子气质、朴素妆发和常服A色材方向；不替代人物基础多视图
参考素材：Image 1=QNXY-REF-003身份主参考；Image 2=QNXY-REF-001三分之四A；Image 3=QNXY-REF-002三分之四B/前臂手部辅助；Image 4=QNXY-REF-004常服A服装发型配饰整体参考
必须继承：同一真人演员骨相五官发际线；170厘米生产尺度观感；明亮但克制、不甜腻
允许补充：自然肤质；按Image 4整体继承服装、发型、发带、花饰、葫芦、铃铛、提篮及穿戴/携带配饰
禁止改变：唯一禁止从Image 4继承的是参考人物脸部五官、骨相与身份信息；林如蔚脸必须只取Image 1—3
输出规格：横向16:9，胸部以上人物剧照，约85mm等效，眼平，中性低反差结构光
确认状态：2026-07-15用户提供候选已登记；主创修正服饰参考为服装发型配饰整体继承，原长辫与发带越界判定撤销；机器有条件通过；身份与肤质待主创确认
```

Prompt正文：

```text
Use case: photorealistic-natural
Asset type: Stage 2A P0 actor-identity casting still for QNXY-CHR-P0-002-林如蔚; static asset validation, not a film shot
Input images: Image 1 is the only main frontal face and identity reference; preserve its facial bone structure, eye-nose-mouth proportions, hairline and real identity. Images 2 and 3 are the same authorized actor and only supplement two three-quarter angles, cheek/jaw continuity, forearm and visible-hand proportions. Image 4 is the complete clothing, hairstyle and accessory reference: inherit its apricot/bean-green/rice-white outfit, exact garment layering, hairstyle, cloth headband, braid, floral ornaments, gourds, bells, basket and worn/carried accessories together unless the creator later excludes a specific element. The ONLY forbidden inheritance from Image 4 is its person's face, facial bone structure and identity; Lin Ruwei's face must come only from Images 1-3.
Primary request: portray the same authorized actor as Lin Ruwei, a young Southern Song lake-dwelling woman in Sichuan/Chongqing, clear-eyed, warm and composed, with restrained intelligence rather than sweet idol styling
Scene/backdrop: seamless warm stone-gray neutral studio backdrop with a faint soft tonal gradient; no lake set and no architecture
Subject: chest-up portrait, natural straight posture, shoulders relaxed, gaze just beside the lens, quiet low-amplitude expression with the slightest warmth; exact same identity as Images 1-3
Hair and makeup: inherit the hairstyle, cloth headband, braid and hair accessories shown in Image 4 while fitting them to the real actor hairline from Images 1-3; preserve natural flyaway hairs, natural brows and lashes and low-saturation lip color
Wardrobe: inherit the complete outfit and accessories shown in Image 4, including garment layers, colors, patterns, belt, sleeve structure, ornaments and worn/carried accessories; do not simplify or independently delete details unless the creator explicitly requests it
Style/medium: photorealistic professional casting photograph, live-action historical drama realism, subtle sensor texture, not concept art and not beauty advertising
Composition/framing: horizontal 16:9 with 4:5 portrait safety area, chest-up, eye-level, 85mm portrait perspective, face fully visible and undistorted
Lighting/mood: neutral 5000K low-contrast structure light, large soft key 45 degrees from front-side and weak fill only, no rim light; calm, humane, grounded
Color palette: natural warm skin, muted apricot, bean green, rice white and warm stone gray
Materials/textures: real pores, slight facial asymmetry, fine baby hair, individual eyebrow and hair strands, visible ramie/hemp weave and soft fabric folds
Constraints: preserve actor identity aggressively; correct human anatomy; no text, no logo, no watermark; identity proof and wardrobe-direction test only
Avoid: unfamiliar face, the Image 4 person's face, idol beauty look, wax skin, enlarged eyes, sharp V-line jaw, heavy makeup, studio glamour, dramatic rim light, teal-orange grade
```

检查：身份相似度；眼鼻唇和下颌；真实皮肤；Image 4服装发型配饰是否整体继承；唯一不得继承的是Image 4人物脸。

## QNXY-2A-TST-003｜龙水湖青石岸母图

```text
Prompt编号：QNXY-2A-TST-003
Prompt版本：V1.0
关联生产资产ID：QNXY-SCN-P0-005-南宋龙水湖湖面与青石岸
场景视图ID：QNXY-SCN-P0-005-南宋龙水湖湖面与青石岸-V-MASTER
上游生产包：QNXY-PKG-07
风格锁定包：V1.0-DRAFT
关联光影：QNXY-LGT-P0-006-龙水湖清晨薄雾金光
生成目的：确认湖面、青石岸、靠岸点、等待/交接区、小院出口、材质和清晨真实光源
参考素材：无直接场景参考；按V4、阶段1空间卡和风格圣经生成
必须继承：南宋巴蜀湖岸、百岛/山影、无现代码头、侧向晨光和湖面反光；空场母图
允许补充：制作坐标内岸线弧度、青石尺度、草石比例和通往小院的朴素路径
禁止改变：不加入人物、小舟、白鹭、竹篮、书卷、建筑主体或现代设施；不得预制正式镜头构图
输出规格：横向16:9，V-MASTER，约28mm等效，受控广角，空场
确认状态：2026-07-15主创确认母图通过
```

Prompt正文：

```text
Use case: historical-scene
Asset type: Stage 2A photorealistic scene master for QNXY-SCN-P0-005-南宋龙水湖湖面与青石岸, view QNXY-SCN-P0-005-南宋龙水湖湖面与青石岸-V-MASTER; empty production-design asset, not a storyboard frame
Primary request: establish a credible Southern Song-period Longshui Lake shoreline in the humid Sichuan/Chongqing landscape, with stable spatial anchors for a small boat arrival, a waiting and handoff area, and a modest path toward an unseen lakeside courtyard
Scene geometry: lake occupies the southern side and most of the left/middle field; an irregular weathered bluestone shoreline curves east-west; a shallow boat landing pocket lies toward the southeast; a level waiting/handoff patch sits at the center of the shore; a narrow worn footpath exits toward the northwest and disappears behind reeds and low trees toward an unseen modest courtyard; distant layered Bayue-like mountains and scattered low islands share one stable horizon
Scene/backdrop: clear early morning after humid night; thin natural mist over water and between islands, not fantasy fog; calm water with small ripples; low shore grass, reeds, moss and water marks; no formal garden and no monumental architecture
Style/medium: photorealistic live-action historical location and production-design master image, tactile real materials, restrained cultural-tourism cinema, not a fantasy painting
Composition/framing: horizontal 16:9 MASTER, camera on slightly raised shore near the northwest side looking diagonally across the landing and lake, about 2 meters high, 28mm controlled wide angle, readable foreground/midground/background, no fisheye and no dramatic hero composition
Lighting/mood: natural 5300K morning side light from frame-left/front, weak warm broken reflections on the lake and wet stones, cool gray shadow under plants, low-to-medium contrast, thin mist remains transparent; quiet, fresh and lived-in
Color palette: lake-mist blue gray, weathered stone gray, moss gray-green, warm rice-beige earth and restrained pale morning gold
Materials/textures: wet bluestone edges, mineral stains, moss in joints, muddy-gravel transitions, reed fibers, matte bark, real water reflections and small shore erosion
Constraints: empty scene; no people, no boat, no bird, no basket, no books, no red ribbon, no readable text, no logo and no watermark; historically plausible but not claimed as an exact reconstruction
Avoid: modern dock, concrete embankment, railings, tourist pavilion, motorboat, manicured park, bright cyan lake, saturated postcard green, giant karst peaks, peach blossom fantasy, floating islands, pagoda skyline, artificial lanterns, game concept art, drone spectacle
```

检查：靠岸/等待/出口三点可读；湖岸材料真实；山岛拓扑稳定；薄雾和碎金不过度；无现代设施/人物/载具污染。

## QNXY-2A-TST-004｜冷珠项绳结构与颈戴尺度

```text
Prompt编号：QNXY-2A-TST-004
Prompt版本：V1.1
关联生产资产ID：QNXY-PRP-P0-001-冷珠
上游生产包：QNXY-PKG-02
风格锁定包：V1.0-DRAFT
生成目的：验证18毫米级古玉、水石质感、深灰细编项绳、珠侧对称结、后颈双滑结、无金属件、女性颈戴比例和低亮反射
参考素材：Image 1=QNXY-REF-015；继承珠体、淡青冷绿、深灰绳、对称结、完整项绳和颈戴比例
必须继承：近球形古玉/水石、颈戴项绳、林如蔚上胸正中佩戴
允许补充：18毫米主珠、约1.5毫米绳径、后颈可调双滑结的结构合理化
禁止改变：不得生成腕戴手链、腰坠、掌心长期握持、玻璃球、夸张冰裂、现代金属扣件、商品珠宝或强自发光
输出规格：横向16:9无字结构验证板；珠体微距＋完整项绳平铺＋中性成年女性颈戴尺度
确认状态：2026-07-15主创最新更正确认为林如蔚颈戴、约18毫米主珠、无金属双滑结；V1.0左腕口径作废；结构比例候选图仍待生成
```

Prompt正文：

```text
Use case: product-mockup
Asset type: Stage 2A P0 prop structure and scale validation board for QNXY-PRP-P0-001-冷珠; one neck-worn asset shown in three consistent views
Input image: Image 1 is the appearance and wearing reference. Inherit its pale cool green near-spherical stone, dark-gray fine braided necklace cord, symmetrical knots beside the bead, full necklace loop and female neck-worn scale.
Primary request: one restrained Southern Song story prop: a single approximately 18 mm pale blue-green ancient-jade/water-stone bead centered on a dark-gray approximately 1.5 mm hand-braided fiber necklace cord, no metal hardware, symmetrical cord knots beside the bead and a compact adjustable double sliding-knot closure at the back of the neck
Layout: one horizontal 16:9 three-part validation board without labels or text: left large macro view of the bead and side knots; upper-right the exact complete necklace laid flat; lower-right the exact same necklace worn by a neutral adult Chinese woman, with the bead centered below the throat and above or within the crossed-collar opening
Stone appearance: softly translucent pale blue-green ancient jade/water-stone, cloudy mineral inclusions, very fine natural age lines, restrained polish and slight wear; not transparent glass and not exaggerated crackle
Cord and closure: matte dark-gray natural-fiber braid, consistent thickness, symmetrical knots at the bead, compact no-metal double sliding knot at the back of the neck, secure ends, no tassels
Style/medium: photorealistic prop-department documentation, restrained handmade historical object, not luxury-jewelry advertising
Lighting/mood: neutral 5000K low-contrast structure light, soft 45-degree key and minimal fill; very faint cool internal response only, never self-illumination
Background: warm light-gray seamless surface; no book, fabric styling or decorative props
Constraints: exact same bead size, color, cord and knot system in all three views; neck-worn only; bead centered on upper chest; no text, scale numbers, logo or watermark
Avoid: wrist bracelet, left or right wrist wearing, waist pendant, palm holding, transparent glass ball, exaggerated crackle glass, resin, gemstone sparkle, metal clasp, gold or silver parts, commercial jewelry styling, oversized bead, energy orb, strong glow, lens flare, extra decorative beads
```

检查：三视一致；项绳完整；颈戴；上胸正中；18毫米视觉比例；古玉非玻璃；无金属；后颈双滑结合理；不强发光。

## QNXY-2A-TST-005｜九龙神龙群写实方向

```text
Prompt编号：QNXY-2A-TST-005
Prompt版本：V1.2
关联生产资产ID：QNXY-CRE-P0-001-九龙神龙群
上游生产包：QNXY-PKG-06
风格锁定包：V1.0-DRAFT
关联场景/VFX：QNXY-SCN-P0-001-巴岳山麓龙水湖神话山湖；QNXY-VFX-P0-001-神话山湖水汽云雾汇聚
生成目的：验证正好九条在天空飞舞盘旋、真实中国神龙体貌、个体差异、山雾/山体遮挡、局部鳞片与非怪物化
参考依据：V4 P010；阶段1资产卡；大足九龙浴太子“九条龙头有差异、龙身隐于山石祥云、水从龙口而出”的地域语汇；不复刻文物构图
必须继承：正好九条；中国长躯神龙；全部龙体在天空，不在水里；山谷雾带、山风和晨光；局部/剪影曝光
允许补充：头角鳞片和体色轻微差异；九条深度分层；躯干部分被云雾遮挡
禁止改变：不得西方翼龙、蜥蜴怪、游戏Boss、九条同模、全正面展示、荧光眼、火焰、法阵、能量爆炸和强珠光
输出规格：横向16:9写实方向验证图，稳定广角，明确九条空中飞舞盘旋的独立数量线索
确认状态：2026-07-15设计口径已确认；V1.0/V1.1水中旧候选不通过；V1.2新候选待生成
```

Prompt正文：

```text
Use case: historical-scene
Asset type: Stage 2A P0 photorealistic mythic-creature direction test for QNXY-CRE-P0-001-九龙神龙群; static concept/structure validation, not a storyboard or action shot
Primary request: show exactly NINE original long-bodied Chinese dragons flying and circling in the sky above a humid Bayue-mountain and Longshui-Lake landscape, grounded in real live-action photography and Dazu-region water-carving sensibility rather than fantasy-game spectacle; none of the nine dragons may be in the lake or emerging from water
Scene/backdrop: layered dark-green-gray mountain ridges, calm island-dotted lake and naturally rising water vapor at dawn; cloud gaps admit restrained neutral morning light; the landscape remains geographically readable
Creatures: exactly nine distinct long-bodied Chinese dragons at different aerial depths; all nine body centerlines remain above the lake surface and weave through the sky over mountain ridges; serpentine torsos with believable muscle and joint transitions, small practical limbs and claws, matte damp scales in restrained stone-gray, blue-gray and muted jade-gray families; subtle individual differences in head silhouette, horn angle and scale pattern, but one coherent species
Visibility strategy: show active airborne circling and varied flight arcs, never a water-emergence pose and never a rigid lineup. Use overlapping mountain fog and ridges so each dragon is identified by a unique head/neck arc, airborne torso curve, partial limb, tail or localized scale detail; exactly nine heads and exactly nine continuous body trajectories exist, with some sections naturally hidden by mountain fog; no dragon is fully frontal; the count must still clearly resolve to nine
Regional visual cue: evoke the order of Dazu's nine-dragon water imagery—varied dragon heads, bodies partly hidden by rock and auspicious cloud, water-linked presence—while creating a completely original mountain-lake composition and not copying any statue or grotto
Style/medium: photorealistic live-action mythic-natural-history image, realistic airborne anatomy, atmosphere and scale, restrained historical microfilm production design, no painterly concept-art finish
Composition/framing: horizontal 16:9, stable wide view around 32mm, lake and mountains remain geographically readable in the lower half, dragons distributed across three aerial depth layers with natural mountain-fog occlusion, no central boss composition and no game loading-screen symmetry
Lighting/mood: natural 5200K dawn side light filtered through cloud, low-to-medium contrast, cool mountain shadow and weak warm lake reflection; dragons receive only environmental light and wet-scale reflection, no self-lit eyes or outlines
Color palette: lake-mist blue gray, mountain slate green, stone gray, restrained pale jade and very small warm cloud highlights
Materials/textures: damp organic scales, fine atmospheric condensation, volumetric but physically plausible mountain mist, matte horns, real cloud density and lake reflection
Constraints: exactly nine dragons, all flying/circling in the sky and none in water; no people, no palace, no beads, no text, no logo and no watermark; original design; readable landscape; physically plausible mountain fog
Avoid: any dragon body touching or entering the lake, water-emergence poses, swimming dragons, western winged dragon, dinosaur, lizard monster, game boss, identical cloned dragons, cute cartoon, anime, nine glowing faces, fire breathing, lightning, magic circle, neon eyes, gold armor, energy beams, explosive cloud, complete frontal lineup, rigid 3-by-3 formation, giant dragon filling the whole frame
```

检查：正好九条；全部在天空飞舞盘旋且不接触湖面；九头与九条连续空中躯干轨迹可核对；山湖仍可读；体貌写实同源有差异；山雾遮挡有物理来源；无游戏/仙侠特效。

## 回流与审批门

首轮候选图全部先登记为`DRAFT / 待主创确认`。机器初检只判断技术和规则一致性，不能替代主创审美确认。人物剧照通过后才生成基础资产；场景母图通过后才生成`V-LAKE-TO-SHORE`；冷珠与九龙方向通过后才扩展组合或VFX测试。
