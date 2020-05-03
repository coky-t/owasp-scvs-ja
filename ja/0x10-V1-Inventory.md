# V1: インベントリ要件

## 管理目標

ソフトウェアの製作に使用されるすべてのコンポーネントの正確なインベントリは、さらなる形態の分析を行うための基本的な要件です。
以下のコントロールには単一アプリケーションインベントリ、組織的インベントリ、および新しいソフトウェアまたはシステムを調達する際にソフトウェアの透明性を向上させるために取るべき手順が盛り込まれています。


コンポーネントの識別はコンポーネントが属するエコシステムに基づいて変化します。
したがって、すべてのインベントリの目的のために、パッケージ URL などの識別子を使用して、管理された依存関係のための命名規則を標準化および正規化できます。


ファーストパーティ、サードパーティ、およびオープンソースのすべてのコンポーネントの組織的インベントリを持つことで、組織内の透明性が高まり、ソフトウェアの標準化と再利用が促進され、迅速な影響分析が可能になります。


## 検証要件

| # | 説明 | L1 | L2 | L3 |
| :---: | :--- | :---: | :---: | :---: |
| **1.1** | すべてのコンポーネントとそのバージョンがビルドの完了時に判明している | ✓ | ✓ | ✓ |
| **1.2** | パッケージマネージャを使用して、すべてのサードパーティバイナリコンポーネントを管理している | ✓ | ✓ | ✓ |
| **1.3** | すべてのサードパーティコンポーネントの正確なインベントリが機械読み取り可能なフォーマットで利用可能である | ✓ | ✓ | ✓ |
| **1.4** | 一般公開されるアプリケーションや市販されるアプリケーションに対してソフトウェア部品表を生成している | ✓ | ✓ | ✓ |
| **1.5** | 新規調達にはソフトウェア部品表を必要としている | | ✓ | ✓ |
| **1.6** | ソフトウェア部品表はすべてのシステムで継続的に保守されている | | | ✓ |
| **1.7** | すべてのコンポーネントを一貫した機械読み取り可能なフォーマットで一意に識別している | ✓ | ✓ | ✓ |
| **1.8** | コンポーネントタイプがインベントリ全体で明確である | | | ✓ |
| **1.9** | コンポーネント機能がインベントリ全体で明確である | | | ✓ |
| **1.10** | すべてのコンポーネントに対して起点が明確である | | | ✓ |