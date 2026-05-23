# 《麦田里的钢铁》—— 第9集《网络那头的人（下）》AI视频生成分镜

> **时间设定：** 研一春季学期。群友在线协作渐入佳境。
> **核心事件：** 小七骨架改进→力矩测试→视觉模型接入→苏晚晴电话中的裂痕加深→小七第一次站住。
> **基调：** 技术上稳步推进（群友协作让效率翻倍）+ 情感线悄然下行。

---

## 统一角色设定

| 角色 | 长相特征 | 服装 |
|------|---------|------|
| 林一鸣（研一下） | 同上，眼袋已有，嘴角偶尔有焊锡小疤 | 深色T恤+灰色外套 |
| 苏晚晴（电话） | 仅声音出场 | — |
| 群友 | 仅通过聊天框/电话声音出场 | — |

---

## 片段列表

#### 片段 001 — PETG骨架打印好了
| 项目 | 内容 |
|------|------|
| 景别/机位 | 中景——实验台上换骨架 |
| 画面描述 | 新骨架用PETG打印出来了。质感比PLA好——摸起来更结实，锤一下没有脆响。他把IronHand的电机装进大腿关节，螺丝拧紧——严丝合缝。转了一下关节——顺滑。 |
| 光线与色调 | 实验室白天自然光 |
| 声音设计 | 塑料件碰撞声+螺丝刀拧紧声+关节转动的轻响 |
| 镜头衔接 | **时间跳接：** 寒假后的新学期 |
| 时长 | 4秒 |
| 生成提示词 | Laboratory daytime, young man testing new PETG robot skeleton, fitting IronHand's motor into thigh joint, smooth rotation, improved build quality |

#### 片段 002 — 老K指出的改进了
| 项目 | 内容 |
|------|------|
| 景别/机位 | 近景——卡簧槽特写 |
| 画面描述 | 他按老K说的加了卡簧槽的位置重新打印了骨架。装上去的时候特别注意了轴向定位——用手推了推，没有串动。 |
| 光线与色调 | 实验室白 |
| 声音设计 | 塑料件卡扣声+推动测试的轻响 |
| 镜头衔接 | **动作匹配：** 从装好关节到检查轴向定位 |
| 时长 | 4秒 |
| 生成提示词 | Close-up of improved robot joint with retaining ring groove, testing axial play, no movement, precision engineering detail |

#### 片段 003 — 力矩测试·差了15%
| 项目 | 内容 |
|------|------|
| 景别/机位 | 中景——测力矩 |
| 画面描述 | 测小腿关节力矩——数据跟理论值差了15%。换了PWM频率，没改善。换了驱动芯片，还是差。在群里问了一句。 |
| 光线与色调 | 实验室台灯聚光 |
| 声音设计 | 测试设备蜂鸣声+键盘打字问问题 |
| 镜头衔接 | **动作匹配：** 从装好到测试 |
| 时长 | 4秒 |
| 生成提示词 | Young man testing joint torque, finding 15% deviation from theoretical value, troubleshooting on computer, laboratory setting |

#### 片段 004 — 小雨·"线径多少？"
| 项目 | 内容 |
|------|------|
| 景别/机位 | 特写——群聊消息 |
| 画面描述 | 小雨回了一个问题："你的电机线是多长的？40厘米。线径呢？24AWG。24AWG走这种电流，40厘米压降差不多15%。换成18AWG。"他查了一下——还真是。 |
| 光线与色调 | 屏幕冷光 |
| 声音设计 | 消息提示音+他查资料时的键盘声 |
| 镜头衔接 | **视线匹配：** 从测力矩到看群聊 |
| 时长 | 5秒 |
| 生成提示词 | Close-up of online chat, group member suggesting wire gauge as root cause of torque issue, young man checking, eureka moment |

#### 片段 005 — 换线·数据正常
| 项目 | 内容 |
|------|------|
| 景别/机位 | 中景——重新测试 |
| 画面描述 | 换了18AWG的线之后再测——数据正常了。差2%以内。他给小雨发了条消息说好了。 |
| 光线与色调 | 实验室 |
| 声音设计 | 焊接声+测试通过声 |
| 镜头衔接 | **时间跳接：** 换线后 |
| 时长 | 3秒 |
| 生成提示词 | Young man replacing wires and retesting torque, data now within 2%, problem solved, satisfaction |

