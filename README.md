# WRIME: 主観と客観の感情分析データセット [[English]](https://github.com/ids-cv/wrime/blob/master/README.en.md)

日本語の感情分析の研究のために、以下の特徴を持つデータセットを構築しました。

- 主観（テキストの筆者1人）と客観（クラウドワーカ3人）の両方の立場から感情ラベルを付与しました。
- Plutchikの基本8感情（喜び、悲しみ、期待、驚き、怒り、恐れ、嫌悪、信頼）を扱いました。
- 各感情の強度を4段階（0:無、1:弱、2:中、3:強）でラベル付けしました。
- Ver.2では、感情極性（-2:強いネガティブ、-1:ネガティブ、0:ニュートラル、1:ポジティブ、2:強いポジティブ）も追加しました。

## 更新履歴

- [@shunk031](https://github.com/shunk031) さんが本データセットを [HuggingFace Datasets Hub](https://huggingface.co/datasets/shunk031/wrime) に登録してくださいました。
- Ver.2: 60人の筆者から収集した35,000件の投稿（Ver.1のサブセット）に感情極性を追加でラベル付けしました。
- Ver.1: 80人の筆者から収集した43,200件の投稿に感情強度をラベル付けしました。

## テキストとラベルの例

投稿：車のタイヤがパンクしてた。。いたずらの可能性が高いんだって。。

||喜び|悲しみ|期待|驚き|怒り|恐れ|嫌悪|信頼|感情極性|
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
|主観 |0|3|0|1|3|0|0|0|0|
|客観A|0|3|0|3|1|2|1|0|-1|
|客観B|0|2|0|2|0|0|0|0|-1|
|客観C|0|2|0|2|0|1|1|0|-2|

## 文献情報

- Haruya Suzuki, Sora Tarumoto, Tomoyuki Kajiwara, Takashi Ninomiya, Yuta Nakashima, Hajime Nagahara. **[Emotional Intensity Estimation based on Writer’s Personality.](https://aclanthology.org/2022.aacl-srw.1/)** In Proceedings of the 2nd Conference of the Asia-Pacific Chapter of the Association for Computational Linguistics and the 12th International Joint Conference on Natural Language Processing: Student Research Workshop (AACL-SRW 2022), pp.1-7, 2022.
- 鈴木陽也, 秋山和輝, 梶原智之, 二宮崇, 武村紀子, 中島悠太, 長原一. **[書き手の性格情報を用いた感情強度推定.](https://doi.org/10.11517/pjsai.JSAI2022.0_4D3GS604)** 人工知能学会第36回全国大会, 2022.
- Haruya Suzuki, Yuto Miyauchi, Kazuki Akiyama, Tomoyuki Kajiwara, Takashi Ninomiya, Noriko Takemura, Yuta Nakashima, Hajime Nagahara. **[A Japanese Dataset for Subjective and Objective Sentiment Polarity Classification in Micro Blog Domain.](https://aclanthology.org/2022.lrec-1.759/)** In Proceedings of the 13th International Conference on Language Resources and Evaluation (LREC 2022), pp.7022-7028, 2022.
- 宮内裕人, 鈴木陽也, 秋山和輝, 梶原智之, 二宮崇, 武村紀子, 中島悠太, 長原一. **[主観と客観の感情極性分類のための日本語データセット.](https://www.anlp.jp/proceedings/annual_meeting/2022/pdf_dir/PH3-13.pdf)** 言語処理学会第28回年次大会, pp.1495-1499, 2022.
- Tomoyuki Kajiwara, Chenhui Chu, Noriko Takemura, Yuta Nakashima, Hajime Nagahara. **[WRIME: A New Dataset for Emotional Intensity Estimation with Subjective and Objective Annotations.](https://aclanthology.org/2021.naacl-main.169/)** In Proceedings of the 2021 Annual Conference of the North American Chapter of the Association for Computational Linguistics (NAACL 2021), pp.2095-2104, 2021.
- 梶原智之, Chenhui Chu, 武村紀子, 中島悠太, 長原一. **[主観感情と客観感情の強度推定のための日本語データセット.](https://www.anlp.jp/proceedings/annual_meeting/2021/pdf_dir/P3-3.pdf)** 言語処理学会第27回年次大会, pp.523-527, 2021.

本データセットを研究で利用された場合、論文情報をご連絡いただきましたらここに掲載させていただきます。

## 謝辞

本研究は、文部科学省による[Society 5.0 実現化研究拠点支援事業](https://www.ids.osaka-u.ac.jp/ildi/index.html)（グラント番号: JPMXP0518071489）の助成を受けたものです。

## ライセンス

本データセットは研究目的で利用可能です。再配布はご遠慮ください。

## 連絡先

- [梶原 智之](https://sites.google.com/site/moguranosenshi/)（愛媛大学 大学院理工学研究科 助教）
- [中島 悠太](https://www.n-yuta.jp/)（大阪大学 データビリティフロンティア機構 准教授）

sentiment-dataset *at* is.ids.osaka-u.ac.jp

