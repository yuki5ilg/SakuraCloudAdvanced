# さくらのクラウド検定 試験対策ドキュメント

さくらのクラウド検定（**アドバンスド** / **ベーシック**）の試験対策ノート集です。公式教材PDFを解析し、トピックごとの対策ノートと暗記チートシートにまとめています。

## リポジトリ構成

```
.
├── README.md   … 本ファイル（全ノート・全教材への索引）
├── docs/       … 試験対策ノート（Markdown）
│   ├── advanced/   … アドバンスド検定の対策ノート（完成）
│   └── basic/      … ベーシック検定の対策ノート（完成・大項目1は範囲外）
└── raw/        … 解析元の教材PDF・シラバス
    ├── advanced/   … アドバンスド検定の教材PDF（全11冊＋シラバス）
    └── basic/      … ベーシック検定の教材PDF（全19冊＋シラバス）
```

各表の「ノート」列が対策ノート（`docs/`）、「教材」列が解析元の公式PDF（`raw/`）へのリンクです。ここから全ファイルに飛べます。

---

## アドバンスド検定 → [`docs/advanced/`](docs/advanced/)

教材 全11冊・計487ページを解析した試験対策ノート。出題範囲は公式シラバス [📄 advanced-syllabus_v1.0.pdf](raw/advanced/advanced-syllabus_v1.0.pdf)（v1.0）に準拠し、下表の11トピックを網羅しています。

- **試験直前** → [`docs/advanced/00_暗記チートシート.md`](docs/advanced/00_暗記チートシート.md)（全体横断の最重要ポイント・数値・比較表）

> シラバスのテーマ: 設計編は **セキュリティ／信頼性と回復力／運用効率／コスト最適化** の4観点を多角的に検討し、組織方針に沿って全体最適化する力が問われます。

### Part 1. さくらのクラウドの高度な活用（要素技術）
| No. | テーマ | ノート | 教材 |
|-----|--------|--------|------|
| 1.1.1 | コンテナサービス（レジストリ / 高火力DOK / AppRun） | [ノート](docs/advanced/1.1.1_コンテナサービス.md) | [📄PDF](raw/advanced/SCA1.1.1_ContainerServices-1.0-202602.0.pdf) |
| 1.1.2 | アプリケーション連携（MQ / 通知 / EventBus / APIゲートウェイ / Workflows） | [ノート](docs/advanced/1.1.2_アプリケーション連携.md) | [📄PDF](raw/advanced/SCA1.1.2_ApplicationIntegration-1.0-202602.0.pdf) |
| 1.2.1 | 分散データベース（NoSQL / Cassandra） | [ノート](docs/advanced/1.2.1_分散データベース.md) | [📄PDF](raw/advanced/SCA1.2.1_DistributedDatabases-1.0-202602.0.pdf) |
| 1.3.1 | CDN（さくらのウェブアクセラレータ） | [ノート](docs/advanced/1.3.1_CDN.md) | [📄PDF](raw/advanced/SCA1.3.1_CDN-1.0-202602.1.pdf) |
| 1.4.1 | モニタリング（モニタリングスイート） | [ノート](docs/advanced/1.4.1_モニタリング.md) | [📄PDF](raw/advanced/SCA1.4.1_Monitoring-1.0-202602.0.pdf) |
| 1.5.1 | データ暗号化（KMS / シークレットマネージャ / クラウドHSM） | [ノート](docs/advanced/1.5.1_データ暗号化.md) | [📄PDF](raw/advanced/SCA1.5.1_DataEncryption-1.0-202602.0-.pdf) |
| 1.5.2 | ガバナンスと統制（サービスポリシー / セキュリティコントロール） | [ノート](docs/advanced/1.5.2_ガバナンスと統制.md) | [📄PDF](raw/advanced/SCA1.5.2_Governance-and-Control-1.0-202602.0.pdf) |

### Part 2. さくらのクラウドでの最適な設計（設計）
| No. | テーマ | ノート | 教材 |
|-----|--------|--------|------|
| 2.1.1 | デザインパターン（設計の定石） | [ノート](docs/advanced/2.1.1_デザインパターン.md) | [📄PDF](raw/advanced/SCA2.1.1_DesignPatterns-1.0-202602.0.pdf) |
| 2.2.1 | 小規模システムのアーキテクチャ設計 | [ノート](docs/advanced/2.2.1_小規模システム設計.md) | [📄PDF](raw/advanced/SCA2.2.1_ArchitectureDesign-for-SmallScaleSystems-1.0-202602.0.pdf) |
| 2.2.2 | 中規模システムのアーキテクチャ設計 | [ノート](docs/advanced/2.2.2_中規模システム設計.md) | [📄PDF](raw/advanced/SCA2.2.2_ArchitectureDesign-for-MediumScaleSystems-1.0-202602.0.pdf) |
| 2.2.3 | 大規模システムのアーキテクチャ設計 | [ノート](docs/advanced/2.2.3_大規模システム設計.md) | [📄PDF](raw/advanced/SCA2.2.3_ArchitectureDesign-for-LargeScaleSystems-1.0-202602.0.pdf) |

#### 学習の全体像（5 STEP）
1. **STEP1 アプリケーション基盤の高度化** … コンテナ（1.1.1）、アプリ連携（1.1.2）
2. **STEP2 データベース** … 分散DB / NoSQL（1.2.1）
3. **STEP3 コンテンツ配信** … CDN（1.3.1）
4. **STEP4 クラウドの運用管理** … モニタリング（1.4.1）
5. **STEP5 セキュリティとガバナンス** … 暗号化（1.5.1）、ガバナンス（1.5.2）

---

## ベーシック検定 → [`docs/basic/`](docs/basic/)

