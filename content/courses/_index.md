---
title: Courses
summary: My courses
type: landing

cascade:
  - target:
      path: '{/courses/*/**}'
    type: docs
    params:
      show_breadcrumb: true

sections:
  - block: markdown
    content:
      title: Courses
      text: |-
        These two graduate courses trace a single thread: how engineering data
        becomes trustworthy evidence, and how that evidence flows to the right
        person, in the right format, at the right time.

        Drawing on 20 years of AEC practice and ongoing research in semantic
        digital twins, both courses combine case-based instruction with a
        term-long capstone project — students leave with a governance
        architecture or integration plan they can defend, not just a grade.

        {{< cards >}}
          {{< card url="engineering-data-governance" title="Engineering Data Governance for Sustainable Strategy" subtitle="工程資料治理永續策略 · Fall · 3 Credits" icon="link" >}}
          {{< card url="smart-construction-flow-integration" title="Smart Construction Flow Integration Practice" subtitle="智慧營建流程整合實務 · Spring · 3 Credits" icon="cube-transparent" >}}
        {{< /cards >}}
---
