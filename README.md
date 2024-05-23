<p align = 'center'>
   <img src="https://koptimizer.github.io/IDALab.io/assets/img/IDAL_gray_1.png" width="500" height="500"><br>
   <b> http://idalab.ac.kr/ </b>
</p>

### IDAL 홈페이지 관리 핵심파일
- ```_config.yml```을 통해서 홈페이지 Title과 description, 메인 화면 텍스트를 변경할 수 있습니다.
- ```_includes/*.html``` 및 ```_layouts/default.html```  파일을 통해서 홈페이지 내부의 모든 내용을 변경할 수 있습니다.
- ```assets/css/main.css```를 통해서 요소들의 속성을 수정하고 정의해줄 수 있습니다.
- 모든 이미지는 ```assets/img/...```에 저장해서 사용해주세요.

### 온라인에서 작업하는 방법
- Github을 이용해서 해당 파일을 직접 수정하면 자동으로 commit 되어서 바로 적용됩니다.
- 실제 웹으로 적용되기까지 1~30분 가량의 시간이 걸리나 수정이 간편해서 간소한 수정에 용이합니다.

### 로컬PC에서 작업하는 방법
- 만약 첫 작업인 경우:
   - [해당 링크](https://rubyinstaller.org/downloads/)에서 Ruby+DevKit 2.x.x 버젼을 다운받습니다.
   - ruby를 설치하고, ruby prompt를 켭니다.
   - ```gem install jekyll bundler```을 실행하여 jekyll과 필요한 gem 파일을 설치합니다.
   - 만약 당신이 ruby 3.0을 다운받았다면...?
     - ```bundle install``` ->> ```bundle add webrick```을 하여 세팅합니다.
- ```$ git clone``` 혹은 ```$ git pull```을 통해 해당 레포지토리를 로컬 pc의 적절한 디렉토리로 끌어옵니다.
- Ruby prompt를 켜고 로컬 레포지토리로 이동한 후, ```jekyll serve```를 입력합니다.
- serve를 실행하면 localhost:4000에서 자신이 작업하는 홈페이지의 모습을 바로 확인할 수 있습니다.
- 모든 작업이 완료되었다면 ```commit -> push (-> pull reqeust)```을 해서 원격 레포지토리에 업로드하시면 됩니다.
- 실제 웹으로 적용되기 까지 1~30분 가량의 시간이 소요됩니다.

### 주의점
- 중요한 정보는 홈페이지에 연동 및 업로드 하지 말아주세요. (보안이 취약합니다.)
- 사진들 사이즈는 하드코딩 되어있습니다. 속성으로 조정하지 마시고 업로드 시 아래의 제약에 맞추는게 훨씬 편합니다.
  - About에 들어가는 사진 3개 : 600 * 400
  - 교수님 사진 : 340*453
  - 학생 사진 : 204*272
  - 활동 사진 : 400*400