#### 片段 006 — 小熊发来视觉模型
| 项目 | 内容 |
|------|------|
| 景别/机位 | 特写——群共享链接 |
| 画面描述 | 小熊在群里发了一个开源项目的链接——视觉模型识别农作物病虫害，准确率93%。他点开看了代码。问能不能在嵌入式平台上跑。小熊说改了个轻量版可以在Jetson Nano上跑实时。 |
| 光线与色调 | 屏幕冷光 |
| 声音设计 | 鼠标点击链接声+代码滚动声 |
| 镜头衔接 | **视线匹配：** 从测试到看群消息 |
| 时长 | 5秒 |
| 生成提示词 | Close-up of online group sharing open source vision model for crop disease detection, young man exploring code, technical collaboration |

#### 片段 007 — "你用来干嘛？"
| 项目 | 内容 |
|------|------|
| 景别/机位 | 中景——他在思考 |
| 画面描述 | 小熊问他用来干嘛。他想了想："还没想好。但我那个机器人——如果它能看见东西，应该比现在有用得多。"他把repo存了下来。一个念头闪过。 |
| 光线与色调 | 实验室自然光 |
| 声音设计 | 键盘声+沉默思考 |
| 镜头衔接 | **对话衔接：** 从看代码到思考用途 |
| 时长 | 4秒 |
| 生成提示词 | Young man thinking about application of vision model for robot, saving repository, germ of an idea forming |

#### 片段 008 — 苏晚晴电话·"想跟你说一下"
| 项目 | 内容 |
|------|------|
| 景别/机位 | 近景——宿舍夜 |
| 画面描述 | 晚宿舍。苏晚晴打电话来说今天被领导批评了——报表小数点点错了。他说以后仔细一点。她说"就是……想跟你说一下"。他说嗯以后注意点。她在电话那头没再说话。一会儿换话题问机器人怎么样了。又说了几句就挂了。 |
| 光线与色调 | 宿舍夜灯暖黄 |
| 声音设计 | 电话通话声+她的声音+沉默 |
| 镜头衔接 | **段落切场：** 从技术讨论到私人通话 |
| 时长 | 10秒 |
| 生成提示词 | Night dormitory, young man on phone with girlfriend, she calls to vent about work but he gives practical advice instead of empathy, growing disconnect |

#### 片段 009 — 挂电话·手机放桌上
| 项目 | 内容 |
|------|------|
| 景别/机位 | 近景——手机屏幕渐暗 |
| 画面描述 | 挂了电话后他把手机放在桌上，看着屏幕暗下去。坐了几秒才起身。 |
| 光线与色调 | 暗光+屏幕渐暗 |
| 声音设计 | 挂断声+安静 |
| 镜头衔接 | **视线匹配：** 从说电话到看手机暗下去 |
| 时长 | 3秒 |
| 生成提示词 | Close-up of phone screen dimming after call, young man sitting in silence for a few seconds, uncomfortable pause |

#### 片段 010 — 画外音·没听懂
| 项目 | 内容 |
|------|------|
| 景别/机位 | 近景——他坐在电脑前 |
| 画面描述 | 他坐在桌前看着笔记本电脑屏幕——屏幕亮着但没有在打字。 |
| 光线与色调 | 屏幕光打在脸上 |
| 声音设计 | 安静+风扇声 |
| 镜头衔接 | **独白空间：** |
| 时长 | 4秒 |
| 生成提示词 | Young man sitting at laptop, screen on but not typing, internal realization he missed what his girlfriend needed, close-up |

#### 片段 011 — 继续调PID
| 项目 | 内容 |
|------|------|
| 景别/机位 | 中景——实验台前 |
| 画面描述 | 他坐回电脑前继续调PID参数。小七的下半身在测试支架上。一行一行地改代码。 |
| 光线与色调 | 实验室灯光 |
| 声音设计 | 键盘编程声+小七支架上的电机微调声 |
| 镜头衔接 | **动作匹配：** 从坐着到回到工作 |
| 时长 | 4秒 |
| 生成提示词 | Young man returning to PID tuning, robot lower body on test stand, focused coding, pushing through |

