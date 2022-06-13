# PLD（Pulsed Laser Deposition）脉冲激光沉积

## 1. Introductin

**脉冲激光沉积**( **PLD** ) 是一种[物理气相沉积](https://en.wikipedia.org/wiki/Physical_vapor_deposition)(PVD) 技术，其中高功率脉冲[激光](https://en.wikipedia.org/wiki/Laser)束在[真空](https://en.wikipedia.org/wiki/Vacuum)室内聚焦以撞击待沉积材料的目标。这种材料从目标（在等离子体羽流中）蒸发，将其作为[薄膜](https://en.wikipedia.org/wiki/Thin_film)沉积在基板（例如面向目标的硅[晶片）上。](https://en.wikipedia.org/wiki/Wafer_(electronics))这个过程可以在[超高真空](https://en.wikipedia.org/wiki/Ultra_high_vacuum)或存在背景气体的情况下进行，例如在沉积氧化物时通常使用的氧气，以使沉积的薄膜完全氧化。

虽然与许多其他沉积技术相比，基本设置很简单，但激光-靶材相互作用和薄膜生长的物理现象相当复杂（参见下面的[过程](https://en.wikipedia.org/wiki/Pulsed_laser_deposition#Process)）。当激光脉冲被目标吸收时，能量首先转化为电子激发，然后转化为热能、化学能和机械能，从而导致蒸发、[烧蚀](https://en.wikipedia.org/wiki/Ablation)、[等离子体](https://en.wikipedia.org/wiki/Plasma_(physics))形成甚至[剥落](https://en.wikipedia.org/wiki/Exfoliation_corrosion)。[[1\]](https://en.wikipedia.org/wiki/Pulsed_laser_deposition#cite_note-Perry-1)喷射出的物质以包含许多高能物质（包括[原子](https://en.wikipedia.org/wiki/Atoms)、[分子](https://en.wikipedia.org/wiki/Molecules)、[电子](https://en.wikipedia.org/wiki/Electrons)、[离子）的羽流形式膨胀到周围的真空中](https://en.wikipedia.org/wiki/Ions)、团簇、微粒和熔融小球，然后沉积在通常很热的基材上。

## 2. 过程

PLD 的详细机制非常复杂，包括[激光](https://en.wikipedia.org/wiki/Laser)照射对目标材料的烧蚀过程、具有高能离子、电子和中性物质的[等离子体羽流的形成以及薄膜本身在加热基板上的晶体生长。](https://en.wikipedia.org/wiki/Plasma_(physics))PLD的过程一般可以分为四个阶段：

- 目标表面上的激光吸收和目标材料的激光烧蚀和等离子体的产生
- 等离子体动力学
- 在基板上沉积烧蚀材料
- 基片表面薄膜的成核和生长

这些步骤中的每一个对于所得薄膜的结晶度、均匀性和[化学计量都是至关重要的。](https://en.wikipedia.org/wiki/Stoichiometry)对 PLD 过程建模最常用的方法是[蒙特卡洛技术](https://en.wikipedia.org/wiki/Monte_Carlo_method)。[[2\]](https://en.wikipedia.org/wiki/Pulsed_laser_deposition#cite_note-2)

### 目标材料的激光烧蚀和等离子体的产生

激光照射时靶材的烧蚀和等离子体的产生是非常复杂的过程。从块状材料中去除原子是通过在非平衡状态下在表面区域蒸发块状来完成的。在这种情况下，入射激光脉冲在穿透深度内穿透材料表面。该尺寸取决于激光波长和目标材料在所施加激光波长下的折射率，并且对于大多数材料而言通常在 10 nm 范围内。由激光产生的强电场足够强以从穿透体积的块状材料中去除电子。该过程发生在 ns 激光脉冲的 10 ps 内，是由非线性过程引起的，例如多光子电离，这些过程由表面、空隙和结节处的微观裂缝增强，从而增加电场。自由电子在激光的电磁场中振荡，可以与块状材料的原子碰撞，从而将它们的一些能量转移到表面区域内目标材料的晶格中。然后目标的表面被加热并且材料被蒸发。

### 等离子体动力学

在第二阶段，由于来自目标表面的库仑排斥和反冲，材料在平行于目标表面的法向矢量的等离子体中向基板膨胀。羽流的空间分布取决于 PLD 室内的背景压力。羽流的密度可以用类似于高斯曲线的 cos n (x) 定律来描述。羽流形状对压力的依赖性可以分为三个阶段：

- 真空阶段，羽流非常窄且向前；背景气体几乎不发生散射。
- 可以观察到高能离子从低能物种分裂的中间区域。飞行时间（TOF）数据可以拟合到冲击波模型；然而，其他模型也是可能的。
- 高压区域，我们发现烧蚀材料的扩散更像扩散。自然，这种散射也取决于背景气体的质量，并且会影响沉积膜的化学计量。

增加背景压力的最重要后果是膨胀的等离子体羽流中高能物质的速度减慢。已经表明，动能约为 50 eV 的粒子可以重新溅射已经沉积在基板上的薄膜。这导致较低的沉积速率并且可以进一步导致膜的化学计量的变化。

### 在基板上沉积烧蚀材料

第三阶段对于确定沉积膜的质量很重要。从靶材烧蚀的高能物质轰击衬底表面，并且可能通过从表面溅射掉原子以及通过在沉积膜中形成缺陷而对表面造成损害。[[3\]](https://en.wikipedia.org/wiki/Pulsed_laser_deposition#cite_note-3)来自基板的溅射物质和从靶材发射的粒子形成碰撞区域，该碰撞区域用作粒子凝聚的源。当冷凝速率足够高时，可以达到热平衡，并且薄膜在基板表面上生长，代价是烧蚀颗粒的直接流动和获得的热平衡。

### 基片表面薄膜的成核和生长

薄膜的[成核](https://en.wikipedia.org/wiki/Nucleation)过程和生长动力学取决于几个生长参数，包括：

- *激光参数——激光能量密度 [Joule/cm* 2 ]、激光能量和烧蚀材料的电离度等几个因素会影响薄膜质量、[化学计量](https://en.wikipedia.org/wiki/Stoichiometry)[[4\]](https://en.wikipedia.org/wiki/Pulsed_laser_deposition#cite_note-4)和沉积通量。通常，成核密度随着沉积通量的增加而增加。
- *表面温度*——表面温度对成核密度有很大影响。通常，成核密度随着温度的升高而降低。[[5\]](https://en.wikipedia.org/wiki/Pulsed_laser_deposition#cite_note-5)表面加热可能涉及加热板或使用[CO 2激光](https://en.wikipedia.org/wiki/Carbon_dioxide_laser)。[[6\]](https://en.wikipedia.org/wiki/Pulsed_laser_deposition#cite_note-6)
- *基板表面*——成核和生长会受到表面处理（如化学蚀刻[[7\]](https://en.wikipedia.org/wiki/Pulsed_laser_deposition#cite_note-7)）、基板的误切以及基板的粗糙度的影响。
- *背景压力*——在氧化物沉积中很常见，需要氧气背景来确保从靶材到薄膜的化学计量转移。例如，如果氧背景太低，则薄膜会偏离[化学计量](https://en.wikipedia.org/wiki/Stoichiometry)，这将影响成核密度和薄膜质量。[[8\]](https://en.wikipedia.org/wiki/Pulsed_laser_deposition#cite_note-8)

在 PLD 中，在脉冲持续时间内基板上会发生大的[过饱和。](https://en.wikipedia.org/wiki/Supersaturation)脉冲持续约 10-40 微秒[[9\]](https://en.wikipedia.org/wiki/Pulsed_laser_deposition#cite_note-9)，具体取决于激光参数。[与分子束外延](https://en.wikipedia.org/wiki/Molecular_beam_epitaxy)或[溅射](https://en.wikipedia.org/wiki/Sputtering)沉积相比，这种高[过饱和导致表面上的成核密度非常大。](https://en.wikipedia.org/wiki/Supersaturation)这种成核密度增加了沉积膜的平滑度。

在 PLD 中，[取决于上述沉积参数] 三种生长模式是可能的：

- *阶梯流生长*——所有基板都有与晶体相关的错切。这些误切会在表面产生原子级。在阶梯流生长中，原子降落在表面上并扩散到阶梯边缘，然后才有机会成核表面岛。生长表面被视为穿过表面的台阶。这种生长模式是通过在高错切基板上沉积或在高温下沉积获得的[[10\]](https://en.wikipedia.org/wiki/Pulsed_laser_deposition#cite_note-10)
- *逐层生长*——在这种生长模式下，岛在表面成核，直到达到临界岛密度。随着更多材料的添加，这些岛屿会继续增长，直到这些岛屿开始相互碰撞。这称为合并。一旦达到聚结，表面就会有大量的凹坑。当向表面添加额外的材料时，原子会扩散到这些凹坑中以完成该层。对每个后续层重复此过程。
- *3D 生长*——这种模式类似于逐层生长，除了一旦形成一个岛，一个额外的岛将在第一个岛的顶部成核。因此，生长不会以逐层方式持续，并且每次添加材料时表面都会变粗糙。

## 3. 技术方面

有许多不同的安排来构建 PLD 的沉积室。被激光蒸发的目标材料通常是一个固定在支架上的旋转圆盘。然而，它也可以被烧结成具有旋转运动和沿其轴线上下平移运动的圆柱形棒。这种特殊的配置不仅允许使用同步的反应气体脉冲，而且还允许使用多组分靶棒，通过该靶棒可以产生不同多层的薄膜。

影响沉积速率的一些因素：

- 目标材料
- 激光脉冲能量
- 激光的重复率[[18\]](https://en.wikipedia.org/wiki/Pulsed_laser_deposition#cite_note-18)
- 基板温度[[19\]](https://en.wikipedia.org/wiki/Pulsed_laser_deposition#cite_note-19)
- 从目标到基板的距离
- 室内气体类型和压力（氧气、氩气等）[[20\]](https://en.wikipedia.org/wiki/Pulsed_laser_deposition#cite_note-20)