教材を解析した試験対策ノート。出題範囲は公式シラバス [📄 basic-syllabus_v2.0.pdf](raw/basic/basic-syllabus_v2.0.pdf)（v2.0）に準拠し、大項目2・3の全19トピックを網羅しています。

- **試験直前** → [`docs/basic/00_暗記チートシート.md`](docs/basic/00_暗記チートシート.md)（全体横断の最重要ポイント・数値・比較表）

> 出題範囲（シラバスv2.0の大項目）:
> 1. **デジタル技術の基礎** … ⚠️範囲が広く一般的な内容のため本ノート集の対象外（教材PDFも未収録）
> 2. **さくらインターネットのサービス** … クラウドインフラ/アプリケーション/物理基盤/周辺サービス
> 3. **さくらのクラウドでのアーキテクチャ設計** … システム構成設計/セキュリティ設計/可用性・拡張性設計/コストパフォーマンス設計

### 大項目2. さくらインターネットのサービス
| No. | テーマ | ノート | 教材 |
|-----|--------|--------|------|
| 2 | さくらインターネットのサービス（クラウド / VPS / 物理基盤 / 周辺サービス） | [ノート](docs/basic/2_さくらインターネットのサービス.md) | [📄PDF](raw/basic/SCB2_SakuraInternetService-2.0-202602.1.pdf) |

### 大項目3. さくらのクラウドでのアーキテクチャ設計
| No. | テーマ | ノート | 教材 |
|-----|--------|--------|------|
| 3.1.1 | コンピューティングリソース | [ノート](docs/basic/3.1.1_コンピューティングリソース.md) | [📄PDF](raw/basic/SCB3.1.1_ComputingResource-2.0-202602.0.pdf) |
| 3.1.2 | ストレージ | [ノート](docs/basic/3.1.2_ストレージ.md) | [📄PDF](raw/basic/SCB3.1.2_Storage-2.0-202602.0.pdf) |
| 3.1.3 | ネットワーク（全3部） | [①](docs/basic/3.1.3_ネットワーク①.md) ／ [②](docs/basic/3.1.3_ネットワーク②.md) ／ [③](docs/basic/3.1.3_ネットワーク③.md) | [📄①](raw/basic/SCB3.1.3_Network1-2.0-202602.0.pdf) ／ [📄②](raw/basic/SCB3.1.3_Network2-2.0-202602.0.pdf) ／ [📄③](raw/basic/SCB3.1.3_Network3-2.0-202602.0.pdf) |
| 3.1.4 | データベース | [ノート](docs/basic/3.1.4_データベース.md) | [📄PDF](raw/basic/SCB3.1.4_Database-2.0-202602.0.pdf) |
| 3.1.5 | データ処理 | [ノート](docs/basic/3.1.5_データ処理.md) | [📄PDF](raw/basic/SCB3.1.5_DataProcessing-2.0-202602.0.pdf) |
| 3.1.6 | 他サービスとの連携 | [ノート](docs/basic/3.1.6_他サービスとの連携.md) | [📄PDF](raw/basic/SCB3.1.6_ServiceIntegration-2.0-202602.0.pdf) |
| 3.2.1 | リソースのセキュリティ | [ノート](docs/basic/3.2.1_リソースのセキュリティ.md) | [📄PDF](raw/basic/SCB3.2.1_ResourceSecurity-2.0-202602.0.pdf) |
| 3.2.2 | データのセキュリティ | [ノート](docs/basic/3.2.2_データのセキュリティ.md) | [📄PDF](raw/basic/SCB3.2.2_DataSecurity-2.0-202602.0.pdf) |
| 3.2.3 | アプリケーションのセキュリティ | [ノート](docs/basic/3.2.3_アプリケーションのセキュリティ.md) | [📄PDF](raw/basic/SCB3.2.3_ApplicationSecurity-2.0-202602.0.pdf) |
| 3.3.1 | 可用性の設計 | [ノート](docs/basic/3.3.1_可用性の設計.md) | [📄PDF](raw/basic/SCB3.3.1_AvailabilityDesign-2.0-202602.0.pdf) |
| 3.3.2 | 拡張性の設計 | [ノート](docs/basic/3.3.2_拡張性の設計.md) | [📄PDF](raw/basic/SCB3.3.2_ScalabilityDesign-2.0-202602.0.pdf) |
| 3.4.1 | コスト設計（料金体系） | [ノート](docs/basic/3.4.1_コスト設計.md) | [📄PDF](raw/basic/SCB3.4.1_CostDesign-2.0-202602.0.pdf) |
| 3.4.2 | コンピューティングのコスト設計 | [ノート](docs/basic/3.4.2_コスト設計_コンピューティング.md) | [📄PDF](raw/basic/SCB3.4.2_CostDesignComputingResource-2.0-202602.0.pdf) |
| 3.4.3 | ストレージのコスト設計 | [ノート](docs/basic/3.4.3_コスト設計_ストレージ.md) | [📄PDF](raw/basic/SCB3.4.3_CostDesignStorage-2.0-202602.0.pdf) |
| 3.4.4 | ネットワークのコスト設計 | [ノート](docs/basic/3.4.4_コスト設計_ネットワーク.md) | [📄PDF](raw/basic/SCB3.4.4_CostDesignNetwork-2.0-202602.0.pdf) |
| 3.4.5 | データベースのコスト設計 | [ノート](docs/basic/3.4.5_コスト設計_データベース.md) | [📄PDF](raw/basic/SCB3.4.5_CostDesignDatabase-2.0-202602.0.pdf) |

---

> 出典: さくらインターネット株式会社「さくらのクラウド検定」教材（CC BY-SA 4.0）。本ノートは学習目的の要約です。仕様・数値は教材本文を逐語的に保持していますが、最終的な正確性は公式ドキュメントもご確認ください。
