# Frame Extractor

**Frame Extractor**는 **동영상을 프레임으로 추출하는 응용프로그램**입니다.

> This application is ⓒ 2022. 비타소프트 Co. All Rights Reserved.
>
> This application use OpenCV Software along with applicable license information, below.
>
> OpenCV  
> url: https://opencv.org  
> license: https://github.com/opencv/opencv/blob/4.4.0/LICENSE
>
> If you have any questions or concerns, please contact us at `help@vitasoft.co.kr`

## 실행환경

- **Windows 10** 기준으로 동작합니다.
- **JDK 1.8 버전 혹은 11 버전**이 설치되어 있어야 합니다.
    - https://www.oracle.com/java/technologies/downloads/

## 사용방법

1. extractor.zip 파일을 압축해제합니다.
    - 압축파일 안에 있는 **vita_extractor.exe**과 **opencv_java3415.dll** 파일이 같은 위치에 있어야 합니다.

![압축 해제 파일](https://user-images.githubusercontent.com/69888508/149287428-03d85e1e-7227-48f8-b873-ff32c5fc5928.png)


2. **vita_extractor.exe**를 실행하면 Console 창에 경로를 입력하라는 문구가 나옵니다.
    - 나오지 않는다면 준비과정을 확인하세요.

![첫 시작 화면](https://user-images.githubusercontent.com/69888508/149287472-c4a2dbcf-aa12-4152-ab2f-22a71fa6094b.png)

3. 동영상 파일을 Console 창에 Drag & Drop 하거나 경로를 직접 입력하세요.

![경로 입력](https://user-images.githubusercontent.com/69888508/149287486-f8e083b6-67a6-4841-8322-a294dbfbf13e.png)

4. 경로를 입력하면 프레임 추출이 시작됩니다.
    - 프레임이 추출되지 않는다면 동영상 경로를 확인해주세요.(에러 문구 확인)
    - 동영상 경로에도 문제가 없다면 해당 동영상은 프레임으로 추출할 수 없습니다.

![프레임 추출 과정](https://user-images.githubusercontent.com/69888508/149287490-7a45a689-ea7d-4e16-8e05-bc509f37c31a.png)

5. 추출이 완료되면 추출된 경로를 확인할 수 있습니다.

![추출 완료](https://user-images.githubusercontent.com/69888508/149287676-7b895ddb-ddef-4fae-9c57-c6aa5b8f5394.png)

6. 해당 경로의 images 폴더에서 추출된 프레임을 확인할 수 있습니다.

![추출된 프레임](https://user-images.githubusercontent.com/69888508/149288108-304ff36c-098b-4a39-a6bc-a92063e6ce56.png)


## ※주의사항※

이미 폴더가 만들어져 있으면 **해당 폴더는 삭제되고 새로 생성**됩니다.  
프로그램을 실행하기 전에 불필요한 삭제가 일어나지 않도록 폴더를 확인해주세요.
