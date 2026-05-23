# 《麦田里的钢铁》—— 第3集《赛场》AI视频生成分镜

> **分镜说明：** 本分镜为AI视频生成工具专用（Sora / Runway / 可灵 / CogVideoX）。
> **时间设定：** 大二下学期→大三上学期。
> **核心功能：** 团队合作与矛盾、技术主心骨但不是队长、第一次在集体中证明自己的价值。
> **人物设定：** 新增王磊、陈宇、张帆（队友）；苏晚晴首次出场。

---

## 统一角色设定

|角色 | 长相特征 | 服装 | 
------|---|------|------|
|林一鸣（20-21岁） | 棱角分明，眉毛浓，比赛时手心出汗但表面冷静 | 格纹衬衫，深色T恤，牛仔裤 |
|周师傅 | 花白头发，手上有常年干活的痕迹 | 深蓝工装，袖口卷着 |
|王磊（大三） | 脸圆爱笑，嗓门大 | 宽松T恤运动裤 |
|陈宇（大三队长） | 稳重，做事有分寸 | 普通学生装 |
|张帆（大二） | 瘦，话少，动手能力强 | 深色外套 |
|苏晚晴（大二） | 短发，浅色外套，笑起来眼睛弯 | 浅色外套 |

---

## 片段列表

### 场1 / 内景 / 机电实验室 / 日（大二下学期）

### 片段 001 — 四足机器人偏航

| 项目 | 内容 |
|------|------|
|景别/机位 | 中景——实验台前，四足机器人正在走动 |
|画面描述 | 机电实验室。林一鸣的四足机器人已经在走了——四条腿交替迈步，走得不快，但确实在走。唯一的问题是它会往左边偏——走一段之后轨迹就歪了。他盯着机器人的腿，看走完一轮，然后在本子上记下一个数据。 |
|光线与色调 | 实验室日光灯冷白。 |
|镜头衔接 | **硬切接第2集结尾：** 第2集末尾他在群里看到了回应，第3集直接从实验室日常开始。 |
|时长 | 4秒 |
|生成提示词 | **Shot 001:** Medium shot of a lab workbench. A small quadruped robot walks across the desk — four legs moving in sequence, steady but not fast. The only problem: it drifts left as it walks. The student watches it complete a lap, notes something down. **Lab fluorescent light.** |

### 片段 002 — 周师傅蹲下看舵机·批次问题

| 项目 | 内容 |
|------|------|
|景别/机位 | 俯拍——周师傅蹲下来用手转动舵机 |
|画面描述 | 周师傅从旁边走过来，蹲下看了看机器人的腿部，用手转动了一下舵机的输出轴。"你那两个舵机不是一个批次的吧？批次不一样，内部阻尼有差异。你软件上调再久也调不平。" |
|对白 | 周师傅（蹲下来看机器人的腿，用手转了转输出轴）："你那两个舵机不是一个批次的吧？批次不一样，内部阻尼有差异。你软件上调再久也调不平。"<br>林一鸣（愣住——他从来没想过这个问题）："那怎么办？"<br>周师傅："换同一批次的舵机。或者——你在代码里给每个腿单独做校准偏置。" |
|光线与色调 | 同上。周师傅手上的油污在灯光下可见。 |
|镜头衔接 | **视线匹配接001：** 001的末尾他盯着机器人看，周师傅的手从旁边伸进画面——顺着他的视线发现机器人腿部的异常。 |
|时长 | 8秒 |
|生成提示词 | **Shot 002:** Overhead close-up as the technician crouches and rotates a servo output shaft with his fingers. "These two servos aren't from the same batch. Internal damping differs. You can tune the software all day and never fix it." The student looks up, surprised — he hadn't considered hardware variance. **Same lab, same light.** |

### 片段 003 — "让机器人自己测偏置"

| 项目 | 内容 |
|------|------|
|景别/机位 | 近景——周师傅递给他一个角度传感器 |
|画面描述 | 周师傅递给他一个角度传感器——"把每个关节的实际角度读出来，跟你代码里下发的角度对比。差值就是偏置。"林一鸣接过传感器看了看——"那如果我能让机器人自己测自己的偏置呢？"周师傅愣了一下笑了："你比你那个机器人脑子好使。" |
|对白 | 周师傅（笑了笑，拿起一个角度传感器递给他）："把每个关节的实际角度读出来，跟你代码里下发的角度对比。差值就是偏置。"<br>林一鸣接过传感器看了看："那如果我能让机器人自己测自己的偏置呢？"<br>周师傅（愣了一下，笑了）："你比你那个机器人脑子好使。" |
|光线与色调 | 同上。角度传感器金属外壳反光。 |
|镜头衔接 | **动作匹配接002：** 002末尾周师傅的手在转动舵机轴，003他直起身去拿传感器——动作连贯。 |
|时长 | 6秒 |
|生成提示词 | **Shot 003:** Medium close-up. The technician hands the student an angle sensor. "Read the actual angle at each joint, compare with your commanded position. The difference is the offset." The student takes it, looks at it: "What if I make the robot self-calibrate?" The technician pauses, then smiles: "You're smarter than your robot." **Same lab, same moment.** |

