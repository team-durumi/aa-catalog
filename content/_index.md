---
title: Introduction
type: docs
---

# AA-Catalog

## Introduction

탐색 / 검색과  같은 사용자 동선을 반영한 페이지를 구성해 1만건 미만의 스크립트 기반의 탐색 / 검색 퍼포먼스를 제공하는 오픈소스 디지털아카이브를 사용할 수 있는 프로젝트명칭입니다. AA는 아이템 / 탐색 / 검색 / 컬렉션 / 콘텐츠 / 전시 UI 영역을 세분화해 구성한 Design System 을 포함합니다.

사용자들에게 공개하는 모든 디지털아카이브가 수십만원대의 서버 인프라 비용을 내고, Java 혹은 PHP 개발언어로 모든 부분을 만들 필요는 없습니다. 수천만원대의 검색엔진 솔루션 비용과 데이터베이스 유지를 위한 유료 소프트웨어를 쓰지 않아도 됩니다. 자료를 공개적으로 아카이브하고자하는 조직과 프로젝트에 빠르게 제공할 수 있도록 구성했습니다.

## Concept
{{< columns >}}
### 정적 사이트 생성기(Static Site Generator)

- Open Source 기반의 SSG(Static Site Generator) | Hugo
- 데이터 구조가 잡혀 있는 사용자의 데이터 폴더를 공개형 디지털아카이브로 전환
- 정적 사이트로 생성된 디지털아카이브 결과물을 무료 서버 공개툴에 공개


<--->

### Data/Record

- Hugo Contents 폴더 Storage에 저장되어 있는 형태를 정적 사이트 생성기가 읽어 들일 수 있는 형태로 처리하는 방식
- 구글드라이브 / 드롭박스  / 아마존 S3 같은 클라우드 저장소에 정리된 폴더와 엑셀로 기록된 메타데이터를 Json, csv 형태로 읽어드려 구조화
- 솔루션 안에 저장공간이 포함되어 있는 것은 아님. 대용량의 자료 저장에 대한 관리는 사용자 스스로 관리

{{< /columns >}}

{{< columns >}}
### 디지털아카이브 웹 공개

- 가볍고, 서버자원을 많이 사용하지 않는 기반
- Serveless Infra를 활용 Netlify, Cloudflare Pages, Github에 직접 1G 미만의 자료 아카이브의 호스팅을 통해 무료로 공개가 가능
- 인프라관리 영역에 대한 책임을 대리하지 않음


<--->

### 디지털아카이브 운영유지

- 해당 프로젝트의 Git 이력 및 관련 이력
- 지속적으로 자료 업데이트에도 관련 솔루션 비용이 증가하지 않도록 운영유지
- G/A 등 사이트 유입 측정에 대한 도구 설치

{{< /columns >}}

## Q&A

- https://aa-catalog.durumi.io/docs/aa/#qa

## Development

### Github/team-durumi

- https://github.com/team-durumi
