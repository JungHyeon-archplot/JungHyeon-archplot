# GeoLog / 갤로그

GPS로 여정을 기록하고 경로·사진을 지도에서 다시 보는 팀 프로젝트입니다. 장정현은 Expo·React Native 기반 Android·Web 앱 구현에 참여했습니다.

[프로필로 돌아가기](../README.md)

## 담당한 구현 범위

- Expo Router를 활용한 로그인·프로필·기록·재생 화면
- 위치 권한과 GPS 포인트 수집, 정확도 필터와 기록 저장
- 지도 위 경로와 시간에 따른 재생
- 사진 선택·업로드와 여정 데이터 연결
- 친구·그룹 기능과 Supabase 계정·데이터 동기화
- Android와 Web의 지도 표시 방식 분리

## 사용 기술

| 영역 | 기술 |
| --- | --- |
| 언어·앱 | TypeScript, React Native, Expo, Expo Router |
| 디바이스 | Expo Location, Task Manager, 사진·미디어 API |
| 지도 | react-native-maps, Web 지도, WebView |
| 데이터 | Supabase Auth, PostgreSQL, Storage, SQL 마이그레이션 |
| 로컬 저장 | AsyncStorage |

## 협업 범위

기존 iOS Swift 앱을 참고해 Android·Web 구현을 진행했습니다. 기존 iOS 앱이나 별도 Express·MySQL 백엔드 전체를 개인 개발 성과로 포함하지 않습니다.

팀의 비공개 소스 프로젝트이며 공개 배포나 앱스토어 출시 완료를 주장하지 않습니다. 실제 이동 경로, 사진, 사용자 정보와 내부 접속 정보는 이 소개에 포함하지 않습니다.