### 场2 / 内景 / 大学食堂 / 日（一周后）

### 片段 004 — 食堂·王磊招手

| 项目 | 内容 |
|------|------|
|景别/机位 | 食堂全景——嘈杂，林一鸣端着餐盘找座位 |
|画面描述 | 大学食堂午餐时间。嘈杂，排队长龙，人声鼎沸。林一鸣端着餐盘找座位——从一张张桌子旁走过，都已经坐满了。一个男生从人群中叫住他——王磊，大三，机器人协会的。 |
|光线与色调 | 食堂日光灯偏暖白。人多，气氛嘈杂热闹。 |
|声音设计 | 食堂特有的嘈杂——碗盘碰撞声、多人说话声、电视播放新闻的声音。 |
|镜头衔接 | **硬切+环境突变接003：** 003是安静的实验室，004是喧闹的食堂——从静到噪的感官对比。 |
|时长 | 4秒 |
|生成提示词 | **Shot 004:** Wide shot of a busy university cafeteria at lunch. Long queues, crowded tables. The student carries a tray looking for a seat — all tables full. A voice calls him from across the room. **Noisy cafeteria atmosphere — dish clatter, multiple conversations.** |

### 片段 005 — 坐下·"你感兴趣不？"

| 项目 | 内容 |
|------|------|
|景别/机位 | 双人中景——两人面对面坐着 |
|画面描述 | 王磊已经吃了一半了，看到林一鸣坐下直接进入主题——"听说你在做四足？能走路了没？""能走。就是走不快。"王磊眼睛一亮："全国大学生机器人大赛报名了。你感兴趣不？"林一鸣停下筷子："什么项目？""搬运对抗。造一台机器人搬方块，搬到指定区域得分，可以互相拦截。" |
|对白 | 王磊："听说你在做四足机器人？能走路了没？"<br>林一鸣："能走。就是走不快。"<br>王磊（眼睛一亮）："牛逼。对了——全国大学生机器人大赛报名了，咱们学校今年组队参加。你感兴趣不？"<br>林一鸣（停下筷子）："什么项目？"<br>王磊："搬运对抗。造一台机器人，在场地里搬方块，搬到指定区域得分。可以互相拦截。"<br>林一鸣想了想："有几个人？"<br>王磊："我，你，还有大二的张帆——他做机械结构比较强。队长是陈宇，大三的，他去年参加过一届，有经验。"<br>林一鸣："陈宇？"<br>王磊："你认识？"<br>林一鸣（摇了摇头）："不认识。行，我加入。" |
|光线与色调 | 同上。餐盘里的饭还在冒着热气。 |
|镜头衔接 | **动作匹配接004：** 004末尾他在人群中看到王磊招手，005他已经坐下了——省略了走过去的动作。 |
|时长 | 14秒 |
|生成提示词 | **Shot 005:** Medium two-shot at a cafeteria table. A senior student is already halfway through his meal, gets straight to the point: "National robot competition signups are open. Interested?" Brief exchange about the event — a cube-moving对抗 competition. The quiet student pauses his chopsticks, thinks, says "I'm in." **Cafeteria atmosphere continues in background.** |

### 场3 / 内景 / 机器人协会活动室 / 日（组队后第一周）

### 片段 006 — 陈宇铺开图纸

| 项目 | 内容 |
|------|------|
|景别/机位 | 全景——四个人围着一张桌子，陈宇展开图纸 |
|画面描述 | 活动室不大，堆满了各种零件和半成品。四个人围着一张旧桌子。队长陈宇在桌上铺开一张图纸——四轮底盘上加一个三自由度的机械臂。麦克纳姆轮全向移动，步进电机驱动机械臂。 |
|光线与色调 | 日光灯。房间不大但光照充足。 |
|镜头衔接 | **硬切接005：** 从食堂对话直接切到团队第一次开会。 |
|时长 | 4秒 |
|生成提示词 | **Shot 006:** Wide shot of a cluttered robotics club room. Four students around a table. The team captain unrolls a design drawing — a four-wheel chassis with a 3-DOF robotic arm. Mecanum wheels for omnidirectional movement, stepper motors for the arm. **Fluorescent light, parts scattered everywhere.** |

### 片段 007 — "底盘为什么不做悬架"

