﻿# 대한민국 행정동 경계(admdongkor)

## 대한민국 행정동 경계 파일입니다.
- 통계청 통계지리정보서비스에서 제공하는 행정동 경계 파일을 바탕으로, 행정동 변경 이력을 수정하여 반영한 파일입니다.
- geojson 형식이며, 좌표계는 WGS84 (EPSG:4326) 입니다.
- geojson 및 csv 파일 인코딩 형식은 UTF-8입니다.
- topology 정합성을 검토하였습니다.(폴리곤 경계끼리 잘 맞습니다) 
- 속성의 adm_cd 는 통계청에서 사용하는 7자리의 [한국행정구역분류코드]입니다.
- 속성의 adm_cd2 는 행정안전부 사용하는 10자리의 [행정기관코드]입니다.(2018.07.24 업데이트 파일부터 적용)
- 속성의 adm_nm 은 통계청에서 사용하는 전국 행정동 이름입니다.
- 일부 지역들이 실제 행정동 경계와 잘 맞지 않습니다. 지속적인 수정이 필요합니다.
- 최신 버젼만 업로드하지 않고 변경 이력별로 지속적으로 남길 예정입니다.
- 앞으로의 변화를 수정할 경우 'for update' 폴더 안의 파일을 fork하여 수정한 후 수정내역.txt와 함께 pull request 해 주시면 검토 후 master branch에 반영하겠습니다.
  - 수정과 업로드는, 폴리곤을 단순화시키지 않은 가장 상세한 버젼으로 올려주시기 바랍니다.



## 파일 버젼
- ver20180724
  - 2018년 7월 23일까지 변경된 모든 행정동에 10자리 행정기관코드를 추가하였습니다. (adm_cd2 필드 참고)
  - 2018년 7월 1일 경기도 고양시 덕양구 신도동이 삼송동으로 명칭 변경되었습니다. (경계 불변)
  - 2018년 7월 1일 인천광역시 서구 행정동 명칭이 5건 변경되었습니다. (경계 불변)
  - 2018년 7월 1일 전라북도 전주시 완산구 효자4동이 효자4동,효자5동,덕진구 혁신동으로 3분할 되었습니다.
  - 2018년 7월 1일 인천광역시 남구가 인천광역시 미추홀구로 명칭 변경 되었습니다. (경계 불변)
  - 2018년 7월 16일~23일에 세종특별자치시 보람동이 보람동, 대평동, 소담동으로 3분할 되었습니다.
  - 2018년 7월 1일까지 변경된 행정동은 새로 부여된 코드를 적었으며, 그 이후 변경된 행정동 코드의 마지막 두자리는 알파벳으로 처리하였습니다.
  

- ver20180401
  - 2018년 4월 1일 울산광역시 울주군 청량면이 청량읍으로 명칭 변경되었습니다. (경계 불변)
  - 2018.6.13 제7회 전국동시지방선거의 행정동 경계로 사용할 수 있습니다. 중앙선거관리위원회 홈페이지에서 청량면 -> 청량읍 변동분까지 반영된 것을 확인하였습니다.

- ver20180301
  - 2017년 12월 11일 경기도 용인시 처인구 모현면과 이동면이 모현읍과 이동읍으로 변경되었습니다. (경계 불변)
  - 2017년 12월 18일 경기도 남양주시 다산1동과 다산2동이 신설되면서 영역과 명칭이 세부적으로 조정되었습니다.
  - 2017년 12월 26일 경기도 수원시 영통구 영통1,2동이 조정되고 영통3동이 신설되었습니다.
  - 2018년 1월 1일 부산광역시 강서구 명지동이 명지1,2동으로 분동되었습니다.
  - 2018년 1월 1일 인천광역시 중구 영종동이 영종동과 영종1동으로 분동되었습니다.
  - 2018년 1월 22일 경기도 화성시 새솔동이 신설되고 동탄 4,5,6동이 조정되었습니다.
  - 2018년 3월 1일 대구광역시 달성군 유가읍이 유가면으로 변경되었습니다.
  - 2018년 1월 1일까지 변경된 행정동은 새로 부여된 코드를 적었으며, 그 이후 변경된 행정동 코드의 마지막 두자리는 알파벳으로 처리하였습니다.

