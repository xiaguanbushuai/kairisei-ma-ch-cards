# 乖离性百万亚瑟王 国服 卡面资源（WebP 备份版）

停服手游《乖离性百万亚瑟王》（乖離性ミリオンアーサー）国服客户端的卡面立绘备份，共 **4385 张**。

> ⚠️ 素材版权归 SQUARE ENIX 及原运营方所有，本仓库不授予任何使用许可，**严禁商业用途与二次分发**。
> 详见 [LICENSE](LICENSE)。

| 项目 | 说明 |
| --- | --- |
| 来源 | [kuuhaku1314/kairisei-ma-ch](https://github.com/kuuhaku1314/kairisei-ma-ch) 资源包 `resource-set/resources/image/chr51/` |
| 格式 | WebP q85 全尺寸转码（保留透明通道，原图 1024×1024 / 1280×1024 RGBA） |
| 体积 | 约 1.0 GB（原 PNG 共 5.4 GB，压缩到约 19%） |
| 画质 | 动漫立绘视觉上与 PNG 无明显差别 |
| 用途 | 配合 [kairisei-ma-ch-wiki](https://github.com/xiaguanbushuai/kairisei-ma-ch-wiki) 资料站使用，或作为个人收藏备份 |

## 下载

**推荐：从 Releases 下分卷 zip**（不必装 Git，两个 zip 各约 530 MB）

到 [Releases](https://github.com/xiaguanbushuai/kairisei-ma-ch-cards/releases/latest) 下载
`chr51-cards-part1of2.zip` 与 `chr51-cards-part2of2.zip`，两个都解压即得到完整的 `chr51/` 目录。
体积接近 1GB，点 GitHub 的「Download ZIP」容易超时，所以走 Release 附件。

也可以浅克隆（只想要少量图片时没必要）：

```bash
git clone --depth 1 https://github.com/xiaguanbushuai/kairisei-ma-ch-cards.git
```

如果只想要少量图片，直接在网页上点开单张图片 → 右侧 Download 即可，不必克隆整个仓库。

## 目录结构

```
images/chr51/chr51_<图鉴ID>.webp
```

文件名与游戏内 pictId 一一对应，与 wiki 的 `cardImage(pictId)` 直接对应。

## 配合 wiki 资料站使用

把 `images/chr51/` 里的 `.webp` 文件拷进便携包的 `images/full/chr51/` 目录，
详情页即显示高清大图（便携包服务端会自动识别 WebP，无需改名，也会自动优先原图）。

## 致谢

卡面素材取自 **[kuuhaku1314/kairisei-ma-ch](https://github.com/kuuhaku1314/kairisei-ma-ch)** —— 《乖离性百万亚瑟王》国服社区保存与本地运行项目。
感谢作者及所有参与保存这款游戏记忆的社区同好。

## 许可与免责声明

- 卡牌立绘等原始素材的版权归 **SQUARE ENIX CO., LTD.** 及该游戏原运营方所有，本仓库与权利人无任何关联
- 本仓库**不适用开源许可**，作者无权授予素材使用许可；仅供个人学习、研究与怀旧参考
- 严禁二次分发、转售或用于任何商业用途；收到权利人通知时应立刻停止使用并删除相关素材

详细条款见 [LICENSE](LICENSE)。