| 项目 | 内容 |
|------|------|
|景别/机位 | 中景——林一鸣从书包里抽出自己画的草图放在桌上 |
|画面描述 | 陈宇讲解方案时，林一鸣一直没说话。看了一阵后他开口了——"底盘为什么不做悬架？"陈宇说比赛场地是平整的。林一鸣解释："没有悬架的话四个轮子的抓地力不一致，麦克纳姆轮对地面贴合度很敏感。"他从书包里抽出自己画的草图放在桌上——同样的四轮底盘和机械臂，但他把关节从步进电机改成了舵机加编码器反馈，底盘加了简单的被动悬架。 |
|对白 | 林一鸣（看了一阵）："底盘为什么不做悬架？"<br>陈宇："比赛场地是平整的。不需要悬架。"<br>林一鸣："我不是说通过性。我是说——没有悬架的话四个轮子的抓地力不一致，全向移动的时候会偏。麦克纳姆轮对地面贴合度很敏感。"<br>陈宇（沉默了几秒）："你有更好的方案？"<br>林一鸣（从书包里拿出自己的草图放在桌上——机械臂关节改成了舵机+编码器反馈，底盘加了被动悬架） |
|光线与色调 | 同上。两张图纸并排——陈宇的印刷图纸和林一鸣的手绘草图。 |
|镜头衔接 | **视线匹配接006：** 006末尾陈宇讲完了方案看向大家，007切到林一鸣的脸——他在思考，然后从书包里拿出自己的图纸。 |
|时长 | 12秒 |
|生成提示词 | **Shot 007:** Medium shot. After listening to the captain's plan for a while, the quiet student speaks up: "Why no suspension?" The captain explains the field is flat. "Mecanum wheels need consistent ground contact — without suspension, traction varies and the robot drifts." He pulls his own hand-drawn design from his backpack — same chassis but with servo+encoder joints instead of stepper motors, and a simple passive suspension. Two drawings side by side. **The room goes quiet.** |

### 片段 008 — 争论·舵机vs步进

| 项目 | 内容 |
|------|------|
|景别/机位 | 近景——两个人的手在图纸上指不同的位置 |
|画面描述 | 张帆插了一句："舵机的扭矩够吗？"林一鸣说用LX-16A做过测试——500克以内没问题。王磊翻了翻规则书——比赛方块400克。陈宇最终点了点头："机械部分按你这个方案做。控制系统呢？""我来写。" |
|对白 | 张帆："舵机的扭矩够吗？"<br>林一鸣："我用LX-16A做过测试。抓取500克以内的方块没问题。比赛方块的重量是多少？"<br>王磊（翻了翻规则书）："400克。"<br>林一鸣："那够了。"<br>陈宇（最终点了点头）："机械部分按你这个方案做。控制系统呢？"<br>林一鸣："我来写。" |
|光线与色调 | 同上。图纸上的铅笔线条在光下。 |
|镜头衔接 | **动作匹配接007：** 007末尾两张图纸摊在桌上，008几个人同时伸手去指不同位置——团队第一次协作。 |
|时长 | 8秒 |
|生成提示词 | **Shot 008:** Close-up of hands pointing at different parts of the drawing. "Torque enough?" "Tested LX-16A — handles 500g. Competition cube is 400g." The captain nods: "We'll use your design for mechanics. Who handles control?" "I will." **First team decision.** |

### 场4 / 内景 / 大学宿舍 / 夜（备赛期间）

### 片段 009 — 深夜焊驱动板

| 项目 | 内容 |
|------|------|
|景别/机位 | 俯拍桌面——烙铁、焊锡丝、板子 |
|画面描述 | 深夜宿舍。桌上摊着图纸、连接线、几块开发板。林一鸣正在焊一块电机驱动板——烙铁在焊点上停留两三秒，焊锡熔化、流动，形成一个光滑的银色锥体。他的动作已经比大一时熟练了很多——每一焊都干脆利落。 |
|光线与色调 | 台灯暖白。烙铁头的红色指示灯在暗处发光。 |
|镜头衔接 | **硬切+时间跳变接008：** 008的白天的活动室→009的深夜宿舍——"整个团队开始分头行动"。 |
|时长 | 5秒 |
|生成提示词 | **Shot 009:** Overhead close-up of soldering. A motor driver board on the desk, soldering iron tip melting solder onto pads forming smooth silver cones. The student's hand is steady and practiced — each joint done cleanly in one motion. **Warm desk lamp, red indicator light on the soldering iron.** |

### 片段 010 — "保研加分"

| 项目 | 内容 |
|------|------|
|景别/机位 | 从桌面摇到上铺刘洋——他在暗影中探头 |
|画面描述 | 刘洋从上铺探出头："你最近天天搞到两三点，在做什么？"林一鸣没抬头说比赛。刘洋问赢了有钱吗？"一等奖有奖杯。还有……保研加分。""加多少？""0.3个绩点。"刘洋躺回去了："那你不如直接好好考试。"林一鸣没接话，继续焊——把刚焊好的板子接上电源，测试输出电压。 |
|对白 | 刘洋（从上铺探出头）："一鸣，你最近天天搞到两三点，在做什么？"<br>林一鸣（没抬头）："比赛。"<br>刘洋："啥比赛？"<br>林一鸣："机器人大赛。"<br>刘洋（想了想）："赢了有钱吗？"<br>林一鸣（焊好最后一个焊点，吹了吹）："一等奖有奖杯。还有……保研加分。"<br>刘洋（来了兴趣）："加分？加多少？"<br>林一鸣："0.3个绩点。"<br>刘洋（躺回去了）："那你不如直接好好考试。"<br>林一鸣没接话。他拿起焊好的板子接上电源，测输出电压。 |
|光线与色调 | 同上。刘洋的脸在暗处几乎看不清——只有声音从上方来。 |
|镜头衔接 | **声音桥接接009：** 009的烙铁滋滋声持续到010——刘洋的声音从画外进来（L-Cut），然后画面才切到上铺。 |
|时长 | 12秒 |
|生成提示词 | **Shot 010:** Starts on the soldering desk, tilts up to the top bunk where the roommate's face is barely visible in shadow. "You're at it till 2AM every day — what gives?" "Competition." "Any prize money?" "Trophy and... bonus points for grad school." "How many?" "0.3 GPA." "You'd be better off just studying." No reply. Student tests voltage on the finished board. **Warm desk lamp, roommate's voice from the dark above.** |

