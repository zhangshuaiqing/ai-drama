# 《麦田里的钢铁》—— 第10集《AI觉醒》AI视频生成分镜

> **时间设定：** 研一暑假→研二开学。全剧中点。
> **核心事件：** 小七从零件到能走、大模型接入、第一次"听懂"指令。

---

## 统一角色设定

| 角色 | 长相特征 | 服装 |
|------|---------|------|
| 林一鸣（研一） | 比开学时瘦了一点，眼神更定，嘴角偶尔有焊锡烫伤的小疤 | 深色T恤或格子衬衫，永远穿同一件灰色外套 |
| 王海燕 | 短发干练，眼神聪明 | 实验室白大褂或深色卫衣 |
| 铁手/老何（网友） | 仅通过聊天框出现 | — |

---

## 片段列表

#### 片段 001 — 暑假·实验室
| 项目 | 内容 |
|------|------|
| 景别/机位 | 中景——实验室暑假空荡感 |
| 画面描述 | 暑假。学校没什么人。小七上半身装好了——两条手臂各四个关节，加上下半身，40公分人形骨架站在实验台上（需要手扶着才能平衡）。他在看一篇关于LLM做机器人任务规划的论文。 |
| 光线与色调 | 窗外夏天阳光很亮，室内偏暗——窗帘半拉 |
| 声音设计 | 空调声+窗外偶尔的鸟叫+翻论文的纸声 |
| 镜头衔接 | **硬开场：** 从黑屏字幕直接切到暑期的实验室 |
| 时长 | 5秒 |
| 生成提示词 | Summer vacation in university laboratory, half-empty room, young researcher reading LLM paper on laptop, 40cm humanoid robot skeleton on workbench, bright sunlight through half-closed curtains, cinematic |

#### 片段 002 — 合上论文写代码
| 项目 | 内容 |
|------|------|
| 景别/机位 | 近景——电脑屏幕+他的手 |
| 画面描述 | 他看完了论文合上，打开代码编辑器开始写。笔记本的RTX 3060在跑一个小模型。 |
| 光线与色调 | 屏幕冷光打在他脸上 |
| 声音设计 | 键盘敲击声+风扇声（显卡在跑） |
| 镜头衔接 | **动作匹配：** 从合上论文到打开编辑器 |
| 时长 | 4秒 |
| 生成提示词 | Close-up of laptop screen with code editor open, young man's hands typing, GPU fan running audible, screen light on face, dark room, cinematic |

#### 片段 003 — 小熊的视觉模型
| 项目 | 内容 |
|------|------|
| 景别/机位 | 特写——标数据的电脑屏幕 |
| 画面描述 | 他花了周末拍了几百张豆角照片标成熟度——眼睛快花了。但模型跑通了。在电脑上测试识别——豆角的成熟度判定准确。 |
| 光线与色调 | 屏幕蓝光 |
| 声音设计 | 鼠标点击声+模型跑通时的提示音 |
| 镜头衔接 | **时间跳接：** 片段002写代码→周末标数据 |
| 时长 | 4秒 |
| 生成提示词 | Close-up of computer screen showing object detection model training, bean images with maturity labels, model running successfully, late night coding atmosphere |

#### 片段 004 — LLM理解指令
| 项目 | 内容 |
|------|------|
| 景别/机位 | 近景——终端界面 |
| 画面描述 | 他在终端里输入一行文字："往前走三步"。模型解析——输出动作序列。虽然只是第一步但证明方向可行。 |
| 光线与色调 | 屏幕光 |
| 声音设计 | 键盘回车声+终端输出滚动的沙沙声 |
| 镜头衔接 | **时间跳接：** 视觉训练完成后到LLM集成测试 |
| 时长 | 4秒 |
| 生成提示词 | Terminal interface showing LLM parsing natural language command into action sequence, "walk forward three steps", command line aesthetic, screen light |

#### 片段 005 — 走了两步栽了
| 项目 | 内容 |
|------|------|
| 景别/机位 | 中景——实验台前 |
| 画面描述 | 让小七走——往前迈了一步，又迈了一步，第三步重心偏了，整个往前栽。他用手接住了。 |
| 光线与色调 | 同上 |
| 声音设计 | 小七迈步的电机声+栽倒碰触他手掌的声音 |
| 镜头衔接 | **动作匹配：** 从终端回车到小七尝试行走 |
| 时长 | 4秒 |
| 生成提示词 | Humanoid robot taking two steps then falling forward, young man catching it with hands, laboratory setting, trial and error moment, medium shot |

