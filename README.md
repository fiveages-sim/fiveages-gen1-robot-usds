# FiveAges Gen1 Robot USDs

中科第五纪（FiveAges）**第一代**机器人的 USD 仿真资产（[fiveages-gen1-robot-usds](https://github.com/fiveages-sim/fiveages-gen1-robot-usds)），作为 [robot_usds](https://github.com/fiveages-sim/robot_usds) 的子模块挂载于 `humanoid/FiveAges/Gen1/`。

## 目录结构

| 路径 | 说明 |
|------|------|
| `W1/` | FiveAges W1 轮式人形 |

## 克隆

本仓库通常不作为独立项目使用，请通过父仓库初始化子模块：

```bash
git clone git@github.com:fiveages-sim/robot_usds.git
cd robot_usds
git submodule update --init humanoid/FiveAges/Gen1
```

## 依赖

`W1` 通过相对路径引用 `robot_usds` 主仓库中的以下资产：

- `grippers/Jodell/RG75/`