### 场5 / 内景 / 活动室 / 日（备赛中期）

### 片段 011 — 电子市场买零件

### 片段 012 — 铁牛一号初具雏形

| 项目 | 内容 |
|------|------|
|景别/机位 | 缓慢的环绕镜头展示铁牛一号各部位 |
|画面描述 | 铁牛一号已经组装起来了。四轮底盘——大约40cm长、30cm宽——四个角各装一个麦克纳姆轮（轮子外圈有与轴心45度排列的短圆柱状辊子）。底盘上有一层薄的被动悬架——四个小弹簧。向上伸出三自由度机械臂：腰部水平旋转、大臂俯仰、小臂俯仰。末端是两指夹具，内侧贴一层薄橡胶增加摩擦。 |
|光线与色调 | 日光灯。机器人的金属和塑料反光。 |
|镜头衔接 | **硬切+时间跳跃接010：** 010的深夜焊接→011的白天组装完成——"几周后"。 |
|时长 | 6秒 |
|生成提示词 | **Shot 011:** Slow tracking shot circling "Iron Bull No.1" on a workbench. Four mecanum wheels at each corner — short cylindrical rollers at 45-degree angles. Thin suspension springs. A 3-DOF robotic arm rising from the chassis — waist rotate, shoulder pitch, elbow pitch. Two-finger gripper with rubber padding on inner surfaces. **Assembled, tested, ready.** |

### 片段 013 — 陈宇看代码·三个控制模式

| 项目 | 内容 |
|------|------|
|景别/机位 | 中景——陈宇站在林一鸣身后看他写的代码 |
|画面描述 | 陈宇拿起林一鸣写的控制代码翻了翻——"你写了三个控制模式？""嗯。手动、半自主、全自主。"陈宇问比赛用哪个。"正常情况下手动。如果被撞了——切半自主，让纠偏算法自己恢复位置。"陈宇点了点头，转向全队："我负责策略，一鸣负责操控。王磊在场边观察对面。"还有两周。有问题吗？""那就干。" |
|对白 | 陈宇（翻着代码）："你写了三个控制模式？"<br>林一鸣："嗯。手动、半自主、全自主。半自主是自己规划路径到目标附近，人工确认后再抓取。全自主从识别到抓取到搬运全程自动。"<br>陈宇："比赛的时候你打算用哪个？"<br>林一鸣："正常情况下手动。如果被撞了——切半自主，让纠偏算法自己恢复位置。"<br>陈宇点了点头："我负责策略。一鸣负责操控。王磊你在场边观察对面机器人动向，随时提醒。"<br>王磊："明白。"<br>陈宇（看了一圈）："还有两周。有问题吗？"（没人说话）"那就干。" |
|光线与色调 | 同上。 |
|镜头衔接 | **视线匹配接011：** 011展示了铁牛一号的全貌，012切到陈宇的目光——他在看控制代码。 |
|时长 | 12秒 |
|生成提示词 | **Shot 012:** Medium shot. Captain flips through the student's code — "Three control modes?" "Manual, semi-autonomous, full autonomous. Manual for normal use. If we get hit — switch to semi-auto, let the recovery algorithm reset position." Captain nods: "Good plan." Assigns roles. Two weeks until competition. "Let's do it." **Team ready.** |

### 场6 / 外景 / 体育馆 / 日（比赛当天）

### 片段 014 — 体育馆全景·开场

| 项目 | 内容 |
|------|------|
|景别/机位 | 全远景——从观众席最高处拍 |
|画面描述 | 体育馆内座无虚席。中央是一块12m×8m的比赛场地，四周白色围栏。红色方块（10cm见方）散落在地面上。两端各有一个得分区。铁牛一号停在场地一角——对面是一台比它大一圈的机器人。 |
|光线与色调 | 聚光灯明亮热烈，观众席暗。 |
|镜头衔接 | **硬切+氛围突变接012：** 012的小活动室→013的体育馆——从窄到宽的视觉冲击。 |
|时长 | 5秒 |
|生成提示词 | **Shot 013:** Wide establishing shot from the highest seating row. Packed gymnasium, arena below — 12x8 meters with white barriers. Red cubes scattered across the field. Two robots at opposite corners — one small (theirs), one larger (opponent). **Bright arena lights, dark audience. Electric atmosphere.** |