#### 片段 006 — 王海燕送水
| 项目 | 内容 |
|------|------|
| 景别/机位 | 中景——从门口视角看过去 |
| 画面描述 | 深夜。王海燕出现在门口端着一杯水。"师兄你还没回去？""再等一下。"她把水放在桌上问晚饭吃了没。他愣了一下说忘了。她端了一碗泡面回来："先吃。机器人倒不了。" |
| 光线与色调 | 深夜实验室暗光+走廊灯光形成反差 |
| 声音设计 | 门被推开的声音+杯子放在桌上的声音+泡面盒打开声 |
| 镜头衔接 | **声音桥接：** 机器人倒下的声音→门被推开声 |
| 时长 | 8秒 |
| 生成提示词 | Night laboratory, female classmate bringing water and instant noodles to young man working late, warm interaction, contrast between dark lab and bright corridor, medium shot |

#### 片段 007 — 吃了一口继续干
| 项目 | 内容 |
|------|------|
| 景别/机位 | 近景——他拿起叉子又放下 |
| 画面描述 | 他看了看泡面，又看了看歪倒的机器人。拿起叉子吃了一口。放下叉子，继续扶正机器人。 |
| 光线与色调 | 宿舍台灯暖黄 |
| 声音设计 | 吃面的吸溜声+放下叉子的清脆声 |
| 镜头衔接 | **动作匹配：** 从接泡面到吃一口到放下 |
| 时长 | 4秒 |
| 生成提示词 | Young man eating one bite of instant noodles then immediately returning to work on robot, unable to stop working, night laboratory, close-up |

#### 片段 008 — 凌晨·代码改了一版
| 项目 | 内容 |
|------|------|
| 景别/机位 | 俯拍——桌面的混乱状态 |
| 画面描述 | 凌晨。他把LLM输出的动作序列和底层运动控制之间的接口重写了一遍。编译通过。 |
| 光线与色调 | 台灯聚光+四周昏暗 |
| 声音设计 | 键盘快速敲击声+编译通过的提示音 |
| 镜头衔接 | **时间跳接：** 从吃泡面到凌晨 |
| 时长 | 4秒 |
| 生成提示词 | Overhead shot of cluttered desk late night, young man coding, compilation successful, warm desk lamp, engineering focus |

#### 片段 009 — 试跑·第一步
| 项目 | 内容 |
|------|------|
| 景别/机位 | 中景——实验台正面 |
| 画面描述 | 再次测试。输入"往前走三步把桌上那瓶水拿给我"。回车。屏幕上的代码开始运行。机器人开始动——第一步，右脚抬起，往前迈，落地。稳住了。 |
| 光线与色调 | 屏幕+小七指示灯+暗环境 |
| 声音设计 | 机器人电机第一次流畅运转的声音+脚步声 |
| 镜头衔接 | **动作匹配：** 从按回车到小七开始动 |
| 时长 | 6秒 |
| 生成提示词 | Robot taking first successful step after LLM integration, steady foot placement, young man watching intently, screen showing running code, breakthrough moment |

#### 片段 010 — 第二步·第三步
| 项目 | 内容 |
|------|------|
| 景别/机位 | 中景——小七全身 |
| 画面描述 | 第二步也迈出去了。第三步——比前两步慢——但落地的时候有一点偏移——差点倒下但自己调整回来了。 |
| 光线与色调 | 同上 |
| 声音设计 | 三步脚步声——第三脚落地时有轻微调整的摩擦声 |
| 镜头衔接 | **动作保持：** 同一个镜头不切——让观众和小七一起走完这三步 |
| 时长 | 5秒 |
| 生成提示词 | Robot walking three steps continuously, slight wobble on third step but self-correcting, continuous shot without cut, tension and relief |

#### 片段 011 — 拿到了水瓶
| 项目 | 内容 |
|------|------|
| 景别/机位 | 特写——夹爪和瓶子 |
| 画面描述 | 小七走到桌前，夹爪打开——握住了水瓶。他在旁边屏着气——因为夹爪力度还没调好。握住了。没有掉。 |
| 光线与色调 | 昏暗实验室中机器人指示灯反射在瓶身上 |
| 声音设计 | 夹爪伺服电机的精密转动声+握住瓶子的轻微碰撞声 |
| 镜头衔接 | **视线匹配：** 从他紧张的表情切到夹爪握住瓶子的瞬间 |
| 时长 | 5秒 |
| 生成提示词 | Close-up of robot gripper successfully grasping a water bottle, precise servo motor sound, young man holding breath watching, laboratory night |

