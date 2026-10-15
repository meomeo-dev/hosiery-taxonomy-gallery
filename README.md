# 常见穿搭丝袜类型中英文全景图鉴与画廊
### Hosiery & Tights Taxonomy and Style Gallery

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/Dataset_License-CC_BY--NC--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![License: MIT](https://img.shields.io/badge/Code_License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![GitHub Pages](https://img.shields.io/badge/Live_Demo-GitHub_Pages-2ea44f.svg)](https://meomeo-dev.github.io/hosiery-taxonomy-gallery/)

本项目是一套系统化的服饰纺织分类图鉴与中英文对照知识库，收录并整理了 **7 大核心分类**、**71 种细分款式**的标准定义、技术规格、触感特征、穿搭场景与高清视觉图解。

🌐 **在线交互图鉴与画廊**：[https://meomeo-dev.github.io/hosiery-taxonomy-gallery/](https://meomeo-dev.github.io/hosiery-taxonomy-gallery/)

---

## 目录结构 (Directory Structure)

```text
.
├── 01_基础厚度与透肤度/        # 极薄隐形、标准透肤、半透、不透、加绒发热、假透肉光腿神器等
├── 02_版型结构与长度剪裁/      # 连裤袜、自立长筒袜、吊带袜、及膝袜、短袜、踩脚袜、开档袜等
├── 03_表面光泽与视觉质感/      # 哑光雾面、缎光水光、油亮镜面高光、偏光、湿感涂层、水钻等
├── 04_渔网与镂空提花/          # 大中小网、菱格网、花卉提花、几何提花、蕾丝镂空等
├── 05_图案印花与线条设计/      # 波点、经典后缝线、假高筒拼接、纹身印花、细条纹、阿盖尔菱格等
├── 06_纺织材质与功能特性/      # 包芯丝、天鹅绒超细纤维、桑蚕丝、压力袜、防勾丝、接触凉感等
├── 07_亚文化与复古风格/        # 洛丽塔白丝、地雷系/量产型、暗黑哥特、废土朋克、复古古着等
├── assets/
│   └── contact_sheets/         # 数据集全量合规审查联印图 (Contact Sheets)
├── 常见穿搭丝袜类型中英文全景对照表.csv # 完整结构化元数据对照表 (UTF-8)
├── index.html                  # 响应式交互画廊前端页面
├── LICENSE                     # 多重开源许可协议文件
├── .nojekyll                   # 禁用 Jekyll 预编译以支持原生静态托管
└── README.md
```

---

## 合规审查联印图 (Visual Compliance Contact Sheets)

为确保数据集在公开托管环境下的内容边界合规（严格杜绝露骨色情、性器官暴露或任何违反平台社区准则的敏感图像），项目生成了全量视觉联印图供公开核查：

* **全景总联印图 (Master Contact Sheet - 142 张)**：[`assets/contact_sheets/contact_sheet_master_all.jpg`](./assets/contact_sheets/contact_sheet_master_all.jpg)
* **01 基础厚度与透肤度 (14 张)**：[`assets/contact_sheets/contact_sheet_01.jpg`](./assets/contact_sheets/contact_sheet_01.jpg)
* **02 版型结构与长度剪裁 (28 张)**：[`assets/contact_sheets/contact_sheet_02.jpg`](./assets/contact_sheets/contact_sheet_02.jpg)
* **03 表面光泽与视觉质感 (16 张)**：[`assets/contact_sheets/contact_sheet_03.jpg`](./assets/contact_sheets/contact_sheet_03.jpg)
* **04 渔网与镂空提花 (18 张)**：[`assets/contact_sheets/contact_sheet_04.jpg`](./assets/contact_sheets/contact_sheet_04.jpg)
* **05 图案印花与线条设计 (24 张)**：[`assets/contact_sheets/contact_sheet_05.jpg`](./assets/contact_sheets/contact_sheet_05.jpg)
* **06 纺织材质与功能特性 (22 张)**：[`assets/contact_sheets/contact_sheet_06.jpg`](./assets/contact_sheets/contact_sheet_06.jpg)
* **07 亚文化与复古风格 (20 张)**：[`assets/contact_sheets/contact_sheet_07.jpg`](./assets/contact_sheets/contact_sheet_07.jpg)

所有图像样本均为中性、客观的纺织品电商主图与正规时尚穿搭摄影，符合主流开源托管平台的合规标准。

---

## 分类维度说明 (Taxonomy Overview)

| 分类编号 | 一级分类名称 | 英文术语 (Category) | 包含代表细分项 |
| :--- | :--- | :--- | :--- |
| **01** | 基础厚度与透肤度 | Sheer & Opacity | 极薄隐形 (5-10D)、标准透肤 (10-20D)、半透肉 (30-50D)、不透肉 (60-90D)、加厚保暖、假透肉光腿神器 |
| **02** | 版型结构与长度剪裁 | Lengths & Silhouettes | 连裤袜、硅胶防滑自立长筒袜、吊袜带长筒袜、及膝丝袜、短袜、九分裤袜、踩脚袜、露趾袜、开档连裤袜等 |
| **03** | 表面光泽与视觉质感 | Finish, Shine & Sheen | 哑光雾面、自然缎光、油亮镜面高光、金银丝微闪、湿感涂层、偏光贝母、天鹅绒吸光、水钻烫钻 |
| **04** | 渔网与镂空提花 | Fishnets, Openwork & Jacquard | 细网 (Micro-net)、中网、粗网/大网、菱格镂空提花、花卉植物提花、几何提花、破损镂空等 |
| **05** | 图案印花与线条设计 | Patterns, Prints & Lines | 波点 (Polka dots)、经典后缝线 (Back-seam)、假高筒/拼接、纹身印花、细条纹、阿盖尔菱格纹等 |
| **06** | 纺织材质与功能特性 | Materials & Functional Textiles | 包芯丝、天鹅绒超细纤维、桑蚕丝、医用/飞行梯度压力袜、防勾丝热熔纱、无缝一体、接触凉感、发热保暖 |
| **07** | 亚文化与复古风格 | Subcultures & Vintage Aesthetics | 纯白洛丽塔、地雷系/量产型暗黑绑带、暗黑哥特蛛网、废土朋克破洞、1950s 复古后缝平口长袜、Y2K 千禧辣妹风 |

---

## 对照表字段定义 (CSV Schema)

`常见穿搭丝袜类型中英文全景对照表.csv` 包含以下核心维度：

* **序号 (ID)**: 款式唯一序号 (1 ~ 71)
* **一级分类 (Category)**: 7 大主分类
* **英文称呼 (English Name / Industry Term)**: 国际通用术语与英文行业规范称谓
* **中文称呼与别名 (Chinese Name & Aliases)**: 常见中文规范名、电商搜索词与市场俗称
* **规格与工艺特征 (Specifications & Craftsmanship)**: 纱线纤度 (Denier / D数)、针织工艺、纤维成分与物理结构
* **视觉效果描述 (Visual Effect)**: 光学透光度、光泽分布、修容塑形效果与视觉风格
* **触感与质感描述 (Tactile & Hand Feel)**: 表面摩擦系数、阻尼感、弹力回馈与亲肤体验
* **常见穿搭风格与场合 (Styling & Occasion)**: 适宜鞋履搭配、服装层叠规则与礼仪场合建议

---

## 本地运行画廊

无需安装任何构建工具或依赖，直接使用任意现代浏览器打开 `index.html` 即可完整浏览和交互；也可以通过本地轻量 HTTP 服务器预览：

```bash
python3 -m http.server 8000
# 浏览器打开 http://localhost:8000
```

---

## 知识产权与许可协议 (Licensing & Terms)

本项目采用分层多重许可协议（Multi-licensing），区分前端代码、结构化数据集与视觉参考媒体：

| 资产类型 (Asset Type) | 适用文件 (Applicable Files) | 许可协议 / 权利声明 (License / Terms) | 权益说明 (Notes) |
| :--- | :--- | :--- | :--- |
| **前端程序与代码** | `index.html`, 交互逻辑与样式表 | **[MIT License](https://opensource.org/licenses/MIT)** | 允许自由商用、修改与再分发 |
| **分类表与数据集元数据** | `常见穿搭丝袜类型中英文全景对照表.csv` 及分类文本 | **[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)** | 允许署名分享与演化衍生，**禁止未经许可的商业盈利**，衍生作品需相同协议共享 |
| **视觉图像参考样本** | `01_*` ~ `07_*` 及 `assets/` 图像文件 | **合理使用与学术引用 (Fair Use / Educational Reference)** | 图片版权归原品牌、摄影师或模特所有，仅供非商业教育科研分类参考 |

### 侵权投诉与移除政策 (DMCA / Takedown)
若相关权利人对项目中引用的参考图片存有异议，请提交 [GitHub Issue](https://github.com/meomeo-dev/hosiery-taxonomy-gallery/issues) 联系维护者，我们将第一时间进行核实并在 24 小时内移除相应素材。