### 片段 015 — 操作区·手心出汗

| 项目 | 内容 |
|------|------|
|景别/机位 | 近景——遥控器在他的手里，手心的汗 |
|画面描述 | 林一鸣站在场地边的操作区里。遥控器握在手里，手心里全是汗。面前有一块屏幕——显示铁牛一号第一人称摄像头画面及实时参数：电机温度、电池电压、激光雷达扫描结果。陈宇站在他旁边，手搭在他肩上，盯着对面。 |
|对白 | 陈宇（盯着对面）："对面底盘比你重，撞不过。"<br>林一鸣："知道。"<br>陈宇："所以不要正面撞。绕侧。"<br>林一鸣："知道。"<br>（裁判哨声响了） |
|光线与色调 | 操作区的暗色背景中，屏幕光照亮他的脸。 |
|镜头衔接 | **视线匹配接013：** 013的全景建立后，014切到操作区——从场地到人。 |
|时长 | 7秒 |
|生成提示词 | **Shot 014:** Close-up of the control station. The student holds the remote — sweaty palms. A monitor shows the robot's POV camera feed and real-time data: motor temp, battery voltage, LIDAR scan. His teammate's hand on his shoulder. "They're heavier. Don't ram — go around." "Got it." **Referee whistle blows.** |

### 片段 016 — 第一回合·横向平移

| 项目 | 内容 |
|------|------|
|景别/机位 | 侧面拍——麦克纳姆轮的独特移动方式一目了然 |
|画面描述 | 铁牛一号启动。四个麦克纳姆轮同时转动——它没有前进，而是像螃蟹一样横向贴着场地边缘移动。对面机器人直线冲过来拦截——扑了个空。铁牛一号在最近的一个方块旁停下——机械臂下降，腰部旋转15度，大臂下压，夹具张开、夹住、抬起。整个过程2.7秒。 |
|光线与色调 | 聚光灯明亮。铁牛一号的白色外壳在灯光下显眼。 |
|镜头衔接 | **声音桥接接014：** 014的哨声响起后没断——015的第一个画面铁牛一号已经在动了，哨声的尾音充当了"开始"的信号。 |
|时长 | 6秒 |
|生成提示词 | **Shot 015:** Side view of the arena. The robot moves sideways like a crab — mecanum wheels showing their unique omni-directional capability. Opponent charges straight — misses completely. Robot reaches a cube, arm descends, gripper closes, lifts. 2.7 seconds. **First point.** |

### 片段 017 — 被撞·方块飞了

| 项目 | 内容 |
|------|------|
|景别/机位 | 观众席视角——撞击的瞬间，一声惊呼 |
|画面描述 | 铁牛一号正在搬运第三个方块。对面机器人改变了战术——"之"字形走位逼近，从右后方撞击。铁牛一号被撞得原地转了大半圈，夹具里的方块飞出去滚落在地上。观众席一声惊呼。 |
|光线与色调 | 同上。 |
|镜头衔接 | **动作匹配接015：** 015末尾铁牛一号在搬运，016第一帧对面机器人已经逼近——观众的惊呼声从016开始持续到017。 |
|时长 | 4秒 |
|生成提示词 | **Shot 016:** Audience POV. The robot is hit from behind by the larger opponent — spins half a turn, the cube flies out and rolls across the floor. Crowd gasps. **Dramatic moment.** |

### 片段 018 — 拇指拨开关·半自主纠偏

| 项目 | 内容 |
|------|------|
|景别/机位 | 极近特写——他的右手拇指在遥控器上拨动开关 |
|画面描述 | 撞击发生的同一瞬间——林一鸣的右手拇指已经拨动了遥控器上的开关。从手动切换到半自主模式。铁牛一号底部的激光雷达开始360度扫描。50毫秒内计算出偏航角11.3度、位移17厘米。底盘自动回调，雷达锁定最近方块，机械臂自动调整抓取位——夹住、抬起。整个过程不到四秒。然后机器人自动向得分区运动。他切回手动微调——方块落进得分区。这时他才感觉到自己的心跳。 |
|光线与色调 | 同上。屏幕上的激光雷达扫描画面快速闪烁。 |
|镜头衔接 | **动作匹配接016：** 016的机器人被撞旋转还没停，017的拇指已经开始拨开关——两个镜头的裁切点在撞击发生的同一帧。用"同时发生"来强调他的即时反应。 |
|时长 | 8秒 |
|生成提示词 | **Shot 017:** Extreme close-up of the operator's thumb switching the remote toggle — simultaneous with the collision in shot 016. The robot's LIDAR spins, recalculates position in milliseconds, auto-repositions, re-grasps a cube, moves to score. He switches back to manual for fine tuning. The cube drops into the scoring zone. He only then feels his own heartbeat. **Instant reaction under pressure.** |

### 片段 019 — 闭眼·缓一口气