#### 片段 012 — 他盯着看了十秒
| 项目 | 内容 |
|------|------|
| 景别/机位 | 近景——他的脸 |
| 画面描述 | 他没有欢呼没有跳。就是盯着小七——和它爪子里那瓶水。看了大概十秒。然后拿起手机拍了张照片。 |
| 光线与色调 | 暗环境+屏幕余光+小七指示灯 |
| 声音设计 | 安静——只有机器人的待机声、风扇声 |
| 镜头衔接 | **视线匹配：** 从夹爪特写切到他的脸 |
| 时长 | 4秒 |
| 生成提示词 | Close-up of young man staring at robot and water bottle for ten seconds, complex emotion of achievement, quiet moment, dim laboratory |

#### 片段 013 — 把照片发给铁手
| 项目 | 内容 |
|------|------|
| 景别/机位 | 特写——手机屏幕 |
| 画面描述 | 他把照片发给铁手。没有文字。就一张照片：小七握着水瓶。过了两分钟铁手回了——"是它自己走的？""它自己。""明天我白天给你打电话。"他笑了。 |
| 光线与色调 | 手机屏幕光在暗环境中 |
| 声音设计 | 微信消息发送声+消息提示音 |
| 镜头衔接 | **视线匹配：** 从看小七到看手机 |
| 时长 | 5秒 |
| 生成提示词 | Close-up of phone screen, sending photo of robot holding water bottle to IronHand, receiving excited response, night, screen light |

#### 片段 014 — 在实验室里走了一圈
| 项目 | 内容 |
|------|------|
| 景别/机位 | 全景——实验室 |
| 画面描述 | 他没有立刻继续改代码。站起来在实验室里走了一圈。不是散步——就是站起来走一走消化刚才那个时刻。走了几步停下来看看窗外。天快亮了。 |
| 光线与色调 | 窗外从深蓝开始变浅——黎明前 |
| 声音设计 | 脚步声+窗外清晨第一声鸟鸣 |
| 镜头衔接 | **空间切场：** 从手机到他在实验室走动的全景 |
| 时长 | 5秒 |
| 生成提示词 | Young man standing up and walking around empty laboratory at dawn, processing the breakthrough moment, window showing sky turning from dark blue to light, wide shot |

#### 片段 015 — 天亮了·小七在待机
| 项目 | 内容 |
|------|------|
| 景别/机位 | 中景——窗边的晨光+小七 |
| 画面描述 | 窗帘缝里透进来的晨光照在小七身上——金属外壳反射着暖黄色的光。小七站在那里——手里还握着那瓶水。 |
| 光线与色调 | 晨光暖调+金属反光 |
| 声音设计 | 清晨宁静+远处校园广播声 |
| 镜头衔接 | **时间跳接：** 从黎明前到太阳升起 |
| 时长 | 4秒 |
| 生成提示词 | Dawn light streaming through window gap onto robot, metallic shell reflecting warm yellow light, robot still holding water bottle, peaceful breakthrough morning |

#### 片段 016 — 铁手打来电话
| 项目 | 内容 |
|------|------|
| 景别/机位 | 近景——他接电话 |
| 画面描述 | 他刚趴下想眯一会儿——手机响了。铁手。"你没睡吧？""没。""我也不睡了。你那个接口方案——发我看看。我给你做一个机械层面的配合。"他愣了一下。"你那边才早上六点。"铁手笑了一声。"看完你的照片——睡不着了。" |
| 光线与色调 | 早晨自然光渐亮 |
| 声音设计 | 电话铃声+铁手在电话里的声音+笑声 |
| 镜头衔接 | **声音桥接：** 从宁静的清晨到电话铃声打破宁静 |
| 时长 | 8秒 |
| 生成提示词 | Young man answering phone call from IronHand early morning, excited technical discussion, sunlight brightening, close-up, collaboration |