- ver20171016
  - 2017년 8월 1일까지 변경된 행정동의 7자리 코드를 채워넣었습니다. 2017년 10월 1일에 통계분류포털에 업데이트 된 행정구역분류코드를 이용하였습니다.
  - 2017년 10월 16일 세종특별자치시 한솔동이 한솔동과 새롬동으로 나뉘었습니다.
  - 변경된 행정동의 코드의 마지막 두자리는 알파벳으로 처리하였습니다.(통계청관리 코드를 아직 알 수 없음)

- ver20170801
  - 2017년 7월 17일 경기도 안산시상록구와 안산시단원구의 일부 행정동의 명칭이 변경되었습니다. 원곡본동의 경우 원곡동과 신길동으로 나뉘었습니다.
  - 2017년 8월 1일 충청남도 홍성군 홍북면이 홍북읍으로 변경되었습니다.

- ver20170418
  - 2017년 4월 18일에 변경된 경기도 김포시 김포본동, 장기본동까지 반영되어 있습니다.
  - 2017년 5월 대통령선거에 사용가능한 버젼입니다.  
  - 중앙선거관리위원회에서 사용하는 행정동 이름과 매칭시킬 수 있는 csv를 동봉하였습니다.
  - 통계청 파일에서 수정한 경계(실제 행정구역도와 대조함, 행정구역 변경 이력과는 별개임)
    - 서울특별시 송파구 위례동, 경기도 성남시 수정구 위례동, 경기도 하남시 위례동의 경계 부근
    - 부산광역시 해운대구
    - 경기도 시흥시의 오이도 부근

- ver20160201
  - 2016년 2월 1일까지의 변경부분이 반영되어 있습니다.
  - 2016년 4월 국회의원 선거에 사용가능한 버젼입니다.
  - 중앙선거관리위원회에서 사용하는 행정동 이름과 매칭시킬 수 있는 csv를 동봉하였습니다.
    - 통계청 행정동과 선관위 행정동은 '제1동' 등에서 차이나는 것이 있습니다.
    - 20대 총선의 경우 이상하게도 선관위 데이터에서 몇몇 동들이 다른 구의 하위 주소로 되어 있습니다. 해당 값들을 매칭시켰습니다.
    - 위의 두 경우는 csv의 '특이사항' 필드에 1로 표시하여 두었습니다.
  - 통계청 파일에서 수정한 경계(실제 행정구역도와 대조함, 행정구역 변경 이력과는 별개임)
    - 서울특별시 송파구 위례동, 경기도 성남시 수정구 위례동, 경기도 하남시 위례동의 경계 부근
    - 부산광역시 해운대구

- ver20121210
  - 2012년 12월 10일까지의 변경부분이 반영되어 있습니다.
  - 2012년 12월 대통령선거에 사용가능한 버젼입니다.



## 속성의 adm_cd
- 통계청에서 사용하는 7자리의 [한국행정구역분류코드]입니다.
- [2자리 시도]+[3자리 시군구]+[2자리 읍면동] 으로 이루어집니다.
  - 따라서,  코드의 특정 문자열들을 이용하여, dissolve로 병합하면 시도 경계나 시군구 경계 파일을 만들 수 있습니다.
- 행정동 경계가 변하면 행정동 이름이 그대로이더라도 코드가 변경됩니다.

## 속성의 adm_cd2
- 행정안전부(행정자치부, 안전행정부 등 이름이 바뀌어도 *행정*부)에서 사용하는 10자리의 행정기관코드입니다.
- [2자리 시도]+[3자리 시군구]+[3자리 읍면동]+[2자리 행정리] 로 이루어집니다.
  - 따라서,  코드의 특정 문자열들을 이용하여, dissolve로 병합하면 시도 경계나 시군구 경계 파일을 만들 수 있습니다.
  - 행정동 이외에 출장소에도 코드가 부여되어 있습니다.
- 행정동 경계가 변해도 행정동 이름이 그대로이면 코드가 변경되지 않습니다.

## 참고 : 행정동 관련 정보
- 2018년 8월 현재, 행정동 경계 파일을 제공하는 곳은 통계청 통계지리정보서비스가 유일합니다.
  - https://sgis.kostat.go.kr/contents/shortcut/shortcut_05_02.jsp
  - 로그인 후 자료신청을 통해 받을 수 있습니다.
  - 2017년 5월 현재 1975~2015년 까지 받을 수 있습니다.
  - 2015년 버젼은 2015년 10월 1일의 행정구역 변경이력까지 반영된 파일입니다.