#### 片段 012 — 连续几天测试
| 项目 | 内容 |
|------|------|
| 景别/机位 | 蒙太奇——参数调整循环 |
| 画面描述 | 蒙太奇：改参数→跑测试→记录→再改参数→再跑测试。桌上那本笔记本越写越厚。 |
| 光线与色调 | 日夜交替 |
| 声音设计 | 键盘声+小七电机运转声+笔写声混剪 |
| 镜头衔接 | **蒙太奇：** 压缩几天的反复测试 |
| 时长 | 4秒 |
| 生成提示词 | Montage of iterative testing cycle, adjusting parameters, running tests, logging results, notebook getting thicker, days passing |

#### 片段 013 — 小腿关节装好了
| 项目 | 内容 |
|------|------|
| 景别/机位 | 中景——小七下半身 |
| 画面描述 | 两条腿的最后一个关节装好了。所有电机就位，所有线接好。他站在小七面前——虽然只有下半身，但看起来已经像那么回事了。 |
| 光线与色调 | 实验室傍晚光 |
| 声音设计 | 最后一个螺丝拧紧声+安静 |
| 镜头衔接 | **时间跳接：** 几天的测试完成后 |
| 时长 | 4秒 |
| 生成提示词 | Robot lower body fully assembled, all joints and motors in place, young man standing in front of it, milestone moment, evening light |

#### 片段 014 — 第一次通电
| 项目 | 内容 |
|------|------|
| 景别/机位 | 近景——手按电源 |
| 画面描述 | 他深吸一口气按了电源。两个髋关节转动——蹲下。膝关节伸展——站起来。脚踝微调——平衡。它站住了。一秒。两秒。三秒。没有倒。 |
| 光线与色调 | 暗实验室+小七指示灯亮起 |
| 声音设计 | 电源启动声+关节电机同步声+安静的三秒 |
| 镜头衔接 | **动作匹配：** 装好到通电 |
| 时长 | 6秒 |
| 生成提示词 | Close-up of pressing power button, robot lower body powering up, hip and knee joints moving, standing steady for three seconds, breakthrough moment |

#### 片段 015 — 他蹲下来平视它
| 项目 | 内容 |
|------|------|
| 景别/机位 | 中景——他和机器人平视 |
| 画面描述 | 他蹲下来——和小七平视。它站在那里，两条腿。几个电机几条线一堆3D打印件——但它站在那里。他伸手轻轻碰了一下它的外壳。 |
| 光线与色调 | 实验室暗+小七指示灯微光 |
| 声音设计 | 安静+手指轻碰外壳的触感声 |
| 镜头衔接 | **视线匹配：** 从站着到蹲下平视 |
| 时长 | 5秒 |
| 生成提示词 | Young man crouching to eye level with robot lower body, gently touching its shell, emotional connection with creation |

#### 片段 016 — 拍了一张照片
| 项目 | 内容 |
|------|------|
| 景别/机位 | 特写——手机相册 |
| 画面描述 | 他拿起手机拍了张照片——小七的下半身站在实验台上。没有发到群里。自己存着。 |
| 光线与色调 | 手机屏幕光 |
| 声音设计 | 手机拍照声 |
| 镜头衔接 | **动作匹配：** 从摸到拍 |
| 时长 | 3秒 |
| 生成提示词 | Close-up of taking photo of robot lower body, not sharing it, keeping it for himself, private milestone |

#### 片段 017 — 铁手发来上位机软件
| 项目 | 内容 |
|------|------|
| 景别/机位 | 特写——收到的文件 |
| 画面描述 | 晚上铁手发来一个上位机软件——调试步态用的界面。界面很简陋——灰底黑字，几个按钮——但能用。他装上试了一下——可以在电脑上实时调每个关节的角度。 |
| 光线与色调 | 屏幕冷光 |
| 声音设计 | 文件接收声+安装声+软件界面点击声 |
| 镜头衔接 | **视线匹配：** 从照片到看电脑 |
| 时长 | 4秒 |
| 生成提示词 | Receiving gait debug software from IronHand, simple UI but functional, real-time joint angle control, night laboratory |

