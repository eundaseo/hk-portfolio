# eunda works

한국경제 AI 교육 포트폴리오. 파우더블루, 로즈핑크, 아이보리, 브라운을 활용한 빈티지 스크랩북 콘셉트입니다. 작품을 골라 보는 컬렉션 탐색 방식을 유지합니다.

전체 페이지에는 CookieRun 웹폰트 Regular(400), Bold(700), Black(900)을 적용했습니다.

## 페이지

- `dist/index.html`: 홈, 컬렉션 안내
- `dist/artcle.html`: 기사 (요청한 파일명 그대로)
- `dist/image.html`: 이미지 갤러리, 카테고리 필터
- `dist/video.html`: 영상 기획안
- `dist/final.html`: Final Project 소개
- `dist/style.css`: 공통 디자인과 반응형 스타일
- `dist/app.js`: 임시 프로젝트 데이터, 페이지 구성, 상세 창, 관심 작품 저장

## 콘텐츠 교체

각 페이지는 독립적인 HTML 진입점을 가지며, 공통 app.js의 items 배열에서 내용을 관리합니다. title(제목), desc(요약), body(본문), image(이미지 경로)를 수정하세요. 새 이미지 파일은 dist/assets에 넣고 경로를 연결합니다. 현재 세 이미지 카드는 같은 생성 이미지의 크롭 스터디입니다.

영상은 아직 실제 영상이 없는 임시 스토리보드입니다. 실제 자료로 교체할 때 영상 파일을 assets에 넣고 video 요소를 연결하거나 영상 서비스 링크를 사용하세요. 현재 파일 업로드 관리자, 로그인, 서버 저장 기능은 없습니다. 파일을 수정한 후 다시 배포하는 정적 웹사이트입니다.

My picks는 현재 브라우저의 localStorage에 저장됩니다. 다른 브라우저나 기기와 동기화되지 않습니다. 임시 기사, 영상 기획, Final Project 내용은 실제 교육 과제나 성과로 오해하지 않도록 예시 표시를 포함합니다.

## 이미지

dist/assets/eunda-daydream.png는 built-in image_gen으로 생성했습니다.

Prompt: Vintage dreamy pastel editorial still life of floating pearlescent glass five-point stars and spheres over a powder blue/rose horizon. Nostalgic 1990s editorial mood, analog paper texture, film grain, pastel mint/ivory/peach refractions, restrained glow and silver sparkles. No typography, logos, UI, watermark, or shopping bag.

## 검증

HTML 진입점과 로컬 파일 경로, JavaScript 구문을 확인했습니다. 브라우저 시각 검증은 수행하지 않았습니다. WebMCP는 지원되는 환경에서만 활성화되며, 현재 환경에서 실제 등록/실행 검증은 하지 못했습니다.
