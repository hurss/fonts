# Font collection

## DOS-style Font

### English

I have created a series of DOS-style fonts from bitmap binary data. We are support TTF and BDF format.

Each license of fonts is based on MIT License, but they can use for commecial propose or subtitles of social media (Youtube and so on).

CJK Ideographs are imported from Hanme-hangul (KS X 1001 Hanja; one of hangul input method in DOS) and jiskan16(https://ja.wikipedia.org/wiki/Jiskan) (JIS X 0213:2004 Kanji); which designed by Imamura and Hanataka from Japan Electronics and Information Technology Industries Association. Still, we will need to resolve minor issues.

Especially, Miraero Normal font only covers Unicode 1.1 glyphs without CJK Ideographs. Its BDF is 24x24 bitmap font.

### Korean

비트맵 데이터를 추출하여 도스 스타일 글꼴을 만들었습니다. TTF 및 BDF를 지원합니다.

해당 글꼴들은 기본적으로 MIT 라이선스에 기반을 두고 있으나, 상업 목적이나 유튜브 등 SNS용 자막으로도 사용이 가능합니다.

한자 글꼴은 도스용 한메한글 한자 글꼴 (KS X 1001 부분) 및 [jiskan16](https://ja.wikipedia.org/wiki/Jiskan) (JIS X 0213:2004)에서 추출하였습니다. 하지만 약간의 문제점을 해결하여야 할 것입니다.

특히 미래로 글꼴은 한자를 제외한 유니코드 1.1 문자들을 커버합니다. 해당 BDF는 24x24 비트맵 글꼴입니다.

### Font Lists

* DOSMyungjo (도스명조)
* DOSGothic (도스고딕)
* DOSSaemmul (도스샘물)
* Sam3KRFont (삼국지3글꼴) - 한자 없음 (Not contains Hanja), MS워드 사용시 자간 뭉개질 수 있음
* MiraeroNormal (미래로 글꼴) - KS X 1001 & KS X 1002 한자 (KS X 1001 & KS X 1002 Hanja), Unicode 1.1 glyphs and Euro Sign Support
* DOSPilgi (도스필기, 추가 예정)
* DOSIyagi (도스이야기, 추가 예정)

### Description
* TTF
It is TrueType format.

트루타입 방식을 사용하였습니다.

* BDF
LINUX reserves its console or terminal.

리눅스 콘솔이나 단말에 사용할 수 있습니다.

### Sample
![Font Sample](/fontsample.PNG)

### Version History

* 0.43 (2020/06/27)
  * Change minor fix: MiraeroNormal font can use commercially
* 0.42 (2020/06/18)
  * Change licenses for social media
* 0.41 (2018/04/24)
  * Move Data Repository and obsolete OTF will not used
* 0.4 (2016/10/30)
  * Update MiraeroNormal (Update KS Hanja)
* 0.3 (2016/10/01)
  * Add MiraeroNormal
* 0.2 (2016/08/19)
  * Add Sam3KRFont
  * Change current license into MIT License
  * Decompress zip files
* 0.15 (2016/04/08)
  * Update CJK Ranges
  * Compressed with ZIP files (due to storage)
* 0.1 (2016/04/07)
  * Add OTF, BDF (16pt) format
  * Add 3 items (DOSMyungjo, DOSGothic and DOSSaemmul)
  * Only support Basic Latin and Hangul

### Support Range
* Basic Latin (기본 라틴)
* Hangul Jamo (한글 자모)
* Hangul Compatibility Jamo (한글 호환 자모)
* Hangul Syllables (한글 낱자)
* CJK Unified Ideographs (KS X 1001 + KS X 1002 (optional) + JIS X 0213:2004)
* CJK Unified Extension A (Compatible with JIS X 0213:2004)
* CJK Unified Extension B (Compatible with JIS X 0213:2004)

### Contact
* leedheo@gmail.com

### References
* [jiskan article in Wikipedia (in Japanese)](http://kanji.zinbun.kyoto-u.ac.jp/~yasuoka/ftp/fonts/)
* [akafuku's GitHub (jiskan16 files)](https://github.com/akahuku/ufo/tree/master/src/jiskan)
* [MiraeroNormal references (in Korean)](http://www.korean.go.kr/front/etcData/etcDataView.do?mn_id=46&etc_seq=47&pageIndex=1)