- 선거 득표 등 특정한 시점의 이벤트를 행정동에 빠짐 없이 맵핑하려면 세세한 행정구역 변경 이력을 확인해야 합니다.
- 행정구역분류 코드 및 변경 이력은 1년에 4번, 분기별로 통계청에 업데이트 됩니다.
  - http://kssc.kostat.go.kr → 행정구역분류 → 자료실
  - 이 곳의 자료로 통계청의 [7자리 행정구역분류코드], 행자부의 [10자리 행정표준코드관리시스템 코드], [10자리 법정동 코드]를 매칭시킬 수 있습니다.
  - 이 곳의 자료에서 과거 행정구역 변경 이력을 알 수 있습니다.
  - 0번 시트에 행정동 코드에 대한 설명이 있습니다.
- 연중 지속적으로 이루어지는 행정구역 변경은 행정안전부 홈페이지에 게시됩니다.
  - http://www.mois.go.kr/frt/bbs/type001/commonSelectBoardList.do?bbsId=BBSMSTR_000000000052
  - [행정안전부 홈페이지](http://www.mois.go.kr/) → [업무안내 → 지방자치분권실 → 주민등록 및 인감] 게시판에서 ‘주민등록주소코드 변경내역’이라는 제목들로 올라온 글에 변경내용이 있습니다.
- 행정구역 코드 변경은 다음과 같이 이루어지는 것 '같습니다'
  - 7자리 코드는 동 통폐합이나 이름 변경시 새로 부여됩니다.
  - 10자리 코드는 통폐합 되더라도 과거의 동 이름이 살아있는한 해당 동의 코드는 그대로 유지됩니다.
- 통계청마이크로데이터서비스의 인구이동 데이터는 10자리 코드와 매칭됩니다. 단, 행정동 이외에도 출장소에 신고된 전입전출 데이터도 있으니 유의하시기 바랍니다.
- 행정동의 관할 법정동 지번과의 관계는 각 시의 조례에 지번까지 상세하게 나와있습니다. 
  - ex) 경기도 안산시 행정운영동의 설치 및 관할구역에 관한 조례

## 참고 : 선거 및 지도 관련 데이터
- 과거 선거 관련 데이터 원본은 [중앙선거관리위원회](http://nec.go.kr/portal/bbs/list/B0000341.do?menuNo=200029)에서 찾을 수 있습니다.
- [2017년 대선 시군구별 득표 지도](https://bl.ocks.org/vuski/raw/e29ed35cfdfb21ae01689c76f4aeea87/) 와 [2017년 대선 읍면동별 득표 지도](https://bl.ocks.org/vuski/raw/7e482f13ef2b2ec4c14bb3622f05c353/) 를 인터랙티브 버젼으로 볼 수 있습니다. 지역별 1~5위 득표지도, 후보별 득표지도, 2016년 총선과의 비교지도가 있고 총 14장입니다. 개략적 지도의 모습과 설명은 [여기](http://www.vw-lab.com/39)에서 확인할 수 있습니다. 시군구별 득표지도는 모바일 화면에 최적화 되어 있고, 읍면동별 득표지도는 pc 화면 비율(가로로 긴 화면)에 최적화 되어 있습니다. 읍면동 득표지도는 모바일에서 느려질 수 있습니다. 
- [ChangHee Lee 님의 repository](https://github.com/WWolf/korea-election)에 몇몇 과거 선거 데이터들과 관련 자료들이 정리되어 있습니다.
- [오마이뉴스 repository](https://github.com/OhmyNews/2017-Election)에도 2017년 대선 데이터과 분석 자료들이 올라와 있습니다.
- [southkorea 계정의 repository](https://github.com/southkorea/southkorea-maps)에는 2011년~2013년 지도 데이터들이 다양한 포맷으로 올라와 있습니다.


## 참고 : mapshaper
- mapshaper.org 에서 여러 가지 작업을 할 수 있습니다. 자세한 것은 다음의 링크를 참고하세요
  - https://github.com/mbloch/mapshaper/wiki
- 맵셰이퍼에서 가능한 작업들
  - 간단한 토폴로지 불일치 자동 수정
  - 웹 용으로 사용할 수 있도록 simplify 하여 용량 줄이기
  - topojson 으로 변경하여 용량 극소화 하기, 기타 다른 형식으로 변경 가능
  - dissolve 등의 명령 사용 가능