| 项目 | 内容 |
|------|------|
|景别/机位 | 正面近景——他的脸在屏幕光中 |
|画面描述 | 方块落进得分区后，林一鸣放开了遥控器一只手，在裤子上擦了一下手心的汗。然后重新握紧。他闭上眼——吸了一口气——慢慢呼出来。陈宇在旁边看到了，没有催他。大概过了五秒。他睁开眼。"好了？""好了。"他把遥控器换了一个更顺手的手势。 |
|对白 | 林一鸣（放下遥控器一只手，擦了一下汗，重新握紧。闭上眼——吸一口气——呼出来）<br>陈宇（看着他，没有催）："好了？"<br>林一鸣（睁开眼，点了下头）："好了。" |
|光线与色调 | 屏幕光照亮他的脸。身后的观众席和赛场的光在他眼睛里有微弱的反光。 |
|镜头衔接 | **视线匹配接017：** 017末尾方块进了得分区他站稳了，018切到他的脸——从动作到人的反应。 |
|时长 | 6秒 |
|生成提示词 | **Shot 018:** Front close-up of the operator's face lit by the monitor. After scoring, he briefly sets down the remote, wipes his palm on his pants, picks it up again. Closes his eyes. Takes a slow breath. Exhales. His teammate watches silently, waits. About five seconds pass. He opens his eyes: "Ready." "Ready." Switches the remote to a more comfortable grip. **The calm after crisis.** |

### 片段 020 — 全自主模式·锁定胜局

| 项目 | 内容 |
|------|------|
|景别/机位 | 中景——他站在操作台前，站直了，没有低头看屏幕——看着场地 |
|画面描述 | 比赛还剩两分钟。林一鸣切换了策略——他把铁牛一号换到全自主模式。机器人开始自己做判断：激光雷达扫描全场，锁定最近方块，规划最短路径，移动、抓取、搬运。他只需要在旁边看着，偶尔微调方向。最后一分钟——铁牛一号抓住第六个方块往得分区移动。对面机器人横在路中间。他打了一个方向——铁牛一号绕了一个弧线从另一侧接近得分区——夹具张开——方块落下。终场哨声。 |
|光线与色调 | 开场时他低头看屏幕，切换到全自主后他站直了，身体语言变了。 |
|镜头衔接 | **动作匹配接018：** 018末尾他睁开了眼说"好了"，019切换了遥控器模式——"从手动到自动"。 |
|时长 | 10秒 |
|生成提示词 | **Shot 019:** Medium shot of the operator standing taller now — switched to full autonomous mode. The robot navigates independently: LIDAR scanning, path planning, cube retrieval, transport. He watches, occasionally corrects. Final minute — opponent blocks the path. He steers smoothly around. Gripper opens. Cube drops. **Final buzzer.** |

### 片段 021 — 放下遥控器·手在抖

| 项目 | 内容 |
|------|------|
|景别/机位 | 特写——他的手，遥控器从手里放下 |
|画面描述 | 终场哨声。最终比分98:87。铁牛一号停在场地中央，六个方块在得分区码得整整齐齐。林一鸣放下遥控器——这才发现自己的右手在微微发抖。他低头看了看自己的手，然后握了一下拳，手不抖了。 |
|光线与色调 | 聚光灯从上方照下来，他的手在光圈里。 |
|镜头衔接 | **视线匹配接019：** 019末尾方块落下终场哨响，020切到他的手——"结果确认后的生理反应"。 |
|时长 | 5秒 |
|生成提示词 | **Shot 020:** Close-up of the hand putting down the remote — trembling slightly. The final score: 98-87. The robot stands in the arena, six cubes neatly stacked in the scoring zone. He looks at his own hand, makes a fist — the trembling stops. **Adrenaline settling.** |

### 场7 / 外景 / 体育馆 / 颁奖台

### 片段 022 — 颁奖台·递奖杯

| 项目 | 内容 |
|------|------|
|景别/机位 | 中景——三人站在颁奖台上，陈宇在中间举奖杯 |
|画面描述 | 颁奖台。陈宇站在中间举起奖杯。林一鸣站在边上，脖子上挂着金牌。陈宇转过身把奖杯递给他——"你来端一下？"他接过奖杯低头看了看，递回去——"你端着吧。"他不是客气。他低头在看场地里——工作人员正在把铁牛一号推走。他的表情不是高兴——是一种确认。这条路是对的。 |
|对白 | 陈宇（转过身，把奖杯递向林一鸣）："你来端一下？"<br>林一鸣（接过奖杯低头看了看，递回去）："你端着吧。" |
|光线与色调 | 舞台光。金牌反光。 |
|镜头衔接 | **视线匹配接020：** 020的末尾他的手不抖了，他抬头看向场地——021顺着他的视线看到颁奖台。 |
|时长 | 6秒 |
|生成提示词 | **Shot 021:** Award ceremony. Three students on the podium with gold medals. Captain offers the trophy to the quiet one: "Hold it?" He takes it briefly, looks at it, hands it back: "You keep it." Not politeness — his gaze is on the arena where workers are wheeling their robot away. His expression: not joy. Confirmation. **This path is right.** |

### 场8 / 外景 / 体育馆门口 / 日

