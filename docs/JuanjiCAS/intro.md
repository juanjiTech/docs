---
sidebar_position: 1
---

# 介绍

JuanjiCAS是卷鸡推出的中央认证服务，为开发者提供了一个高效、安全、可靠的身份认证解决方案。CAS是“Central Authentication Service”的缩写，它是一个开源的认证协议，旨在为Web应用程序提供单点登录（SSO）功能。CAS具有以下功能和特性：

1. 单点登录（SSO）：CAS允许用户使用一组凭据登录一个Web应用程序，并且在同一会话中不需要再次输入凭据即可访问其他受保护的应用程序。
2. 集中式身份验证：CAS提供了一个中央认证服务器，该服务器负责处理身份验证请求和凭据存储。
3. 安全性：CAS使用加密技术和安全协议保护用户凭据的传输和存储。用户的凭据永远不会在网络上以明文传输。
4. 易于集成：CAS提供了基于标准协议的API，开发者可以使用这些API轻松地将CAS集成到他们的Web应用程序中。

使用JuanjiCAS的步骤如下：

1. 通过电子邮件或是兔小巢社区联系我们。
2. 在自己的Web应用程序中引入CAS客户端库。
3. 在应用程序中配置CAS客户端，包括CAS服务地址和应用程序的URL等。
4. 在需要进行身份认证的页面或应用程序中使用CAS客户端进行身份认证。
5. CAS验证用户的信息并使用户带上凭据重定向回应用程序。
6. 使用CAS客户端获取用户信息并授权访问相应的资源。

JuanjiCAS的使用方法简单且高效，可以帮助开发者快速实现Web应用程序的身份认证功能，从而节约开发成本。

> 目前 JuanjiCAS 支持 CAS 协议，正在完成 SAML 协议的支持。
