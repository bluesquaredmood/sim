# 수업용 시뮬레이터

- [KNN 설명 페이지](summary_knn.html)
- [KNN 시뮬레이터](bias.html)


# 잠깐, 자주 발생하는 문제

## README.md와 summary_knn.html 두 개를 올렸는데 README만 보입니다.
index.html이 없으면 GitHub Pages는 README.md를 대문 페이지로 대신 씁니다.
HTML이 사라진 게 아니라, 자기 주소에 그대로 있는데 대문이 README일 뿐입니다.
### 해결 A — 이름 바꾸기(권장)
저장소에서 파일 클릭 → 오른쪽 위 ⋯ → Rename → index.html → Commit. 1~2분 뒤 저장소 주소만으로 열립니다.
### 해결 B — README를 목차로 쓰기
시뮬레이터를 여러 개 올릴 계획이면 이쪽이 낫습니다. 

## 404가 뜹니다.
1~2분 더 기다리기. 또는 Public인지, Branch가 main인지 확인
## 수정했는데 그대로입니다.
브라우저 캐시. Ctrl+Shift+R (Mac은 Cmd+Shift+R)
## 한글이 깨집니다.
HTML 첫머리에 <meta charset="utf-8">이 있는지 확인
