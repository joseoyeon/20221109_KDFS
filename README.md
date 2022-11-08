# 외형적 특징을 활용한 문서 작성 집단 분류 방법

## 실험 대상 기관 

* 고용노동부(A) : [https://www.moel.go.kr/news/enews/report/enewsList.do?pageIndex=1](https://www.moel.go.kr/news/enews/report/enewsList.do?pageIndex=1)
* 국립생태원(B) : [https://www.nie.re.kr/nie/bbs/BMSR00029/list.do?menuNo=200097&pageIndex=1](https://www.nie.re.kr/nie/bbs/BMSR00029/list.do?menuNo=200097&pageIndex=1)
* 금융위원회(C) : [https://fsc.go.kr/no010101?curPage=1](https://fsc.go.kr/no010101?curPage=1)
* 기획재정부(D) : [https:\\www.moef.go.kr/nw/nes/nesdta.do?searchBbsId1=MOSFBBS_000000000028&menuNo=4010100&pageIndex=1](https:\\www.moef.go.kr/nw/nes/nesdta.do?searchBbsId1=MOSFBBS_000000000028&menuNo=4010100&pageIndex=1)
* 산업통상자원부(E) : [https://www.motie.go.kr/motie/ne/presse/press2/bbs/bbsList.do?bbs_cd_n=81](https://www.motie.go.kr/motie/ne/presse/press2/bbs/bbsList.do?bbs_cd_n=81) 
* 외교부(F) : [https://www.mofa.go.kr/www/brd/m_4080/list.do?page=1](https://www.mofa.go.kr/www/brd/m_4080/list.do?page=1)
* 행정안전부(G) : [https://www.mois.go.kr/frt/bbs/type010/commonSelectBoardList.do?bbsId=BBSMSTR_000000000008&pageIndex=1](https://www.mois.go.kr/frt/bbs/type010/commonSelectBoardList.do?bbsId=BBSMSTR_000000000008&pageIndex=1)

## 성능 

### 선별된 55개의 특징으로 학습된 각 알고리즘별 분류 성능 지표

<html xmlns="http://www.w3.org/TR/REC-html40" xmlns:o="urn:schemas-microsoft-com:office:office" xmlns:v="urn:schemas-microsoft-com:vml" xmlns:w="urn:schemas-microsoft-com:office:word"><head><!--[if !mso]>
<style>
v\:* {behavior:url(#default#vml);}
o\:* {behavior:url(#default#vml);}
w\:* {behavior:url(#default#vml);}
.shape {behavior:url(#default#vml);}
</style>
<![endif]
--><title></title><style type="text/css"><!--p.0
{mso-style-name:"바탕글";line-height:160%;margin-left:0pt;margin-right:0pt;text-indent:0pt;margin-top:0pt;margin-bottom:0pt;text-align:justify;word-break:break-hangul;layout-grid-mode:both;vertical-align:baseline;mso-pagination:none;text-autospace:none;mso-padding-alt:0pt 0pt 0pt 0pt;mso-ascii-font-family:함초롬바탕;mso-ascii-font-family:함초롬바탕;mso-font-width:100%;letter-spacing:0pt;mso-text-raise:0pt;font-size:10.0pt;color:#000000;mso-font-kerning:0pt;}
p.1
{mso-style-name:"표안";line-height:130%;margin-left:0pt;margin-right:0pt;text-indent:0pt;margin-top:0pt;margin-bottom:0pt;text-align:center;word-break:keep-all;layout-grid-mode:none;vertical-align:baseline;mso-pagination:none;text-autospace:none;mso-padding-alt:0pt 0pt 0pt 0pt;mso-ascii-font-family:신명 중명조;mso-ascii-font-family:한양신명조;mso-font-width:95%;letter-spacing:-0.4pt;mso-text-raise:0pt;font-size:8.0pt;color:#000000;mso-font-kerning:0pt;}
--></style></head><body><!--StartFragment--><p class="0" style="mso-pagination:none;text-autospace:none;mso-padding-alt:0pt 0pt 0pt 0pt;">

알고리즘별 성능 지표
--
  | 정확도(Accuracy) | 정밀도(Precision) | 재현율(Recall) | F1-Score
  | 평균(%) | 표준편차(%) | 평균(%) | 표준편차(%) | 평균(%) | 표준편차(%) | 평균(%) | 표준편차(%)
SVM | 27.4898 | 00.8317 | 22.9225 | 01.6635 | 26.9726 | 00.8706 | 19.8921 | 01.0549
DecisionTree | 87.5102 | 01.7191 | 87.7607 | 01.6485 | 87.5061 | 01.7269 | 87.5405 | 01.7210
RandomForest | 95.2653 | 00.8649 | 95.3903 | 00.8264 | 95.2704 | 00.8729 | 95.2891 | 00.8634
ExtraTrees | 95.0612 | 01.1058 | 95.1549 | 01.0731 | 95.0618 | 01.1161 | 95.0716 | 01.1110

</p><div id='hwpEditorBoardContent' class='hwp_editor_board_content' data-hjsonver='1.0' data-jsonlen='48022'><!--[data-hwpjson]{
"documentPr": {
"di": "",
"dp": {
"dn": "test.hwp",
"ta": 1,
"d1": 5,
"d2": 1,
"dv": 0,
"dr": 1,
"do": 1,
"vj": "1.1",
"an": "Hancom Office Hangul",
"av": "11, 0, 0, 2129",
"ao": "WIN",
"ab": "32",
"ar": "LE",
"as": "Windows_8"
},
"dis": false,
"ds": {
"ti": "",
"la": "ko",
"cr": "",
"su": "",
"de": "",
"cd": "2022-11-08T11:16:53.170Z",
"md": "1601-01-01T09:00:00.000Z",
"pd": "1601-01-01T09:00:00.000Z",
"ke": ""
}
},
"dh": {
"do": {
"pa": 1,
"fo": 1,
"en": 1,
"pi": 1,
"tb": 1,
"eq": 1
},
"fo": [ ],
"cd": {
"tp": 0,
"lc": {
"af": false,
"ui": false,
"fu": false,
"dn": false,
"ul": false,
"el": false,
"at": false,
"tq": false,
"da": false,
"dw": false,
"dj": false,
"bc": false,
"bu": false,
"al": false,
"ab": false,
"ap": false,
"an": false,
"aa": false,
"ds": false,
"de": false,
"as": false,
"cp": false,
"ao": false,
"et": false,
"ay": false,
"am": false,
"a1": false,
"bt": false,
"av": false,
"dh": false,
"dp": false,
"d1": false,
"mf": false,
"bl": false,
"ag": false,
"dg": false,
"ae": false,
"df": false,
"do": false,
"dl": false,
"di": false,
"d2": false,
"d3": false,
"ob": false,
"d4": false,
"ev": false,
"d5": false,
"d6": false,
"a2": false,
"dc": false
}
},
"ld": {
"pa": "",
"pi": true,
"fo": false
}
},
"bf": {
"01D8F3182B4E35200000009D": {
"id": 1,
"td": false,
"sh": false,
"st": 0,
"sc": 0,
"si": false,
"bt": 0,
"bi": false,
"cl": 0,
"bc": false,
"lt": 0,
"lw": 0,
"lc": 0,
"rt": 0,
"rw": 0,
"rc": 0,
"tt": 0,
"tw": 0,
"tc": 0,
"bbt": 0,
"bbw": 0,
"bbc": 0,
"dt": 1,
"dw": 0,
"dc": 0,
"fi": { }
},
"01D8F3182B4E35200000009E": {
"id": 2,
"td": false,
"sh": false,
"st": 0,
"sc": 0,
"si": false,
"bt": 0,
"bi": false,
"cl": 0,
"bc": false,
"lt": 0,
"lw": 0,
"lc": 0,
"rt": 0,
"rw": 0,
"rc": 0,
"tt": 0,
"tw": 0,
"tc": 0,
"bbt": 0,
"bbw": 0,
"bbc": 0,
"dt": 1,
"dw": 0,
"dc": 0,
"fi": {
"wb": {
"fc": 4294967295,
"hc": 4278190080,
"al": 0,
"hs": -1
}
}
},
"01D8F3182B4E35200000009F": {
"id": 3,
"td": false,
"sh": false,
"st": 0,
"sc": 0,
"si": false,
"bt": 0,
"bi": false,
"cl": 0,
"bc": false,
"lt": 1,
"lw": 1,
"lc": 0,
"rt": 1,
"rw": 1,
"rc": 0,
"tt": 1,
"tw": 1,
"tc": 0,
"bbt": 1,
"bbw": 1,
"bbc": 0,
"dt": 0,
"dw": 0,
"dc": 0,
"fi": { }
},
"01D8F3182B4E3520000000A0": {
"id": 4,
"td": false,
"sh": false,
"st": 0,
"sc": 0,
"si": false,
"bt": 0,
"bi": false,
"cl": 0,
"bc": false,
"lt": 1,
"lw": 1,
"lc": 0,
"rt": 1,
"rw": 1,
"rc": 0,
"tt": 1,
"tw": 1,
"tc": 0,
"bbt": 1,
"bbw": 1,
"bbc": 0,
"dt": 1,
"dw": 1,
"dc": 0,
"fi": {
"wb": {
"fc": 11711154,
"hc": 10066329,
"al": 0,
"hs": -1
}
}
},
"01D8F3182B4E3520000000A1": {
"id": 5,
"td": false,
"sh": false,
"st": 0,
"sc": 0,
"si": false,
"bt": 0,
"bi": false,
"cl": 0,
"bc": false,
"lt": 1,
"lw": 1,
"lc": 0,
"rt": 1,
"rw": 1,
"rc": 0,
"tt": 1,
"tw": 1,
"tc": 0,
"bbt": 1,
"bbw": 1,
"bbc": 0,
"dt": 1,
"dw": 1,
"dc": 0,
"fi": { }
},
"01D8F3182B4E5C30000000A2": {
"id": 6,
"td": false,
"sh": false,
"st": 0,
"sc": 0,
"si": false,
"bt": 0,
"bi": false,
"cl": 0,
"bc": false,
"lt": 0,
"lw": 0,
"lc": 0,
"rt": 0,
"rw": 0,
"rc": 0,
"tt": 0,
"tw": 0,
"tc": 0,
"bbt": 0,
"bbw": 0,
"bbc": 0,
"dt": 1,
"dw": 0,
"dc": 0,
"fi": {
"wb": {
"fc": 4294967295,
"hc": 0,
"al": 0,
"hs": -1
}
}
}
},
"cp": {
"01D8F3182B4E5C30000000A3": {
"id": 0,
"he": 1000,
"tc": 0,
"sc": 4294967295,
"uf": false,
"uk": false,
"sm": 0,
"bf": "01D8F3182B4E35200000009D",
"f1": "한컴바탕",
"t1": 1,
"f2": "한컴바탕",
"t2": 1,
"f3": "함초롬바탕",
"t3": 1,
"f4": "한컴바탕",
"t4": 1,
"f5": "한컴바탕",
"t5": 1,
"f6": "한컴바탕",
"t6": 1,
"f7": "한컴바탕",
"t7": 1,
"r1": 100,
"r2": 100,
"r3": 100,
"r4": 100,
"r5": 100,
"r6": 100,
"r7": 100,
"s1": 0,
"s2": 0,
"s3": 0,
"s4": 0,
"s5": 0,
"s6": 0,
"s7": 0,
"e1": 100,
"e2": 100,
"e3": 100,
"e4": 100,
"e5": 100,
"e6": 100,
"e7": 100,
"o1": 0,
"o2": 0,
"o3": 0,
"o4": 0,
"o5": 0,
"o6": 0,
"o7": 0,
"it": false,
"bo": false,
"ut": 0,
"us": 1,
"uc": 0,
"st": false,
"ss": 1,
"so": 0,
"ot": 0,
"ht": 0,
"hc": 0,
"hx": 0,
"hy": 0,
"em": false,
"en": false,
"su": false,
"sb": false
},
"01D8F3182B4E5C30000000A4": {
"id": 1,
"he": 1000,
"tc": 0,
"sc": 4294967295,
"uf": false,
"uk": false,
"sm": 0,
"bf": "01D8F3182B4E35200000009E",
"f1": "함초롬바탕",
"t1": 1,
"f2": "함초롬바탕",
"t2": 1,
"f3": "함초롬바탕",
"t3": 1,
"f4": "함초롬바탕",
"t4": 1,
"f5": "함초롬바탕",
"t5": 1,
"f6": "함초롬바탕",
"t6": 1,
"f7": "함초롬바탕",
"t7": 1,
"r1": 100,
"r2": 100,
"r3": 100,
"r4": 100,
"r5": 100,
"r6": 100,
"r7": 100,
"s1": 0,
"s2": 0,
"s3": 0,
"s4": 0,
"s5": 0,
"s6": 0,
"s7": 0,
"e1": 100,
"e2": 100,
"e3": 100,
"e4": 100,
"e5": 100,
"e6": 100,
"e7": 100,
"o1": 0,
"o2": 0,
"o3": 0,
"o4": 0,
"o5": 0,
"o6": 0,
"o7": 0,
"it": false,
"bo": false,
"ut": 0,
"us": 1,
"uc": 0,
"st": false,
"ss": 1,
"so": 0,
"ot": 0,
"ht": 0,
"hc": 0,
"hx": 0,
"hy": 0,
"em": false,
"en": false,
"su": false,
"sb": false
},
"01D8F3182B4E5C30000000A5": {
"id": 2,
"he": 800,
"tc": 0,
"sc": 4294967295,
"uf": false,
"uk": false,
"sm": 0,
"bf": "01D8F3182B4E35200000009E",
"f1": "신명 중고딕",
"t1": 2,
"f2": "신명 중고딕",
"t2": 2,
"f3": "신명 중고딕",
"t3": 2,
"f4": "신명 중고딕",
"t4": 2,
"f5": "한양신명조",
"t5": 2,
"f6": "한양중고딕",
"t6": 2,
"f7": "명조",
"t7": 2,
"r1": 95,
"r2": 95,
"r3": 95,
"r4": 95,
"r5": 95,
"r6": 95,
"r7": 95,
"s1": -5,
"s2": -5,
"s3": -5,
"s4": -5,
"s5": -5,
"s6": -5,
"s7": -5,
"e1": 100,
"e2": 100,
"e3": 100,
"e4": 100,
"e5": 100,
"e6": 100,
"e7": 100,
"o1": 0,
"o2": 0,
"o3": 0,
"o4": 0,
"o5": 0,
"o6": 0,
"o7": 0,
"it": false,
"bo": true,
"ut": 0,
"us": 1,
"uc": 0,
"st": false,
"ss": 1,
"so": 0,
"ot": 0,
"ht": 0,
"hc": 0,
"hx": 0,
"hy": 0,
"em": false,
"en": false,
"su": false,
"sb": false
},
"01D8F3182B4E5C30000000A6": {
"id": 3,
"he": 800,
"tc": 0,
"sc": 4294967295,
"uf": false,
"uk": false,
"sm": 0,
"bf": "01D8F3182B4E35200000009E",
"f1": "신명 중명조",
"t1": 2,
"f2": "신명 중명조",
"t2": 2,
"f3": "신명 중명조",
"t3": 2,
"f4": "신명 신명조",
"t4": 2,
"f5": "한양신명조",
"t5": 2,
"f6": "한양신명조",
"t6": 2,
"f7": "명조",
"t7": 2,
"r1": 95,
"r2": 95,
"r3": 95,
"r4": 95,
"r5": 95,
"r6": 95,
"r7": 95,
"s1": -5,
"s2": -5,
"s3": -5,
"s4": -5,
"s5": -5,
"s6": -5,
"s7": -5,
"e1": 100,
"e2": 100,
"e3": 100,
"e4": 100,
"e5": 100,
"e6": 100,
"e7": 100,
"o1": 0,
"o2": 0,
"o3": 0,
"o4": 0,
"o5": 0,
"o6": 0,
"o7": 0,
"it": false,
"bo": false,
"ut": 0,
"us": 1,
"uc": 0,
"st": false,
"ss": 1,
"so": 0,
"ot": 0,
"ht": 0,
"hc": 0,
"hx": 0,
"hy": 0,
"em": false,
"en": false,
"su": false,
"sb": false
},
"01D8F3182B4E5C30000000A7": {
"id": 4,
"he": 800,
"tc": 0,
"sc": 4294967295,
"uf": false,
"uk": false,
"sm": 0,
"bf": "01D8F3182B4E35200000009D",
"f1": "신명 중명조",
"t1": 2,
"f2": "신명 중명조",
"t2": 2,
"f3": "신명 중명조",
"t3": 2,
"f4": "신명 신명조",
"t4": 2,
"f5": "한양신명조",
"t5": 2,
"f6": "한양신명조",
"t6": 2,
"f7": "명조",
"t7": 2,
"r1": 95,
"r2": 95,
"r3": 95,
"r4": 95,
"r5": 95,
"r6": 95,
"r7": 95,
"s1": -4,
"s2": -4,
"s3": -4,
"s4": -4,
"s5": -4,
"s6": -4,
"s7": -4,
"e1": 100,
"e2": 100,
"e3": 100,
"e4": 100,
"e5": 100,
"e6": 100,
"e7": 100,
"o1": 0,
"o2": 0,
"o3": 0,
"o4": 0,
"o5": 0,
"o6": 0,
"o7": 0,
"it": false,
"bo": false,
"ut": 0,
"us": 1,
"uc": 0,
"st": false,
"ss": 1,
"so": 0,
"ot": 0,
"ht": 0,
"hc": 0,
"hx": 0,
"hy": 0,
"em": false,
"en": false,
"su": false,
"sb": false
},
"01D8F3182B4E5C30000000A8": {
"id": 5,
"he": 800,
"tc": 0,
"sc": 4294967295,
"uf": false,
"uk": false,
"sm": 0,
"bf": "01D8F3182B4E35200000009D",
"f1": "신명 중고딕",
"t1": 2,
"f2": "신명 중고딕",
"t2": 2,
"f3": "신명 중고딕",
"t3": 2,
"f4": "신명 중고딕",
"t4": 2,
"f5": "한양신명조",
"t5": 2,
"f6": "한양중고딕",
"t6": 2,
"f7": "명조",
"t7": 2,
"r1": 95,
"r2": 95,
"r3": 95,
"r4": 95,
"r5": 95,
"r6": 95,
"r7": 95,
"s1": -4,
"s2": -4,
"s3": -4,
"s4": -4,
"s5": -4,
"s6": -4,
"s7": -4,
"e1": 100,
"e2": 100,
"e3": 100,
"e4": 100,
"e5": 100,
"e6": 100,
"e7": 100,
"o1": 0,
"o2": 0,
"o3": 0,
"o4": 0,
"o5": 0,
"o6": 0,
"o7": 0,
"it": false,
"bo": false,
"ut": 0,
"us": 1,
"uc": 0,
"st": false,
"ss": 1,
"so": 0,
"ot": 0,
"ht": 0,
"hc": 0,
"hx": 0,
"hy": 0,
"em": false,
"en": false,
"su": false,
"sb": false
}
},
"tp": {
"01D8F3182B4E5C30000000A9": {
"id": 0,
"al": false,
"ar": false,
"tp": [ ]
},
"01D8F3182B4E5C30000000AA": {
"id": 1,
"al": false,
"ar": false,
"tp": [
{
"po": 3840,
"ty": 0,
"le": 0
},
{
"po": 6360,
"ty": 0,
"le": 0
},
{
"po": 7320,
"ty": 0,
"le": 0
},
{
"po": 8760,
"ty": 0,
"le": 0
},
{
"po": 46320,
"ty": 0,
"le": 0
}
]
},
"01D8F3182B4E5C30000000AB": {
"id": 2,
"al": false,
"ar": false,
"tp": [
{
"po": 3840,
"ty": 0,
"le": 0
},
{
"po": 6360,
"ty": 0,
"le": 0
},
{
"po": 7320,
"ty": 0,
"le": 0
},
{
"po": 8760,
"ty": 0,
"le": 0
},
{
"po": 46320,
"ty": 0,
"le": 0
}
]
}
},
"nu": { },
"bu": { },
"pp": {
"01D8F3182B4E5C30000000AC": {
"id": 0,
"ah": 0,
"av": 0,
"ht": 0,
"hi": "",
"hl": 0,
"tp": "01D8F3182B4E5C30000000A9",
"kb": 0,
"kn": true,
"ko": false,
"kk": false,
"kl": false,
"kp": false,
"kw": 0,
"co": 0,
"fl": false,
"st": true,
"sl": false,
"ae": false,
"aa": false,
"mi": 0,
"ml": 0,
"mr": 0,
"mp": 0,
"mn": 0,
"lt": 0,
"lv": 160,
"bf": "01D8F3182B4E35200000009D",
"bl": 0,
"br": 0,
"bt": 0,
"bb": 0,
"bc": false,
"bi": false
},
"01D8F3182B4E5C30000000AD": {
"id": 1,
"ah": 3,
"av": 0,
"ht": 0,
"hi": "",
"hl": 0,
"tp": "01D8F3182B4E5C30000000AA",
"kb": 0,
"kn": false,
"ko": false,
"kk": false,
"kl": false,
"kp": false,
"kw": 0,
"co": 0,
"fl": false,
"st": false,
"sl": false,
"ae": false,
"aa": false,
"mi": 0,
"ml": 0,
"mr": 0,
"mp": 0,
"mn": 0,
"lt": 0,
"lv": 130,
"bf": "01D8F3182B4E35200000009E",
"bl": 0,
"br": 0,
"bt": 0,
"bb": 0,
"bc": false,
"bi": false
},
"01D8F3182B4E5C30000000AE": {
"id": 2,
"ah": 3,
"av": 0,
"ht": 0,
"hi": "",
"hl": 0,
"tp": "01D8F3182B4E5C30000000A9",
"kb": 0,
"kn": false,
"ko": false,
"kk": false,
"kl": false,
"kp": false,
"kw": 0,
"co": 0,
"fl": false,
"st": false,
"sl": false,
"ae": false,
"aa": false,
"mi": 0,
"ml": 0,
"mr": 0,
"mp": 0,
"mn": 0,
"lt": 0,
"lv": 130,
"bf": "01D8F3182B4E35200000009D",
"bl": 0,
"br": 0,
"bt": 0,
"bb": 0,
"bc": false,
"bi": false
},
"01D8F3182B4E5C30000000AF": {
"id": 3,
"ah": 3,
"av": 0,
"ht": 0,
"hi": "",
"hl": 0,
"tp": "01D8F3182B4E5C30000000A9",
"kb": 0,
"kn": false,
"ko": false,
"kk": false,
"kl": false,
"kp": false,
"kw": 0,
"co": 0,
"fl": false,
"st": false,
"sl": false,
"ae": false,
"aa": false,
"mi": 0,
"ml": 0,
"mr": 0,
"mp": 0,
"mn": 0,
"lt": 0,
"lv": 130,
"bf": "01D8F3182B4E5C30000000A2",
"bl": 0,
"br": 0,
"bt": 0,
"bb": 0,
"bc": false,
"bi": false
},
"01D8F3182B4E5C30000000B0": {
"id": 4,
"ah": 0,
"av": 0,
"ht": 0,
"hi": "",
"hl": 0,
"tp": "01D8F3182B4E5C30000000A9",
"kb": 0,
"kn": true,
"ko": false,
"kk": false,
"kl": false,
"kp": false,
"kw": 0,
"co": 0,
"fl": false,
"st": true,
"sl": false,
"ae": false,
"aa": false,
"mi": 0,
"ml": 0,
"mr": 0,
"mp": 0,
"mn": 0,
"lt": 0,
"lv": 160,
"bf": "01D8F3182B4E35200000009E",
"bl": 0,
"br": 0,
"bt": 0,
"bb": 0,
"bc": false,
"bi": false
},
"01D8F3182B4E5C30000000B1": {
"id": 5,
"ah": 0,
"av": 0,
"ht": 0,
"hi": "",
"hl": 0,
"tp": "01D8F3182B4E5C30000000AB",
"kb": 0,
"kn": true,
"ko": false,
"kk": false,
"kl": false,
"kp": false,
"kw": 0,
"co": 0,
"fl": false,
"st": false,
"sl": false,
"ae": false,
"aa": false,
"mi": 0,
"ml": 0,
"mr": 0,
"mp": 0,
"mn": 0,
"lt": 0,
"lv": 130,
"bf": "01D8F3182B4E35200000009D",
"bl": 0,
"br": 0,
"bt": 0,
"bb": 0,
"bc": false,
"bi": false
}
},
"st": {
"01D8F3182B4E5C30000000B2": {
"id": 0,
"ty": 0,
"na": "바탕글",
"en": "Normal",
"pp": "01D8F3182B4E5C30000000B0",
"cp": "01D8F3182B4E5C30000000A4",
"ns": "01D8F3182B4E5C30000000B2",
"li": 1042,
"lf": false
},
"01D8F3182B4E5C30000000B3": {
"id": 1,
"ty": 0,
"na": "표안",
"en": "",
"pp": "01D8F3182B4E5C30000000AE",
"cp": "01D8F3182B4E5C30000000A7",
"ns": "01D8F3182B4E5C30000000B3",
"li": 1042,
"lf": false
},
"01D8F3182B4E5C30000000B4": {
"id": 2,
"ty": 0,
"na": "그림캡션",
"en": "",
"pp": "01D8F3182B4E5C30000000B1",
"cp": "01D8F3182B4E5C30000000A8",
"ns": "01D8F3182B4E5C30000000B4",
"li": 1042,
"lf": false
}
},
"mp": { },
"ro": {
"hp": "01D8F3182B4E352000000033",
"01D8F3182B4E352000000033": {
"np": "",
"id": 0,
"pp": "01D8F3182B4E5C30000000AC",
"si": "01D8F3182B4E5C30000000B2",
"bf": 3,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A3",
"ch": [
{
"cc": 2,
"ci": 1936024420,
"co": "01D8F3182B4E352000000030"
}
,
{
"cc": 2,
"ci": 1668246628,
"co": "01D8F3182B4E352000000031"
}
,
{
"cc": 11,
"ci": 1952607264,
"co": "01D8F3182B4E352000000032"
}
,
{
"t": ""
}
]
}
]
}
},
"sl": {
"01D8F3182B4E352000000034": {
"co": "01D8F3182B4E352000000032",
"id": 1,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A0",
"ac": 0,
"ar": 0,
"sc": 9,
"sr": 1,
"sw": 45581,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000035"
},
"01D8F3182B4E352000000035": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AE",
"si": "01D8F3182B4E5C30000000B3",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "알고리즘별 성능 지표"
}
]
}
]
}
,
"01D8F3182B4E352000000036": {
"co": "01D8F3182B4E352000000032",
"id": 2,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 0,
"ar": 1,
"sc": 1,
"sr": 1,
"sw": 6808,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000037"
},
"01D8F3182B4E352000000037": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": ""
}
]
}
]
}
,
"01D8F3182B4E352000000038": {
"co": "01D8F3182B4E352000000032",
"id": 3,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 1,
"ar": 1,
"sc": 2,
"sr": 1,
"sw": 9694,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000039"
},
"01D8F3182B4E352000000039": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "정확도(Accuracy)"
}
]
}
]
}
,
"01D8F3182B4E35200000003A": {
"co": "01D8F3182B4E352000000032",
"id": 4,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 3,
"ar": 1,
"sc": 2,
"sr": 1,
"sw": 9694,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E35200000003B"
},
"01D8F3182B4E35200000003B": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "정밀도(Precision)"
}
]
}
]
}
,
"01D8F3182B4E35200000003C": {
"co": "01D8F3182B4E352000000032",
"id": 5,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 5,
"ar": 1,
"sc": 2,
"sr": 1,
"sw": 9694,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E35200000003D"
},
"01D8F3182B4E35200000003D": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "재현율(Recall)"
}
]
}
]
}
,
"01D8F3182B4E35200000003E": {
"co": "01D8F3182B4E352000000032",
"id": 6,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 7,
"ar": 1,
"sc": 2,
"sr": 1,
"sw": 9691,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E35200000003F"
},
"01D8F3182B4E35200000003F": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "F1-Score"
}
]
}
]
}
,
"01D8F3182B4E352000000040": {
"co": "01D8F3182B4E352000000032",
"id": 7,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 0,
"ar": 2,
"sc": 1,
"sr": 1,
"sw": 6808,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000041"
},
"01D8F3182B4E352000000041": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": ""
}
]
}
]
}
,
"01D8F3182B4E352000000042": {
"co": "01D8F3182B4E352000000032",
"id": 8,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 1,
"ar": 2,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000043"
},
"01D8F3182B4E352000000043": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "평균(%)"
}
]
}
]
}
,
"01D8F3182B4E352000000044": {
"co": "01D8F3182B4E352000000032",
"id": 9,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 2,
"ar": 2,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000045"
},
"01D8F3182B4E352000000045": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "표준편차(%)"
}
]
}
]
}
,
"01D8F3182B4E352000000046": {
"co": "01D8F3182B4E352000000032",
"id": 10,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 3,
"ar": 2,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000047"
},
"01D8F3182B4E352000000047": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "평균(%)"
}
]
}
]
}
,
"01D8F3182B4E352000000048": {
"co": "01D8F3182B4E352000000032",
"id": 11,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 4,
"ar": 2,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000049"
},
"01D8F3182B4E352000000049": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "표준편차(%)"
}
]
}
]
}
,
"01D8F3182B4E35200000004A": {
"co": "01D8F3182B4E352000000032",
"id": 12,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 5,
"ar": 2,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E35200000004B"
},
"01D8F3182B4E35200000004B": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "평균(%)"
}
]
}
]
}
,
"01D8F3182B4E35200000004C": {
"co": "01D8F3182B4E352000000032",
"id": 13,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 6,
"ar": 2,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E35200000004D"
},
"01D8F3182B4E35200000004D": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "표준편차(%)"
}
]
}
]
}
,
"01D8F3182B4E35200000004E": {
"co": "01D8F3182B4E352000000032",
"id": 14,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 7,
"ar": 2,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E35200000004F"
},
"01D8F3182B4E35200000004F": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "평균(%)"
}
]
}
]
}
,
"01D8F3182B4E352000000050": {
"co": "01D8F3182B4E352000000032",
"id": 15,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 8,
"ar": 2,
"sc": 1,
"sr": 1,
"sw": 4844,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000051"
},
"01D8F3182B4E352000000051": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "표준편차(%)"
}
]
}
]
}
,
"01D8F3182B4E352000000052": {
"co": "01D8F3182B4E352000000032",
"id": 16,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 0,
"ar": 3,
"sc": 1,
"sr": 1,
"sw": 6808,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000053"
},
"01D8F3182B4E352000000053": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "SVM"
}
]
}
]
}
,
"01D8F3182B4E352000000054": {
"co": "01D8F3182B4E352000000032",
"id": 17,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 1,
"ar": 3,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000055"
},
"01D8F3182B4E352000000055": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "27.4898"
}
]
}
]
}
,
"01D8F3182B4E352000000056": {
"co": "01D8F3182B4E352000000032",
"id": 18,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 2,
"ar": 3,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000057"
},
"01D8F3182B4E352000000057": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "00.8317"
}
]
}
]
}
,
"01D8F3182B4E352000000058": {
"co": "01D8F3182B4E352000000032",
"id": 19,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 3,
"ar": 3,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000059"
},
"01D8F3182B4E352000000059": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "22.9225"
}
]
}
]
}
,
"01D8F3182B4E35200000005A": {
"co": "01D8F3182B4E352000000032",
"id": 20,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 4,
"ar": 3,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E35200000005B"
},
"01D8F3182B4E35200000005B": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "01.6635"
}
]
}
]
}
,
"01D8F3182B4E35200000005C": {
"co": "01D8F3182B4E352000000032",
"id": 21,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 5,
"ar": 3,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E35200000005D"
},
"01D8F3182B4E35200000005D": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "26.9726"
}
]
}
]
}
,
"01D8F3182B4E35200000005E": {
"co": "01D8F3182B4E352000000032",
"id": 22,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 6,
"ar": 3,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E35200000005F"
},
"01D8F3182B4E35200000005F": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "00.8706"
}
]
}
]
}
,
"01D8F3182B4E352000000060": {
"co": "01D8F3182B4E352000000032",
"id": 23,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 7,
"ar": 3,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000061"
},
"01D8F3182B4E352000000061": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "19.8921"
}
]
}
]
}
,
"01D8F3182B4E352000000062": {
"co": "01D8F3182B4E352000000032",
"id": 24,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 8,
"ar": 3,
"sc": 1,
"sr": 1,
"sw": 4844,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000063"
},
"01D8F3182B4E352000000063": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "01.0549"
}
]
}
]
}
,
"01D8F3182B4E352000000064": {
"co": "01D8F3182B4E352000000032",
"id": 25,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 0,
"ar": 4,
"sc": 1,
"sr": 1,
"sw": 6808,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000065"
},
"01D8F3182B4E352000000065": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "DecisionTree"
}
]
}
]
}
,
"01D8F3182B4E352000000066": {
"co": "01D8F3182B4E352000000032",
"id": 26,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 1,
"ar": 4,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000067"
},
"01D8F3182B4E352000000067": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "87.5102"
}
]
}
]
}
,
"01D8F3182B4E352000000068": {
"co": "01D8F3182B4E352000000032",
"id": 27,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 2,
"ar": 4,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000069"
},
"01D8F3182B4E352000000069": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "01.7191"
}
]
}
]
}
,
"01D8F3182B4E35200000006A": {
"co": "01D8F3182B4E352000000032",
"id": 28,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 3,
"ar": 4,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E35200000006B"
},
"01D8F3182B4E35200000006B": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "87.7607"
}
]
}
]
}
,
"01D8F3182B4E35200000006C": {
"co": "01D8F3182B4E352000000032",
"id": 29,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 4,
"ar": 4,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E35200000006D"
},
"01D8F3182B4E35200000006D": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "01.6485"
}
]
}
]
}
,
"01D8F3182B4E35200000006E": {
"co": "01D8F3182B4E352000000032",
"id": 30,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 5,
"ar": 4,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E35200000006F"
},
"01D8F3182B4E35200000006F": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "87.5061"
}
]
}
]
}
,
"01D8F3182B4E352000000070": {
"co": "01D8F3182B4E352000000032",
"id": 31,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 6,
"ar": 4,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000071"
},
"01D8F3182B4E352000000071": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "01.7269"
}
]
}
]
}
,
"01D8F3182B4E352000000072": {
"co": "01D8F3182B4E352000000032",
"id": 32,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 7,
"ar": 4,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000073"
},
"01D8F3182B4E352000000073": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "87.5405"
}
]
}
]
}
,
"01D8F3182B4E352000000074": {
"co": "01D8F3182B4E352000000032",
"id": 33,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 8,
"ar": 4,
"sc": 1,
"sr": 1,
"sw": 4844,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000075"
},
"01D8F3182B4E352000000075": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "01.7210"
}
]
}
]
}
,
"01D8F3182B4E352000000076": {
"co": "01D8F3182B4E352000000032",
"id": 34,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 0,
"ar": 5,
"sc": 1,
"sr": 1,
"sw": 6808,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000077"
},
"01D8F3182B4E352000000077": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "RandomForest"
}
]
}
]
}
,
"01D8F3182B4E352000000078": {
"co": "01D8F3182B4E352000000032",
"id": 35,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 1,
"ar": 5,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000079"
},
"01D8F3182B4E352000000079": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "95.2653"
}
]
}
]
}
,
"01D8F3182B4E35200000007A": {
"co": "01D8F3182B4E352000000032",
"id": 36,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 2,
"ar": 5,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E35200000007B"
},
"01D8F3182B4E35200000007B": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "00.8649"
}
]
}
]
}
,
"01D8F3182B4E35200000007C": {
"co": "01D8F3182B4E352000000032",
"id": 37,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 3,
"ar": 5,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E35200000007D"
},
"01D8F3182B4E35200000007D": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "95.3903"
}
]
}
]
}
,
"01D8F3182B4E35200000007E": {
"co": "01D8F3182B4E352000000032",
"id": 38,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 4,
"ar": 5,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E35200000007F"
},
"01D8F3182B4E35200000007F": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "00.8264"
}
]
}
]
}
,
"01D8F3182B4E352000000080": {
"co": "01D8F3182B4E352000000032",
"id": 39,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 5,
"ar": 5,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000081"
},
"01D8F3182B4E352000000081": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "95.2704"
}
]
}
]
}
,
"01D8F3182B4E352000000082": {
"co": "01D8F3182B4E352000000032",
"id": 40,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 6,
"ar": 5,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000083"
},
"01D8F3182B4E352000000083": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "00.8729"
}
]
}
]
}
,
"01D8F3182B4E352000000084": {
"co": "01D8F3182B4E352000000032",
"id": 41,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 7,
"ar": 5,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000085"
},
"01D8F3182B4E352000000085": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "95.2891"
}
]
}
]
}
,
"01D8F3182B4E352000000086": {
"co": "01D8F3182B4E352000000032",
"id": 42,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 8,
"ar": 5,
"sc": 1,
"sr": 1,
"sw": 4844,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000087"
},
"01D8F3182B4E352000000087": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "00.8634"
}
]
}
]
}
,
"01D8F3182B4E352000000088": {
"co": "01D8F3182B4E352000000032",
"id": 43,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 0,
"ar": 6,
"sc": 1,
"sr": 1,
"sw": 6808,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000089"
},
"01D8F3182B4E352000000089": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "ExtraTrees"
}
]
}
]
}
,
"01D8F3182B4E35200000008A": {
"co": "01D8F3182B4E352000000032",
"id": 44,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 1,
"ar": 6,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E35200000008B"
},
"01D8F3182B4E35200000008B": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "95.0612"
}
]
}
]
}
,
"01D8F3182B4E35200000008C": {
"co": "01D8F3182B4E352000000032",
"id": 45,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 2,
"ar": 6,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E35200000008D"
},
"01D8F3182B4E35200000008D": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "01.1058"
}
]
}
]
}
,
"01D8F3182B4E35200000008E": {
"co": "01D8F3182B4E352000000032",
"id": 46,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 3,
"ar": 6,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E35200000008F"
},
"01D8F3182B4E35200000008F": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "95.1549"
}
]
}
]
}
,
"01D8F3182B4E352000000090": {
"co": "01D8F3182B4E352000000032",
"id": 47,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 4,
"ar": 6,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000091"
},
"01D8F3182B4E352000000091": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "01.0731"
}
]
}
]
}
,
"01D8F3182B4E352000000092": {
"co": "01D8F3182B4E352000000032",
"id": 48,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 5,
"ar": 6,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000093"
},
"01D8F3182B4E352000000093": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "95.0618"
}
]
}
]
}
,
"01D8F3182B4E352000000094": {
"co": "01D8F3182B4E352000000032",
"id": 49,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 6,
"ar": 6,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000095"
},
"01D8F3182B4E352000000095": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "01.1161"
}
]
}
]
}
,
"01D8F3182B4E352000000096": {
"co": "01D8F3182B4E352000000032",
"id": 50,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 7,
"ar": 6,
"sc": 1,
"sr": 1,
"sw": 4847,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000097"
},
"01D8F3182B4E352000000097": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "95.0716"
}
]
}
]
}
,
"01D8F3182B4E352000000098": {
"co": "01D8F3182B4E352000000032",
"id": 51,
"td": 0,
"lw": 0,
"va": 1,
"ll": "",
"ln": "",
"tc": {
"he": false,
"hm": false,
"pr": false,
"ed": false,
"di": false,
"bf": "01D8F3182B4E3520000000A1",
"ac": 8,
"ar": 6,
"sc": 1,
"sr": 1,
"sw": 4844,
"sh": 1368,
"ml": 141,
"mr": 141,
"mt": 141,
"mb": 141
},
"hp": "01D8F3182B4E352000000099"
},
"01D8F3182B4E352000000099": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AF",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A6",
"ch": [
{
"t": "01.1110"
}
]
}
]
}
,
"01D8F3182B4E35200000009A": {
"co": "01D8F3182B4E352000000032",
"id": 52,
"td": 0,
"lw": 0,
"va": 0,
"ll": "",
"ln": "",
"ca": {
"si": 2,
"fs": false,
"wi": 8504,
"ga": 852,
"lw": -1
},
"hp": "01D8F3182B4E35200000009B"
},
"01D8F3182B4E35200000009B": {
"np": "01D8F3182B4E35200000009C",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AD",
"si": "01D8F3182B4E5C30000000B2",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A5",
"ch": [
{
"t": "\u003C표 6\u003E 선별된 55개의 특징으로 학습된 각 알고리즘별 분류 성능 지표"
}
]
}
]
},
"01D8F3182B4E35200000009C": {
"np": "",
"id": -2147483648,
"pp": "01D8F3182B4E5C30000000AD",
"si": "01D8F3182B4E5C30000000B4",
"bf": 0,
"ru": [
{
"cp": "01D8F3182B4E5C30000000A5",
"ch": [
{
"t": "\u003CTable 6\u003E Classification Evaluation Metrics for each algorithm learned with 55 selected features"
}
]
}
]
}
},
"cs": {
"01D8F3182B4E352000000030": {
"cc": 2,
"ci": 1936024420,
"td": 0,
"tv": false,
"sc": 1134,
"ts": 8000,
"ms": "",
"os": "",
"gl": 0,
"gc": 0,
"gw": false,
"ns": 0,
"np": 0,
"ni": 0,
"nt": 0,
"ne": 0,
"hh": false,
"hf": false,
"hm": false,
"fb": false,
"hb": false,
"fi": false,
"hi": false,
"hp": false,
"he": false,
"sl": false,
"lr": 0,
"lc": 0,
"ld": 0,
"ls": 0,
"pp": {
"ls": false,
"wi": 59528,
"he": 84188,
"gt": 0,
"ml": 8504,
"mr": 8504,
"mt": 5668,
"mb": 4252,
"mh": 4252,
"mf": 4252,
"mg": 0
},
"fn": {
"at": 0,
"au": "",
"ap": "",
"ac": ")",
"as": false,
"ll": -1,
"lt": 1,
"lw": 1,
"lc": 0,
"sa": 850,
"sb": 567,
"st": 283
,
"nt": 0,
"nn": 1,
"pp": 0,
"pb": false
},
"en": {
"at": 0,
"au": "",
"ap": "",
"ac": ")",
"as": false,
"ll": -4,
"lt": 1,
"lw": 1,
"lc": 0,
"sa": 850,
"sb": 567,
"st": 0
,
"nt": 0,
"nn": 1,
"pp": 0,
"pb": false
},
"pb": [
{
"ty": 0,
"bf": "01D8F3182B4E35200000009D",
"tb": true,
"hi": false,
"fi": false,
"fa": 0,
"ol": 1417,
"or": 1417,
"ot": 1417,
"ob": 1417
},
{
"ty": 1,
"bf": "01D8F3182B4E35200000009D",
"tb": true,
"hi": false,
"fi": false,
"fa": 0,
"ol": 1417,
"or": 1417,
"ot": 1417,
"ob": 1417
},
{
"ty": 2,
"bf": "01D8F3182B4E35200000009D",
"tb": true,
"hi": false,
"fi": false,
"fa": 0,
"ol": 1417,
"or": 1417,
"ot": 1417,
"ob": 1417
}
],
"mp": [ ]
}
,
"01D8F3182B4E352000000031": {
"cc": 2,
"ci": 1668246628,
"ty": 0,
"la": 0,
"co": 1,
"ss": true,
"sg": 0,
"lt": 0,
"lw": 0,
"lc": 0,
"cs": [ ]
}
,
"01D8F3182B4E352000000032": {
"cc": 11,
"ci": 1952607264,
"id": 2126892271,
"zo": 0,
"nt": 2,
"tw": 1,
"tf": 0,
"lo": false,
"swi": 45581,
"she": 9576,
"swr": 4,
"shr": 2,
"spr": false,
"pta": true,
"pal": false,
"pvr": 2,
"phr": 2,
"pva": 0,
"ph1": 0,
"pvo": 0,
"ph2": 0,
"pfw": true,
"pao": false,
"pha": false,
"ole": 0,
"ori": 0,
"oto": 0,
"obo": 0,
"ca": {
"so": "01D8F3182B4E35200000009A",
"li": 52
},
"sc": ""
,
"pb": 0,
"rh": true,
"na": true,
"ho": false,
"if": true,
"sa": false,
"rc": 7,
"cco": 9,
"cs": 0,
"bf": "01D8F3182B4E35200000009F",
"ile": 0,
"iri": 0,
"ito": 284,
"ibo": 284,
"cl": [ ],
"tr": [
[
{
"so": "01D8F3182B4E352000000034",
"li": 1
}
],
[
{
"so": "01D8F3182B4E352000000036",
"li": 2
},
{
"so": "01D8F3182B4E352000000038",
"li": 3
},
{
"so": "01D8F3182B4E35200000003A",
"li": 4
},
{
"so": "01D8F3182B4E35200000003C",
"li": 5
},
{
"so": "01D8F3182B4E35200000003E",
"li": 6
}
],
[
{
"so": "01D8F3182B4E352000000040",
"li": 7
},
{
"so": "01D8F3182B4E352000000042",
"li": 8
},
{
"so": "01D8F3182B4E352000000044",
"li": 9
},
{
"so": "01D8F3182B4E352000000046",
"li": 10
},
{
"so": "01D8F3182B4E352000000048",
"li": 11
},
{
"so": "01D8F3182B4E35200000004A",
"li": 12
},
{
"so": "01D8F3182B4E35200000004C",
"li": 13
},
{
"so": "01D8F3182B4E35200000004E",
"li": 14
},
{
"so": "01D8F3182B4E352000000050",
"li": 15
}
],
[
{
"so": "01D8F3182B4E352000000052",
"li": 16
},
{
"so": "01D8F3182B4E352000000054",
"li": 17
},
{
"so": "01D8F3182B4E352000000056",
"li": 18
},
{
"so": "01D8F3182B4E352000000058",
"li": 19
},
{
"so": "01D8F3182B4E35200000005A",
"li": 20
},
{
"so": "01D8F3182B4E35200000005C",
"li": 21
},
{
"so": "01D8F3182B4E35200000005E",
"li": 22
},
{
"so": "01D8F3182B4E352000000060",
"li": 23
},
{
"so": "01D8F3182B4E352000000062",
"li": 24
}
],
[
{
"so": "01D8F3182B4E352000000064",
"li": 25
},
{
"so": "01D8F3182B4E352000000066",
"li": 26
},
{
"so": "01D8F3182B4E352000000068",
"li": 27
},
{
"so": "01D8F3182B4E35200000006A",
"li": 28
},
{
"so": "01D8F3182B4E35200000006C",
"li": 29
},
{
"so": "01D8F3182B4E35200000006E",
"li": 30
},
{
"so": "01D8F3182B4E352000000070",
"li": 31
},
{
"so": "01D8F3182B4E352000000072",
"li": 32
},
{
"so": "01D8F3182B4E352000000074",
"li": 33
}
],
[
{
"so": "01D8F3182B4E352000000076",
"li": 34
},
{
"so": "01D8F3182B4E352000000078",
"li": 35
},
{
"so": "01D8F3182B4E35200000007A",
"li": 36
},
{
"so": "01D8F3182B4E35200000007C",
"li": 37
},
{
"so": "01D8F3182B4E35200000007E",
"li": 38
},
{
"so": "01D8F3182B4E352000000080",
"li": 39
},
{
"so": "01D8F3182B4E352000000082",
"li": 40
},
{
"so": "01D8F3182B4E352000000084",
"li": 41
},
{
"so": "01D8F3182B4E352000000086",
"li": 42
}
],
[
{
"so": "01D8F3182B4E352000000088",
"li": 43
},
{
"so": "01D8F3182B4E35200000008A",
"li": 44
},
{
"so": "01D8F3182B4E35200000008C",
"li": 45
},
{
"so": "01D8F3182B4E35200000008E",
"li": 46
},
{
"so": "01D8F3182B4E352000000090",
"li": 47
},
{
"so": "01D8F3182B4E352000000092",
"li": 48
},
{
"so": "01D8F3182B4E352000000094",
"li": 49
},
{
"so": "01D8F3182B4E352000000096",
"li": 50
},
{
"so": "01D8F3182B4E352000000098",
"li": 51
}
]
]
}
},
"bi": [ ],
"bidt": { }
}--></div><!--EndFragment--></body></html>


![image](https://user-images.githubusercontent.com/46625602/199924398-4cc731c9-cdf8-4fb3-93bf-78586b83b02e.png)
![image](https://user-images.githubusercontent.com/46625602/199923856-474b5625-34bd-4369-9ae9-01712ab5946d.png)
