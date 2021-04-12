# WRIME: Dataset for Emotional Intensity Estimation

We annotated SNS posts with emotional intensity to construct a Japanese emotion analysis dataset.

- We provide both subjective (i.e. based on what the writer feels), and objective (i.e. based on what humans and other machines think that the writer feels) annotations.
- Annotations follow Plutchik’s 8-category emotion schema on a 4-point intensity scale (0:no, 1:weak, 2:medium, and 3:strong).
- We annotate 43,200 Japanese posts from 80 crowdsourced workers.

## Examples

Text: タイヤがパンクしてた。。いたずらの可能性が高いんだって。。<br>
(The tire of my car was flat. I heard that it might be mischief.)

||Joy|Sadness|Anticipation|Surprise|Anger|Fear|Disgust|Trust|
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
|Writer  |0|3|0|1|3|0|0|0|
|Reader 1|0|3|0|3|1|2|1|0|
|Reader 2|0|2|0|2|0|0|0|0|
|Reader 3|0|2|0|2|0|1|1|0|


## Research with WRIME

A list of known publications that use WRIME is shown below.
If you know more, please let us know.

- Tomoyuki Kajiwara, Chenhui Chu, Noriko Takemura, Yuta Nakashima, Hajime Nagahara. WRIME: A New Dataset for Emotional Intensity Estimation with Subjective and Objective Annotations. In Proceedings of the 2021 Annual Conference of the North American Chapter of the Association for Computational Linguistics (NAACL 2021), 2021. (to appear)
- 梶原智之, Chenhui Chu, 武村紀子, 中島悠太, 長原一. [主観感情と客観感情の強度推定のための日本語データセット.](https://www.anlp.jp/proceedings/annual_meeting/2021/pdf_dir/P3-3.pdf) 言語処理学会第27回年次大会, pp.523-527, 2021.

## Acknowledgments

This work was supported by Innovation Platform for Society 5.0 from Japan Ministry of Education, Culture, Sports, Science and Technology.


## Licence

- The dataset is available for research purposes only.
- Redistribution of the dataset is prohibited.


## Authors

- [Tomoyuki Kajiwara](http://moguranosenshi.sakura.ne.jp/cv.pdf) (Assistant Professor, Graduate School of Science and Engineering, Ehime University, Japan)
- [Yuta Nakashima](https://www.n-yuta.jp/) (Associate Professor, Institute for Datability Science, Osaka University, Japan)

sentiment-dataset *at* is.ids.osaka-u.ac.jp

