欢迎使用 IdentityServer4 (ASP.NET Core 3.x)
=============================================

.. image:: images/logo.png
   :align: center

IdentityServer4 是一套为 ASP.NET Core 实现 OpenID Connect 和 OAuth 2.0 的框架.

可为您的应用提供以下特性:


| **身份验证（Authentication） 服务** 
| 为您所有的应用(web, native, mobile, services) 集中管理登陆逻辑及流程. IdentityServer 是一套`官方认可 <https://openid.net/certification/>`的 OpenID Connect 实现.

| **单点登陆** 
| 为多个应用实现单点登陆.

| **API 访问控制** 
| 为多类终端提供访问令牌, e.g. server to server, web applications, SPAs and native/mobile apps.

| **联合网关**
| 支持外部身份认证，例如 Azure Active Directory, Google, Facebook 等. 您无须了解这些身份认证服务细节.

| **专注定制化**
| IdentityServer 是一套框架而不是一个打包好的产品或者Sas化的服务，因此您可以根据自己的需求，自行编码来适应您的应用场景.

| **Mature Open Source**
| IdentityServer 使用 `Apache 2 <https://www.apache.org/licenses/LICENSE-2.0>` 许可，允许您基于IdentityServer开发任何商业产品. 同时它也是 `.NET Foundation <https://dotnetfoundation.org/>` 的一部分，为您提供长久支持.

| **免费和商业支持**
| 如果您在搭建身份认证平台时遇到困难, :ref:`let us know <refSupport>`. 我们有多种方式为您提供帮助.

.. toctree::
   :maxdepth: 3
   :hidden:
   :caption: Introduction

   intro/big_picture
   intro/architecture
   intro/terminology
   intro/specs
   intro/packaging
   intro/support
   intro/test
   intro/contributing

.. toctree::
   :maxdepth: 3
   :hidden:
   :caption: Quickstarts

   quickstarts/0_overview
   quickstarts/1_client_credentials
   quickstarts/2_resource_owner_passwords
   quickstarts/3_interactive_login
   quickstarts/4_external_authentication
   quickstarts/5_hybrid_and_api_access
   quickstarts/6_javascript_client
   quickstarts/7_entity_framework
   quickstarts/8_aspnet_identity
   quickstarts/community

.. toctree::
   :maxdepth: 3
   :hidden:
   :caption: Configuration

   configuration/startup
   configuration/resources
   configuration/clients
   configuration/mvc
   configuration/apis

.. toctree::
   :maxdepth: 3
   :hidden:
   :caption: Topics

   topics/startup
   topics/resources
   topics/clients
   topics/signin
   topics/signin_external_providers
   topics/windows
   topics/signout
   topics/signout_external_providers
   topics/signout_federated
   topics/federation_gateway
   topics/consent
   topics/apis
   topics/deployment
   topics/logging
   topics/events
   topics/crypto
   topics/grant_types
   topics/secrets
   topics/extension_grants
   topics/resource_owner
   topics/refresh_tokens
   topics/reference_tokens
   topics/mtls
   topics/request_object
   topics/custom_token_request_validation
   topics/cors
   topics/discovery
   topics/add_apis
   topics/add_protocols
   topics/tools

.. toctree::
   :maxdepth: 3
   :hidden:
   :caption: Endpoints

   endpoints/discovery
   endpoints/authorize
   endpoints/token
   endpoints/userinfo
   endpoints/device_authorization
   endpoints/introspection
   endpoints/revocation
   endpoints/endsession

.. toctree::
   :maxdepth: 3
   :hidden:
   :caption: Reference

   reference/identity_resource
   reference/api_resource
   reference/client
   reference/grant_validation_result
   reference/profileservice
   reference/interactionservice
   reference/deviceflow_interactionservice
   reference/options
   reference/ef
   reference/aspnet_identity

.. toctree::
   :maxdepth: 3
   :hidden:
   :caption: Misc

   misc/training
   misc/blogs
   misc/videos
