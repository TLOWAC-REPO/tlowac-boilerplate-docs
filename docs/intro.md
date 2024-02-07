---
sidebar_position: 1
---

# Boilerplate Guide

`Frontend` | `Backend` | `Chrome Extension` 보일러 프로젝트 초기 구성 가이드 입니다.

:::warning
현재 해당 페이지의 내용은 개발 작업중인 상황이기 때문에 실질적인 사용이 불가능 합니다.
:::


## Getting Started

필요한 개발 스펙에 맞춰 boilerplate 를 선정했다면, CLI 또는 [tlowac-boilerplate (Github)](https://github.com/TLOWAC-REPO/tlowac-boilerplate) 를 통해 프로젝트를 다운 받을 수 있습니다.


### What you'll need
프로젝트 시작전 아래의 환경 셋팅을 진행해야 합니다.

- v18 버전 이상의 [Node.js](https://nodejs.org/en/download/) 설치가 필요 합니다.
- 패키지 매니저로 [pnpm](https://pnpm.io/installation) 설치가 필요 합니다.

## Boilerplate List

### 1) FrontEnd
| Boilerplate        | Tech Stack   |
| ------------------ | ------------ |
| `react-recoil-mui` | ex) react.js |
| `next-recoil-mui`  | ex) react.js |


### 2) Backend
| Boilerplate       | Tech Stack  |
| ----------------- | ----------- |
| `nest-prisma-api` | ex) nest.js |
| `nest-prisma-gql` | ex) nest.js |

### 3) Chrome Extension
| Boilerplate              | Tech Stack     |
| ------------------------ | -------------- |
| `extension-with-storage` | ex) typescript |
| `extension-with-api`     | ex) typescript |


## Generate a new boilerplate

`create-tlowac` 의 cli prompt 를 사용해 프로젝트를 구성하거나

`git clone <boilerplate_url>` 를 통해 프로젝트 구성 할 수 있습니다.


### 1) Using `create-tlowac` cli prompt

총 3개의 과정을 통해 생성하고자 하는 boilerplate 를 선택하고 생성합니다.

- `1단계` : 프로젝트 이름 작성
- `2단계` : 생성하고자 하는 프로젝트의 종류 선택 ( ex: Frontend / Backend / Chrome Extension )
- `3단계` : 생성하고자 하는 boilerplate 선택 ( ex: nest-prisma-api / nest-prisma-gql ) 

:::info

CLI 프롬프트인 `create-tlowac` 는 작업중에 있습니다.  
현재 해당 명령어는 동작하지 않기 때문에 `git clone` 을 활용한 boilerplate 구성 방식을 권장 합니다.

:::

```bash
❯ npm create tlowac@latest
Need to install the following packages:
create-tlowac
Ok to proceed? (y) y
✔ Project name: … my-app
? Select a boilerplate type: › - Use arrow-keys. Return to submit.
        Frontend
    ❯   Backend
        Chrome Extension
        Monorepo
? Select a boilerplate: › - Use arrow-keys. Return to submit.
    ❯   nest-prisma-api
        nest-prisma-gql
```


### 2) `git clone <boilerplate_url>`

:::info

boilerplate 는 현재 별도의 Github Repo 에서 작업되고 있습니다. ( [링크](https://github.com/TLOWAC-REPO/tlowac-boilerplate) )

:::

```bash
git clone <boilerplate_url>
```