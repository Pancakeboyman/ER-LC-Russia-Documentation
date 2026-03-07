---
hidden: true
---

# ✨ ClueControl M V2

<h3 id="api" align="center"><strong>Аутентификация API</strong></h3>

Все запросы к API должны содержать валидный заголовок **Authentication**.

**Не знаете, где взять API ключ?**

Инструкция по получению API-ключа здесь: [documentation-api-v1](../documentation-api-v1/ "mention").

<h3 id="api" align="center"><strong>Справка по API</strong></h3>

Команда ER:LC Россия и подпроектов (в т.ч. Moscow RolePlay) **не оказывает поддержку** по написанию кода или интеграции API в сторонние решения.

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/status" method="get" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/shard_pings" method="get" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/guild_shard/{guild_id}" method="get" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/get_online_staff" method="get" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/get_mutual_guilds" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/approve_application" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/deny_application" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/notify_new_application" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/send_staff_request" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/send_priority_dm" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/send_priority" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/send_loa" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/accept_loa" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/deny_loa" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/send_application_wave" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/all_members/{guild_id}" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/send_logging" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/get_staff_guilds" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/check_staff_level" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/get_guild_settings" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/update_guild_settings" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/get_guild_roles" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/get_guild_channels" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/get_last_warnings" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/authorize_token" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/get_fivem" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/duty_on_actions" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/duty_off_actions" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/duty_break_actions" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/duty_end_break_actions" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/duty_voided_actions" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/duty_on" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/duty_off" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/guild/{guild_id}" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/issue_infraction" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/revoke_infraction" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/get_infraction_wave_preview" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/start_infraction_wave" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="cluecontrol-m-api" path="/v2/cluecontrol-m/search_guild_members" method="post" %}
[OpenAPI cluecontrol-m-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/568c03933bf1deb763403736172bbb54e785b4609832048d91522cff2fa73c1c.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260307%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260307T195612Z&X-Amz-Expires=172800&X-Amz-Signature=8f747faffa81b39f47ae2c56063d6ec19501176db648a043b1716f84c00225cf&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}
