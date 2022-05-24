---
title: 'MSSQL varchar와 nvarchar 차이'
excerpt: MSSQL
categories:
  - Database
tags:
  - - database
    - mssql
toc: true
toc_sticky: true
date: 2022-05-12
last_modified_at: 2022-05-12
published: false
---

# MSSQL varchar 와 nvarchar 차이

* varchar : 가변 문자열, 영문이나 숫자는 1byte로 저장하고 한글이나 한자는 2bytes로 저장.
* nvarchar : 가변 유니코드 문자열. 어떤 문자든 2bytes로 저장.다국어 지원 시 해당 데이터 타입 사용.
