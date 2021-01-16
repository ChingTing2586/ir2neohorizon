![Image text](https://github.com/ChingTing2586/ir2neohorizon/blob/main/img/cad4.png)

## Psi 图形化编程模组  超简易傻瓜式指南

#### 1【简要说明】

//部分网络环境下本分配图无法显示请使用魔法方式查看！//<br/>
本文仅作为Psi模组教程解锁参考所用，具体请以实际使用为准，部分术士仅作为解锁章节，术士辅助演算机实际执行无任何效果，如一个存档中的教程已全解，新存档可选择是否继承解锁内容。
默认按【C键】可打开教程，教程逐级解锁，研究该章节并执行该章节相应术士模块后可获得研究点数解锁下一节内容。
术士相关代码可使用术士编写台导入导出功能进行快速解锁，更多样化的应用玩家可自行尝试研究，本文仅供如博主之类“**计算机代码脑部功能性障碍症**”患者使用。
一个玩家身上最多仅能有一台术士辅助演算机，Psi工具与装甲需玩家身上有术士辅助演算机才能施放相应术士。
**相关实用性范例在文末part7！**

#### 2【相关链接】

下载：https://www.curseforge.com/minecraft/mc-mods/psi <br/>
官网：http://psi.vazkii.us/index.php <br/>
百科：http://www.mcmod.cn/class/470.html <br/>
视频教程：https://space.bilibili.com/4435845/video?keyword=psi <br/>

#### 3【CAD装配器界面介绍】
![Image text](https://github.com/ChingTing2586/ir2neohorizon/blob/main/img/cad0.png)

#### 4【术士编写台界面介绍】
![Image text](https://github.com/ChingTing2586/ir2neohorizon/blob/main/img/cad5.png)

![Image text](https://github.com/ChingTing2586/ir2neohorizon/blob/main/img/cad2.png)

#### 5【术士子弹安装与使用】
![Image text](https://github.com/ChingTing2586/ir2neohorizon/blob/main/img/cad1.png)

![Image text](https://github.com/ChingTing2586/ir2neohorizon/blob/main/img/cad3.png)

#### 6【教程各章节解锁代码】

 部分术士仅作为解锁章节，术士辅助演算机实际执行部分代码无任何效果，以下以教程章节顺序贴出

```
{spellName:"教程1-调试",uuidMost:8876535557246764258L,validSpell:1b,spellList:[{data:{key:"selectorCaster"},x:3,y:4},{data:{params:{_number:0,_target:3},key:"trickDebug"},x:4,y:4}],uuidLeast:-7546452597502590049L}
```

```
{spellName:"教程2-数字",uuidMost:2309552623614509411L,validSpell:1b,spellList:[{data:{key:"selectorCaster"},x:3,y:4},{data:{params:{_number:4,_target:3},key:"trickDebug"},x:4,y:4},{data:{key:"constantNumber",constantValue:"2"},x:5,y:4}],uuidLeast:-5216336938584534749L}
```
```
{spellName:"教程3-运动",uuidMost:-2625754695706786000L,validSpell:1b,spellList:[{data:{key:"selectorCaster"},x:3,y:3},{data:{params:{_direction:4,_speed:2,_target:1},key:"trickAddMotion"},x:3,y:4},{data:{key:"constantNumber",constantValue:"2"},x:3,y:5},{data:{params:{_target:3},key:"operatorEntityLook"},x:4,y:3},{data:{params:{_target:1},key:"connector"},x:4,y:4}],uuidLeast:-8665580017112217485L}
```

```
{spellName:"教程4-爆炸",uuidMost:1091142893842614127L,validSpell:1b,spellList:[{data:{key:"selectorCaster"},x:2,y:3},{data:{params:{_target:1},key:"operatorEntityPosition"},x:2,y:4},{data:{params:{_target:3},key:"operatorEntityLook"},x:3,y:3},{data:{params:{_ray:1,_max:0,_position:3},key:"operatorVectorRaycast"},x:3,y:4},{data:{params:{_power:2,_position:3},key:"trickExplode"},x:4,y:4},{data:{key:"constantNumber",constantValue:"1"},x:4,y:5}],uuidLeast:-5065504755389140883L}
```

```
{spellName:"5-1向量初识",uuidMost:3457812369884203406L,validSpell:1b,spellList:[{data:{key:"selectorCaster"},x:2,y:3},{data:{params:{_direction:4,_speed:2,_target:3},key:"trickAddMotion"},x:3,y:3},{data:{key:"constantNumber",constantValue:"2"},x:3,y:4},{data:{params:{_x:0,_y:4,_z:0},key:"operatorVectorConstruct"},x:4,y:3},{data:{key:"constantNumber",constantValue:"2"},x:5,y:3}],uuidLeast:-7354981041489250226L}
```

```
{spellName:"5-2实体初识",uuidMost:-6773901074628656340L,validSpell:1b,spellList:[{data:{key:"selectorCaster"},x:2,y:3},{data:{params:{_target:3},key:"operatorEntityPosition"},x:3,y:3},{data:{params:{_target:1},key:"connector"},x:3,y:4},{data:{key:"constantNumber",constantValue:"5"},x:4,y:2},{data:{params:{_position:3,_radius:1},key:"selectorNearbyLiving"},x:4,y:3},{data:{params:{_target:1,_position:3},key:"operatorClosestToPoint"},x:4,y:4},{data:{key:"constantNumber",constantValue:"1"},x:4,y:5},{data:{params:{_target:3},key:"operatorEntityPosition"},x:5,y:4},{data:{params:{_power:3,_position:1},key:"trickExplode"},x:5,y:5}],uuidLeast:-7639148222845018830L}
```

```
{spellName:"5-3数字初识",uuidMost:2311849440730105935L,validSpell:1b,spellList:[{data:{key:"constantNumber",constantValue:"1"},x:1,y:5},{data:{params:{_number:0,_target:2},key:"trickDebug"},x:2,y:4},{data:{params:{_number2:4,_number3:0,_number1:3},key:"operatorSum"},x:2,y:5},{data:{key:"constantNumber",constantValue:"2"},x:3,y:5}],uuidLeast:-7031307089980565610L}
```

```
{spellName:"6-1另类施法",uuidMost:3957320434015619971L,validSpell:1b,spellList:[{data:{key:"selectorFocalPoint"},x:2,y:4},{data:{params:{_target:3},key:"operatorEntityPosition"},x:3,y:4},{data:{params:{_power:4,_position:3},key:"trickExplode"},x:4,y:4},{data:{key:"constantNumber",constantValue:"1"},x:5,y:4}],uuidLeast:-8886273175035398956L}
```

```
{spellName:"6-2方块操作",uuidMost:3804520567373254260L,validSpell:1b,spellList:[{data:{key:"selectorCaster"},x:2,y:3},{data:{params:{_target:1},key:"operatorEntityPosition"},x:2,y:4},{data:{params:{_target:1},key:"connector"},x:2,y:5},{data:{params:{_target:3},key:"operatorEntityLook"},x:3,y:3},{data:{params:{_ray:1,_max:0,_position:3},key:"operatorVectorRaycast"},x:3,y:4},{data:{params:{_max:4,_target:1,_position:3},key:"trickBreakInSequence"},x:3,y:5},{data:{key:"constantNumber",constantValue:"3"},x:4,y:5}],uuidLeast:-7417653282514200329L}
```

```
{spellName:"10金属聚变",uuidMost:-8766992738165242471L,validSpell:1b,spellList:[{data:{key:"trickInfusion"},x:3,y:3}],uuidLeast:-8985399243822670776L}
```

```
{spellName:"11-元素即艺术-雷击",uuidMost:-2046482719744506403L,validSpell:1b,spellList:[{data:{params:{_target:4},key:"connector"},x:3,y:3},{data:{params:{_target:1},key:"operatorEntityLook"},x:3,y:4},{data:{key:"selectorCaster"},x:4,y:3},{data:{params:{_ray:3,_max:0,_position:4},key:"operatorVectorRaycast"},x:4,y:4},{data:{params:{_position:1},key:"trickSmite"},x:4,y:5},{data:{params:{_target:3},key:"connector"},x:5,y:3},{data:{params:{_target:1},key:"operatorEntityPosition"},x:5,y:4}],uuidLeast:-8533052176214010983L}
```

```
{spellName:"11-方块移动-无效果",uuidMost:-3710415377591614759L,validSpell:1b,spellList:[{data:{params:{_target:4},key:"connector"},x:3,y:3},{data:{params:{_target:1},key:"operatorEntityLook"},x:3,y:4},{data:{params:{_x:0,_y:2,_z:0},key:"operatorVectorConstruct"},x:3,y:5},{data:{key:"constantNumber",constantValue:"2"},x:3,y:6},{data:{key:"selectorCaster"},x:4,y:3},{data:{params:{_ray:3,_max:0,_position:4},key:"operatorVectorRaycast"},x:4,y:4},{data:{params:{_target:1,_position:3},key:"trickMoveBlock"},x:4,y:5},{data:{params:{_target:3},key:"connector"},x:5,y:3},{data:{params:{_target:1},key:"operatorEntityPosition"},x:5,y:4}],uuidLeast:-5656122574211911193L}
```

```
{spellName:"11-移动进阶",uuidMost:-3868466086743620146L,validSpell:1b,spellList:[{data:{key:"constantNumber",constantValue:"3"},x:2,y:3},{data:{params:{_distance:3,_target:4},key:"trickBlink"},x:3,y:3},{data:{key:"selectorCaster"},x:4,y:3}],uuidLeast:-5567317910789087147L}
```

```
{spellName:"12-循环施法",uuidMost:-2657253939157905841L,validSpell:1b,spellList:[{data:{key:"selectorLoopcastIndex"},x:3,y:4},{data:{params:{_number:3,_target:4},key:"trickDebug"},x:4,y:4},{data:{key:"selectorCaster"},x:5,y:4}],uuidLeast:-8063000872636383338L}
```

```
{spellName:"15-1高级聚变",uuidMost:-2888695050884264104L,validSpell:1b,spellList:[{data:{key:"trickGreaterInfusion"},x:4,y:4}],uuidLeast:-9031211290088421827L}
```

```
{spellName:"15-2阴阳聚变",uuidMost:-3477893874268749804L,validSpell:1b,spellList:[{data:{key:"trickEbonyIvory"},x:4,y:4}],uuidLeast:-8964275576200639429L}
```
↑ 该术士需要在末地才能执行

```
{spellName:"16-1工具施法-目标",uuidMost:1303744609057196969L,validSpell:1b,spellList:[{data:{key:"selectorAttackTarget"},x:4,y:4},{data:{key:"constantNumber",constantValue:"2"},x:5,y:2},{data:{params:{_power:1,_position:2},key:"trickExplode"},x:5,y:3},{data:{params:{_target:3},key:"operatorEntityPosition"},x:5,y:4}],uuidLeast:-4774756600977630852L}
```
↑ 该术士及以下几个使用术士子弹安装在Psi金属工具上

```
{spellName:"16-2工具施法-方块",uuidMost:4548092819220611509L,validSpell:1b,spellList:[{data:{key:"selectorBlockBroken"},x:4,y:4},{data:{key:"constantNumber",constantValue:"2"},x:5,y:2},{data:{params:{_power:1,_position:2},key:"trickExplode"},x:5,y:3},{data:{params:{_target:3},key:"connector"},x:5,y:4}],uuidLeast:-5110078153237879748L}
```
```
{spellName:"16-3正面效果-速度",uuidMost:-4902983086342716650L,validSpell:1b,spellList:[{data:{key:"constantNumber",constantValue:"2"},x:3,y:4},{data:{key:"selectorCaster"},x:4,y:3},{data:{params:{_power:3,_time:4,_target:1},key:"trickSpeed"},x:4,y:4},{data:{key:"constantNumber",constantValue:"5"},x:5,y:4}],uuidLeast:-8997151196731183431L}
```

```
{spellName:"16-2工具施法-方块破坏-镐",uuidMost:6085689153769194652L,validSpell:1b,spellList:[{data:{params:{_position:2},key:"trickBreakBlock"},x:4,y:3},{data:{key:"selectorBlockBroken"},x:4,y:4}],uuidLeast:-7317014284449110587L}
```

```
{spellName:"17-负面效果-凋零",uuidMost:-489293640287433044L,validSpell:1b,spellList:[{data:{key:"constantNumber",constantValue:"5"},x:3,y:4},{data:{params:{_power:4,_time:3,_target:2},key:"trickWither"},x:4,y:4},{data:{key:"selectorAttackTarget"},x:4,y:5},{data:{key:"constantNumber",constantValue:"1"},x:5,y:4}],uuidLeast:-6103936415931812011L}
```

```
{spellName:"19套装施法",uuidMost:-4362141410693331220L,validSpell:1b,spellList:[{data:{key:"constantNumber",constantValue:"2"},x:3,y:3},{data:{params:{_power:3,_time:4,_target:2},key:"trickRegeneration"},x:4,y:3},{data:{key:"selectorCaster"},x:4,y:4},{data:{key:"constantNumber",constantValue:"5"},x:5,y:3}],uuidLeast:-4734776633774558453L}
```
↑ 该术士使用术士子弹安装在Psi金属装甲上

```
{spellName:"19-套装施法-时间",uuidMost:7789447415714040854L,validSpell:1b,spellList:[{data:{key:"selectorCaster"},x:3,y:3},{data:{params:{_number:2,_target:3},key:"trickDebug"},x:4,y:3},{data:{key:"selectorTime"},x:4,y:4}],uuidLeast:-7667535776053369502L}
```

```
{spellName:"20-三角函数",uuidMost:5248304504858296608L,validSpell:1b,spellList:[{data:{key:"constantPi"},x:3,y:4},{data:{key:"selectorCaster"},x:4,y:3},{data:{params:{_number:3,_target:1},key:"trickDebug"},x:4,y:4}],uuidLeast:-9009558861617476665L}
```

```
{spellName:"20冶炼工厂-方块",uuidMost:-825403352594759148L,validSpell:1b,spellList:[{data:{key:"selectorCaster"},x:2,y:4},{data:{params:{_target:3},key:"operatorEntityPosition"},x:3,y:4},{data:{params:{_target:4},key:"trickSmeltItem"},x:3,y:5},{data:{key:"constantNumber",constantValue:"5"},x:4,y:3},{data:{params:{_position:3,_radius:1},key:"selectorNearbyItems"},x:4,y:4},{data:{params:{_target:1},key:"operatorRandomEntity"},x:4,y:5}],uuidLeast:-8247682971935985835L}
```

```
{spellName:"20方块构筑",uuidMost:-7724618301327914609L,validSpell:1b,spellList:[{data:{params:{_target:4},key:"operatorEntityPosition"},x:3,y:3},{data:{params:{_time:0,_position:1},key:"trickConjureBlock"},x:3,y:4},{data:{key:"selectorCaster"},x:4,y:3}],uuidLeast:-8527105661853059547L}
```

```
{spellName:"20构筑方块",uuidMost:6478437158476531930L,validSpell:1b,spellList:[{data:{key:"selectorCaster"},x:2,y:3},{data:{params:{_target:1},key:"operatorEntityPosition"},x:2,y:4},{data:{params:{_target:2},key:"operatorEntityPosition"},x:2,y:5},{data:{key:"selectorCaster"},x:2,y:6},{data:{params:{_target:3},key:"operatorEntityLook"},x:3,y:3},{data:{params:{_ray:1,_max:0,_position:3},key:"operatorVectorRaycast"},x:3,y:4},{data:{params:{_ray:2,_max:0,_position:3},key:"operatorVectorRaycastAxis"},x:3,y:5},{data:{params:{_target:3},key:"operatorEntityLook"},x:3,y:6},{data:{params:{_target:3},key:"connector"},x:4,y:4},{data:{params:{_vector3:0,_vector2:3,_vector1:1},key:"operatorVectorSum"},x:4,y:5},{data:{params:{_time:0,_position:3},key:"trickConjureBlock"},x:5,y:5}],uuidLeast:-7296941851129333530L}
```

```
{spellName:"20构筑方块-光线",uuidMost:-2250246079677579085L,validSpell:1b,spellList:[{data:{key:"selectorCaster"},x:2,y:3},{data:{params:{_target:1},key:"operatorEntityPosition"},x:2,y:4},{data:{params:{_target:2},key:"operatorEntityPosition"},x:2,y:5},{data:{key:"selectorCaster"},x:2,y:6},{data:{params:{_target:3},key:"operatorEntityLook"},x:3,y:3},{data:{params:{_ray:1,_max:0,_position:3},key:"operatorVectorRaycast"},x:3,y:4},{data:{params:{_ray:2,_max:0,_position:3},key:"operatorVectorRaycastAxis"},x:3,y:5},{data:{params:{_target:3},key:"operatorEntityLook"},x:3,y:6},{data:{params:{_target:3},key:"connector"},x:4,y:4},{data:{params:{_vector3:0,_vector2:3,_vector1:1},key:"operatorVectorSum"},x:4,y:5},{data:{params:{_time:0,_position:3},key:"trickConjureLight"},x:5,y:5}],uuidLeast:-6814569790825883608L}
```

```
{spellName:"20流控制",uuidMost:-2506623549968268307L,validSpell:1b,spellList:[{data:{params:{_number:0,_target:4},key:"trickDebug"},x:3,y:4},{data:{params:{_time:4},key:"trickDelay"},x:4,y:4},{data:{key:"constantNumber",constantValue:"2"},x:5,y:4}],uuidLeast:-6460204806361923762L}
```

```
{spellName:"21内存管理",uuidMost:-779451033239336238L,validSpell:1b,spellList:[{data:{params:{_x:0,_y:4,_z:0},key:"operatorVectorConstruct"},x:3,y:3},{data:{params:{_number:4,_target:1},key:"trickSaveVector"},x:3,y:4},{data:{key:"constantNumber",constantValue:"4"},x:4,y:3},{data:{key:"constantNumber",constantValue:"1"},x:4,y:4}],uuidLeast:-5175390395516160759L}
```

```
{spellName:"21检测聚焦",uuidMost:8878039461333516864L,validSpell:1b,spellList:[{data:{key:"constantNumber",constantValue:"3"},x:3,y:3},{data:{params:{_shift:0,_position:0},key:"trickSwitchTargetSlot"},x:4,y:3}],uuidLeast:-6371558836585368971L}
```

```
{spellName:"21次要运算",uuidMost:7962493784193126385L,validSpell:1b,spellList:[{data:{params:{_number:0,_target:2},key:"trickDebug"},x:3,y:3},{data:{params:{_number:4},key:"operatorSquare"},x:3,y:4},{data:{key:"constantNumber",constantValue:"200"},x:4,y:4}],uuidLeast:-5787970034939850805L}
```

```
{spellName:"24时空操控",uuidMost:1798505438560209505L,validSpell:1b,spellList:[{data:{key:"constantNumber",constantValue:"5"},x:4,y:3},{data:{params:{_time:1},key:"trickEidosReversal"},x:4,y:4}],uuidLeast:-8812557252450889140L}
```

至此，所有教程全解！

#### 7【实用术士范例】

部分实用性术士范例，收集至网络，请以实际使用为准！

```
{spellName:"方块移动",uuidMost:8484263420781742903L,validSpell:1b,spellList:[{data:{key:"selectorCaster"},x:2,y:3},{data:{params:{_target:1},key:"operatorEntityLook"},x:2,y:4},{data:{params:{_target:3},key:"operatorEntityPosition"},x:3,y:3},{data:{params:{_ray:3,_max:0,_position:1},key:"operatorVectorRaycast"},x:3,y:4},{data:{params:{_target:4,_position:3},key:"trickMoveBlock"},x:4,y:4},{data:{key:"constantNumber",constantValue:"1"},x:5,y:3},{data:{params:{_x:0,_y:1,_z:0},key:"operatorVectorConstruct"},x:5,y:4}],uuidLeast:-8852352488576412626L}
```

```
{spellName:"撒骨粉催生",uuidMost:8214174121752217696L,validSpell:1b,spellList:[{data:{key:"selectorCaster"},x:2,y:3},{data:{params:{_target:1},key:"operatorEntityPosition"},x:2,y:4},{data:{params:{_target:2},key:"operatorEntityPosition"},x:2,y:5},{data:{key:"selectorCaster"},x:2,y:6},{data:{params:{_target:3},key:"operatorEntityLook"},x:3,y:3},{data:{params:{_ray:1,_max:0,_position:3},key:"operatorVectorRaycast"},x:3,y:4},{data:{params:{_ray:2,_max:0,_position:3},key:"operatorVectorRaycastAxis"},x:3,y:5},{data:{params:{_target:3},key:"operatorEntityLook"},x:3,y:6},{data:{params:{_target:3},key:"connector"},x:4,y:4},{data:{params:{_vector3:0,_vector2:3,_vector1:1},key:"operatorVectorSum"},x:4,y:5},{data:{params:{_position:3},key:"trickOvergrow"},x:5,y:5}],uuidLeast:-8906283635234641910L}
```

```
{spellName:"点火",uuidMost:-4802236952423479079L,validSpell:1b,spellList:[{data:{key:"selectorCaster"},x:2,y:3},{data:{params:{_target:1},key:"operatorEntityPosition"},x:2,y:4},{data:{params:{_target:2},key:"operatorEntityPosition"},x:2,y:5},{data:{key:"selectorCaster"},x:2,y:6},{data:{params:{_target:3},key:"operatorEntityLook"},x:3,y:3},{data:{params:{_ray:1,_max:0,_position:3},key:"operatorVectorRaycast"},x:3,y:4},{data:{params:{_ray:2,_max:0,_position:3},key:"operatorVectorRaycastAxis"},x:3,y:5},{data:{params:{_target:3},key:"operatorEntityLook"},x:3,y:6},{data:{params:{_target:3},key:"connector"},x:4,y:4},{data:{params:{_vector3:0,_vector2:3,_vector1:1},key:"operatorVectorSum"},x:4,y:5},{data:{params:{_position:3},key:"trickBlaze"},x:5,y:5}],uuidLeast:-5268419165597186890L}
```

```
{spellName:"放水",uuidMost:6383612203875518518L,validSpell:1b,spellList:[{data:{params:{_target:4},key:"connector"},x:3,y:3},{data:{params:{_target:1},key:"operatorEntityLook"},x:3,y:4},{data:{key:"selectorCaster"},x:4,y:3},{data:{params:{_ray:3,_max:0,_position:4},key:"operatorVectorRaycast"},x:4,y:4},{data:{params:{_position:1},key:"trickTorrent"},x:4,y:5},{data:{params:{_target:3},key:"connector"},x:5,y:3},{data:{params:{_target:1},key:"operatorEntityPosition"},x:5,y:4}],uuidLeast:-4800318860724069276L}
```

```
{spellName:"方块放置",uuidMost:-632468014905343578L,validSpell:1b,spellList:[{data:{key:"selectorCaster"},x:2,y:3},{data:{params:{_target:1},key:"operatorEntityPosition"},x:2,y:4},{data:{params:{_target:2},key:"operatorEntityPosition"},x:2,y:5},{data:{key:"selectorCaster"},x:2,y:6},{data:{params:{_target:3},key:"operatorEntityLook"},x:3,y:3},{data:{params:{_ray:1,_max:0,_position:3},key:"operatorVectorRaycast"},x:3,y:4},{data:{params:{_ray:2,_max:0,_position:3},key:"operatorVectorRaycastAxis"},x:3,y:5},{data:{params:{_target:3},key:"operatorEntityLook"},x:3,y:6},{data:{params:{_target:3},key:"connector"},x:4,y:4},{data:{params:{_vector3:0,_vector2:3,_vector1:1},key:"operatorVectorSum"},x:4,y:5},{data:{key:"constantNumber",constantValue:"5"},x:5,y:3},{data:{params:{_x:0,_y:1,_z:0},key:"operatorVectorConstruct"},x:5,y:4},{data:{params:{_max:2,_target:1,_position:3},key:"trickPlaceInSequence"},x:5,y:5},{data:{key:"constantNumber",constantValue:"1"},x:5,y:6}],uuidLeast:-8080785190861667216L}
```
↑ 注意：该术士放置方块需放置在术士辅助演算机后面一格的槽位

```
{spellName:"方块破坏",uuidMost:-1580787659183995198L,validSpell:1b,spellList:[{data:{key:"selectorCaster"},x:2,y:3},{data:{params:{_target:1},key:"operatorEntityPosition"},x:2,y:4},{data:{params:{_target:3},key:"operatorEntityLook"},x:3,y:3},{data:{params:{_ray:1,_max:0,_position:3},key:"operatorVectorRaycast"},x:3,y:4},{data:{params:{_position:3},key:"trickBreakBlock"},x:4,y:4}],uuidLeast:-5690642392410758325L}
```

```
{spellName:"砍树",uuidMost:2308259725319947143L,validSpell:1b,spellList:[{data:{key:"constantNumber",constantValue:"5"},x:2,y:4},{data:{params:{_x:0,_y:1,_z:0},key:"operatorVectorConstruct"},x:2,y:5},{data:{params:{_target:4},key:"operatorEntityPosition"},x:3,y:3},{data:{params:{_ray:4,_max:0,_position:1},key:"operatorVectorRaycast"},x:3,y:4},{data:{params:{_max:4,_target:3,_position:1},key:"trickBreakInSequence"},x:3,y:5},{data:{key:"selectorCaster"},x:4,y:3},{data:{params:{_target:1},key:"operatorEntityLook"},x:4,y:4},{data:{key:"constantNumber",constantValue:"5"},x:4,y:5}],uuidLeast:-5823382794295867626L}
```

```
{spellName:"物品熔炼",uuidMost:2290515535382069369L,validSpell:1b,spellList:[{data:{params:{_target:2},key:"trickSmeltItem"},x:4,y:4},{data:{params:{_target:4},key:"connector"},x:4,y:5},{data:{key:"selectorFocalPoint"},x:4,y:6},{data:{params:{_target:4,_position:2},key:"operatorClosestToPoint"},x:5,y:5},{data:{params:{_target:3},key:"operatorEntityPosition"},x:5,y:6},{data:{key:"constantNumber",constantValue:"32"},x:6,y:4},{data:{params:{_position:2,_radius:1},key:"selectorNearbySmeltables"},x:6,y:5},{data:{params:{_target:3},key:"connector"},x:6,y:6}],uuidLeast:-4850956419026228596L}
```

```
{spellName:"砍树烧木炭",uuidMost:-746640810159750555L,validSpell:1b,spellList:[{data:{key:"constantNumber",constantValue:"5"},x:2,y:3},{data:{params:{_time:1},key:"trickDelay"},x:2,y:4},{data:{key:"selectorBlockBroken"},x:2,y:5},{data:{key:"constantNumber",constantValue:"2"},x:3,y:4},{data:{params:{_position:3,_radius:1},key:"selectorNearbySmeltables"},x:3,y:5},{data:{params:{_target:2},key:"trickSmeltItem"},x:4,y:4},{data:{params:{_target:3},key:"operatorRandomEntity"},x:4,y:5}],uuidLeast:-9021015400850243748L}
```

```
{spellName:"空岛铺地",uuidMost:-2398988261599722310L,validSpell:1b,spellList:[{data:{key:"selectorCaster"},x:2,y:3},{data:{params:{_target:1},key:"operatorEntityPosition"},x:2,y:4},{data:{params:{_target:3},key:"operatorEntityAxialLook"},x:3,y:3},{data:{params:{_vector3:1,_vector2:3,_vector1:2},key:"operatorVectorSum"},x:3,y:4},{data:{params:{_x:0,_y:4,_z:0},key:"operatorVectorConstruct"},x:3,y:5},{data:{params:{_number2:4,_vector1:3},key:"operatorVectorMultiply"},x:4,y:3},{data:{params:{_max:4,_target:1,_position:3},key:"trickPlaceInSequence"},x:4,y:4},{data:{key:"constantNumber",constantValue:"-2"},x:4,y:5},{data:{params:{_target:2},key:"connector"},x:5,y:3},{data:{key:"constantNumber",constantValue:"9"},x:5,y:4}],uuidLeast:-6059554718617958648L}
```

```
{spellName:"3x3范围挖掘",uuidMost:-5165902046422809258L,validSpell:1b,spellList:[{data:{params:{_target:2},key:"operatorEntityPosition"},x:1,y:1},{data:{key:"selectorCaster"},x:1,y:2},{data:{params:{_target:4},key:"connector"},x:1,y:4},{data:{params:{_target:1},key:"connector"},x:1,y:5},{data:{params:{_target:1},key:"connector"},x:1,y:6},{data:{params:{_target:1},key:"connector"},x:1,y:7},{data:{params:{_target:1},key:"connector"},x:1,y:8},{data:{params:{_ray:2,_max:0,_position:3},key:"operatorVectorRaycastAxis"},x:2,y:1},{data:{params:{_target:3},key:"operatorEntityLook"},x:2,y:2},{data:{params:{_target:4},key:"connector"},x:2,y:4},{data:{params:{_position:4},key:"trickBreakBlock"},x:2,y:5},{data:{params:{_vector3:0,_vector2:4,_vector1:3},key:"operatorVectorSum"},x:2,y:6},{data:{params:{_position:1},key:"trickBreakBlock"},x:2,y:7},{data:{params:{_target:3},key:"connector"},x:2,y:8},{data:{params:{_target:3},key:"connector"},x:3,y:1},{data:{params:{_target:1},key:"connector"},x:3,y:2},{data:{params:{_target:1},key:"operatorVectorExtractY"},x:3,y:3},{data:{params:{_target:4},key:"connector"},x:3,y:4},{data:{params:{_target:2},key:"connector"},x:3,y:5},{data:{params:{_ray:2,_max:0,_position:4},key:"operatorVectorRaycast"},x:3,y:6},{data:{params:{_target:4},key:"operatorEntityLook"},x:3,y:7},{data:{params:{_target:3},key:"connector"},x:3,y:8},{data:{params:{_target:3},key:"connector"},x:4,y:1},{data:{params:{_target:1},key:"operatorVectorExtractX"},x:4,y:2},{data:{params:{_x:4,_y:1,_z:3},key:"operatorVectorConstruct"},x:4,y:3},{data:{params:{_target:1},key:"connector"},x:4,y:4},{data:{params:{_target:3},key:"connector"},x:4,y:5},{data:{params:{_target:2},key:"operatorEntityPosition"},x:4,y:6},{data:{key:"selectorCaster"},x:4,y:7},{data:{params:{_target:3},key:"connector"},x:4,y:8},{data:{params:{_target:3},key:"connector"},x:5,y:1},{data:{params:{_target:1},key:"connector"},x:5,y:2},{data:{params:{_target:1},key:"operatorVectorExtractZ"},x:5,y:3},{data:{params:{_target:3},key:"connector"},x:5,y:4},{data:{params:{_vector3:0,_vector2:1,_vector1:3},key:"operatorVectorSubtract"},x:5,y:5},{data:{params:{_position:1},key:"trickBreakBlock"},x:5,y:6},{data:{params:{_target:2},key:"connector"},x:5,y:7},{data:{params:{_number2:4,_vector1:3},key:"operatorVectorMultiply"},x:5,y:8},{data:{params:{_target:3},key:"trickEvaluate"},x:6,y:1},{data:{params:{_target:3},key:"connector"},x:6,y:2},{data:{params:{_target:1},key:"connector"},x:6,y:3},{data:{params:{_vector2:1,_vector1:3},key:"operatorVectorCrossProduct"},x:6,y:4},{data:{params:{_vector3:0,_vector2:1,_vector1:3},key:"operatorVectorSum"},x:6,y:5},{data:{params:{_max:4,_target:2,_position:1},key:"trickBreakInSequence"},x:6,y:6},{data:{params:{_target:3},key:"connector"},x:6,y:7},{data:{key:"constantNumber",constantValue:"3"},x:6,y:8},{data:{params:{_number2:4,_vector1:3},key:"operatorVectorMultiply"},x:7,y:4},{data:{params:{_vector3:0,_vector2:1,_vector1:3},key:"operatorVectorSum"},x:7,y:5},{data:{key:"constantNumber",constantValue:"3"},x:7,y:6},{data:{params:{_target:3},key:"connector"},x:7,y:7},{data:{key:"constantNumber",constantValue:"-2"},x:8,y:4},{data:{params:{_target:3},key:"connector"},x:8,y:5},{data:{params:{_max:3,_target:2,_position:1},key:"trickBreakInSequence"},x:8,y:6},{data:{params:{_target:3},key:"connector"},x:8,y:7}],uuidLeast:-9046225823719398062L}
```

```
{spellName:"凋零-缓慢剑",uuidMost:540897610409266528L,validSpell:1b,spellList:[{data:{key:"constantNumber",constantValue:"9"},x:2,y:4},{data:{key:"constantNumber",constantValue:"1"},x:3,y:3},{data:{params:{_power:1,_time:3,_target:4},key:"trickSlowness"},x:3,y:4},{data:{key:"constantNumber",constantValue:"9"},x:4,y:2},{data:{params:{_power:3,_time:1,_target:2},key:"trickWeakness"},x:4,y:3},{data:{key:"selectorAttackTarget"},x:4,y:4},{data:{key:"constantNumber",constantValue:"1"},x:5,y:3},{data:{params:{_power:1,_time:4,_target:3},key:"trickWither"},x:5,y:4},{data:{key:"constantNumber",constantValue:"8"},x:6,y:4}],uuidLeast:-5603946310192402136L}
```

更多实用性术士代码可点击查看以下链接：**[943](https://tartaricacid.github.io/2017/02/04/PsiSpotlightFile/)**

by: ChingTing
2021/01/15

![](https://i.loli.net/2019/04/04/5ca5b1d0a422b.jpg)