### 片段 023 — 体育馆门口·苏晚晴

| 项目 | 内容 |
|------|------|
|景别/机位 | 从侧面拍——她走过来，在他旁边站住 |
|画面描述 | 体育馆侧门口。阳光很好。林一鸣靠着墙站着，低头看脖子上的金牌。一个女生在旁边站住了——苏晚晴，短发，浅色外套。她笑了笑："恭喜啊。我在看台上看到了。""你也来了？""王磊说的你们今天比赛。正好没课，就过来看看。" |
|对白 | 苏晚晴（笑了笑）："恭喜啊。我在看台上看到了。"<br>林一鸣（抬起头）："你也来了？"<br>苏晚晴："王磊说的你们今天比赛。正好没课，就过来看看。"<br>林一鸣（把金牌摘下来看了看）："也就那样。差一点被撞翻了。"<br>苏晚晴："我看你后来稳住了。反应挺快的。" |
|光线与色调 | 室外自然光，阳光好但不刺眼。偏暖的午后光。 |
|镜头衔接 | **硬切+环境突变接021：** 021室内舞台光→022室外自然光——从颁奖出来到门口遇见。 |
|时长 | 8秒 |
|生成提示词 | **Shot 022:** Outside the gymnasium entrance. Warm afternoon sunlight. The student leans against the wall looking at his gold medal. A short-haired girl approaches and stops beside him: "Congrats. I saw it from the stands." He looks up, surprised but not unhappy. **First encounter — casual, natural.** |

### 片段 024 — "你那个机器人走得挺帅的"

| 项目 | 内容 |
|------|------|
|景别/机位 | 双人中景——她比他矮半个头，说话时微微仰头 |
|画面描述 | 她问晚上团队吃饭她去不去。林一鸣说王磊也在，说让她来。她笑了一下说那行。走了两步又回头："哦对了——你那个机器人，走得挺帅的。"然后走了。林一鸣站在原地愣了一下。 |
|对白 | 苏晚晴："晚上他们说要吃饭，你去不去？"<br>林一鸣："王磊也在。他说让你来。"<br>苏晚晴（笑了一下）："那行。"（走了两步又回头）"哦对了——你那个机器人，走得挺帅的。"（然后走了）<br>林一鸣站在原地，愣了一下。 |
|光线与色调 | 同上。她转身时阳光在她头发上。 |
|镜头衔接 | **视线匹配接022：** 022末尾她对视说完，023她转身要走——顺着她的动作拍到她的背影和回眸。 |
|时长 | 6秒 |
|生成提示词 | **Shot 023:** Medium two-shot. She asks about the team dinner. He says she should come. She smiles, agrees. Takes two steps, turns back: "Oh — your robot. It moved pretty cool out there." Then walks away. He stands there for a moment, processing. **Warm sunlight in her hair as she turns.** |

### 场9 / 内景 / 饭店包间 / 夜（庆功宴）

### 片段 025 — 举杯

| 项目 | 内容 |
|------|------|
|景别/机位 | 全景——小圆桌，几个人举杯 |
|画面描述 | 饭店小包间。暖黄灯光。四个人加上周师傅和陈志强院长围着一张圆桌。几盘菜和一箱啤酒。陈志强举起杯："来，为几位同学的全国一等奖——干一杯。"大家碰杯。气氛好。 |
|对白 | 陈志强（举起杯）："来，为几位同学的全国一等奖——干一杯。" |
|光线与色调 | 包间暖黄。啤酒瓶在灯光下反光。热气从菜盘上升起来。 |
|镜头衔接 | **硬切+光线转换接023：** 023的室外午后光→024的室内暖黄夜灯——从白天到夜晚。 |
|时长 | 4秒 |
|生成提示词 | **Shot 024:** Full shot of a small round table in a restaurant private room. Warm yellow light. Four students plus the lab technician and the dean raising glasses. "To the national first prize — cheers." Clinking glasses. **Warm celebration atmosphere, steam rising from dishes.** |

### 片段 026 — 压低声音·"考更好的"

| 项目 | 内容 |
|------|------|
|景别/机位 | 近景双人——陈宇侧过身低声说，周围声音渐弱 |
|画面描述 | 气氛热闹。王磊在高声说"明年冲冠军"。陈宇坐在林一鸣旁边，压低声音——"你保研的事……准备了没有？"林一鸣顿了一下："我绩点不够。""差多少？""综合排名二十多。名额只有十个。"陈宇沉默了一会儿："那你什么打算？""先考吧。""考本校？"林一鸣摇了摇头："考更好的。"陈宇看了他一眼，举起酒瓶碰了一下他的瓶子——"行。" |
|对白 | 陈宇（压低声音）："你保研的事……准备了没有？"<br>林一鸣（顿了一下）："我绩点不够。"<br>陈宇："差多少？"<br>林一鸣："综合排名二十多。名额只有十个。"<br>陈宇沉默了一会儿："那你什么打算？"<br>林一鸣："先考吧。"<br>陈宇："考本校？"<br>林一鸣（摇了摇头）："考更好的。"<br>陈宇看了他一眼，举起酒瓶碰了一下他的瓶子："行。" |
|光线与色调 | 暖黄灯光。周围热闹的声音作为背景——他们的对话是压低声音的。 |
|镜头衔接 | **动作匹配接024：** 024的碰杯声还在，025切到陈宇侧过身的动作——从欢乐到安静的瞬间。 |
|时长 | 12秒 |
|生成提示词 | **Shot 025:** Close two-shot. While the rest of the table celebrates loudly, the captain lowers his voice: "Have you prepared for grad school recommendation?" "My GPA isn't enough." "By how much?" "Ranked 20-something, only 10 spots." Silence. "What's your plan?" "I'll take the exam." "This school?" He shakes his head: "A better one." The captain looks at him, clinks their bottles: "Alright." **The celebration continues around them, but this conversation is private.** |

