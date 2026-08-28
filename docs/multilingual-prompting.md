# Multilingual MiniMax H3 Prompting

The 100 English recipes are the canonical collection maintained by bestimage.ai. This guide provides eight localized examples linked to their corresponding English recipes.

Localize the complete creative specification, including reference roles, action order, camera, timing, sound, and constraints, rather than only translating style keywords. These examples are writing references, not claims of tested MiniMax H3 outputs.

**Languages in this sampler:** 简体中文 · 日本語 · 한국어 · Español · Français · Deutsch · Português · العربية

## Localization rules

1. Keep reference labels stable: `Image 1`, `Video 1`, and `Audio 1` should match the uploaded asset order.
2. Translate creative direction, action, camera, timing, sound, continuity, and negative constraints together.
3. Keep required on-screen copy in quotes and identify its intended language explicitly.
4. Do not translate model identifiers, file names, product geometry, or approved brand spelling.
5. For right-to-left output, define reading direction and UI mirroring separately from scene direction.
6. Review culturally specific clothing, gestures, food, architecture, geography, and legal disclosure with a knowledgeable human.

## 简体中文：山顶观测站茶饮发布片

**英文原文：** [BRD-001 Midnight Observatory Tea Launch](../prompts/01-brand-advertising.md#brd-001-midnight-observatory-tea-launch)  
**画幅与目标时长：** 16:9，12–15 秒。可选的 Audio 1 只参考节奏和克制的声音风格。

```text
为虚构茶饮品牌“NORTH WINDOW”制作一支 16:9 高级新品发布短片。故事发生在黎明前安静的山顶观测站内。Image 1 只用于锁定瓶身：烟灰色高挑玻璃瓶、浅石色标签、深绿色瓶盖，标签位置与拼写必须保持不变，不要虚构功效声明；Image 2 只用于观测站的圆形建筑、望远镜结构与蓝调黎明色彩。

开场：一束狭窄星光滑过桌面，逐渐显露瓶身轮廓，镜头水平缓慢推进。中段：瓶壁自然凝结水汽，一滴水沿真实曲面下滑；观测站屋顶打开，冷色天光进入。结尾：产品保持静止，远方地平线从靛蓝转为一条克制的暖金色，镜头停在留有上方文案安全区的英雄画面。

光线应有真实来源，保留玻璃折射、柔和金属反射和真实凝结水汽。声音意图：安静的屋顶机械声、远处风声、一记低沉玻璃音，不要旁白。避免漂浮原料、液体爆炸、标签变化、夸张光晕、额外文字、第三方品牌和水印。
```

## 日本語：デスクライトの自然なファーストインプレッション

**英語原文：** [UGC-001 Desk Lamp Honest First Impression](../prompts/03-ugc-lifestyle.md#ugc-001-desk-lamp-honest-first-impression)  
**画面比率・目標尺：** 9:16、12秒。任意の Audio 1 は室内の環境音のみの参考にする。

```text
夕暮れの小さなホームオフィスで、縦型9:16の自然な商品体験動画を作る。Image 1 の成人クリエイターの顔・髪型・服装を維持する。Image 2 の「FOLDLINE」デスクライトは、細い黒い支柱、楕円形ベース、暖白色のライトバー、真鍮色のヒンジ1個を正確に保つ。これは架空のデモであり、実在する顧客の証言として見せない。

冒頭：手持ちのスマートフォン撮影はすでに始まっており、クリエイターがライトをノートの横に置く。生成されたせりふは入れず、表情は好奇心を示す程度で大げさにしない。中盤：片手でヒンジを開き、ベースを一度タップし、スケッチを光の下へ滑らせる。クリエイターが紙面をのぞき込み、露出は一度だけ自然に調整され、その後安定する。最後：カメラに目を向けて小さく満足げにうなずき、それからライトを外側に回して画面への映り込みが減る様子を見せる。

スマートフォンらしい自然なピント、軽い手ぶれ、日常的な室内の質感、正しい手と物の接触を保つ。音：ヒンジの摩擦、ベースのタップ、紙が滑る音、外の静かな街の環境音。過剰な美肌、手と商品の融合、不可能なライトの関節動作、視線のずれ、販売字幕、架空の五つ星評価、スポンサーのブランド表示、透かしを避ける。
```

## 한국어：화이트 피치 로즈메리 스파클링 티 광고

**영어 원문:** [FNB-003 Sparkling Botanical Tea Macro Ad](../prompts/05-food-beverage.md#fnb-003-sparkling-botanical-tea-macro-ad)  
**화면 비율 및 목표 길이:** 9:16, 8초.

```text
가상의 음료 “MEADOW FIZZ” 화이트 피치 로즈메리 티를 위한 9:16 세로형 매크로 광고를 만든다. Image 1의 투명한 세로 골 유리병, 옅은 금빛 액체, 크림색 라벨, 세이지색 캡을 정확히 유지하고 라벨 문구나 효능 표현을 새로 만들지 않는다. Image 2는 실제 로즈메리 가지와 흰 복숭아 조각의 형태만 참고한다.

시작은 석회암 위에 놓인 차가운 병의 매크로 클로즈업이다. 작은 탄산 기포가 액체 안에서 올라오고 병 어깨에 응결 방울 하나가 생긴다. 중간에는 캡이 절제된 소리와 함께 열리고, 음료가 투명한 긴 잔에 한 번에 부어진다. 기포가 로즈메리와 복숭아 주변에 자연스럽게 모인다. 마지막에는 액체가 잔잔해지는 동안 카메라가 잔을 조금 돌아 뒤쪽의 병 라벨과 위쪽 여백을 함께 보여준다.

밝고 부드럽게 확산된 자연광, 사실적인 굴절, 깔끔한 하이라이트, 옅고 자연스러운 색을 사용한다. 소리: 캡이 열리는 소리, 또렷한 따르기 소리, 부드러운 탄산 소리, 잎이 한 번 움직이는 소리. 과일 폭발, 떠다니는 재료, 과도한 거품, 병의 세로 골 변화, 거울처럼 뒤집힌 라벨, 추가 슬로건과 워터마크를 피한다.
```

## Español：Revelación de una casa de huéspedes en una isla volcánica

**Original en inglés:** [TRV-002 Volcanic Island Guesthouse Reveal](../prompts/04-travel-hospitality.md#trv-002-volcanic-island-guesthouse-reveal)  
**Formato y duración objetivo:** 16:9, 10 segundos.

```text
Crear un video horizontal de 10 segundos para una casa de huéspedes ficticia situada en una isla volcánica. Image 1 define la habitación: paredes encaladas, cama baja de roble, cabecero tejido, suelo de piedra negra y cortinas de lino. Image 2 solo define la costa de lava oscura y el horizonte oceánico pálido visible fuera. Image 3 fija la posición de la puerta y la ventana.

Comenzar con un primer plano de una llave de latón sobre una repisa de roble. La cámara retrocede mientras la puerta se abre y revela, en un único movimiento, la cama y la ventana. Las cortinas reaccionan suavemente al aire marino. La cámara pasa junto a la cama a altura humana y termina en la terraza abierta, donde dos sillas vacías miran hacia la costa. No se necesitan personas.

La iluminación cambia de forma natural entre la luz cálida rebotada del interior y la luz diurna fría del exterior. Sonido: contacto de la llave, pestillo, movimiento del lino y oleaje distante. No alterar la geometría de la habitación ni añadir piscina, servicios, una posición imposible del océano, distorsión de gran angular excesiva, valoraciones, texto promocional ni marcas de agua.
```

## Français：Éditorial lunettes — étude du vent

**Original anglais :** [FSH-001 Wind-Study Eyewear Editorial](../prompts/06-fashion-beauty.md#fsh-001-wind-study-eyewear-editorial)  
**Format et durée cible :** 9:16, 10 secondes. La recette source ne prescrit pas de bande-son.

```text
Créer un film de mode vertical minimaliste dans un studio gris chaud sans raccord visible. Conserver l’identité du modèle adulte de la référence Image 1 : même visage, cheveux courts texturés, peau naturelle et col montant anthracite. Reconstruire exactement les lunettes des références Image 2 et Image 3 : monture fumée translucide, verres ovales étroits, charnières argentées et branches droites. Video 1 sert uniquement de référence pour le rythme du mouvement de tête.

Ouverture en gros plan : le modèle présente le visage de trois quarts, détourné de l’objectif, pendant qu’un ventilateur contrôlé déplace seulement quelques mèches et le bord du col. La caméra glisse lentement sur le côté tandis que le modèle tourne le visage vers l’objectif au rythme de Video 1. À mi-parcours, une lumière traverse une seule fois les verres sans cacher les yeux. Finir sur un gros plan frontal stable ; le modèle baisse légèrement le menton et garde un regard calme.

Utiliser une grande source principale douce, un fin éclairage de contour, des pores naturels et des reflets fidèles sur les verres. Ne pas ajouter de texte publicitaire beauté. Éviter toute modification de la largeur de la monture, de la teinte des verres, de la position des charnières, de la forme du visage ou de la couleur des yeux, les reflets opaques, les lunettes dupliquées, une chevelure violemment agitée, la peau plastique, les bijoux ajoutés, les logos et les filigranes.
```

## Deutsch：Produktrundgang für einen Fokus-Timer

**Englische Vorlage:** [DIG-001 Focus Timer Product Walkthrough](../prompts/11-ui-game-digital.md#dig-001-focus-timer-product-walkthrough)  
**Format und Ziellänge:** 16:9, 12 Sekunden. Image 4 legt die Reihenfolge der Interaktionen fest; das optionale Video 1 dient ausschließlich als Referenz für die Cursorgeschwindigkeit.

```text
Erstelle eine 16:9-Produktdemo für den fiktiven Desktop-Fokus-Timer „QUIET HOUR“. Übernimm ausschließlich die freigegebenen UI-Zustände aus Image 1 bis Image 3: anthrazitfarbenes Fenster, cremefarbene Timer-Karte, grüner Fortschrittsring, Aufgabenliste und Pausensteuerung. Alle gelieferten Texte müssen exakt erhalten bleiben; keine Kennzahlen, Bewertungen oder Menüpunkte erfinden.

Beginne im Ruhezustand. Der Cursor bewegt sich mit der natürlichen Geschwindigkeit aus Video 1, wählt eine Aufgabe und klickt auf Start. Die Oberfläche wechselt mit einem sanften Übergang von 250 ms in den aktiven Zustand; der Timer läuft an, der Ring schreitet leicht voran und die aktive Aufgabe erhält eine dezente grüne Markierung. Eine kleine Benachrichtigung gleitet einmal ins Bild. Der Nutzer aktiviert „Silence alerts“, danach klappt die Meldung zusammen. Abschließend herauszoomen und die unveränderte App auf einem realistischen Laptop mit freier Fläche für Text daneben zeigen.

Die Oberfläche bleibt scharf und während der Interaktion frei von perspektivischer Verzerrung; dezente Bildschirmreflexionen erst in der abschließenden Laptop-Aufnahme. Nur zwei dezente Klicks und ein gedämpfter Ton. Keine unlesbare Mikroschrift, erfundenen Diagramme, zufälligen Hover-Effekte, springenden Cursorbewegungen, zusätzlichen Fenster, Markenlogos oder Wasserzeichen.
```

## Português：Comédia silenciosa em uma lavanderia automática

**Original em inglês:** [SOC-003 Alien at the Self-Service Laundry](../prompts/12-transitions-comedy-social.md#soc-003-alien-at-the-self-service-laundry)  
**Formato e duração pretendida:** 9:16, 10 segundos.

```text
Criar uma comédia vertical e discreta na lavanderia tranquila de autoatendimento mostrada na referência Image 2. Manter a criatura original da referência Image 1: pele verde-menta, três olhos, capa de chuva curta azul-marinho, duas mãos e proporções compactas. A criatura é amigável e fictícia. Image 3 define a ordem correta de uso da máquina; não alterar os controles.

No início, a criatura observa a porta redonda da lavadora e coloca cuidadosamente uma única meia listrada no tambor. Fecha a porta, insere uma ficha simples e pressiona o botão aprovado. Quando o tambor começa a girar, os três olhos acompanham a meia em perfeita sincronia circular. A criatura abre um caderno, desenha apenas uma espiral sem palavras e então percebe que a meia correspondente já está em seu próprio pé. Ela olha para a câmera, envergonhada, sem falar.

Som: queda da ficha, sinal sonoro do botão, movimento do tambor e um roçar da capa de chuva. Manter o humor discreto e físico. Evitar aparência assustadora, membros extras, uso perigoso da máquina, corpo entrando na máquina, textos gerados, semelhança com personagens conhecidos, logos ou marca-d’água.
```

## العربية：سوق مسائي من منظور الزائر

**النص الإنجليزي الأصلي:** [TRV-003 First-Person Night Market Wayfinding](../prompts/04-travel-hospitality.md#trv-003-first-person-night-market-wayfinding)  
**نسبة العرض إلى الارتفاع والمدة المستهدفة:** 9:16، 12 ثانية. يُستخدم Audio 1 الاختياري مرجعاً للأجواء الصوتية فقط.

```text
أنشئ فيديو عمودياً بنسبة 9:16 من منظور شخص يسير في السوق المسائي الظاهر في Image 1 وImage 2. استخدم Image 3 فقط لتحديد المسار ومواقع الأكشاك: مدخل الفوانيس، ثم بائع الفاكهة، ثم كشك الوجبات الخفيفة المطهوة بالبخار، ثم منطقة جلوس صغيرة مفتوحة. لا تخترع أسماء متاجر أو أسعاراً قابلة للقراءة.

تتحرك الكاميرا بسرعة مشي مريحة مع ثبات طبيعي لحركة الجسم، من دون الاندفاع بين الناس أو الاصطدام بهم. عند بائع الفاكهة تتوقف لحظة بينما يزن ثلاث برتقالات. عند كشك الوجبات الخفيفة يُرفع غطاء من الخيزران، فيمر البخار أمام العدسة لفترة قصيرة من دون إخفاء الطريق. ينتهي الفيديو بالانعطاف نحو منطقة الجلوس حيث تظهر طاولة فارغة واحدة. حافظ على طريق قابل للمرور وترتيب ثابت للأكشاك.

الإضاءة مزيج من دفء الأكشاك وبرودة المساء، مع ألوان بشرة طبيعية وضبط محدود للتعريض. الصوت: ضجيج سوق هادئ، نقرة الميزان، خروج البخار وأدوات الطعام. تجنب تكرار الوجوه، القفز المكاني، الاصطدام بالناس، اللقطات القريبة للنصوص غير المقروءة، التفاصيل التي تصور الثقافة بصورة غرائبية، التصوير المتطفل، العلامات التجارية والعلامة المائية.
```

## Human review checklist

- Reference numbering still matches the uploaded assets;
- Required copy, punctuation, names, and reading direction are correct;
- Camera direction was not accidentally mirrored during RTL localization;
- Cultural, geographic, and product details are appropriate;
- Audio and dialogue intent sound natural to a native speaker;
- The localized version preserves every safety and continuity constraint.

Return to the [100-prompt library](../prompts/README.md).