#### 片段 018 — 调了一整晚步态
| 项目 | 内容 |
|------|------|
| 景别/机位 | 中景——深夜调参 |
| 画面描述 | 有了上位机软件，他调了一整晚步态。四个关节的角度曲线在屏幕上跳动。小七的腿在测试架上交替摆动——像一个在学走路的孩子被提着走。 |
| 光线与色调 | 深夜暗+屏幕光 |
| 声音设计 | 软件操作声+小七腿部交替摆动的电机声 |
| 镜头衔接 | **时间跳接：** 收到软件后立刻开始 |
| 时长 | 5秒 |
| 生成提示词 | Night debugging session with new gait software, robot legs moving alternately on test stand, joint angle curves on screen, intense focus |

#### 片段 019 — 凌晨四点的消息
| 项目 | 内容 |
|------|------|
| 景别/机位 | 特写——群聊时间戳 |
| 画面描述 | 凌晨四点。他在群里发了一条消息——一段十秒的视频：小七的下半身在测试架上走了一圈。没有配文字。过了一会——IronHand回了三个字："有那味了。"小熊回了一个竖起大拇指的表情。老K回了一个"继续"。他看了三遍回复。 |
| 光线与色调 | 暗+屏幕光 |
| 声音设计 | 消息发送声+回复提示声连续响起 |
| 镜头衔接 | **视线匹配：** 从调参到发消息 |
| 时长 | 5秒 |
| 生成提示词 | 4am group chat, young man posting 10-second video of robot walking on test stand, IronHand replies "getting there", small wins with online community |

#### 片段 020 — 关了电脑·躺下
| 项目 | 内容 |
|------|------|
| 景别/机位 | 中景——关电脑 |
| 画面描述 | 他关了电脑。没有洗漱，直接躺下。窗外天已经有点发白了。他闭着眼睛——嘴角有一点弧度。 |
| 光线与色调 | 窗外黎明前深蓝 |
| 声音设计 | 电脑关闭声+衣服摩擦声+躺下声 |
| 镜头衔接 | **动作匹配：** 从发消息到关电脑 |
| 时长 | 4秒 |
| 生成提示词 | Young man closing laptop and lying down without washing,窗外dawn light, slight smile of satisfaction, exhausted but fulfilled |

#### 片段 021 — 第二天·去食堂的路上
| 项目 | 内容 |
|------|------|
| 景别/机位 | 远景——校园日景 |
| 画面描述 | 第二天下午他走去食堂。太阳很好。他走得不快。口袋里手机震了一下——是小熊发来的消息，说那个视觉模型他改了轻量版框架，发了一个链接。 |
| 光线与色调 | 下午阳光温暖 |
| 声音设计 | 脚步声+手机消息声+校园背景 |
| 镜头衔接 | **时间跳接：** 第二天 |
| 时长 | 4秒 |
| 生成提示词 | Young man walking to cafeteria on sunny afternoon, phone buzzing with message from online group member about vision model update, relaxed pace |

#### 片段 022 — 边走边看代码
| 项目 | 内容 |
|------|------|
| 景别/机位 | 近景——边走边看手机 |
| 画面描述 | 他边走边打开链接——小熊的轻量版视觉模型。在手机屏幕上滑了一下代码——边走路边看。差点撞到一棵树——闪了一下继续走。 |
| 光线与色调 | 阳光斑驳的校园路 |
| 声音设计 | 脚步+手机滑动声+差点撞树的声响+笑 |
| 镜头衔接 | **动作匹配：** 从食堂路上到边走边看 |
| 时长 | 4秒 |
| 生成提示词 | Young man walking while reading code on phone, almost walking into a tree, dodging at last moment, campus sunlight |

#### 片段 023 — 回到实验室立刻试
| 项目 | 内容 |
|------|------|
| 景别/机位 | 中景——接视觉模块 |
| 画面描述 | 到实验室饭都没吃，他把小熊的轻量版视觉模型接到小七的树莓派上。编译——通过。运行——摄像头画面里出现了一个框——框住了桌上的螺丝刀。"螺丝刀"——置信度87%。 |
| 光线与色调 | 实验室灯光 |
| 声音设计 | 键盘编译声+树莓派风扇声+软件运行提示音 |
| 镜头衔接 | **动作匹配：** 从差点撞树到冲到实验室 |
| 时长 | 5秒 |
| 生成提示词 | Young man rushing to lab, integrating lightweight vision model on Raspberry Pi, camera recognizing screwdriver with 87% confidence, successful object detection |

