12조 스마트 쉑쉑
=============================================================
![이미지1 스마트쉑쉑](http://blogfiles.naver.net/MjAxNjExMTZfMTA2/MDAxNDc5MjkyNTEzODYz.VijYQT78SuLeslOCVC_lBjFUnXMwn6SvWo83gGV7eocg.aXnknam3cioBmiZassjvKfNvBLQQffC7EQTziE-e21Ug.JPEG.dbgkrgus1/KakaoTalk_20161116_184547403.jpg)

[이미지 출처 - 유학현 블로그](http://blog.naver.com/dbgkrgus1/220863351742)
[이미지 출처 - 유재언 블로그](http://blog.naver.com/iopk9010)


**[조원 & GIT ID]**
김효진(*sa833591@gmail.com*)
유재언(*iopk9010@naver.com*)
유학현(*cjd1110@koreatech.ac.kr*)

----------------


필요성
---------------------
**[문제인식]**
_**음식을 할 때**, 간을 잘 못 맞추는 사람들이 많아 **불편함**을 겪는다._
 > 25살 재언 이는 음식을 할 때 정확한 양을 조절하지 못하여, 매번 음식이 맛이 없다.음식의 조리법을 봤을 때, 조미료의 양이 숟가락의 횟수로 나와 있거나 그램으로 나와 있다.이러면, 재언 이는 숟가락의 크기가 어떤지 모르고 정확한 양을 재지 못한다. 또한, 그램으로 나와 있을 때는 저울로 무게를 측정해야 하는 불편함이 생기게 된다.
 
  * 예상 사용자
* 요리를 잘 못하는 사람들
* 바깥에서 요리를 하는 사람들(ex 캠핑 족)
* 캠핑 족이 늘고있는 추세 
(출처 : http://www.fntimes.com/paper/view.aspx?num=159203)

**[시장조사]**

| **뉴스기사 1 : "추석 앞두고 스마트 주방 용품 인기"** |
| :-----------  |
| ![news1](http://postfiles3.naver.net/MjAxNjExMTZfNzcg/MDAxNDc5MzAzMDI1OTE3.zDT0rM59CBvFow_x9vkKc9tNsFCNwJw8R0Zk8R50QJ4g.TTdtXm_OYaxsh_XVvaePkdDZ9EPSKRCbTCjcIbzBzIQg.JPEG.iopk9010/news1.jpg?type=w3)                  **【서울=뉴시스】**김종민 기자 = 추석 명절을 앞두고 주부들의 일손을 덜어줄 이색 스마트 주방용품들이 인기를 끌고 있다. http://www.newsis.com/ar_detail/view.html?ar_id=NISX20160904_0014366905&cID=10401&pID=10400|
| **뉴스기사 2 : 사물인터넷 시대, 알아서 요리해주는 지능형 요리도구 '눈길'** |
| ![news2](http://postfiles13.naver.net/MjAxNjExMTZfMjkw/MDAxNDc5MzAzMDI2MTMz.8ZqJxM4ZDR-5wb7fhkN3YL557d0yvRY9tnQdXCdl-psg.5VUeZmhLo-3ndgzCObJYxZ2Gh-PdH8iLTSyat5X-TWAg.PNG.iopk9010/news2.png?type=w3)                  **아주경제** 장윤정 기자 = #예비신부 직장인 A씨는 이번 주말 남자친구를 초대해 저녁을 대접할 계획이다.           http://www.ajunews.com/view/20150210110117197  |
| **설문조사 : 요리도구 개선-설문조사를 실시** |
| ![research1](http://postfiles13.naver.net/MjAxNjExMTZfNjUg/MDAxNDc5MzAzMDI2NzQ3.D0YbNb5Gv-oMcTE0ddMnynq8dXvC25sB32OSTUpfT3cg.Yxne8W-oazwvTeGUhP9z4op0ICd4-cb28eXlir0-Sx8g.PNG.iopk9010/research1.png?type=w3)![research1-1](http://postfiles14.naver.net/MjAxNjExMTZfMzEg/MDAxNDc5MzAzMDI3MjIz.qQG1Vi-C07WTkZyMJl6du4izN3tHl9u_acvUTx-uu00g.gmSY_x5TDffn8FbTv3NFbdMl6JAdH9R_S6JG-96V5GIg.PNG.iopk9010/research1-1.png?type=w3)                **가장 많이** 사용하는 부엌 도구는 계량컵과 스푼같은 ‘재는 도구’ 였습니다. 재기 위해서 뿐 아니라 ‘계량이 가능한 컵’과 ‘계량도 할 수 있는 스푼’처럼 볼 대신이나 전자레인지 용기 등, 멀티로 사용할 수 있는 것이 인기있었습니다.   http://www.muji.com/kr/blog/20160328_332/|

**[결론]** : **음식을 할 때**, 간을 잘 못 맞추는 사람들이 많아 **불편함**을 겪는다.


----------------


시스템 개요
---------------------
### 요구사항
 1. 사용자가 레시피대로 정확한 양의 조미료를 사용할 수 있도록, **무게를 측정한다.** 
 2. 측정된된 무게만큼 조미료가 **분출**된다. 
 3. 통은 한 가지의 조미료를 담는 것이 아닌 **다양한** 조미료를 담을 수 있도록 보관의 용이성을 가진다. 
 4. 사용자는 원하는 레시피를 휴대폰 어플에서 선택하여, 통으로 레시피를 전달한다. 통에서는 **레시피의 조리 과정**을 디스플레이 해준다. 
 5. 어플 **게시판**에서 서로의 레시피를 공유할 수 있다.

----------------


기존 관련 사례
---------------------

![이미지2 특허사례 - 조미료 통 이미지](http://blogfiles.naver.net/MjAxNjExMTZfMTEx/MDAxNDc5MjkyNjI5NTgw.zj82x7kf2sBHd2IQXTsH7KIsLz5n3E5Tajrl_txGZAIg.1WzV-XPP6U3xtm4giHP2Tx1G9F9uhvUODepvRGe-z9Qg.JPEG.dbgkrgus1/measure2.JPG " 계량기능을 갖는 용기(CONTAINER HAVING MEASURING FUNCTION)")

[그림1. 특허사례 - 조미료통]

|     **설명**   |
| :-----------  |
| 본 발명에 의한 계량 기능을 갖는 양념통에 따르면, 크기가 커지거나 복잡한 장치 구성이 배제되므로, 일반적인 병으로 형태의 양념통 구조의 변경을 최소화 시킬 수 있어 양념통 본래의 사용 형태와 기능을 유지하도록 하여 싱크대, 식탁 등에 놓고 사용할 수 있도록 하는 동시에 양념의 계량 기능을 제공하여 사용의 편리함을 증대시킬 수 있다. 또한, 계량 부재에 다양한 크기의 계량홈을 형성할 수 있으므로 세밀한 계량이 가능하다. 또한, 거치패치를 싱크대 상부장의 하부면 등에 부착하고, 거치패치 하부에 양념통을 결합할 수 있어, 싱크대 공간을 절약할 수 있다. 또한 덮개 부재를 열지 않고도 다양한 양의 양념을 사용할 수 있도록 함으로써 사용자의 불편을 덜어줄 수 있다.|
>[출처 - 특허정보넷 키프리스][1]


![이미지3 아마존 쇼핑 - 계량 스푼](http://macrostacks.com/wp-content/uploads/2016/06/Digital-Measuring-Spoon-2.png "아마존 쇼핑 - 계량 스푼)")

[그림2. 아마존 쇼핑 - 계량 스푼]

|     **설명**   |
| :-----------  |
|  이 디지털 계량스푼은 500g까지 측정할 수 있는 0.1g의 높은 정밀도를 가지며 변화하는 무게의 4 단위를 제공한다. 소금, 설탕, 전분과 같이 양념 무게를 측정 할 수 있도록 중량의 단위를 제공한다. 이 제품은 또한 씻을 수 있게 스푼과 스틱의 분리가 가능하도록 설계되어있으며, LCD를 통해 무게(g)를 볼 수 있다. 1분 동안 사용하지 않는다면 스푼의 전원이 자동으로 꺼진다.|
>[출처 - 아마존 쇼핑 - 계량 스푼][2]

----------------



참고
-------------
* [요리도구 설문조사] (http://www.muji.com/kr/blog/20160328_332/ "MUJI [상품개발프로젝트] 1.요리도구 개선-설문조사를 실시했습니다.")
* [인기 캠핑 요리도구] (http://www.fntimes.com/paper/view.aspx?num=159203 "네이버 검색으로 알아보는 ‘여름 캠핑’ 인기 키워드")

[1]: http://kportal.kipris.or.kr/kportal/search/total_search.do "특허사례 - 조미료 통"
[2]: https://www.amazon.com/HuntGold-Digital-Kitchen-Electric-Measuring/dp/B010CL5T16/ref=pd_sbs_79_4?_encoding=UTF8&pd_rd_i=B010CL5T16&pd_rd_r=8THVJFDEP798VH6PN09X&pd_rd_w=1ARdb&pd_rd_wg=4FHDA&psc=1&refRID=8THVJFDEP798VH6PN09X/ "아마존 쇼핑 - 계량 스푼"

----------------


