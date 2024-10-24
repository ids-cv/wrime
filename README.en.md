# WRIME: Dataset for Emotional Intensity Estimation

We annotated SNS posts with emotional intensity to construct a Japanese emotion analysis dataset.

- We provide both subjective (i.e. based on what the writer feels) and objective (i.e. based on what humans and other machines think that the writer feels) annotations.
- Annotations follow Plutchik’s 8-category emotion schema on a 4-point intensity scale (0:no, 1:weak, 2:medium, and 3:strong).
- In Ver.2, we also annotate sentiment polarity (-2: Strong Negative, -1: Negative, 0: Neutral, 1: Positive, 2: Strong Positive).

## Change Log

- Thanks to [@shunk031](https://github.com/shunk031), WRIME is now available on the [HuggingFace Datasets Hub](https://huggingface.co/datasets/shunk031/wrime).
- Ver.2: We annotate 35,000 Japanese posts from 60 crowdsourced workers (a subset of Ver.1) with both emotional intensity and sentiment polarity.
- Ver.1: We annotate 43,200 Japanese posts from 80 crowdsourced workers with emotional intensity.

## Examples

Text: 車のタイヤがパンクしてた。。いたずらの可能性が高いんだって。。<br>
(The tire of my car was flat. I heard that it might be mischief.)

||Joy|Sadness|Anticipation|Surprise|Anger|Fear|Disgust|Trust|Sentiment Polarity|
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
|Writer  |0|3|0|1|3|0|0|0|0|
|Reader 1|0|3|0|3|1|2|1|0|-1|
|Reader 2|0|2|0|2|0|0|0|0|-1|
|Reader 3|0|2|0|2|0|1|1|0|-2|


## Research with WRIME

A list of known publications that use WRIME is shown below.
If you know more, please let us know.

- Haruya Suzuki, Sora Tarumoto, Tomoyuki Kajiwara, Takashi Ninomiya, Yuta Nakashima, Hajime Nagahara. **[Emotional Intensity Estimation based on Writer’s Personality.](https://aclanthology.org/2022.aacl-srw.1/)** In Proceedings of the 2nd Conference of the Asia-Pacific Chapter of the Association for Computational Linguistics and the 12th International Joint Conference on Natural Language Processing: Student Research Workshop (AACL-SRW 2022), pp.1-7, 2022.
- Haruya Suzuki, Yuto Miyauchi, Kazuki Akiyama, Tomoyuki Kajiwara, Takashi Ninomiya, Noriko Takemura, Yuta Nakashima, Hajime Nagahara. **[A Japanese Dataset for Subjective and Objective Sentiment Polarity Classification in Micro Blog Domain.](http://www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.759.pdf)** In Proceedings of the 13th International Conference on Language Resources and Evaluation (LREC 2022), pp.7022-7028, 2022.
- Tomoyuki Kajiwara, Chenhui Chu, Noriko Takemura, Yuta Nakashima, Hajime Nagahara. **[WRIME: A New Dataset for Emotional Intensity Estimation with Subjective and Objective Annotations.](https://aclanthology.org/2021.naacl-main.169/)** In Proceedings of the 2021 Annual Conference of the North American Chapter of the Association for Computational Linguistics (NAACL 2021), pp.2095-2104, 2021.


## Acknowledgments

This work was supported by [Innovation Platform for Society 5.0](https://www.ids.osaka-u.ac.jp/ildi/en/index.html) from Japan Ministry of Education, Culture, Sports, Science and Technology.


## Licence

[CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/)


## Authors

- [Tomoyuki Kajiwara](http://moguranosenshi.sakura.ne.jp/cv.pdf) (Senior Assistant Professor, Graduate School of Science and Engineering, Ehime University, Japan)
- [Yuta Nakashima](https://www.n-yuta.jp/) (Professor, D3 Center, Osaka University, Japan)

sentiment-dataset *at* is.ids.osaka-u.ac.jp

