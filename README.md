# img-bed

个人图床仓库。所有图片按「题材 → 子类」分层存放，文件名统一为小写 kebab-case 英文描述名，便于稳定引用与 CDN 加速。

## 目录结构

```
img-bed/
├── nature/              # 自然风光
│   ├── mountains/       # 山地、雪山、高山草甸
│   └── lakes/           # 湖泊、水面
└── illustration/        # 插画 / 二次元
    └── anime/           # 动漫风角色插画
```

## 图片索引

| 路径 | 尺寸 | 大小 | 说明 |
| --- | --- | --- | --- |
| `nature/mountains/alpine-valley-village.jpg` | 1920×1373 | 1.09 MB | 阿尔卑斯山谷牧场与木屋，晨光草坡 |
| `nature/mountains/snow-mountain-heather-trail.jpg` | 1920×1080 | 880 KB | 雪山下的石阶小径与紫色花丛 |
| `nature/lakes/turquoise-lake-bench.jpg` | 1920×1280 | 794 KB | 碧绿湖水、湖畔长凳与大树 |
| `illustration/anime/whale-girl-standing.jpg` | 1024×1536 | 151 KB | 蓝发鲸尾少女，白色外套站姿 |
| `illustration/anime/whale-girl-underwater.png` | 1199×1312 | 1.79 MB | 蓝发鲸尾少女，海底气泡场景 |
| `illustration/anime/star-cat-girl.png` | 1024×1536 | 1.72 MB | 星星主题兽耳少女插画 |

## 引用方式

- 原始地址：`https://raw.githubusercontent.com/biyuewuluo/img-bed/main/<path>`
- jsDelivr CDN：`https://cdn.jsdelivr.net/gh/biyuewuluo/img-bed@main/<path>`

## 命名与归档约定

1. 目录按题材分层：`nature/`（自然风光）、`illustration/`（插画）。
2. 文件名全部小写 kebab-case，使用英文描述主体与场景，避免空格、中文与下划线。
3. 同一主体的系列图用 `-01`、`-02` 序号区分。
4. 新增图片直接放入对应分类目录；新增一级题材时同步更新本文档。