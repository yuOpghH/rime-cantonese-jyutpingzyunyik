# 粵語廣東話 粵拼轉譯羅馬字(拉丁化)/注音/諺文/ rime-cantonese-jyutpingzyunyik
Cantonese Base rime use Jyutping convert to Romanization / hangul / Zyujam(zhuyin/Bopomofo)

基於RIME依賴[jyut6ping3](https://github.com/rime/rime-cantonese)使用粵拼轉譯輸出羅馬字(拉丁化)/注音/諺文。

注意！注意！注意！並不是以”羅馬字/注音/諺文 輸出=> 漢字粵文“ ，而是”粵拼=>羅馬字/注音/諺文 化的粵文“

有乜嘢用？好玩囉！

(可能有誤，望見諒)

<p align="center">
<img src="https://github.com/yuOpghH/rime-cantonese-jyutpingzyunyik/blob/main/test01.jpg"  style="width:300px;"/>
</p>
<p align="center">
<img src="https://github.com/yuOpghH/rime-cantonese-jyutpingzyunyik/blob/main/test4.gif"  style="width:400px;"/>
</p>

 ## 使用

 - pc windows rime
   - 下載安裝[Rime](https://rime.im/)，下載[本方案](https://github.com/yuOpghH/rime-cantonese-jyutpingzyunyik/releases/tag/1.0)，部署到“用户文件夾”，“輸入法設定”選中本方案，部署即可

 - 新增快速鍵`shift+space`，輸出時便於可用單手上屏，亦可使用RIME預設之`ctrl+shift+enter`、`shift+enter`上屏
 - 諺文和注音方案擊打粵拼碼後，可使用\`鍵，切換至“無聲調”模式。

## 羅馬字

jyut6ping3-lomaazi.schema 基於Telegram交流谷rime_cantonese的用户Lanihu Tamasulasan羅馬字注音方案

## 注音

jyut6ping3-zyujam.schema

基於[國民政府注音方案](https://zh.wikipedia.org/zh-hk/%E7%B2%B5%E8%AA%9E%E6%B3%A8%E9%9F%B3%E7%AC%A6%E8%99%9F)+音調標記採用一腦方案

￥eo  サoe兩音分別使用兩字符分開標記

## 諺文

jyut6ping3-hangul

非標準。基於知乎用户[荷達-粵語諺文方案](https://www.zhihu.com/question/27563380/answer/123653538)。

優點在於：挪用gwㄲ kwㄸ  wㅆ zㅈ jㅉ ㅓa ㅔai ㅏaa ㅐㅁai ㅕeo ㅑoe  即在範圍內字符情況下覆蓋粵文

## 展示


| 漢字粵文 | 漢◯混寫 | O化粵文 | 
| :------- | :------ | :------- | 
| 漢羅混寫 | 漢lò混寫 | hón-lò-wạn-sẻ
| 漢注混寫 | 漢ㄗㄩˋ混寫 | ㄏ干ˋㄗㄩˋㄨㇵㄋˎㄙㄝˊ
| 漢諺混寫 | 漢찐ˎ混寫 | 혼ˋ찐ˎ썬ˎ스ˊ

| 人皆生而平等，享有造物主賦予給他們的不可剝奪的權利，包括生命、自由和追求幸福的權利 
| :------- | 
| jàn-gaai sang-jì-pìng-dảng ，hỏeng-jãu zọu-mạt-zyủ fú-jyũ kap taa-mùn dik bat-hỏ-mok-dyụt dik kyùn-lẹi ，baau-kút sang-mịng、zị-jàu wò zeoi-kàu hạng-fuk dik kyùn-lẹi 
| 一ㇵㄋˏ ㄍㄞˉ ㄙㇵㄥˉ一ˏㄆㄧㄥˏㄉㇵㄥˊ，ㄏサㄥˊ一ㇵㄨ˘ ㄗㄡˎㄇㇵㄊˎㄗㄩˊ ㄈㄨˋ一ㄩ˘ ㄎㇵㄆˉ ㄊㄚˉㄇㄨㄣˏ ㄉㄧㄎˉ ㄅㇵㄊˉㄏㄛˊㄇㄛㄎˉㄉㄩㄊˎ ㄉㄧㄎˉ ㄎㄩㄣˏㄌㄟˎㄅㄠˉㄎㄨㄊˋ ㄙㇵㄥˉㄇㄧㄥˎ、ㄗㄧˊ一ㇵㄨ˘ ㄨㄛˏ ㄗ￥ㄧˉㄎㇵㄨˏ ㄏㇵㄥˎㄈㄨㄎˉ ㄉㄧㄎˉ ㄎㄩㄣˏㄌㄟˎ 
| 쩐ˏ 개ˉ 성ˉ찌ˏ핑ˏ덩ˊ ，향ˊ쩔˘ 졸ˎ먿ˎ쥬ˊ 뿌ˉ쮸ˎ 컵ˉ 타ˉ문ˏ 딕ˉ 벋ˉ호ˊ목ˉ듇ˎ 딕ˉ 큔ˏ릐ˎ ， 발ˉ쿧ˋ 성ˉ밍ˎ 、지ˊ쩔˘ 쏘ˏ 졔ˉ컬ˏ 헝ˎ뿍ˉ 딕ˉ 큔ˏ릐ˎ


## 致謝


- 感謝以下項目的無私貢獻及項目成果。可能有遺漏敬請原諒。
  - 粵拼方案來源 [Rime 粵語拼音方案](https://github.com/rime/rime-cantonese)
 


