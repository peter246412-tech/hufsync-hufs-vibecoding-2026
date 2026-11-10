# 근거 및 참고자료

기획안에 사용한 연구와 공식 자료를 정리했습니다. 문서 정리일은 **2026-11-11**이며, 원문·초록·공식 공지 등 확인 범위를 구분했습니다.

## 1. 한국외대 학교 현황

[한국외국어대학교 Facts & Figures](https://stat.hufs.ac.kr/hufs/11142/subview.do)

공식 페이지의 2025-04-01 기준 자료를 확인했습니다.

| 동일 범위의 지표 | 수치 |
| --- | --- |
| 서울캠퍼스 학부 재학생 | 9,823명 |
| 서울캠퍼스 외국인 학부 학위과정 학생 | 2,108명 |
| 위 두 수치로 계산한 비율 | 약 21.5% |

이는 `2,108 ÷ 9,823 × 100`으로 계산한 값입니다. 학위·연수·어학과정을 합산한 비율과 구분하며, 다른 대학과의 순위를 주장하는 자료로 사용하지 않습니다.

## 2. 상호문화 팀 프로젝트 연구

서윤경·김수영(2026). 「내⋅외국인 대학생의 상호문화 팀 프로젝트 기반 학습에서 나타나는 참여 구조 탐색－‘포용적 배제’와 교수자 지원 방향－」. 『사고와표현』, 19(2), 299–334.

[KCI 서지·초록](https://www.kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART003372009) · [DOI](https://doi.org/10.19042/kstc.2026.19.2.299)

확인 범위는 KCI 서지와 초록입니다. 한국인 25명·외국인 유학생 19명의 성찰일지를 분석한 질적 연구로, 언어 장벽과 공유된 협업 이해 부족, 배려에 따른 참여 제한 등을 다룹니다. 외대 학생 전체의 발생 비율이나 HUFSync의 효과를 입증한 자료로 해석하지 않습니다.

## 3. 그룹 채팅 AI 조정 연구

Do, H. J., Kong, H.-K., Lee, J., & Bailey, B. P. (2022). *How Should the Agent Communicate to the Group? Communication Strategies of a Conversational Agent in Group Chat Discussions.* Proceedings of the ACM on Human-Computer Interaction, 6(CSCW2), Article 387, 1–23.

[DOI](https://doi.org/10.1145/3555112) · [저자 공개 원문](https://jaewook-lee.com/files/papers/CSCW2022_CA_Communication.pdf)

원문을 확인했습니다. 185명·42개 그룹을 대상으로 의사소통 방식을 비교했습니다. 비공개 개인 지원과 공개 그룹 방식의 설계 시사점을 참고하되, 비공개 개인 방식이 모든 지표에서 모든 방식보다 우월했다고 일반화하지 않습니다.

초기 기획의 연구 설명을 점검하며 다음을 구분했습니다.

- 실제 그룹 과제는 30분이며, 메시지 수·고유 단어 수를 6분마다 확인해 개입 대상을 판단했습니다.
- RQI와 품질 가중 지니계수는 연구자의 사후 평가에 사용됐습니다.
- 실시간 개입 대상 판단과 사후 효과 평가를 같은 처리로 설명하지 않습니다.

논문 PDF 자체는 저장소에 재배포하지 않고 원문 링크로 연결합니다.

## 4. 기존 협업 서비스

[Slack: Guide to AI features in Slack](https://slack.com/intl/en-gb/help/articles/27918234552979-Tips-for-working-with-AI-in-Slack)

공식 안내에서 대화 요약·번역·개인 메시지 설명 기능을 확인했습니다. 번역·요약 자체를 HUFSync의 최초 기능으로 주장하는 대신, 다국어 대학 팀플의 논의와 업무 이해를 연결하는 사용 흐름을 검토했습니다.

## 5. 대회 공식 공지

[2026 한국외대 AI 캠퍼스: 바이브코딩 경진대회](https://contest.hufs.ac.kr/)

대회 취지, 서류·발표 평가 항목, 본선 개발 기간 11.16~12.06을 확인했습니다. 공식 일정과 평가 기준은 변경될 수 있으므로 실제 참가 시 최신 공지를 확인하는 자료로 연결합니다. 저장소는 기획·설계 포트폴리오이며, 공식 주최기관의 서비스나 결과 발표 페이지가 아닙니다.

## 6. 기획서에서 인용한 기사

송주하(2026.08.09). 「유학생 25만 시대… 강의실은 준비됐나」. 대학알리(외대알리).

[기사 원문](https://www.univalli.com/news/article.html?no=25966)

제공된 기획서의 참고문헌에 포함된 자료입니다. 이번 정리에서는 원문에 재접근하지 못했으므로 기획서의 인용 자료로 구분해 남겼습니다. 세부 인터뷰 문구를 새로 직접 인용하지 않았습니다.

## 7. 검토한 기술 문서

- [NAVER Cloud CLOVA Studio Structured Outputs](https://api.ncloud-docs.com/docs/clovastudio-chatcompletionsv3-so): 안건·업무 추출 결과를 구조화하는 방식의 검토 자료.
- [Supabase Realtime](https://supabase.com/docs/guides/realtime): 채팅·상태 동기화 검토 자료.
- [Supabase Row Level Security](https://supabase.com/docs/guides/database/postgres/row-level-security): 팀 공유·개인 데이터의 접근 권한 검토 자료.
- [Next.js on Vercel](https://vercel.com/docs/frameworks/full-stack/nextjs): 웹앱 배포 검토 자료.

문서의 기능 안내가 HUFSync에 해당 기술이 이미 구현되거나 검증됐다는 의미는 아닙니다. 실제 API·모델·권한 정책은 개발 단계에서 확정하고 테스트할 계획입니다.

[기획안](proposal.md) · [설계 변화](design-evolution.md) · [프로젝트 소개](../README.md)
