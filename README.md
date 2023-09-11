## Chalimpyo
* **[안내] 식단표 조회가 불가능한 현상은 스킨의 문제가 아닙니다.**
    * **NEIS 4세대 개편 이후 학교 측에서 확정한 식단표 정보만 조회가 가능하게 변경되었습니다.** 타 학교의 경우 정상적으로 식단표 조회가 가능하며 식단표 공개를 거듭 요청했으나 여전히 문제가 해결되지 않고 있습니다.
    * 또한 NEIS 역시 서버 불안정, 오류 등의 문제가 반복되는 상황이기에 당분간 스킨의 정상적인 동작은 어려울 것으로 보입니다. 제물포고등학교 학생회 인스타그램 혹은 교실 내 게시된 식단표 정보를 확인하시기 바랍니다.

**Chalimpyo**는 제물포고등학교의 식단 정보를 바탕 화면에 표시하는 [Rainmeter](https://www.rainmeter.net) 스킨입니다.

## 실행 모습
![1](https://github.com/bunubbv/chalimpyo/assets/75381985/53e265f2-83ce-4245-a4ac-99029c0bd376)

스킨이 로드되면 당일 식단표 정보가 표시됩니다.

![2](https://github.com/bunubbv/chalimpyo/assets/75381985/8684cfad-846f-4ecd-9e8c-9edd4e92a0b1)

마우스를 올리면 스킨의 최신 버전 여부를 확인할 수 있습니다.

## 라이선스
Chalimpyo는 GNU Lesser General Public License v2.1 라이선스로 배포됩니다. 자세한 내용은 [LICENSE](/LICENSE)를 참조하세요.

## 업데이트
* 과거 내역은 별도로 기록하지 않았습니다.
* 2023-05-08 1.6.0
    * 자동 업데이트 기능 추가, 정규표현식 버그 수정
* 2023-05-11 1.6.1
    * 업데이트 과정 중 생성되는 다운로드 폴더 삭제
* 2023-05-12 1.6.2
    * 업데이트 스크립트를 인라인으로 실행하여 속도 향상, 업데이트 이후 무한 루프 발생하는 버그 수정
    * 폰트 기본 탑재 및 설치 후 스킨이 자동으로 로드되지 않는 버그 수정
* 2023-05-16 1.6.3
    * 정규표현식 버그 수정
* 2023-08-13 2.0.0
    * 스킨 리팩토링 (코드 최적화)
    * 업데이트 구조 변경으로 안정성 향상
        * 파일 다운로드 구조 변경
        * 파일 무결성 검증 진행
        * 호환성 문제로 요구 버전 윈도우 10으로 상향
        * 오류 방지를 위해 다시 시작 시 업데이트 반영
    * 스킨 디자인 및 폰트 변경
    * 스킨 로드 시 레이아웃 및 설정 자동 적용
    * 오픈 소스로 스킨 배포
    * 정규표현식 버그 수정
* 2023-08-28 2.1.0
    * 코드 리팩토링, 최적화 진행
        * Windows 10 1909 이전 버전에서 업데이트 시 오류가 발생하는 문제 해결
        * 업데이트를 Lua가 아닌 내부에서 처리하게 변경
        * 불필요한 함수, 변수 정리 및 이름 변경
        * 그 외 스킨 구조 개선, 최적화 진행
    * 가독성을 위해 고정폭 폰트(Pretendard GOV)로 변경
    * 말풍선을 통해 버전 정보 표시
    * 정규표현식 버그 수정
    * 깃허브 링크 변경
* 2023-08-30 2.1.1
    * 일부 정규표현식 수정으로 가독성 향상
    * Windows 10 1904에서 업데이트 중 파일이 손상되는 문제 해결
    * 업데이트 이후 스킨을 자동으로 다시 로드
    * 업데이트 코드를 분리하여 스킨 안정성 향상
* 2023-08-30 2.1.2
    * 정규표현식 버그 수정
* 2023-09-02 2.1.3
    * 업데이트 실패 시 관련 말풍선이 안 뜨는 버그 수정
    * 인터넷 연결 실패 후 60초 뒤 자동으로 다시 로드

## 그 외
* Rainmeter는 HiDPI를 지원하지 않아 시인성 문제가 발생할 수 있습니다. 이를 해결하려면 Rainmeter 폴더(Program Files/Rainmeter)에서 "Rainmeter.exe"를 우클릭한 후, "속성", "호환성", "높은 DPI 설정 변경"에서 "높은 DPI 조정 동작을 재정의합니다."를 활성화하세요.