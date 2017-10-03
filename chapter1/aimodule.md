# AIModule

&gt;Runtime&gt;AIModule

为AI Pawns和功能提供行为树支持的控制器

#### 过滤器

| Actions | BehaviorTree | Blueprint | DataProviders |
| :--- | :--- | :--- | :--- |
| EnvironmentQuery | HotSpots | Navigation | Perception |
| Tasks |  |  |  |

#### 类

|  | 名称 | 描述 |
| :--- | :--- | :--- |
|  | AAIController | AIContoller是为AI操控的Pawn提供控制器的基础类 |
|  | ADetourCrowdAIController |  |
|  | AGridPathAIController |  |
|  | FAIBasicCounter |  |
|  | FAIGenericID |  |
|  | FAIMessage |  |
|  | FAIMessageObserver |  |
|  | FAIMoveCompletedSignature |  |
|  | FAIMoveRequest |  |
|  | FAINamedID | TCounter需要提供以下功能：默认构造函数typedef X类型; 其中X是用作ID的内部类型的整数类型TCounter :: Type GetNextAvailableID（） - 返回下一个可用的ID，并提前执行内部计数器uint32 GetSize（）const - 返回迄今创建的唯一ID的数量OnIndexForced（TCounter :: Type 索引） - 当给定索引已被强制使用时调用。 |
|  |  |  |



