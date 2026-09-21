# 실습과제1
#### 사용자 홈디렉터리 안에 work 디렉터리를 만들고 다음과 같이 서브디렉터리 dir1, dir2, dir3를 만들고 각각 디렉터리 안에 다음과 같이 빈파일을 작성하시오. tree 명령어를 이용하면 파일목록을 트리구조로 출력해줌
<img width="1110" height="329" alt="image" src="https://github.com/user-attachments/assets/1515c642-dbe7-4039-b218-03a9701ff0d6" />

# 실습과제2
- #### 하나의 명령어를 이용하여 실습과제1에서만든 dir1 디렉터리의 파일을 아래처럼cpdir1 디렉터리로 복사하시오.
<img width="306" height="370" alt="image" src="https://github.com/user-attachments/assets/c18ea9cf-319b-475f-b767-c85ee01c1162" />

- #### cpdir2 디렉터리를 먼저 만들고 실습과제1에서 만든 dir2 디렉터리의 파일을 파일단위로 1개씩 복사하시오.
<img width="370" height="268" alt="image" src="https://github.com/user-attachments/assets/fd3dceae-a866-41fb-abb6-8ec8d4f8f693" />

- #### cpdir3 디렉터리를 먼저 만들고 실습과제1에서 만든 dir3 디렉터리의 파일을 경로확장기능을 사용하여 하나의 명령어로 복사하시오.
<img width="343" height="307" alt="image" src="https://github.com/user-attachments/assets/ce0ca7eb-6502-4989-93a1-30926671b653" />

# 실습과제3
- #### 실습과제 1에서 만든 dir1 디렉터리와 안에 있는 파일명을 그림처럼변경하시오.
<img width="341" height="98" alt="image" src="https://github.com/user-attachments/assets/cc9c7d74-2ed0-4a4f-958d-ee0bd909d643" />
<img width="156" height="87" alt="image" src="https://github.com/user-attachments/assets/28b8bed2-f794-4a5b-8870-fc673a0be6e1" />

- #### mvdir2 디렉터리를 생성하고 실습과제 1에서 만든 dir2 디렉터리 안에 있는 모든 파일을 그림처럼 이동하시오. dir2는 비어 있어야함
<img width="388" height="98" alt="image" src="https://github.com/user-attachments/assets/6eb3869a-3c91-4122-b71d-84cf9ed78e7f" />
<img width="163" height="155" alt="image" src="https://github.com/user-attachments/assets/31331355-e187-4987-a63d-601c351710cc" />

- #### mvdir3 디렉터리를 생성하고 실습과제 1에서 만든 dir3 디렉터리 안에 있는 모든 파일을 그림처럼 이동하고 파일명도 변경하시오. dir3는비어 있어야함
<img width="434" height="102" alt="image" src="https://github.com/user-attachments/assets/c40e2c89-0b62-4382-af62-b4c997c14d1f" />
<img width="156" height="263" alt="image" src="https://github.com/user-attachments/assets/97bcdc3e-1f22-4044-bbf8-db17aca2a6dd" />

# 실습과제4
- #### 하드링크와 심볼릭 링크의 차이를 설명하라.
|-|특징|
|-|------|
|하드링크|하나의 파일에 이름을 여러개 부여하는 것이다. 어는 것이 원본인지 구분할 수 없으며, 디렉토리에는 하드 링크를 적용할 수 없다.|
|심볼릭 링크|원본 파일에 대한 별명을 붙여주는 것이다. 어는 것이 원본인지 구분할 수 있다.|

- #### 심볼릭 링크를 확인하는 명령어를 설명하라
- ls에 -l, -f 옵션을 지정하면 심볼릭 링크 여부를 확인 할 수 있다.

- #### 실제로 심볼릭 링크를 만들고 확인한 결과를 첨부하라.
<img width="797" height="134" alt="image" src="https://github.com/user-attachments/assets/38fa8240-caf3-4a3a-9f0f-5542d77af6d4" />

- #### 빈파일과 빈디렉토리를 만든 후 파일속성(ls -l)을 출력하면 아래처럼 디렉터리는 하드링크의 수가 2이고 파일은 1이다. 이유를 설명하라
- 디렉토리는 본인 및 하위 디렉토리가 있을 때 부모 디렉토리를 역할을 할 . 과 ..으로 2개의 하드링크가 있다.
- 파일은 본인 자신 디렉토리를 나타내는 .의 하드링크 1개가 있다.
