# LUNA CRUENTA

<p align="center">
  <img src="docs/screenshots/title.png" width="560" alt="타이틀 화면: 죽은 나무 뒤로 뜬 붉은 달과 고딕 글씨의 LUNA CRUENTA">
</p>

<p align="center"><b>한국어</b> &nbsp;·&nbsp; <a href="#english">English ↓</a></p>

쇠공을 휘둘러서 다 때려잡는 게임입니다. HTML 하나로 9,999바이트가 나왔습니다.<br>
[10 Kilobytes Jam](https://itch.io/jam/10-kilobytes-jam-)에 내려고 만들었습니다.

이미지 파일도 폰트도 음악 파일도 없고, 그림·글씨·음악·효과음이 전부 그 파일 하나에 들어 있습니다.<br>
10KB가 얼마나 작은지는 만들면서 알았습니다.

## 해보기

[`luna-cruenta.html`](luna-cruenta.html)을 받아서 브라우저로 열거나 깃허브 페이지로 구동됩니다.

<!-- TODO: 업로드 후 itch.io 페이지 링크를 여기에 추가 -->

- 마우스: 캐릭터가 포인터를 따라 달립니다.
- 터치: 화면 아무 데나 대고 끌면 됩니다. 손가락이 캐릭터를 가리지 않게, 목표 지점이 손가락보다 1.5배 멀리 움직입니다.
- 키보드는 안 씁니다. 클릭 한 번으로 시작하고, 카드 고르고, 죽으면 다시 시작합니다.

타이틀 화면에서 음악이 안 나오면 화면을 한 번 눌러주세요. 그게 음악을 켜는 터치고, 한 번 더 누르면 시작합니다. 왜 이렇게 됐는지는 아래에 적어뒀습니다.

## 화면

<p align="center">
  <img src="docs/screenshots/play.gif" width="480" alt="6초 분량의 플레이: 무리 속에서 쇠공을 휘두르고, 강화 카드 세 장이 나타난다.">
</p>

|   |   |   |
| :---: | :---: | :---: |
| <img src="docs/screenshots/play-crowd.png" width="270" alt="모든 종류의 망자가 몰려든 장면"> | <img src="docs/screenshots/cards.png" width="270" alt="강화 카드 세 장"> | <img src="docs/screenshots/queen-beam.png" width="270" alt="빔을 쏘는 진홍의 여왕"> |
| 다섯 종류가 한꺼번에 몰려올 때 | 레벨 업 카드 | 여왕 공격 패턴 |
| <img src="docs/screenshots/regicide.png" width="270" alt="여왕이 죽은 뒤 피 흘리는 벽"> | <img src="docs/screenshots/horror-tentacle.png" width="270" alt="원에서 솟구치는 호러의 촉수"> | <img src="docs/screenshots/eclipsed.png" width="270" alt="사망 화면"> |
| 여왕을 잡으면 벽이 피를 흘립니다 | 두 번째 보스의 촉수 | 사망화면 |

<details>
<summary><b>스포일러: 마지막 1분, 엔딩, 한 판의 흐름</b></summary>

|   |   |   |
| :---: | :---: | :---: |
| <img src="docs/screenshots/flood.png" width="270" alt="붉게 잠기는 바닥"> | <img src="docs/screenshots/rush.png" width="270" alt="모든 것이 달려든다"> | <img src="docs/screenshots/ending-throne.png" width="270" alt="붉은 바다 앞, 왕좌에 앉은 뒷모습"> |
| 전체 타일이 피로 물들어갑니다. | 적들이 몰려 옵니다. | 결국 적들의 왕이 되어 왕좌에 앉는 모습 |
| <img src="docs/screenshots/credits.png" width="270" alt="마지막 문장들"> | <img src="docs/screenshots/name.png" width="270" alt="이름 입력"> | <img src="docs/screenshots/menu.png" width="270" alt="순위표, 그리고 MAIN과 INFINITY 선택"> |
| 크레딧 | 이름 다섯 글자 | 메인으로, 아니면 무한으로 |

한 판은 이렇게 흘러갑니다. 끝까지 4~5분쯤 걸립니다.

1. 망자가 벽에서 들어옵니다. 처음엔 느립니다.
2. 500점이 되면 첫번 째 보스가 나옵니다. 필드에 있던 몬스터는 전부 터집니다.
3. 여왕을 잡으면 벽이 피를 흘리고, 게임은 더 어려워진 채로 계속됩니다.
4. 1000점에 두 번째 보스가 나옵니다.
5. 호러를 잡으면 세상이 3분의 1 속도로 느려지고 깜빡이면서 모든 바닥타일이 피로 물듭니다.(데미지를 입지 않습니다.)
6. 마지막 카드 한 장, BLOOD AWAKENING. 모든 강화가 최대가 되고 하트가 여섯 개가 됩니다.
7. 10초 동안 몬스터들이 미친 듯이 달려듭니다.
8. 각성을 한 뒤 모든 적을 제압하고 왕좌에 앉습니다.
9. 3위 안에 들면 이름을 다섯 글자까지 남길 수 있습니다. '게임' 이라는 장르에 맞게 만든 기능이고 기록은 로컬브라우저에 저장됩니다.
10. 메인으로 돌아가거나INFINITY 모드로 계속합니다. 한 번 엔딩을 보면 타이틀 화면 맨 아랫줄에서도 INFINITY를 고를 수 있습니다.

</details>

## 줄거리

붉은 달 아래, 놈들은 당신을 쇠공에 묶어 죽은 자들에게 던져 넣었습니다. 당신은 대신 그 사슬을 휘둘렀습니다.

충분히 죽이면 진홍의 여왕이 내려와 묻습니다.<br>
누가 감히 왕좌에 도전하느냐고. <br>
여왕을 죽이면 벽이 피를 흘리고, 게임이 당신더러 이제 네가 괴물이라고 합니다. <br>
그다음엔 왕 천 명을 삼켰다는 놈이 빈자리를 차지하러 옵니다.

제가 그리고 싶었던 건 나쁜 놈들을 잡는 주인공이 아니라,<br>
나쁜 놈들의 왕이 되려는 주인공이었습니다.

## 조작과 규칙

<img src="docs/sprites/you.png" width="40" align="middle" alt="플레이어"> 이게 당신이고 <img src="docs/sprites/ball.png" width="40" align="middle" alt="쇠공"> 이게 쇠공입니다. 사슬은 당기기만 하기 때문에 공을 직접 움직일 방법은 없습니다. 원을 그리며 달리면 공이 돌고, 멈추면 축 늘어집니다.

- 공이 빨라야 죽습니다. 느린 공은 망자를 밀어내기만 합니다. 브루트는 제대로 휘둘러야 잡힙니다.
- 하트는 세 개. 망자나 침, 보스에 닿으면 하나 잃고, 1.5초 동안은 안 맞습니다. <img src="docs/sprites/heart.png" width="32" align="middle" alt="하트"> 하트는 브루트가 떨어뜨리고 다른 놈들도 가끔 떨어뜨리는데, 10초에 하나까지만 나옵니다. 체력이 꽉 찼을 때 주우면 5점입니다.
- 1초쯤 안에 연달아 잡으면 점수가 1, 2, 3, 4… 콤포점수로 올라갑니다.
- 흘린 피는 안 지워집니다. 바닥에 남아서 천천히 검붉게 마릅니다.

몇 마리 잡을 때마다(4, 5, 8, 13, 20… 점점 늘어납니다) 카드 세 장이 쾅쾅쾅 박히고, 그중 하나를 고릅니다.

| 카드 | 횟수 | 효과 |
| --- | :---: | --- |
| LONGER CHAIN | 4 | 사슬이 처음 길이의 4분의 1씩 길어짐 |
| BIGGER BALL | 2 | 공이 커지고 닿는 범위가 넓어짐 |
| FASTER SPIN | 4 | 팽팽한 사슬이 공을 돌던 방향으로 더 밀어줌 |
| FASTER LEGS | 4 | 달리기가 빨라짐. 그만큼 공도 빨라짐 |
| EXTRA HEART | 3 | 하트 하나 추가, 전부 회복 |

## 나오는 놈들

<p align="center"><img src="docs/sprites/the-dead.png" width="620" alt="실제 크기 비율로 본 망자 다섯 종: 섐블러, 러너, 스피터, 블로터, 브루트"></p>

이름은 코드에서 부르던 그대로입니다. 시간이 지날수록 뒤쪽 놈들이 섞여 나오고, 전부 처음 100초 동안 1.5배까지 빨라집니다. 보스가 있는 동안에는 이 시계가 멈추고, 보스를 잡으면 40초 되감깁니다.

|   | 이름 | 등장 | 하는 짓 |
| :---: | --- | :---: | --- |
| <img src="docs/sprites/shambler.png" width="64" alt="섐블러"> | **섐블러** (Shambler) | 시작 | 그냥 걸어옵니다. 잡는 놈의 절반이 얘입니다. |
| <img src="docs/sprites/runner.png" width="64" alt="러너"> | **러너** (Runner) | 15초 | 작고, 두 배 넘게 빠릅니다. |
| <img src="docs/sprites/spitter.png" width="64" alt="스피터"> | **스피터** (Spitter) | 25초 | 멀찍이 서서 2초마다 세 갈래로 침을 뱉습니다. |
| <img src="docs/sprites/bloater.png" width="64" alt="블로터"> | **블로터** (Bloater) | 30초 | 죽으면 터지면서 옆의 놈들을 같이 날립니다. 가까이 있으면 나도 맞습니다. |
| <img src="docs/sprites/brute.png" width="96" alt="브루트"> | **브루트** (Brute) | 45초 | 두 배 크기. 대충 휘두르면 공이 튕겨 나옵니다. 죽으면 하트를 남깁니다. |

스피터는 나중에 넣은 놈입니다. 마우스를 아무 생각 없이 빙빙 돌리기만 해도 꽤 오래 버텨져서, 가만히 한자리에서 돌리는 사람을 맞히려고 넣었습니다.

### 진홍의 여왕 (The Crimson Queen)

<p align="center"><img src="docs/sprites/queen.png" width="312" alt="진홍의 여왕"></p>

500점에 나옵니다. 등장 대사는 "WHO DARES CHALLENGE THE THRONE"(누가 감히 왕좌에 도전하는가).

플레이어를 따라 떠다니면서 구슬로는 불덩이 열두 개를 원형으로 뿌리고, 펼친 손바닥으로는 플레이어가 선 자리를 겨눈 다음 선을 보여주고 빔을 쏩니다. 체력이 절반 아래로 가면 둘 다 빨라집니다. 죽으면 "† REGICIDE † NOW YOU ARE THE MONSTER"(국왕 시해. 이제 네가 괴물이다)가 뜨고 벽이 피를 흘리기 시작합니다.

### 호러 (The Horror)

<p align="center"><img src="docs/sprites/horror.png" width="312" alt="호러"></p>

여왕을 잡은 뒤 1000점에 나옵니다. 대사는 "I HAVE EATEN A THOUSAND KINGS"(나는 왕 천 명을 삼켰다).

구슬 하나가 다섯 갈래로 탄을 쏩니다. 바닥에서는 점선 원이 플레이어를 쫓아오다 멈추고, 거기서 촉수가 솟구친 다음 플레이어 쪽으로 한 번 내리칩니다. 솟을 때도 맞고 내리칠 때도 맞습니다. 죽으면 "† USURPER † THE THRONE IS EMPTY NOW"(찬탈자. 이제 왕좌는 비었다).

보스들은 빠른 공에 1, 제대로 휘두른 공에 2씩 깎입니다. 잡으면 100점에 하트가 전부 찹니다.

## 10KB에 넣느라 겪은 일들

먼저 밝혀둘 게 있습니다. 저는 개발을 배우는 중인 초보이고, 이 게임의 코드는 Claude(AI)와 대화하면서 만들었습니다. 제가 한 일은 주로 "이걸 넣자", "이건 이상하다", "그럼 이건 빼자"를 정하는 쪽이었습니다. 그러면서 10KB가 뭘 허락하고 뭘 안 하는지 하나씩 부딪혀 가며 알게 됐고, 아래는 그 기록입니다. 기술적인 부분은 제가 이해한 만큼만 적었습니다.

### 시작은 가벼웠습니다

잼 규칙을 읽고 "색을 2비트만 쓰는 고어 게임"으로 정한 게 전부였습니다. 처음 버전은 방향키로도 움직였는데, 마우스로만 하는 쪽이 더 재밌어서 키보드를 일부러 뺐습니다. 강화도 처음엔 고르는 창이 따로 떴는데, 폰으로 해보니 누르기가 애매해서 카드로 바꿨습니다. 기왕 카드면 날아와서 쾅쾅쾅 박히면 좋겠다고 했고, 지금 그렇게 됩니다.

이때까지는 용량 걱정을 해본 적이 없습니다.

### 한글을 뺐는데 용량이 늘었습니다

한영 전환을 넣었다가, 한글 폰트가 영 마음에 안 들어서 뺐습니다. 그런데 뺀 버전이 오히려 더 컸습니다. 왜냐고 물었더니 답에 "패커"라는 말이 나와서, 패커가 뭐냐고 또 물었습니다. 제가 10KB를 진지하게 생각하기 시작한 게 이때입니다.

패커는 코드를 압축해서 스스로 풀리는 형태로 만들어주는 도구입니다.<br>
여기서는 [Roadroller](https://github.com/lifthrasiir/roadroller)를 씁니다. 숫자로 보면 이렇습니다.

|   | 바이트 |
| --- | ---: |
| 주석 달린 원본 소스 | 34,478 |
| 변수 이름 줄이고 공백 없앤 것 (terser) | 23,299 |
| 패커로 압축한 것. 이게 제출 파일입니다 | **9,999** |

그 9,999 중에 압축을 푸는 코드가 655바이트를 차지합니다.<br>
아무것도 안 넣어도 내야 하는 기본요금 같은 겁니다.

그리고 압축된 파일은 "글자 수 = 용량"이 아니라는 걸 배웠습니다. <br>
뭘 빼도 생각만큼 안 줄고, 어떤 건 더 길게 썼더니 줄었습니다. <br>
그래서 뭘 바꿀 때마다 실제로 빌드해서 재보는 수밖에 없었습니다.

### 그림은 전부 글자입니다

이미지 파일을 못 쓰니까 스프라이트는 픽셀 하나에 숫자 하나씩 적은 문자열입니다.<br>
이 저장소의 `src/art`에 가면 텍스트 파일로 그려진 여왕을 볼 수 있습니다.

보스가 제일 비쌉니다. 하나씩 빼고 다시 빌드해서 잰 값입니다.

|   | 크기 | 바이트 |
| --- | --- | ---: |
| 진홍의 여왕 | 68×56 픽셀 | 471 |
| 호러 | 34×40 픽셀 (오른쪽 절반만) | 240 |
| 타이틀 글씨 | 글자 9개 | 192 |
| 페이지 자체 (캔버스와 CSS) | 174자 | 171 |
| 크레딧 문장 | 188자 | 113 |
| 작은 스프라이트 7개 | 8×8씩 | 103 |
| 작은 폰트 | 글리프 40개 | 101 |
| 음악 선율 | 96자 | 81 |
| 나머지 (코드 전부와 남은 글자들) |   | 약 7,850 |

아낀 방법은 단순합니다.<br>
브루트는 섐블러를 두 배로 키워 그린 거라 그림이 따로 없습니다.<br>
호러는 좌우 대칭이라 반쪽만 그렸습니다.<br>
보스 그림에서 따로 찍힌 점들도 정리했는데, 지저분한 그림일수록 압축이 안 된다고 해서입니다.

### 화면은 작게, 색은 네 개

<p><img src="docs/palette.png" width="240" alt="네 가지 색: 검정, 마른 피, 신선한 피, 뼈"></p>

화면은 160×144이고 색은 검정, 마른 피, 신선한 피, 뼈색 네 가지입니다. 픽셀마다 0~3 숫자 하나만 들고 있어서, 화면 효과 대부분이 그 숫자로 치는 장난입니다.

- 맞았을 때 번쩍하는 건 숫자를 뒤집는 겁니다(0↔3, 1↔2).
- 어두워지는 건 대각선 무늬로 픽셀을 조금씩 검게 지우는 겁니다. 색이 네 개뿐이라 "조금 어두운 빨강" 같은 게 없습니다.
- 화면 흔들림은 캔버스를 CSS로 통째로 흔듭니다.
- 바닥의 피는 안 지우는 버퍼에 그냥 써넣습니다. 피가 남는다는 게 게임의 핵심인데, 구현으로는 그게 제일 쌌습니다.

### 글자도 아껴 썼습니다

작은 폰트는 3×5 픽셀이고 글자가 딱 40개입니다. 공백, 숫자, 대문자, 단검(†), 지우기 화살표, 마침표. 소문자가 없고 아포스트로피도 없어서, 게임 안에 "DOESN'T" 같은 말은 못 씁니다. 크레딧에 "DOES NOT"이라고 풀어 쓴 게 그래서입니다.

타이틀 글씨는 더 심합니다. L, U, N, A, C, R, E, T, 그리고 끝에 오는 키 큰 A. 이 아홉 개뿐이라 LUNA CRUENTA 말고는 아무것도 못 씁니다.

<p><img src="docs/sprites/title-letters.png" width="520" alt="타이틀 글자 9개"></p>

글자 가장자리의 밝은 테두리는 따로 저장한 게 아닙니다. 왼쪽 위가 비어 있는 픽셀만 밝게 찍습니다.

### 엔딩은 여러 번 고쳤습니다

마지막 장면은 왕좌에 앉아 피바다를 바라보는 뒷모습입니다. 첫 버전은 뭐가 뭔지 알아볼 수가 없었습니다. 이 해상도에서 알아볼 수 있는 장면 아이디어를 세 개 받아서 그중 실루엣 안을 골랐고, 지금 장면은 원판 하나(빛), 가로선 몇 줄(물결), 보스전에서 쓰던 촉수 함수, 그리고 타원과 사각형으로 쌓은 검은 실루엣입니다. 그림 데이터는 한 바이트도 없습니다.

왕좌에 앉을 때 나는 웃음소리도 넣었었는데, 들어보니 맥 빠지는 전자음이어서 뺐습니다.

크레딧 글자가 하얀 빛 위를 지나갈 때 안 읽혀서 글자마다 검은 테두리를 둘렀습니다. 반투명 배경을 깔고 싶었지만 색이 네 개라 안 됩니다.

음악은 16마디짜리 선율 하나를 세 번 우려먹습니다. 플레이 중에는 빠르게, 타이틀에서는 걷는 속도로, 엔딩에서는 그보다 더 느리게. 타이틀과 엔딩은 편곡이 같고 속도만 다릅니다. 소리는 전부 함수 하나(음이 미끄러지는 오실레이터, 아니면 필터 먹인 노이즈)로 냅니다.

크레딧 마지막 줄은 원래 "LONG LIVE THE QUEEN"이었습니다. 누가 왕이 되든 결국 남는 건 피뿐이라는 쪽이 더 맞는 것 같아서 "ONLY THE BLOOD REMAINS.."로 바꿨습니다.

### 타이틀 화면은 550바이트짜리 욕심이었습니다

게임이 거의 다 됐을 때 타이틀 화면을 제대로 만들고 싶어졌습니다.<br>
붉은 달, 구름, 죽은 나무, 고딕 글씨. 그때 남은 여유가 50바이트였는데 넣어보니 550바이트가 들었습니다.

그림은 저장하지 않고 그리는 쪽으로 최대한 아꼈습니다.

- 달은 원판 두 장을 한 픽셀 어긋나게 겹친 겁니다. 그 틈이 밝은 테두리가 됩니다.
- 달의 얼룩과 구름은 좌표를 적어둔 게 아니라 계산식 한 줄에서 나옵니다. 손으로 자리를 잡은 쪽이 조금 더 예뻤는데 48바이트를 더 먹어서 포기했습니다.
- 나무는 가지 하나를 그리고 끝에서 자기 자신을 두 번 부르는 작은 함수입니다. 제일 짧은 가지 끝에는 방울이 매달립니다.

그래도 모자랐습니다. 나머지를 메운 건 아래 두 가지입니다.

### 패커가 옆을 못 본다는 얘기

Roadroller는 "앞의 몇 글자를 보고 다음 글자를 맞히는" 방식으로 압축합니다.<br>
잘 맞힐수록 그 글자가 싸집니다.

스프라이트를 세로줄 순서로 쭉 적으면, 어떤 픽셀의 **위** 픽셀은 바로 앞 글자입니다. 그런데 **왼쪽** 픽셀은 세로줄 하나만큼 앞에 있습니다. 여왕은 높이가 56이니까 56글자 앞입니다. 패커는 그렇게 멀리 못 봅니다(기본으로는 9글자, 최대로 늘려도 30글자쯤). 그러니까 그림을 폭 1픽셀짜리 줄로 알고 압축하고 있었던 겁니다.

그래서 두 가지를 바꿨습니다.

1. 그림을 전부 28줄 높이의 띠로 잘라서 저장합니다. 여왕은 띠 두 개. 이러면 어떤 그림이든 왼쪽 픽셀이 정확히 28글자 앞에 옵니다.
2. 패커에게 28글자 앞도 보라고 알려줍니다. 빌드할 때 패커 설정을 이리저리 바꿔 보면서 실제 파일 크기가 가장 작은 조합을 찾는 탐색이 돕니다.

같은 코드를 놓고 잰 결과입니다.

| 패커 설정 | 바이트 |
| --- | ---: |
| Roadroller 기본값 | 10,462 |
| Roadroller가 스스로 찾은 최선 | 10,255 |
| 위 탐색으로 찾은 설정 | **9,999** |

코드는 한 글자도 안 줄이고 256바이트가 생겼습니다. 타이틀 화면 값의 절반 가까이가 여기서 나왔습니다.

### 좋을 줄 알았는데 오히려 커진 것들

전부 실제로 해보고 잰 겁니다.

- 세로줄을 "앞 줄과 달라진 부분"만 저장하기. 여왕이 626바이트에서 765바이트로 늘었습니다.
- 같은 색이 이어지는 길이로 저장하기(런 렝스). 제일 잘 나온 게 634, 그냥 적은 게 630이었습니다.
- 글자 하나에 픽셀 두 개씩 담기. 634에서 660으로.
- 작은 스프라이트를 16진수로, 폰트를 36진수로 줄여 적기. 한동안 이렇게 돼 있었는데, 미련하게 픽셀 하나에 숫자 하나로 풀어 적었더니 소스는 600자쯤 길어지고 파일은 70바이트쯤 줄었습니다.

사람 눈에 짧은 것과 패커가 맞히기 쉬운 것은 다른 얘기였습니다.

### 결국 뺀 것들

- 한영 전환
- 음악의 솔로 구간, 리드 에코, 아르페지오
- 피 위에 찍히던 발자국
- 사망 화면에서 세상을 몇 퍼센트 물들였는지 알려주던 줄. 그 줄에서만 쓰던 `%` 글자도 같이 뺐습니다.
- 크레딧 집계의 농담 줄들(QUEENS SLAIN 1, TEARS SHED 0 같은 것)
- 하트가 사라지기 전에 깜빡이던 것
- 페이지의 viewport 태그. 빼고 나니 폰에서 게임이 오히려 더 크게 나와서, 이건 손해가 아니었습니다.
- 페이지에서 doctype, `<title>`, `<html>`·`<head>`·`<body>` 같은 것들. 없어도 브라우저는 엽니다.

### 마지막에는 1바이트 단위였습니다

막판에는 뭘 하나 넣으려면 뭘 하나 빼야 했습니다.

제일 기억나는 건 크레딧 끝의 마침표 두 개입니다. "ONLY THE BLOOD REMAINS.."의 그 점 두 개를 찍으려면 폰트에 마침표 글자를 추가해야 했고, 그러고 나니 10,001바이트였습니다. 1바이트를 어디서 구했냐면, 사망 화면의 "TOUCH TO START"를 6픽셀 아래로 내렸습니다. 아마 타이틀 화면의 같은 문구와 좌표 숫자가 똑같아져서, 패커가 1바이트를 덜 썼습니다. 그걸로 딱 10,000. 패커 설정 탐색을 한 번 더 돌려서 1바이트를 더 얻었고, 그렇게 9,999가 됐습니다.

잼 규칙에는 "10 KB"라고만 돼 있어서 그게 10,000바이트인지 10,240바이트인지 모릅니다. 그래서 작은 쪽에 맞췄습니다.

## 직접 빌드하기

[Node.js](https://nodejs.org)가 있으면 됩니다.

```
npm install
npm run build
```

도구 버전을 고정해 둬서 빌드하면 매번 똑같은 9,999바이트가 나옵니다.

| 명령 | 하는 일 |
| --- | --- |
| `npm run build` | `luna-cruenta.html`과, `dist/`에 읽을 수 있는 소스와 디버그 빌드를 만듭니다 |
| `npm run search` | 패커 설정 탐색을 1,500번 돌리고 더 작은 걸 찾으면 저장합니다. 코드를 고친 다음 돌려볼 만합니다 |
| `npm run test-build` | 여왕이 6점, 호러가 26점에 나오는 테스트용 빌드를 `dist/`에 만듭니다 |

보스나 엔딩을 고칠 때마다 처음부터 플레이해서 확인하는 게 너무 귀찮아서 디버그 빌드를 만들었습니다. `dist/luna-cruenta-debug.html`을 열고 게임을 시작한 다음 숫자 키를 누릅니다.

| 키 |   |
| :---: | --- |
| `1` | 여왕이 한 대만 맞으면 죽는 상태로 나옴 |
| `2` | 호러가 한 대만 맞으면 죽는 상태로 나옴 |
| `3` | 엔딩 바로 시작 |
| `4` | 크레딧 도중에 누르면 크레딧 끝으로 |

## 폴더 구조

```
luna-cruenta.html            제출 파일. 9,999바이트
index.html                   위 파일로 넘겨주는 리다이렉트 (GitHub Pages 주소용)
README.md
package.json                 terser, roadroller 버전 고정
src/
  game.html                  게임 본체. 주석 달린 읽을 수 있는 소스
  music.js                   음악
  debug.js                   디버그 키 (디버그 빌드에만 들어감)
  art/
    sprites.js               8x8 스프라이트 7개와 3x5 폰트
    queen.txt                진홍의 여왕
    horror.txt               호러의 오른쪽 절반
    title-letters.txt        타이틀 글자 9개
tools/
  build.js                   소스 합치기 -> 줄이기 -> 압축, 그리고 패커 설정 탐색
  data.js                    src/art의 그림을 게임에 들어갈 문자열로 바꿈
  packer-settings.json       탐색이 찾아낸 설정
dist/
  luna-cruenta-source.html   게임 전체를 읽을 수 있는 파일 하나로 합친 것
  luna-cruenta-debug.html    위와 같고 디버그 키 포함
docs/                        이 글에 쓴 이미지
```

제출 파일 이름이 `index.html`이 아닌 건 잼 규칙이 index 파일을 금지해서입니다.

## 고마운 것들

- [Roadroller](https://github.com/lifthrasiir/roadroller) (Kang Seonghoon). 이게 없었으면 10KB 안에 못 들어갔습니다.
- [terser](https://terser.org)
- 코드를 같이 짠 Claude
- 판을 깔아준 [10 Kilobytes Jam](https://itch.io/jam/10-kilobytes-jam-)

---

<a id="english"></a>

<details>
<summary><b>English</b> (click to open)</summary>

<p align="right"><a href="#luna-cruenta">한국어 ↑</a></p>

You are chained to a spiked iron ball and thrown into a crowd of the dead, and you swing the ball until none of them are left. Four colours, one HTML file, 9,999 bytes.

I made it for the [10 Kilobytes Jam](https://itch.io/jam/10-kilobytes-jam-). There are no image files, no fonts and no audio files. The pictures, the lettering, the music and the sound effects are all inside that one file.

I only found out how small 10KB is by trying to fit a game into it. Half of this page is about that.

## Play

Download [`luna-cruenta.html`](luna-cruenta.html) and open it in a browser. That is all.

- Mouse: you run after the pointer.
- Touch: drag anywhere. The target moves one and a half times as far as your finger, so your hand does not cover you.
- No keyboard. One click starts a run, picks a card, and retries after you die.

If the title screen is silent, tap once. That tap turns the music on, and the next one starts the run. The reason is further down.

## Screens

<p align="center">
  <img src="docs/screenshots/play.gif" width="480" alt="Six seconds of play: swinging the ball through a crowd, and three upgrade cards slamming down">
</p>

|   |   |   |
| :---: | :---: | :---: |
| <img src="docs/screenshots/play-crowd.png" width="270" alt="A crowd of every kind of the dead"> | <img src="docs/screenshots/cards.png" width="270" alt="Three upgrade cards"> | <img src="docs/screenshots/queen-beam.png" width="270" alt="The Crimson Queen firing her beam"> |
| All five kinds at once | Level-up cards | The queen's beam |
| <img src="docs/screenshots/regicide.png" width="270" alt="The walls bleed after the queen dies"> | <img src="docs/screenshots/horror-tentacle.png" width="270" alt="The Horror's tentacle bursting out of its ring"> | <img src="docs/screenshots/eclipsed.png" width="270" alt="The death screen"> |
| Kill the queen and the walls bleed | The second boss's tentacle | When you die |

<details>
<summary><b>Spoilers: the last minute, the ending, and how a run goes</b></summary>

|   |   |   |
| :---: | :---: | :---: |
| <img src="docs/screenshots/flood.png" width="270" alt="The floor floods red"> | <img src="docs/screenshots/rush.png" width="270" alt="Everything runs at you"> | <img src="docs/screenshots/ending-throne.png" width="270" alt="A figure on a throne, seen from behind, before a red sea"> |
| The floor floods | Everything runs at you | The throne |
| <img src="docs/screenshots/credits.png" width="270" alt="The closing words"> | <img src="docs/screenshots/name.png" width="270" alt="Entering a name"> | <img src="docs/screenshots/menu.png" width="270" alt="The board, and a choice between MAIN and INFINITY"> |
| Credits | Five letters for a name | Back to the title, or on forever |

A run goes like this, and takes four or five minutes to the end.

1. The dead come in from the walls, slowly at first.
2. At 500 points the Crimson Queen arrives, and everything on the floor bursts.
3. Kill her and the walls bleed. The game carries on, harder.
4. At 1000 points, the second boss: the Horror.
5. Kill it and the world drops to a third of its speed and flickers while the floor fills to the last tile. From here you cannot die.
6. One last card, BLOOD AWAKENING: every upgrade at its maximum and six hearts.
7. Ten seconds of nothing but runners, faster and faster.
8. A roar, a flash, the dark. Then the throne and the credits.
9. A score in the top three gets a name of up to five letters, kept in the browser.
10. Back to the title, or on into INFINITY mode, which has no bosses and no end. Once you have finished the game, INFINITY can also be picked from the bottom line of the title screen.

</details>

## Story

Under a blood moon, they chained you to an iron ball and threw you to the dead. You swung the chain instead.

Kill enough of them and the Crimson Queen comes to ask who dares challenge her throne. Kill her and the walls bleed, and the game tells you that you are the monster now. Then something that says it has eaten a thousand kings comes for the empty seat.

What I wanted was not a hero who kills the bad ones. I wanted someone trying to become their king. The throne does not care who sits on it, and what is left is blood.

## Rules

<img src="docs/sprites/you.png" width="40" align="middle" alt="you"> This is you and <img src="docs/sprites/ball.png" width="40" align="middle" alt="the ball"> this is the ball. The chain can only pull, so there is no way to move the ball directly. Run in circles and it swings. Stop and it hangs slack.

- The ball has to be fast to kill. A slow one only shoves the dead aside. A brute needs a proper swing.
- Three hearts. Touching the dead, their spit or a boss costs one, and then nothing can hit you for a second and a half. <img src="docs/sprites/heart.png" width="32" align="middle" alt="a heart"> Brutes drop hearts and so, now and then, does anything else, but only one every ten seconds. Picked up at full health, a heart is 5 points.
- Kills within about a second of each other score 1, 2, 3, 4 and so on.
- Blood is never wiped. It stays on the floor and slowly dries dark.

Every few kills (4, then 5, 8, 13, 20 and up) three cards slam down and you pick one.

| Card | Times | What it does |
| --- | :---: | --- |
| LONGER CHAIN | 4 | The chain grows by a quarter of its first length |
| BIGGER BALL | 2 | A larger ball with a longer reach |
| FASTER SPIN | 4 | A taut chain pushes the ball further the way it is already turning |
| FASTER LEGS | 4 | You run faster, so the ball does too |
| EXTRA HEART | 3 | One more heart, and all of them refilled |

## The dead

<p align="center"><img src="docs/sprites/the-dead.png" width="620" alt="The five kinds of the dead, to scale: shambler, runner, spitter, bloater, brute"></p>

The names are what they were called in the code. The later ones join in as time passes, and all of them speed up to one and a half times over the first hundred seconds. That clock stops while a boss is in the room and goes back forty seconds when a boss dies.

|   | Name | From | What it does |
| :---: | --- | :---: | --- |
| <img src="docs/sprites/shambler.png" width="64" alt="shambler"> | **Shambler** | start | Walks at you. Half of what you kill is these. |
| <img src="docs/sprites/runner.png" width="64" alt="runner"> | **Runner** | 15 s | Small, and more than twice as fast. |
| <img src="docs/sprites/spitter.png" width="64" alt="spitter"> | **Spitter** | 25 s | Stands off and spits a spread of three every two seconds. |
| <img src="docs/sprites/bloater.png" width="64" alt="bloater"> | **Bloater** | 30 s | Bursts when it dies and takes its neighbours with it. You too, if you are close. |
| <img src="docs/sprites/brute.png" width="96" alt="brute"> | **Brute** | 45 s | Twice the size. A lazy swing bounces off it. Leaves a heart when it dies. |

The spitter was added later. Spinning the mouse in circles without thinking kept you alive for far too long, so it is there to hit people who stand in one place and spin.

### The Crimson Queen

<p align="center"><img src="docs/sprites/queen.png" width="312" alt="The Crimson Queen"></p>

Arrives at 500 points, saying "WHO DARES CHALLENGE THE THRONE".

She drifts after you. Her orb throws a ring of twelve fireballs, and her open hand aims at where you stand, shows the line, and fires a beam along it. Below half health she does both faster. When she dies you get "† REGICIDE † NOW YOU ARE THE MONSTER" and the walls start to bleed.

### The Horror

<p align="center"><img src="docs/sprites/horror.png" width="312" alt="The Horror"></p>

Arrives at 1000 points, once the queen is dead, saying "I HAVE EATEN A THOUSAND KINGS".

One of its orbs spits a fan of five. On the floor a dotted ring follows you, stops, and a tentacle bursts up through it and then slaps down once in your direction. Both the burst and the slap hurt. When it dies: "† USURPER † THE THRONE IS EMPTY NOW".

A boss loses 1 to a fast ball and 2 to a full swing. Killing one is worth 100 points and refills your hearts.

## What fitting it into 10KB was like

One thing first. I am a beginner who is still learning to program, and the code for this game was written in conversation with Claude, an AI. My part was mostly deciding: put this in, this looks wrong, then take that out. Along the way I ran into what 10KB allows and what it does not, one wall at a time, and this is the record. The technical parts are written as far as I understand them.

### It started lightly

I read the jam rules and decided on "a gory game in two bits of colour", and that was the whole plan. The first version could be played with the arrow keys as well. Mouse only turned out to be more fun, so the keyboard was taken out on purpose. Upgrades were picked from a pop-up at first, which was awkward to tap on a phone, so they became cards. If they were going to be cards I wanted them to fly in and slam down, and now they do.

At this point I had not thought about size once.

### I took the Korean out and the file got bigger

There was a Korean and English toggle for a while. I did not like how the Korean font looked and removed it, and the version without it was larger. I asked why, the answer had the word "packer" in it, and then I had to ask what a packer was. That is when I started taking the 10KB seriously.

A packer compresses the code into a file that unpacks itself. This one is [Roadroller](https://github.com/lifthrasiir/roadroller). In numbers:

|   | Bytes |
| --- | ---: |
| The source, with comments | 34,478 |
| With names shortened and spaces removed (terser) | 23,299 |
| Packed. This is the entry | **9,999** |

Of those 9,999, the code that does the unpacking takes 655. It is a flat fee you pay before putting anything in.

I also learned that in a packed file, the number of characters is not the size. Removing something saves less than you expect, and a few things got smaller when they were written out longer. So every change had to be built and measured.

### All the pictures are text

With no image files, a sprite is a string with one digit for each pixel. In `src/art` you can open the queen as a text file.

The bosses cost the most. These were measured by taking each piece out and building again.

|   | Size | Bytes |
| --- | --- | ---: |
| The Crimson Queen | 68×56 pixels | 471 |
| The Horror | 34×40 pixels (right half only) | 240 |
| Title lettering | nine letters | 192 |
| The page itself (canvas and CSS) | 174 characters | 171 |
| The credits text | 188 characters | 113 |
| Seven small sprites | 8×8 each | 103 |
| The small font | 40 glyphs | 101 |
| The tune | 96 characters | 81 |
| The rest (all the code, and the other text) |   | about 7,850 |

The savings are simple ones. The brute is the shambler drawn at double size, so it has no picture of its own. The Horror is symmetrical, so only half of it is stored. Stray single pixels were cleaned out of the boss sprites, because a messy picture packs badly.

Neither boss was right the first time. The queen's face looked a bit stupid at first, so her eyes were redone, and the hand that held a whip was opened into a palm because she fires a beam from it. The first version of the last boss looked to me like a strange castle, and it was thrown away and started again.

### A small screen and four colours

<p><img src="docs/palette.png" width="240" alt="The four colours: black, dried blood, fresh blood, bone"></p>

The screen is 160×144 and the colours are black, dried blood, fresh blood and bone. Each pixel is just a number from 0 to 3, and most of the screen effects are tricks played on that number.

- The flash when something is hit swaps the numbers (0↔3, 1↔2).
- Fading to dark blacks out pixels in a diagonal pattern, a few more each frame. With four colours there is no "slightly darker red".
- Screen shake moves the whole canvas with CSS.
- Blood is written into a buffer that is never cleared. Blood that stays is the point of the game, and it was also the cheapest thing to build.

### Letters were rationed too

The small font is 3×5 pixels and has exactly 40 characters: a space, digits, capitals, a dagger (†), a delete arrow and a full stop. There is no lower case and no apostrophe, so the game cannot say "DOESN'T". That is why the credits say "DOES NOT".

The title lettering is worse. L, U, N, A, C, R, E, T, and the tall A at the end. Nine letters, which can spell LUNA CRUENTA and nothing else.

<p><img src="docs/sprites/title-letters.png" width="520" alt="The nine title letters"></p>

The bright edge on those letters is not stored. A pixel is drawn bright only if the spot up and to the left of it is empty.

### The ending took several tries

The last scene is someone seen from behind, on a throne, looking out over a sea of blood. In the first version you could not tell what anything was. I asked for three ideas that would still read at this resolution and picked the silhouette. What is there now is one disc for the light, a few horizontal lines for the water, the tentacle function from the boss fight, and a black figure built out of ellipses and boxes. It uses no picture data at all.

There was a laugh as the figure sat down, too. It came out as a limp electronic bleep, so it went.

The credits could not be read where they crossed the white light, so each letter got a black outline. I would have liked a see-through panel behind them, but there are four colours.

The music is one sixteen-bar tune used three times: fast during play, at walking pace on the title, and slower still at the ending. The title and the ending are the same arrangement at different speeds. Every sound comes from one function, which is either an oscillator sliding between two pitches or noise through a filter.

The last line of the credits used to be "LONG LIVE THE QUEEN". It seemed truer that whoever ends up on the throne, blood is what remains, so it became "ONLY THE BLOOD REMAINS..".

### The title screen was 550 bytes of wanting too much

When the game was nearly done I wanted a proper title screen: a red moon, clouds, a dead tree, gothic letters. There were 50 bytes to spare and it cost 550.

As much as possible is drawn by code and not stored.

- The moon is two discs laid one pixel apart. The gap is its bright rim.
- The dark patches on the moon and the clouds come from one line of arithmetic each. Placing them by hand looked a little better and cost 48 bytes more, so that was dropped.
- The tree is a small function that draws one limb and then calls itself twice from the end of it. The shortest twigs end in a drip.

It still did not fit. The rest came from the next two sections.

### The packer cannot look sideways

As I understand it: Roadroller compresses by looking at the last few characters and guessing the next one. The better the guess, the cheaper that character is.

Write a sprite out column by column and the pixel **above** any pixel is the previous character. But the pixel **to the left** is one whole column back. The queen is 56 tall, so that is 56 characters back, and the packer cannot see that far (nine characters by default, about thirty at the very most). It had been packing every picture as if it were a strip one pixel wide.

Two things were changed.

1. Every picture is cut into strips 28 rows tall. The queen is two strips. Now the pixel to the left is always exactly 28 characters back.
2. The packer is told to look 28 back. The build tries out packer settings and keeps the combination that gives the smallest real file.

Measured on the same code:

| Packer settings | Bytes |
| --- | ---: |
| Roadroller defaults | 10,462 |
| The best Roadroller finds for itself | 10,255 |
| The settings from that search | **9,999** |

That is 256 bytes without removing a character of code, and nearly half the price of the title screen.

### Things that should have helped and made it bigger

All tried and measured.

- Storing each column as only what changed from the column before. The queen went from 626 bytes to 765.
- Storing runs of the same colour as a length. The best attempt was 634 against 630 for writing it out plainly.
- Two pixels to a character. 634 became 660.
- Hex for the small sprites and base 36 for the font. It was like that for a long time. Writing them out the dumb way, one digit a pixel, made the source about 600 characters longer and the file about 70 bytes smaller.

What looks short to a person and what the packer finds easy to guess turned out to be different things.

### What was taken out in the end

- The Korean and English toggle
- From the music: a solo section, an echo on the lead, an arpeggio
- Footprints in the blood
- A line on the death screen saying what percentage of the world you had painted, and the `%` character only that line used
- Joke lines in the final tally (QUEENS SLAIN 1, TEARS SHED 0 and the like)
- Hearts blinking before they disappear
- The viewport tag. Without it the game came out larger on a phone, so that one was not a loss.
- The doctype, `<title>`, `<html>`, `<head>` and `<body>`. A browser opens the page without them.

### At the end it was one byte at a time

By the end, putting anything in meant taking something out.

The one I remember best is the two full stops at the end of the credits. To print the dots in "ONLY THE BLOOD REMAINS.." the font needed a full-stop character, and with that the file was 10,001 bytes. One byte came from moving "TOUCH TO START" on the death screen six pixels down. Probably because that gave it the same coordinate as the same words on the title screen, the packer spent one byte less. That made exactly 10,000. One more run of the packer-settings search found another byte, and that is how the file got to 9,999.

The rules say "10 KB" and do not say whether that means 10,000 bytes or 10,240. I aimed for the smaller one.

### Why the music does not start by itself

After the title music went in I asked about three times whether it could play the moment the page opens. It cannot. Browsers block sound until the person has clicked or tapped once, and a page has no way round that.

So the game tries to play straight away, and if it was blocked, the first tap only turns the music on and the second starts the run. I wanted people to hear the title theme at least once on the way in.

### What is still wrong

- The "† USURPER †" message that appears when the Horror dies stays up until the last card arrives, and shows through behind it. The fix needs 3 bytes and there is 1 left.
- It has only been checked in Chromium browsers. Other browsers and a real iPhone have not been tried.
- Unpacking uses `eval`, so the file may not open somewhere with a strict security policy.
- The board and the "finished" flag are kept in the browser's `localStorage` as `pulpR` and `pulpW`. PULP was the game's first working title.

## Building it

You need [Node.js](https://nodejs.org).

```
npm install
npm run build
```

The tool versions are pinned, so the build comes out as the same 9,999 bytes every time.

| Command | What it does |
| --- | --- |
| `npm run build` | Writes `luna-cruenta.html`, plus the readable source and the debug build in `dist/` |
| `npm run search` | Runs 1,500 steps of the packer-settings search and keeps anything smaller. Worth running after changing the code |
| `npm run test-build` | Writes a test build to `dist/` in which the queen arrives at 6 points and the Horror at 26 |

Playing from the start every time I changed a boss or the ending was too tedious, which is why there is a debug build. Open `dist/luna-cruenta-debug.html`, start a run, and press a number key.

| Key |   |
| :---: | --- |
| `1` | The queen arrives, one hit from death |
| `2` | The Horror arrives, one hit from death |
| `3` | The ending starts now |
| `4` | During the credits: skip to their end |

## Folders

```
luna-cruenta.html            the entry. 9,999 bytes
index.html                   a redirect to it (for the GitHub Pages address)
README.md
package.json                 pins terser and roadroller
src/
  game.html                  the game, readable and commented
  music.js                   the music
  debug.js                   the debug keys (debug build only)
  art/
    sprites.js               seven 8x8 sprites and the 3x5 font
    queen.txt                the Crimson Queen
    horror.txt               the right half of the Horror
    title-letters.txt        the nine title letters
tools/
  build.js                   join the source -> shrink -> pack, and the packer-settings search
  data.js                    turns the pictures in src/art into the strings the game carries
  packer-settings.json       what the search found
dist/
  luna-cruenta-source.html   the whole game joined into one readable file
  luna-cruenta-debug.html    the same, with the debug keys
docs/                        the images on this page
```

The entry is not named `index.html` because the jam does not allow index files.

## Thanks

- [Roadroller](https://github.com/lifthrasiir/roadroller) by Kang Seonghoon. Without it this would not have fitted in 10KB.
- [terser](https://terser.org)
- Claude, which wrote the code with me
- The [10 Kilobytes Jam](https://itch.io/jam/10-kilobytes-jam-), for the excuse

</details>
