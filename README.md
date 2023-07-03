# PLAIF

> If you want to proceed reading about `PLAIF Inc.` in english, please visit [the english version](/readme/english.md).

이 repository 는 `PLAIF(혹은 플라잎)` 에 대해 소개하는 자료가 보관된 repository 입니다. 이 repository 에는 다음 내용을 모두가 읽을 수 있게 문서화 합니다.

 1. `PLAIF` 회사 소개
 2. 회사 구성원 소개

## 플라이퍼 로서 소개하기

이 섹션을 읽고 있으시다면, `PLAIF` 새로 합류하신 분이 분명하군요. 함께 하게되어 영광입니다! 여러분이 어떤 사람인지 플라이퍼에게 알려주셨으면 좋겠습니다. 여러분에게 더 쉽게 다가갈 수 있게요. 다음은 어떻게 알릴 수 있는지에 대한 방법입니다.

### 1. 소개 페이지 작성하기

markdown 을 이용하여, 소개페이지를 작성해주세요. 어떤 직무를 하고 있는지, 어떤 툴을 사용하는지, 관심사는 무엇인지 자유롭게 작성해주세요. 막막하시다구요? 다음 [예시](/profile/software/members/jusung.md)를 참고해서 조금만 변경해서 그대로 작성해주셔도 전혀 무방하답니다 😊. 아 참, 어떻게 소개페이지를 작성하는지 설명하는 것을 깜빡했군요. 다음 과정을 따르세요!

1. 이 repository `clone` 하기(e.g. `git clone https://github.com/plaif-dev/.github.git`)
2. 소개 페이지를 추가할 `branch` 만들고 해당 branch로 이동하기(e.g. `git switch -c jusung/introduction`)
3. `/profile` 아래 해당하는 팀의 `members` 아래에 영어 이름으로 `markdown 파일 만들기` (e.g. `profile/software/members/jusung.md`)
   1. 해당 팀이 존재하지 않다면, 팀 이름의 directory 를 만들고, 다음과 같은 구조로 directory 를 구성하세요

```plaintext
팀 이름
├─ 팀 이름.md
└─ members/
    └─ 플라이퍼 이름.md
```

4. 자유롭게(!) 자신 소개하는 페이지 작성하기
5. 팀 페이지(e.g. `profile/software/software.md`) 에 상대 경로로 새로 작성한 페이지와 링크 연결하기

### 2. 소개 페이지 검토 받기

페이지를 모두 작성하셨나요? 거의 다왔습니다. 이제 소개페이지를 팀원들과 `double-check` 해봅시다. 혹시 오타가 있을 수도 있잖아요! 다음 방법을 따라서 검토해봅시다.(저희는 `github flow`를 따르고 있어요 😊.)

1. 소개페이지 커밋 하기(e.g. `git commit -m "📝docs(introduction): add intro for 누구누구"`)
2. 소개페이지 푸시 하기(e.g. `git push origin jusung/introduction`)
3. Pull Request 보내서 검토받기(e.g. [웹페이지에서 PR 보내기](https://github.com/PLAIF-dev/.github/compare))

```markdown
<!--참고 템플릿-->

## 설명

* 신규 입사자 readme page 추가

## 체크리스트

제출한 Pull Request가 다음 사항을 만족하는지 확인해주세요:

- [ ] 😊 커밋 메시지가 변경 내용을 충분히 설명하고 있습니다.
- [ ] 💯 오타가 있는지 확인하였습니다.

```

4. 혹시나 수정이 필요한 경우 수정후 `1~2 과정 반복`하기
5. 수정을 거쳐 구성원 모두로 부터 `approve` 받기

### 3. 소개 페이지 공유하기

소개 페이지를 모두 검토 받으셨나요? 그러면 `merge` 하여 모두가 볼 수 있게 해주세요. `approve`를 모두 받은 경우, Pull Request 하단에 Merge 라는 버튼이 초록색으로 활성화 되어있을거에요. 버튼을 눌러 main branch 에 merge 해주세요. 모두 합친 이후에는 작업했던 branch 를 삭제하는 것도 잊지 말자구요!
