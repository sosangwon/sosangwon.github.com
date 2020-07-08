---
layout: default
title: Setup jekyll
nav_order: 2
# has_children: true
parent: Etc
---

# Setup jekyll
{: .no_toc }

---

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

---

## Goals
* Seting up jekyll
* Apply to theme simply

---

## Summary
It's very simple. 
1. Modify `_config.yml` file
2. Make directory & files

Base theme is [just the docs](https://pmarsceill.github.io/just-the-docs/)

---

## Action

Assume that repository is ready.

1. Installation 
    - Change `_config.yml`
        ```yml
        remote_theme: pmarsceill/just-the-docs
        ```
2. Adding directory & Setup
    > https://pmarsceill.github.io/just-the-docs/docs/navigation-structure/
    1. Make directory 
    2. Set up directory 
        - Make `index.md` file in 1. and make up directory structure using below parameters.
            - has_children, parent, grand_parent

    3. Change title at top-left
        ```yml
        title: "Sosangwon"
        ```

> reference `_config.yml` 
>  - https://github.com/pmarsceill/just-the-docs/blob/master/_config.yml

## Gathering info 

### Theme

Use below
- [just the docs](https://pmarsceill.github.io/just-the-docs/)


### Unralated info
Markdown explaination
- https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax

Writing structure
- Education
  - https://www.monash.edu/rlo/assignment-samples/education/education-reflective-writing/reflective-writing-structure
- Engineering
  - https://www.monash.edu/rlo/assignment-samples/engineering/eng-writing-technical-reports



### Installation
- `_config.yml` 파일 설정만 하면됨.
- `just the dosc` repository의 theme를 그대로 사용하기 때문에 local에 따로 환경을 구성할 필요가 없음. Install 없음.  


test testtest  
testtest
띄어쓰기 테스트 테스트  
한줄띄고 여긴 carriage return 
없다


다음 세팅은 필요함. 
- https://pmarsceill.github.io/just-the-docs/#quick-start-use-as-a-github-pages-remote-theme


굳이 local환경을 구성하고자 한다면 다음 link에서 확인
- https://pmarsceill.github.io/just-the-docs/#local-installation-use-the-gem-based-theme


### page 구조 
https://pmarsceill.github.io/just-the-docs/docs/navigation-structure/#pages-with-children







