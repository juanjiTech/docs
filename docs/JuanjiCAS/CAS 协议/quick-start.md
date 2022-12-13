# 快速开始

下面将简单介绍 CAS 登录流程与登出流程

## 登录流程

1. 服务提供方（Service Provicer，下文简称SP）发现用户未登录，发起登录流程，用户从 SP 站点跳转至 CAS 进行登录。
2. CAS 认证客户身份完成后重定向回 SP 地址。
3. SP 收到 CAS 提供的 Ticket 信息，联系 CAS 验证 Ticket 信息，验证成功且成功获取用户信息则用户成功在 SP 登录。

## 登出流程

1. 用户在 SP 发起登出请求，SP 将用户状态改为登出，并且让用户跳转至 CAS 登出地址进行登出。
2. CAS 成功将用户登出，并跳转回 SP。

## 接入CAS

JuanjiCAS 目前支持 CAS 2.0 协议中的 [`/serviceValidate` 接口](https://apereo.github.io/cas/6.6.x/protocol/CAS-Protocol-V2-Specification.html#25-servicevalidate-cas-20)，卷鸡目前提供 [Golang 版本的 SDK](https://github.com/juanjiTech/juanjiCAS-Go-SDK) 便于您接入 JuanjiCAS。

未完待续······
