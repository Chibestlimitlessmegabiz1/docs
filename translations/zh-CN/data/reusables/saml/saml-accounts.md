If you configure SAML SSO, members of your organization will continue to sign into their personal accounts on {% data variables.product.prodname_dotcom_the_website %}. When a member accesses non-public resources within your organization, {% data variables.product.prodname_dotcom %} redirects the member to your IdP to authenticate. After successful authentication, your IdP redirects the member back to {% data variables.product.prodname_dotcom %}. 更多信息请参阅“[关于使用 SAML 单点登录进行身份验证](/enterprise-cloud@latest/authentication/authenticating-with-saml-single-sign-on/about-authentication-with-saml-single-sign-on)”。

{% note %}

**Note:** SAML SSO does not replace the normal sign-in process for {% data variables.product.prodname_dotcom %}. Unless you use {% data variables.product.prodname_emus %}, members will continue to sign into their personal accounts on {% data variables.product.prodname_dotcom_the_website %}, and each personal account will be linked to an external identity in your IdP.

{% endnote %}