# UTAU TL式客語擴充方案

## 大綱
* [介紹](#介紹)
* [中文主體](#中文主體)
* [客語擴充](#客語擴充)

## 介紹
* 歌声合成ツールUTAU，是由飴屋／菖蒲氏開發的免費歌聲合成軟體。特色在於可由使用者自行錄製聲音庫後讓UTAU發出該聲音。完整的聲音庫便能唱出所謂虛擬歌手的歌聲。
* 有鑑於客語在台灣的使用率越來越低，為了保存客語，秉持著實驗精神，開發UTAU的客語擴充方案。
* 客語相較於台語，和中文的重疊率更高。在經過多次嘗試後，將客語作為中文CVVC的擴充方案呈現。
* 本文的主要對象為對UTAU中文CVVC方案具有一定熟悉度者；若是熟悉客語或對客語有興趣，但未曾接觸過UTAU的人會較為吃力。
* 本專案提供內容：
    * 8字Oremo用guide BGM
    * 中文錄音表
    * 客語錄音表
    * 客語oto模板(未完成)
    * Oremo用的typelist.txt

## 中文主體
主體為哈魯魯大大開發的中文CVVC方案，TL方案所使用的預設中文為8字錄音表。
<br>因客語僅作為擴充方案呈現，故中文主體使用的錄音表不會影響客語的錄音表。
<br>在此提供哈魯魯大大的UTAU教學(教程)網站：https://utaujc.jimdofree.com/hr-j-cvvc/
<br>對UTAU有興趣的新手可以觀看教學。
<br>最新版或是舊版的中文CVVC也可至哈魯魯大大的UTAU教學(教程)網站尋找。

* **中文錄音須知**
<br>哈魯魯大大使用的中文CVVC是以大陸的口音為主，在錄音的時候須注意配合大陸的口音錄製。
<br>考量到此點，會在下一段介紹客語擴充方案下的台灣口音。

* **中文使用拼音表**
<br>和注音不同，大陸所使用的為拼音，此處將介紹大陸的拼音音表。
<br>在此會以注音符號表示大陸的口音呈現。
<br>拼音表和UTAU 中文CVVC使用的聲音符號未必相同，需要注意。

<table>
    <tr>
        <td colspan="8">聲母</td>
    <tr>
        <td>ㄅ</td><td>ㄆ</td><td>ㄇ</td><td>ㄈ</td>
        <td>ㄉ</td><td>ㄊ</td><td>ㄋ</td><td>ㄌ</td>
    <tr>
        <td>b</td><td>p</td><td>m</td><td>f</td>
        <td>d</td><td>t</td><td>n</td><td>l</td>
    <tr>
        <td>ㄍ</td><td>ㄎ</td><td>ㄏ</td><td>ㄐ</td>
        <td>ㄑ</td><td>ㄒ</td><td></td><td></td>
    <tr>
        <td>g</td><td>k</td><td>h</td><td>j</td>
        <td>q</td><td>x</td><td></td><td></td>
    <tr>
        <td>ㄓ</td><td>ㄔ</td><td>ㄕ</td><td>ㄖ</td>
        <td>ㄗ</td><td>ㄘ</td><td>ㄙ</td><td></td>
    <tr>
        <td>zh</td><td>ch</td><td>sh</td><td>r</td>
        <td>z</td><td>c</td><td>s</td><td></td>
    <tr>
        <td colspan="8"></td>
    <tr>
        <td colspan="8">介音</td>
    <tr>
        <td>ㄧ</td><td>ㄨ</td><td>ㄩ</td><td></td>
        <td></td><td></td><td></td><td></td>
    <tr>
        <td>yi</td><td>wu</td><td>yu</td><td></td>
        <td></td><td></td><td></td><td></td>
    <tr>
        <td colspan="8"></td>
    <tr>
        <td colspan="8">韻母</td>
    <tr>
        <td>ㄚ</td><td>ㄛ</td><td>ㄜ</td><td>ㄝ</td>
        <td>ㄞ</td><td>ㄟ</td><td>ㄠ</td><td>ㄡ</td>
    <tr>
        <td>a</td><td>o</td><td>e</td><td>e</td>
        <td>ai</td><td>ei</td><td>ao</td><td>ou</td>
    <tr>
        <td>ㄢ</td><td>ㄣ</td><td>ㄤ</td><td>ㄥ</td>
        <td>ㄦ</td><td></td><td></td><td></td>
    <tr>
        <td>an</td><td>en</td><td>ang</td><td>eng</td>
        <td>er</td><td></td><td></td><td></td>
    <tr>
        <td colspan="8"></td>
    <tr>
        <td colspan="8">複韻母</td>
    <tr>
        <td>ㄧㄚ</td><td>ㄧㄝ</td><td>ㄧㄞ</td><td>ㄧㄠ</td>
        <td>ㄧㄡ</td><td>ㄧㄢ</td><td>ㄧㄣ</td><td>ㄧㄤ</td>
    <tr>
        <td>ya</td><td>ye</td><td>yai</td><td>yao</td>
        <td>you</td><td>yan</td><td>yin</td><td>yang</td>
    <tr>
        <td>ㄧㄥ</td><td></td><td></td><td></td>
        <td></td><td></td><td></td><td></td>
    <tr>
        <td>ying</td><td></td><td></td><td></td>
        <td></td><td></td><td></td><td></td>
    <tr>
        <td>ㄨㄚ</td><td>ㄨㄛ</td><td>ㄨㄞ</td><td>ㄨㄟ</td>
        <td>ㄨㄢ</td><td>ㄨㄣ</td><td>ㄨㄤ</td><td>ㄨㄥ</td>
    <tr>
        <td>wa</td><td>wo</td><td>wai</td><td>wei</td>
        <td>wan</td><td>wen</td><td>wang</td><td>weng</td>
    <tr>
        <td>ㄩㄝ</td><td>ㄩㄢ</td><td>ㄩㄣ</td><td>ㄩㄥ</td>
        <td></td><td></td><td></td><td></td>
    <tr>
        <td>yue</td><td>yuan</td><td>yun</td><td>yong</td>
        <td></td><td></td><td></td><td></td>
    </tr>

</table>

* **註記**
<br>※ ㄖ的大陸口音會有點像英文的Z的發音(平音)，在此以台灣口音(捲舌音)錄製即可。
<br>※ (聲母)ㄧㄡ雖然拼音是記-iu，但發音是-i(o)u。
<br>※ ㄨㄥ需以大陸口音的ㄨ(ㄜ)ㄥ錄製，台灣的口音是ㄨ(ㄛ)ㄥ。
<br>※ ㄅㄥ需以ㄅ(ㄜ)ㄥ錄製，台灣的口音是ㄅ(ㄛ)ㄥ。
<br>※ (聲母)ㄨㄟ是記成(-)ui錄製，但錄音時發uei即可。
<br>※ 單獨寫ㄓㄔㄕㄖㄗㄘㄙ的拼音時，會記成zhi, chi, shi, ri, zi, ci, si。

* **拆音方式**
<br>UTAU CVVC需要透過拆音方式達成歌聲上較自然的銜接。
    * 在各個音(CV)之間以(VC)銜接。
    * 範例：茉莉花：| mo | (o l) | li | (i h) | hua |
    * 詳細的UTAU CVVC教學可至哈魯魯的教學網站觀看。

## 客語擴充
考量中文口音的主體並檢視台灣客家語拼音方案後，提出了客語的TL式擴充方案。而在UTAU中欲使用的客語音素如下：
<table>
    <tr>
        <td colspan="8">濁聲母</td>
    <tr>
        <td colspan="2">ㄅ濁音</td><td colspan="2">ㄈ濁音</td><td colspan="2">ㄋ濁音</td><td colspan="2">ㄖ平音</td>
    <tr>
        <td colspan="2">bb</td><td colspan="2">ff</td><td colspan="2">nn</td><td  colspan="2">rr</td>
    <tr>
        <td colspan="8"></td>
    <tr>
        <td colspan="8">複韻母</td>
    <tr>
        <td colspan="2">ㄢ(ㄇ)</td><td colspan="2">ㄝ(ㄣ)</td><td colspan="2">ㄣ(ㄇ)</td><td colspan="2">ㄝ(ㄣ)ㄇ</td>
    <tr>
        <td colspan="2">am</td><td colspan="2">en0</td><td colspan="2">em</td><td  colspan="2">em0</td>
    <tr>
        <td colspan="2">ㄧ(ㄨ)</td><td colspan="2">ㄧ(ㄣ)ㄇ</td><td colspan="2">ㄛ(ㄣ)</td><td colspan="2">ㄛ(ㄣ)ㄇ</td>
    <tr>
        <td colspan="2">iu0</td><td colspan="2">im</td><td colspan="2">on</td><td  colspan="2">om</td>
    <tr>
        <td colspan="2">ㄨㄧ</td><td colspan="2">ㄨ(ㄨ)ㄣ</td><td colspan="2">ㄨ(ㄜㄣ)ㄇ</td><td  colspan="2">ㄨ(ㄨㄣ)ㄇ</td>
    <tr>
        <td colspan="2">ui0</td><td colspan="2">un0</td><td colspan="2">um</td><td colspan="2">um0</td>
    <tr>
        <td colspan="2">ㄛㄧ</td><td colspan="2">ㄧㄛ</td><td colspan="2">ㄨ(ㄜ)ㄥ</td><td colspan="2"></td>
    <tr>
        <td colspan="2">oi</td><td colspan="2">io</td><td colspan="2">ung</td><td colspan="2"></td>
    <tr>
        <td colspan="8"></td>
    <tr>
        <td colspan="8">鼻音</td>
    <tr>
        <td></td><td></td><td></td><td></td><td></td><td></td><td colspan="2"></td>
    <tr>
        <td>n</td><td>m</td><td>nn</td><td>hn</td><td>hm</td><td>hng</td><td colspan="2"></td>
    <tr>
        <td colspan="8"></td>
    <tr>
        <td colspan="8">韻尾</td>
    <tr>
        <td colspan="4">ㄚ入聲韻尾</td><td colspan="4">ㄝ入聲韻尾</td>
    <tr>
        <td>ab</td><td>ad</td><td>ag</td><td></td><td>eb0</td><td>ed0</td><td>eg0</td><td></td>
    <tr>
        <td colspan="4">ㄧ入聲韻尾</td><td colspan="4">ㄛ入聲韻尾</td>
    <tr>
        <td>ib</td><td>id</td><td>ig</td><td></td><td>ob0</td><td>od0</td><td>og0</td><td></td>
    <tr>
        <td colspan="4">ㄨ入聲韻尾</td><td colspan="4">ㄜ入聲韻尾</td>
    <tr>
        <td>ub</td><td>ud</td><td>ug</td><td></td><td>eb</td><td>ed</td><td>eg</td><td></td>
    <tr>
        <td colspan="8">平舌音韻尾</td>
    <tr>
        <td>iib</td><td>iid</td><td>iig</td><td>iin</td><td>iim</td><td>iing</td><td colspan="2"></td>
    </tr>

</table>

* **註記**
<br>※ ㄈ的濁音在客語的拼音方案為v，為了不與中文的"ㄩ"衝突而作修正。
<br>※ ㄋ的濁音在客語的拼音方案為ng，為了不與中文韻尾衝突而作修正。

* **錄音表**
<br>錄音表為混字錄音表，最多8字。
<br>檔名為 Reclist_TL_Hakka_20210724.txt。

* **收錄內容：**
    * 濁聲母CV、濁聲母VC
    * ㄖ捲舌音、ㄖ平音的擴充韻母
    * 入聲韻尾
    * 擴張整音
    * 中文缺少的單聲母整音採樣
    * 複韻母-複韻母VC
    * 複韻母-聲母VC
    * 因為錄音量的緣故，未製作開頭音與較少使用的客語整音。

* **UTAU中的客語擴充使用方式**
<br>大部分都能以CVVC的方式銜接，唯有一部分有額外的拆音方式：

    * 入聲、平舌音韻尾：
        * 用於入聲字要銜接下一個歌詞的時候。
        * 例如：煞猛(sad mang)：
        * | sa | (ad R) | mang |
    * 擴張整音：
        * 用於歌詞遇到連續音的時候，將音符拆開可做更多的調整。
        * 因為錄音量的問題，部分字音僅能透過拆音達成，請見諒。
        * 包含複韻母的整音，例如_iang、_iong等
        * 例如：打拚(da biang)：
        * | da | (a b) | bia | (_ang) |
        * 例如：點紅妝(diam fung zong)：
        * | dia | (_iam) | (am f) | feng0 | (ong z) | zong |
    * 鼻音：
        * 鼻音未錄製VC，故銜接上同入聲韻尾的使用方法。
        * 例如：毋使(m siid)：
        * | m | m R | si | iid R |
    * 客語在中文CVVC中的處理：
        * 製作擴充方案時，為了原本熟悉中文CVVC的使用者，原音設定是以中文CVVC為主。
        * 因此有一些相似的字音偏向中文CVVC而不使用台灣客家語拼音方案。
        * v：使用ff
        * ng：使用nn
        * rh：使用r
        * -e：使用e0
        * i：使用yi
        * -o：使用o0
        * -iu：使用iu0；yiu直接使用yiu
        * -ui：使用ui0
        * bung、pung、mung、fung：使用beng0、peng0、meng0、feng0
        * ung：使用ong
        * zii、cii、sii：使用zi、ci、si
        * 複韻母韻尾參照上表

[> 回大綱](#大綱)
<br>[> 下載客語擴充錄音表(含未完成oto模板)](https://github.com/Shangliu-63/TL_HAKKA_UTAU/blob/master/download/TL_Hakka.zip)
<br>> 下載TL示範音源(尚未公布)
<br>[> 參考資料: 自製TL中客音表整理](https://github.com/Shangliu-63/TL_HAKKA_UTAU/blob/master/reference/TL%E5%AE%A2%E8%AA%9E%E6%95%B4%E9%9F%B3%E8%A1%A8.xlsx)

###### 本文最後編輯：2021/07/28
###### 本文上次編輯：2021/04/12