#### 片段 017 — 挂了电话写方案
| 项目 | 内容 |
|------|------|
| 景别/机位 | 俯拍——他趴在桌上写 |
| 画面描述 | 挂了电话。他没有睡。打开笔记本开始写机械接口方案。手画了一张草图——把关节的力控精度要求标了上去。 |
| 光线与色调 | 清晨光越来越亮 |
| 声音设计 | 铅笔在纸上快速移动的声音+偶尔停下来思考 |
| 镜头衔接 | **动作匹配：** 从挂电话到立刻开始画图 |
| 时长 | 4秒 |
| 生成提示词 | Overhead shot of young man sketching mechanical interface design on paper, morning light brightening, engineering drawing, intense focus |

#### 片段 018 — 铁手也发来一份
| 项目 | 内容 |
|------|------|
| 景别/机位 | 特写——接收到的文件 |
| 画面描述 | 两小时后铁头发来一份机械接口的初步方案——密密麻麻的尺寸标注和材料说明。附言："你先看着。不对的标红。" |
| 光线与色调 | 屏幕光 |
| 声音设计 | 文件接收提示音 |
| 镜头衔接 | **视线匹配：** 从他画图到看手机收到的文件 |
| 时长 | 3秒 |
| 生成提示词 | Close-up of receiving engineering document from IronHand, detailed mechanical drawings, collaborative remote work, screen light |

#### 片段 019 — 小七走得更稳了
| 项目 | 内容 |
|------|------|
| 景别/机位 | 中景——走廊测试 |
| 画面描述 | 下午。小七加了铁手建议的阻尼参数后——步态比上午稳了很多。走出六步没有晃。他在旁边跟着走——像陪一个小孩学走路。 |
| 光线与色调 | 走廊自然光 |
| 声音设计 | 小七稳定的脚步声+他的脚步声（跟在后面） |
| 镜头衔接 | **时间跳接：** 下午，从改方案到测试 |
| 时长 | 5秒 |
| 生成提示词 | Robot walking steadily in laboratory corridor, six steps without wobble, young man walking alongside like teaching a child, afternoon natural light, medium shot |

#### 片段 020 — 王海燕在门口看了一眼
| 项目 | 内容 |
|------|------|
| 景别/机位 | 中景——门口视角 |
| 画面描述 | 王海燕路过实验室门口，看到他还在里面。没有进来。站在门口看了一会儿，然后走了。 |
| 光线与色调 | 走廊比实验室亮 |
| 声音设计 | 走廊脚步声+实验室门半掩的声音 |
| 镜头衔接 | **视线匹配：** 从走廊测试到她路过看到的视角 |
| 时长 | 3秒 |
| 生成提示词 | Female classmate passing by laboratory door, watching young man working with robot for a moment then leaving, POV from doorway, natural interaction |

#### 片段 021 — 写下计划
| 项目 | 内容 |
|------|------|
| 景别/机位 | 特写——笔记本 |
| 画面描述 | 他在笔记本上写了一个列表：1.步态稳定 2.视觉接入 3.室外测试。看了看合上。 |
| 光线与色调 | 台灯光 |
| 声音设计 | 笔在纸上写字的沙沙声+笔记本合上的声音 |
| 镜头衔接 | **动作匹配：** 从门口看他写计划 |
| 时长 | 4秒 |
| 生成提示词 | Close-up of notebook with to-do list: gait stability, vision integration, outdoor testing, young man closing the notebook, determined planning |

#### 片段 022 — 深夜喝水
| 项目 | 内容 |
|------|------|
| 景别/机位 | 中景——饮水机旁 |
| 画面描述 | 深夜。他去接水的时候路过小七。在它面前站了一下。然后继续走。 |
| 光线与色调 | 走廊感应灯+饮水机灯 |
| 声音设计 | 饮水机出水声+脚步声停顿又继续 |
| 镜头衔接 | **视线匹配：** 从写计划到深夜 |
| 时长 | 3秒 |
| 生成提示词 | Night laboratory corridor, young man passing robot to get water, pausing briefly to look at it, quiet moment, medium shot |

#### 片段 023 — 夏天快结束了
| 项目 | 内容 |
|------|------|
| 景别/机位 | 全景——窗内外对比 |
| 画面描述 | 窗外的蝉鸣声开始变了——夏天快过去了。小七从一堆零件变成了能走三步的机器人。 |
| 光线与色调 | 傍晚窗外金色 |
| 声音设计 | 渐弱的蝉鸣声+小七待机声 |
| 镜头衔接 | **时间跳接：** 夏天的快速流逝——蒙太奇式过渡 |
| 时长 | 4秒 |
| 生成提示词 | Window showing late summer, cicada sounds fading, robot standing in laboratory transformed from parts to functional prototype, poetic transition |

