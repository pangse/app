# app - App
> Business Application
> version: 0.0.2
> version: 0.0.3
ci/cd test modify Readme.md 
생성 실패후 실패한 인스턴스 삭제하엿으나. ci/cd 툴에서는 릴리즈가 오류나고 있다. 
하지만 인스턴스 생성은 성공이라 했으니..별다른 변경없이 git버젼만 변경해본다. 
> version: 0.0.4
간단한 소스 수정 과 인스턴스 삭제후 다시 진행에서는 인스턴스 생성이 정상적이지만 ci/cd 툴에서는 계속 릴리즈 오류가 발생하고 있다.
인스턴스를 모두 삭제한후 다시 시도한다.
> version: 0.0.5 (성공)
브라우져 오류로 인하여 403에러가 발생하기도 한다. 모든 인스턴스를 지우고 브라우져캐쉬 또는 스크릿 모드로 확인해야 한다.

> version : 0.0.5
NASA-api key 등록

> version : 0.0.7 Commit ce25b9a
transport management 설정
.pipeline/config.xml > tmsUpload: true 

> version: 0.0.8 Commit 47b110d
mta.yaml 소스 추가. 
- npx rimraf gen/db/src/gen/data
- npx rimraf gen/db/src/gen/csv

> version: 0.0.9 
slack alert설정이후 확인 버젼

> version: 0.0.10
test 