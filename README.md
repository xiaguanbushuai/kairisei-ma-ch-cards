# 乖离性百万亚瑟王 国服 卡面资源（WebP 备份版）

停服手游《乖离性百万亚瑟王》（乖離性ミリオンアーサー）国服客户端的卡面立绘备份，共 **4385 张**。

| 项目 | 说明 |
| --- | --- |
| 来源 | 国服客户端资源包 `resource-set/resources/image/chr51/` |
| 格式 | WebP q85 全尺寸转码（保留透明通道，原图 1024×1024 / 1280×1024 RGBA） |
| 体积 | 约 1.1 GB（原 PNG 共 5.4 GB，压缩到约 21%） |
| 画质 | 动漫立绘视觉上与 PNG 无明显差别 |
| 用途 | 配合 [karisei-ma-ch-wiki](https://github.com/xiaguanbushuai/karisei-ma-ch-wiki) 资料站使用，或作为个人收藏备份 |

## 目录结构

```
images/chr51/chr51_<图鉴ID>.webp
```

文件名与游戏内 pictId 一一对应，与 wiki 的 `cardImage(pictId)` 直接对应。

## 配合 wiki 使用

把本仓库 clone 到本地后，wiki 的便携包把图片放进 `images/full/` 即可显示高清大图：
把 `images/chr51` 里的 webp 拷进 `kairisei-wiki-portable/images/full/chr51/`（服务端会自动优先原图）。

## 版权与免责声明

卡牌立绘等原始素材的版权归 **SQUARE ENIX CO., LTD.** 及该游戏原运营方所有，
本仓库与权利人无任何关联、未获其授权或认可。

- 仅限个人学习、研究与怀旧参考等**非商业用途**
- 严禁二次分发、转售或用于任何商业用途
- 收到权利人通知时应立刻停止使用并删除相关素材

详细条款见 [LICENSE](LICENSE)。
