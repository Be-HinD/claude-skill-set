# dev-skill-kit (EN)

A repository for creating and curating skills for LLM agent environments, managed at the framework level — separate from individual projects.

## Structure

```
dev-skill-kit/
├── back/v1/          # Java backend skills
└── workflow/         # Workflow commands (git, etc.)
```

## Versioning

Each domain folder (`back`, `workflow`, etc.) contains versioned subdirectories (`v1`, `v2`, ...).

| Rule | Description |
|------|-------------|
| New version | When the structure, format, or assumptions of existing skills change significantly |
| Same version | Content improvements, bug fixes, or adding new skills |
| No backward compatibility | Compatibility between versions is not guaranteed — each project explicitly selects a version |

> A version is a **unit of consistency**, not a quality indicator. Skills within the same version follow the same format and design principles.

## Skills

### back/v1

| Skill | Description |
|-------|-------------|
| `api-contract-review` | Audit REST API design |
| `architecture-review` | Analyze project architecture |
| `clean-code` | Apply Clean Code principles and refactor |
| `concurrency-review` | Review concurrent code |
| `design-patterns` | Apply design patterns |
| `java-code-review` | Java code review |
| `jpa-patterns` | JPA/Hibernate patterns and anti-patterns |
| `logging-patterns` | Logging best practices |

### workflow/git

| Command | Description |
|---------|-------------|
| `commit` | Write commit messages |
| `create-pr` | Create pull requests |

## License

This repository is licensed under the [MIT License](LICENSE).
For externally sourced skills, see [CREDITS.md](CREDITS.md).

---

# dev-skill-kit (KR)

LLM 에이전트 환경에서 사용할 스킬을 생성·큐레이션하고, 프로젝트와 분리된 프레임워크 레벨로 관리하기 위한 저장소입니다.

## 구조

```
dev-skill-kit/
├── back/v1/          # Java 백엔드 스킬
└── workflow/         # 워크플로우 커맨드 (git 등)
```

## 버저닝

각 도메인 폴더(`back`, `workflow` 등)는 하위에 버전 디렉토리(`v1`, `v2`, ...)를 가집니다.

| 규칙 | 설명 |
|------|------|
| 새 버전 생성 | 기존 스킬의 구조·포맷·전제가 크게 달라질 때 |
| 같은 버전 유지 | 내용 보완, 오류 수정, 스킬 추가 |
| 하위 호환 없음 | 버전 간 호환을 보장하지 않으며, 프로젝트마다 사용할 버전을 명시적으로 선택 |

> 버전은 스킬 품질 기준이 아니라 **일관성 단위**입니다. 같은 버전 내 스킬들은 동일한 포맷과 설계 원칙을 따릅니다.

## 스킬 목록

### back/v1

| 스킬 | 설명 |
|------|------|
| `api-contract-review` | REST API 설계 감사 |
| `architecture-review` | 프로젝트 아키텍처 분석 |
| `clean-code` | Clean Code 원칙 적용 및 리팩토링 |
| `concurrency-review` | 동시성 코드 검토 |
| `design-patterns` | 디자인 패턴 적용 |
| `java-code-review` | Java 코드 리뷰 |
| `jpa-patterns` | JPA/Hibernate 패턴 및 안티패턴 |
| `logging-patterns` | 로깅 모범 사례 |

### workflow/git

| 커맨드 | 설명 |
|--------|------|
| `commit` | 커밋 메시지 작성 |
| `create-pr` | PR 생성 |

## 라이선스

이 저장소는 [MIT License](LICENSE) 하에 배포됩니다.
외부 출처 스킬은 [CREDITS.md](CREDITS.md)를 참고하세요.
