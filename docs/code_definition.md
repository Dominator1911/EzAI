---
title: Code Definition
layout: default
---

# Code Definition

**仕様コードはプロジェクトの中で共通です。**  
**開発を進める上では、IssueやPull Requestを仕様コードで管理することになります。**

| Code Header | Role     | Code Example     |
|-------------|----------|------------------|
| S           | System   | S-?-nnnn-version |
| A           | Admin    | A-?-nnnn-version |
| E           | Engineer | E-?-nnnn-version |
| U           | User     | U-?-nnnn-version |
| O           | Other    | O-?-nnnn-version |

| Func Header | Meaning        | Code Example     |
|-------------|----------------|------------------|
| F           | Functional     | S-F-nnnn-version |
| N           | Non Functional | S-N-nnnn-version |

| Scope      | Number Range |
|------------|--------------|
| Frontend   | 0000 ~ 1999  |
| Backend    | 2000 ~ 3999  |
| Trainer    | 4000 ~ 5999  |
| API Server | 6000 ~ 7999  |
| Other      | 8000 ~ 9999  |

# Code Example

S-F-0001-0.0.1 ... システムに関わるのver.0.0.1の機能要件の1番  
A-F-0010-1.1.2 ... 管理者に関わるver1.1.2の機能要件の10番  
E-N-0101-2.0.3 ... エンジニアに関わるver2.0.3の非機能要件の101番  

E-F-0001-0.0.0 ... Frontend要件  
E-F-2001-0.0.0 ... Backend要件  
E-F-4001-0.0.0 ... Trainer要件

# Project repository

[EzAI Frontend](https://github.com/Dominator1911/EzAI-Frontend)  
[EzAI Backend](https://github.com/Dominator1911/EzAI-Backend)  
[EzAI Trainer](https://github.com/Dominator1911/EzAI-Trainer)  
[EzAI API Server](https://github.com/Dominator1911/EzAI-API-Server)

# Links

[Index](index.md)
