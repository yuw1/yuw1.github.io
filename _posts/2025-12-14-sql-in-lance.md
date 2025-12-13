---
layout: single
author_profile: true
title: "Lance 对 SQL 查询的支持现状"
date: 2025-12-14 10:00:00 +0800
categories: [技术]
tags: [Lance]
---
# Lance 对 SQL 查询的支持现状
## Lance 介绍
Lance 是一个基于 Apache Arrow 的列式存储格式，它的设计目标是之一是为了实现基于二级索引（indice）的点查。Lance 支持 SQL 查询，但是除了 LanceDB 企业版之外，其他的 SQL 查询方案都不支持使用二级索引（indice）
## 现状
### datafusion
datafusion 是一个基于 Apache Arrow 的 SQL 查询引擎。目前已经实现了对于 Lance 个数数据的 sql 查询，但是无法使用二级索引

### duckdb


### spark

