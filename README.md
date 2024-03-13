# Font collection
## Acknowledgement

개인적인 사정에 따라, 제시한 글꼴 외에 추가로 글꼴을 만들기 어렵게 되었습니다.

다운로드: https://github.com/hurss/fonts/files/8644954/fonts_220507.zip

**글꼴 개조 문의나 추가 글꼴 제작요청은 받지 않습니다.**

## DOS-style Font

비트맵 데이터를 추출하여 도스 스타일 글꼴을 만들었습니다. TTF 및 BDF를 지원합니다.

해당 글꼴들은 MIT 라이선스에 기반을 둡니다.

한자 글꼴은 [jiskan16](https://ja.wikipedia.org/wiki/Jiskan) (JIS X 0213:2004)과 도스 간체자/번체자 글꼴에서 추출하였습니다.

특히 미래로 글꼴은 한자를 제외하고 유니코드 1.1 문자들을 커버합니다. 해당 BDF는 24x24 비트맵 글꼴입니다.

### 종류

* TTF
트루타입 방식을 사용하였습니다.

* BDF
리눅스 터미널에 사용할 수 있습니다.

### Font Lists

* DOSMyungjo (도스명조)
* DOSGothic (도스고딕)
* DOSSaemmul (도스샘물)
* Sam3KRFont (삼국지3글꼴) - 한자 없음 (Not contains Hanja), MS워드 사용시 자간 뭉개질 수 있음
* MiraeroNormal (미래로 글꼴) - KS X 1001 & KS X 1002 한자 (KS X 1001 & KS X 1002 Hanja), Unicode 1.1 glyphs and Euro Sign Support
* DOSIyagiBoldface (도스이야기) - **이야기 굵은체**
* DOSPilgi (도스필기)

## Sample
![Font Sample](/fontsample.PNG)

## FAQ
1. 상업적 이용 문의 (라이선스 관련)
현재 MIT 라이선스로 배포하고 있습니다.

2. 영리목적 사용 (메신저 이모티콘 등)
가능합니다. 대신 부가 설명에 ‘글꼴(폰트)로 도스샘물체(leedheo 제작)를 사용하였습니다’ 형태로 기재하시면 되겠습니다.
 
3. 폰트 출처 및 이용 명시 등에 관하여
폰트 원출처는 https://github.com/hurss/fonts 입니다. 눈누에 갱신 관련 연락을 넣어 보았으나 닉네임에 사이트 링크가 되지 않은 관계로, 출처 표시를 해 주시면 감사하겠습니다.

## English Description

I have created a series of DOS-style fonts from bitmap binary data. We are support TTF and BDF format.

They licensed by MIT License.

CJK Ideographs are imported from Hanme-hangul (KS X 1001 Hanja; one of hangul input method in DOS) and jiskan16(https://ja.wikipedia.org/wiki/Jiskan) (JIS X 0213:2004 Kanji); which designed by Imamura and Hanataka from Japan Electronics and Information Technology Industries Association. Still, we will need to resolve minor issues.

Especially, Miraero Normal font only covers Unicode 1.1 glyphs without CJK Ideographs. Its BDF is 24x24 bitmap font.

### Kinds by Extension
* TTF
It is TrueType format.

* BDF
It can used in LINUX terminal.

### Support Range
* Basic Latin (기본 라틴)
* Hangul Jamo (한글 자모)
* Hangul Compatibility Jamo (한글 호환 자모)
* Hangul Syllables (한글 낱자)
* CJK Unified Ideographs (KS X 1001 + KS X 1002 (optional) + JIS X 0213:2004)
* CJK Unified Extension A (Compatible with JIS X 0213:2004)
* CJK Unified Extension B (Compatible with JIS X 0213:2004)

## Version History
### Korean
* 1.0 (2022/05/07)
  * DOSIyagiBoldface 한자 수정, DOSPilgi (필기체) 추가
* 0.5 (2022/05/03)
  * DOSIyagiBoldface (이야기 굵은체) 추가
* 0.41 (2018/04/24)
  * 데이터 정리, OTF글꼴 제거
* 0.4 (2016/10/30)
  * MiraeroNormal KS한자 업데이트
* 0.3 (2016/10/01)
  * MiraeroNormal 추가
* 0.2 (2016/08/19)
  * Sam3KRFont 추가
  * MIT License로 변경
  * 글꼴 파일의 압축 해제
* 0.15 (2016/04/08)
  * CJK한자 범위 변경
  * 공간 절약을 위하여 파일 압축
* 0.1 (2016/04/07)
  * OTF, BDF (16pt) 추가
  * 3개 글꼴 추가 (DOSMyungjo, DOSGothic and DOSSaemmul)
  * 라틴 문자와 한글만 지원

### English
* 1.0 (2022/05/07)
  * Correct Hanja of DOSIyagiBoldface, Add DOSPilgi
* 0.5 (2022/05/03)
  * Add DOSIyagiBoldface (Boldface-like font)
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

### References
* [jiskan article in Wikipedia (in Japanese)](http://kanji.zinbun.kyoto-u.ac.jp/~yasuoka/ftp/fonts/)
* [akafuku's GitHub (jiskan16 files)](https://github.com/akahuku/ufo/tree/master/src/jiskan)
* [MiraeroNormal references (in Korean)](http://www.korean.go.kr/front/etcData/etcDataView.do?mn_id=46&etc_seq=47&pageIndex=1)
