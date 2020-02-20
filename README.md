# 동행 매칭 챗봇

최근 1인 여행객들이 증가함에 따라 같이 여행하는 동행을 구하는 소요도 증가하고 있습니다.
사용자가 접근하기 쉬운 채팅 플랫폼을 이용한 챗봇을 통해 자신의 여행정보를 등록해서  
같은 기간, 같은 장소에 여행중인 사람들과 매칭해주는 챗봇을 만들면 좋지 않을까라는 아이디어로 기획한 프로젝트입니다.


# Chatbot 여(행하는) 우(友 친구)
![사진](https://mblogthumb-phinf.pstatic.net/20160620_99/mikybong113_1466431410996E1LXs_JPEG/ART1512210710071B2G9KTC.jpg?type=w2)
```
"길들인다는게 무슨 뜻이야?"

"그건 너무나 잊혀져 있는거지.

그건 '관계를 맺는다...'는 의미야."
여우가 말했어요.

"관계를 맺는다고?"

"물론이지. 내겐 넌 아직 수십만의 아이들과 같은 어린아이일뿐이야.
난 네가 필요하지 않고. 너 역시 내가 필요하지 않아.
너에게는 수십만의 여우들과 같은 여우에 불과하니까.
하지만 네가 나를 길들인다면 우리는 서로를 필요하게 될거야.
너는 나에게 이 세상에 유일한 존재가 될 거야.
나는 너한테 세상에 단 하나밖에 없는 존재가 될 거고..."  - 어린왕자 여우 대사 中
```
Team Lost Star 는 Chatbot 여우를 길들이는 중입니다 :D 

[카카오톡 여우 만나러가기](https://pf.kakao.com/_xcwxjxgT)

## Design


다양한 아이디어를 수집했고, 팀원들간의 생각을 비교 분석한 결과 '동행'이라는 주제의 챗봇이 선정이 되었고 [동행 매칭 서비스 분석](https://github.com/saitros/Team-Lost-Star/blob/master/Design/chanwoo/%EB%8F%99%ED%96%89%20%EB%A7%A4%EC%B9%AD%20%ED%95%A9%EB%A6%AC%ED%99%94%EC%8B%9C%ED%82%A4%EA%B8%B0.pptx)과 같이 간단한 현 상황을 확인 (발표 후 카카오톡 사용자 모자이크 처리 필요)

![Design](https://user-images.githubusercontent.com/16240290/69395298-d103f200-0d21-11ea-84a9-c0110b4d235f.jpg)


## Flow Chart

아직 길들여지지 않은 여우는 새침한 표정으로 두가지 대답밖에 해주지 않고있습니다.
첫번째는, 여행지를 등록한 사람들간의 일정 매칭을 통한 사용자 검색이고
두번째는, 가지고 있는 여행 정보중 일부만 살짝 알려주고있습니다.

여우가 보여준 사고회로는 다음과 같아요.(Feat. Google Draw.io)

![Untitled Diagram](https://github.com/saitros/Team-Lost-Star/blob/master/Design/Jun/Lost-Star.drawio.png)


## 데이터베이스 명세

![DB 명세](https://user-images.githubusercontent.com/16240290/69401795-59da5800-0d39-11ea-9909-805c7f496741.png)


## After Issue 

작업간 추가된 사후 개선사항에 대한 명세는 다음 [이슈](https://github.com/saitros/Team-Lost-Star/issues/5)를 참고

## Authors

* **ChanWoo Kim** - *Telegram work* - [cw0516](https://github.com/cw0516)
* **Jihwan Lee** - *DB work* - [vkdnjznd](https://github.com/vkdnjznd)
* **Jaeick Hwang** - *Kakaotalk work* - [jaicoco](https://github.com/jaicoco)
* **Junho Lee** - *Sub work* - [saitros](https://github.com/saitros)

See also the list of [contributors](https://github.com/saitros/Team-Lost-Star/graphs/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/saitros/Team-Lost-Star/blob/master/LICENSE) file for details