#### 片段 024 — 在群里发了一张截图
| 项目 | 内容 |
|------|------|
| 景别/机位 | 特写——群聊截图 |
| 画面描述 | 他截了一张图——螺丝刀被框住的那个画面。发到群里。配了一行字："小七有眼睛了。"群聊消息：小熊回"666"、老K回"终于"、IronHand回了一个表情——握拳。 |
| 光线与色调 | 屏幕光 |
| 声音设计 | 截图声+消息发送声+回复声 |
| 镜头衔接 | **视线匹配：** 从看到桌面的框到截屏 |
| 时长 | 4秒 |
| 生成提示词 | Close-up of group chat, sharing screenshot of object detection working, robot can now see, online community celebration with emojis |

#### 片段 025 — 画外音·一个遥远的想法
| 项目 | 内容 |
|------|------|
| 画面描述 | 他坐在电脑前，看着摄像头画面里那个框。 |
| 光线与色调 | 屏幕光 |
| 声音设计 | 安静+机器待机声 |
| 镜头衔接 | **独白空间：** |
| 时长 | 5秒 |
| 生成提示词 | Close-up of young man looking at camera feed with object detection boxes, quiet contemplation, a distant idea forming |

#### 片段 026 — 他想了想·写了几个字在笔记本上
| 项目 | 内容 |
|------|------|
| 景别/机位 | 特写——笔记本 |
| 画面描述 | 他翻开笔记本，在空白页上写了几个字："能看见——就能自己判断。"下面划了一条线。然后合上本子。 |
| 光线与色调 | 台灯暖光 |
| 声音设计 | 笔写字的沙沙声+本子合上声 |
| 镜头衔接 | **动作匹配：** 从想到写 |
| 时长 | 3秒 |
| 生成提示词 | Close-up of notebook, writing "seeing means autonomous judgment", underlining it, closing the notebook, seed of future breakthrough |

#### 片段 027 — 小七在测试架上走了一圈又一圈
| 项目 | 内容 |
|------|------|
| 景别/机位 | 全景——小七在走 |
| 画面描述 | 小七在测试架上走了一圈又一圈。他在旁边改代码。屏幕上的曲线越来越平。笔记本上记录的数据越来越密。 |
| 光线与色调 | 实验室夜 |
| 声音设计 | 小七有节奏的脚步声+键盘声 |
| 镜头衔接 | **时间跳接：** 又过了几天 |
| 时长 | 5秒 |
| 生成提示词 | Time-lapse of robot walking on test stand repeatedly, young man refining code, data curves getting smoother, notebook filling up, night laboratory |

#### 片段 028 — 北风发来控制算法参考
| 项目 | 内容 |
|------|------|
| 景别/机位 | 特写——收到的PDF |
| 画面描述 | 北风在群里发了一篇论文链接——关于双足机器人的步态控制算法。还有一句："这个你应该用得上。别只看摘要——正文里有一个附录写了力矩分配公式。"他存了。 |
| 光线与色调 | 屏幕光 |
| 声音设计 | 论文链接点击声+PDF下载声 |
| 镜头衔接 | **视线匹配：** 从小七走到看手机消息 |
| 时长 | 4秒 |
| 生成提示词 | Receiving academic paper link on bipedal gait control from group member, recommended to read full appendix with torque distribution formula, collaborative research |

#### 片段 029 — 切黑屏·字幕
| 项目 | 内容 |
|------|------|
| 画面描述 | 黑屏。第九集完。 |
| 时长 | 4秒 |

#### 片段 030 — 彩蛋·群聊截屏
| 项目 | 内容 |
|------|------|
| 画面描述 | 一张群聊截屏飞快划过——片段024的群聊画面放大：IronHand发的握拳表情、小熊的"666"。然后是手机锁屏。 |
| 光线与色调 | 屏幕光 |
| 声音设计 | 消息提示音快速划过 |
| 镜头衔接 | **彩蛋：** 快速回放群聊精彩瞬间 |
| 时长 | 4秒 |