#### 片段 024 — 小七关机前
| 项目 | 内容 |
|------|------|
| 景别/机位 | 近景——手和夹爪 |
| 画面描述 | 他关掉小七的电源之前，按了一下它的手——夹爪轻轻握了一下他的手指。他愣了一下。然后关掉了电源。 |
| 光线与色调 | 实验室暗+小七指示灯逐渐熄灭 |
| 声音设计 | 夹爪闭合的轻音+电源关闭的提示音+安静 |
| 镜头衔接 | **动作匹配：** 从窗边到关电源前 |
| 时长 | 4秒 |
| 生成提示词 | Close-up of young man pressing robot's gripper before shutdown, gripper gently squeezing his finger, surprised reaction, power-down sequence, emotional moment |

#### 片段 025 — 他站在实验室门口回头看了一眼
| 项目 | 内容 |
|------|------|
| 景别/机位 | 中景——门框视角 |
| 画面描述 | 他收拾完东西站在实验室门口。回头看了一眼——小七站在实验台上。房间很暗。只有路由器和小七的指示灯亮着。他关了灯。带上门。 |
| 光线与色调 | 走廊灯亮+室内暗+指示灯发光 |
| 声音设计 | 灯开关声+门锁声 |
| 镜头衔接 | **空间切场：** 从关电源到站在门口回头 |
| 时长 | 5秒 |
| 生成提示词 | Young man standing at laboratory doorway looking back one last time, robot standing in dark with only indicator lights glowing, turning off light and closing door, end of day |

#### 片段 026 — 走在校园里
| 项目 | 内容 |
|------|------|
| 景别/机位 | 远景——校园主干道 |
| 画面描述 | 他走在暑假空荡荡的校园里。天已经黑了。路灯把他的影子拉得很长。步子不快不慢。 |
| 光线与色调 | 路灯暖黄+校园夜色 |
| 声音设计 | 脚步声+远处有学生在打篮球的声音——空旷的回响 |
| 镜头衔接 | **视线匹配：** 从关实验室门到走在校园里 |
| 时长 | 5秒 |
| 生成提示词 | Young man walking across empty summer campus at night, streetlights casting long shadows, quiet atmosphere, wide shot, contemplative |

#### 片段 027 — 宿舍灯亮了
| 项目 | 内容 |
|------|------|
| 景别/机位 | 远景——宿舍楼窗户 |
| 画面描述 | 宿舍楼的窗户亮了一盏。是他那间。过了一会儿——灭了。 |
| 光线与色调 | 宿舍楼外景+亮起的窗户 |
| 声音设计 | 安静的夜+远处偶尔的车声 |
| 镜头衔接 | **空间切场：** 从校园路上到宿舍楼外景 |
| 时长 | 4秒 |
| 生成提示词 | Wide shot of dormitory building at night, one window lighting up then turning off after a short while, tranquil campus night |

#### 片段 028 — 第二天·新的开始
| 项目 | 内容 |
|------|------|
| 景别/机位 | 中景——小七特写→拉开 |
| 画面描述 | 第二天。他走进实验室。打开灯。小七还在那里。他按下开机键——指示灯亮了。新的一天。 |
| 光线与色调 | 晨光+灯光打开 |
| 声音设计 | 开关声+小七启动的自检音 |
| 镜头衔接 | **时间跳接：** 第二天清晨 |
| 时长 | 4秒 |
| 生成提示词 | Young man entering laboratory in morning, turning on lights, powering up robot, new day begins, morning light, hopeful atmosphere |

#### 片段 029 — 看回放·昨晚的测试
| 项目 | 内容 |
|------|------|
| 景别/机位 | 近景——屏幕播放昨晚的录像 |
| 画面描述 | 他打开手机看昨晚拍的测试视频——小七走三步拿水瓶。看了好几遍。然后打开代码继续改进。 |
| 光线与色调 | 屏幕光 |
| 声音设计 | 视频播放的声音+他按下空格暂停又播放 |
| 镜头衔接 | **视线匹配：** 从开机到看昨晚的视频回放 |
| 时长 | 4秒 |
| 生成提示词 | Close-up of young man watching yesterday's test video on phone, robot walking three steps and grabbing water bottle, replaying multiple times, morning laboratory |

#### 片段 030 — 切黑屏·字幕
| 项目 | 内容 |
|------|------|
| 画面描述 | 黑屏。第十集完。 |
| 时长 | 4秒 |
