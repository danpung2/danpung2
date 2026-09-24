# Backend & Reliability

[English](#english) · [한국어](#한국어)

## English

I'm a developer interested in backend engineering and system reliability.

I enjoy understanding how systems behave in production and where they fail. I turn recurring problems into tools and build small versions of systems to explore how they work internally.

### Things I've built

#### StreamSheet

**A streaming SDK for large Excel exports**

I built StreamSheet to address memory issues and repetitive code when exporting large datasets to Excel. Using Kotlin and Apache POI SXSSF, I limited the number of rows held in memory, verified exports with hundreds of thousands of rows, and published the SDK to Maven Central.

#### LogPilot

**A lightweight event streaming broker for small deployments**

I built LogPilot to understand how events are stored and consumed. I implemented consumer offset tracking, replay, and batch ingestion in Java, then measured memory usage under load.

#### Flowly

**A workflow platform for experimenting with infrastructure automation and asynchronous AI processing**

Flowly is a personal project where I explore deployment automation and asynchronous AI processing by running them myself. I moved an AWS environment configured with Terraform and Ansible to a home server, added knowledge retrieval and task queues, and worked through connection leaks and race conditions.

### What I'm exploring now

I'm designing LLM-assisted test authoring alongside validation of the results. I'm interested in what evidence we need to trust the output of automation.

---

## 한국어

백엔드와 시스템 신뢰성에 관심을 두고 개발합니다.

시스템이 운영 환경에서 어떻게 동작하고 어디서 실패하는지 알아가는 과정을 좋아합니다. 반복되는 문제는 도구로 만들고, 내부 동작이 궁금한 시스템은 작은 규모로 직접 구현해 봅니다.

### 직접 만들어 본 것들

#### StreamSheet

**대용량 엑셀 내보내기를 위한 스트리밍 SDK**

대량 데이터를 엑셀로 내보낼 때 겪은 메모리 부족과 반복 구현을 줄이기 위해 만들었습니다. Kotlin과 Apache POI SXSSF로 메모리에 유지하는 행 수를 제한하고, 수십만 행 내보내기를 확인한 뒤 Maven Central에 배포했습니다.

#### LogPilot

**소규모 환경을 위한 경량 이벤트 스트리밍 브로커**

이벤트가 저장되고 소비되는 원리를 직접 이해하고 싶어 만들었습니다. Java로 소비 위치 관리와 재생, 배치 수신을 구현하고 부하에 따른 메모리 변화를 측정했습니다.

#### Flowly

**인프라 자동화와 비동기 AI 처리를 실험하는 워크플로우 플랫폼**

배포 자동화와 비동기 AI 처리를 직접 운영해 보는 개인 실험 프로젝트입니다. Terraform·Ansible로 구성한 AWS 환경을 홈서버로 옮기고, 지식 검색과 작업 큐를 붙이며 커넥션 누수와 레이스 컨디션을 다뤘습니다.

### 요즘 관심을 두는 것

LLM을 활용한 테스트 작성과 결과 검증을 함께 설계하고 있습니다. 자동화가 만든 결과를 어떤 근거로 신뢰할 수 있는지에 관심을 두고 있습니다.