### 片段 027 — 画外音·真正的难题才开始

| 项目 | 内容 |
|------|------|
|景别/机位 | 蒙太奇——空场地→装箱→奖杯→夜晚街道 |
|画面描述 | 快速蒙太奇：体育馆空了的场地→铁牛一号被装进箱子→金色的奖杯放在桌上→林一鸣走出饭店，外面是夜晚的街道，路灯把人的影子拉得很长。他一个人的背影。 |
|对白 | 【画外音·中年林一鸣】"拿了奖之后，大家都很高兴。但我心里清楚——一等奖改变不了排名。比赛结束了，真正的难题才开始。" |
|光线与色调 | 从暖到冷——从包间暖黄切到冷色夜晚街道。 |
|镜头衔接 | **解说性插入接025：** 025末尾陈宇碰了瓶，026切入蒙太奇——从微观对话拉到宏观视角。 |
|时长 | 6秒 |
|生成提示词 | **Shot 026:** Quick montage: empty arena → robot being packed into a case→ gold trophy on table → young man walking alone on an empty night street, street light casting a long shadow behind him. **Voice-over:** "Winning changed nothing about my ranking. The real challenge was just beginning." **Cool blue night tone.** |

### 片尾

### 片段 028 — 切黑屏·字幕

| 项目 | 内容 |
|------|------|
|画面描述 | 纯黑屏。白色字幕："第三集·完"。 |
|镜头衔接 | **渐隐接026：** 026的夜晚街道渐渐暗下→黑屏。 |
|时长 | 4秒 |
|生成提示词 | Black screen. White text: "End of Episode 3." Fades out. |

### 片段 029 — 彩蛋·铁手在群里@了Yiming_Lin

| 项目 | 内容 |
|------|------|
|景别/机位 | 手机屏幕俯拍 |
|画面描述 | 手机屏幕。"机器人杂货铺"群。IronHand转发了一条全国机器人大赛的新闻链接，@Yiming_Lin："你们的防碰撞纠偏算法是自己写的？方便分享一下思路吗？"焊工小王和北风在下面接着问技术细节。林一鸣盯着屏幕——还没想好怎么回。但他知道，这群人在看他做的东西。 |
|光线与色调 | 手机屏幕亮白。周围暗。 |
|镜头衔接 | **硬切换026/027：** 字幕结束后直接切到手机屏幕。 |
|时长 | 6秒 |
|生成提示词 | **Shot 028:** Smartphone screen. Group chat "Robot Hobbyist Shop." IronHand shares a news link about the competition, @mentions Yiming_Lin: "That collision recovery algorithm — did you write it yourself? Would love to hear your approach." Other members asking technical questions. He stares at the screen, hasn't replied yet. **But he knows they're watching.** |

### 片段 030 — 锁屏·微笑

| 项目 | 内容 |
|------|------|
|景别/机位 | 近景——他的脸，屏幕光在暗下去 |
|画面描述 | 林一鸣看完了群里的消息。没有回复。但他把手机锁屏时——嘴角有一个自己都没察觉到的上扬。他站起身，从宿舍窗口往外看了一眼。夜色里的校园。然后把手机放进口袋，走回实验台前。 |
|光线与色调 | 手机屏幕光在他脸上→暗下去→窗外夜色。 |
|镜头衔接 | **动作匹配接028：** 028末尾手机屏幕上的消息滚动，029切到他的脸——从"在看"到"看完之后的反应"。 |
|时长 | 4秒 |
|生成提示词 | **Shot 029:** Close-up of his face as phone screen goes dark. After reading the group chat messages — he doesn't reply. But as he locks the phone, a slight upward corner of his mouth — he doesn't even notice it himself. He stands, looks out the window at the night campus, puts the phone in his pocket, walks back to his workbench. **Quiet satisfaction.** |

### 片段 031 — 切黑屏·字幕

| 项目 | 内容 |
|------|------|
|画面描述 | 纯黑屏。白色字幕："第三集·完"。 |
|镜头衔接 | **渐隐接029：** 029的夜色校园渐渐暗下→黑屏。 |
|时长 | 4秒 |
|生成提示词 | Black screen. White text: "End of Episode 3." Fades out. |