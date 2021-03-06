---
title: Productos de GitHub
intro: 'Un resumen de los productos de {% data variables.product.prodname_dotcom %} y de los planes de precios.'
redirect_from:
  - /articles/github-s-products
  - /articles/githubs-products
  - /github/getting-started-with-github/githubs-products
versions:
  free-pro-team: '*'
  enterprise-server: '*'
  github-ae: '*'
topics:
  - Accounts
  - CLI
  - Mobile
  - Desktop
  - Security
---

### Acerca de los productos de {% data variables.product.prodname_dotcom %}

{% data variables.product.prodname_dotcom %} ofrece productos gratuitos y pagos. Puedes ver los precios y una lista completa de las funciones de cada producto en <{% data variables.product.pricing_url %}>. {% data reusables.products.product-roadmap %}

### {% data variables.product.prodname_free_user %} for user accounts

Con {% data variables.product.prodname_free_team %} para cuentas de usuario, puedes trabajar con colaboradores ilimitados en repositorios públicos ilimitados con un juego completo de características, y en repositorios privados ilimitados con un conjunto limitado de características.

Con {% data variables.product.prodname_free_user %}, tu cuenta de usuario incluye:
- {% data variables.product.prodname_gcf %}
- {% data variables.product.prodname_dependabot_alerts %}
- Aplicación de la autenticación de dos factores
- 2,000 minutos de {% data variables.product.prodname_actions %}
- 500MB de almacenamiento de {% data variables.product.prodname_registry %}

### {% data variables.product.prodname_pro %}

Adicionalmente a las características disponibles con {% data variables.product.prodname_free_user %} para cuentas de usuario, {% data variables.product.prodname_pro %} incluye:
- {% data variables.contact.github_support %} por correo electrónico
- 3,000 minutos de {% data variables.product.prodname_actions %}
- 2GB de almacenamiento de {% data variables.product.prodname_registry %}
- Herramientas y perspectivas avanzadas en repositorios privados:
  - Revisores requeridos para solicitudes de extracción
  - Revisores múltiples para solicitudes de extracción
  - Referencias auto-vinculadas
  - {% data variables.product.prodname_pages %}
  - Wikis
  - Ramas protegidas
  - Propietarios del código
  - Gráficos de información del repositorio: pulso, contribuyentes, tráfico, confirmaciones, frecuencia de código, red y bifurcaciones

### {% data variables.product.prodname_free_team %} para organizaciones

Con {% data variables.product.prodname_free_team %} para organizaciones, puedes trabajar con colaboradores ilimitados en repositorios públicos ilimitados con un juego completo de características, o en repositorios privados ilimitados con un conjunto limitado de características.

Adicionalmente a las características disponibles con {% data variables.product.prodname_free_user %} para cuentas de usuario, {% data variables.product.prodname_free_team %} para organizaciones incluye:
- {% data variables.product.prodname_gcf %}
- Debates de equipo
- Controles de acceso del equipo para administrar grupos
- 2,000 minutos de {% data variables.product.prodname_actions %}
- 500MB de almacenamiento de {% data variables.product.prodname_registry %}

### {% data variables.product.prodname_team %}

Adicionalmente a las características disponibles con {% data variables.product.prodname_free_team %} para organizaciones, {% data variables.product.prodname_team %} incluye:
- {% data variables.contact.github_support %} por correo electrónico
- 3,000 minutos de {% data variables.product.prodname_actions %}
- 2GB de almacenamiento de {% data variables.product.prodname_registry %}
- Herramientas y perspectivas avanzadas en repositorios privados:
  - Revisores requeridos para solicitudes de extracción
  - Revisores múltiples para solicitudes de extracción
  - {% data variables.product.prodname_pages %}
  - Wikis
  - Ramas protegidas
  - Propietarios del código
  - Gráficos de información del repositorio: pulso, contribuyentes, tráfico, confirmaciones, frecuencia de código, red y bifurcaciones
  - Solicitudes de extracción en borrador
  - Revisores de equipo para solicitudes de extracción
  - Recordatorios programados

{% data reusables.github-actions.actions-billing %}

### {% data variables.product.prodname_enterprise %}

{% data variables.product.prodname_enterprise %} incluye dos opciones de despliegue: hospedado en la nuba y auto-hospedado.

Adicionalmente a las características disponibles con {% data variables.product.prodname_team %}, {% data variables.product.prodname_enterprise %} incluye:
- {% data variables.contact.enterprise_support %}
- Controles de seguridad, cumplimiento e implementación adicionales
- Autenticación con inicio de sesión único SAML
- Provisión de acceso con SAML o SCIM
- {% data variables.product.prodname_github_connect %}{% if currentVersion == "free-pro-team@latest" or currentVersion == "github-ae@latest" or currentVersion ver_gt "enterprise-server@2.22" %}
- La opción para comprar {% data variables.product.prodname_GH_advanced_security %}. Para obtener más información, consulta la sección "[Acerca del {% data variables.product.prodname_GH_advanced_security %}](/github/getting-started-with-github/about-github-advanced-security)". {% endif %}

{% data variables.product.prodname_ghe_cloud %} también incluye lo siguiente:
- {% data variables.contact.enterprise_support %}. Para obtener más información, consulta "<a href="/articles/github-enterprise-cloud-support" class="dotcom-only">{% data variables.product.prodname_ghe_cloud %} soporte</a>" y "<a href="/articles/github-enterprise-cloud-addendum" class="dotcom-only">{% data variables.product.prodname_ghe_cloud %} Adenda</a>."
- 50,000 minutos de {% data variables.product.prodname_actions %}
- 50GB de almacenamiento de {% data variables.product.prodname_registry %}
- Control de acceso para los sitios de {% data variables.product.prodname_pages %}. Para obtener más información, consulta la sección "<a href="/pages/getting-started-with-github-pages/changing-the-visibility-of-your-github-pages-site" class="dotcom-only">Cambiar la visibilidad de tu sitio de {% data variables.product.prodname_pages %}</a>"
- Un acuerdo de nivel de servicio del 99.9% de tiempo activo mensual
- La opción de administrar de forma centralizada las políticas y la facturación de múltiples organizaciones {% data variables.product.prodname_dotcom_the_website %} con una cuenta de empresa. Para obtener más información, consulta la sección "<a href="/articles/about-enterprise-accounts" class="dotcom-only">Acerca de las cuentas empresariales</a>."

Puedes configurar una prueba para evaluar {% data variables.product.prodname_ghe_cloud %}. Para obtener más información, consulta "<a href="/articles/setting-up-a-trial-of-github-enterprise-cloud" class="dotcom-only">Configurar una prueba de {% data variables.product.prodname_ghe_cloud %}</a>".

Para obtener más información acerca de hospedar tu propia instancia de [{% data variables.product.prodname_ghe_server %}](https://enterprise.github.com), contacta a {% data variables.contact.contact_enterprise_sales %}. {% data reusables.enterprise_installation.request-a-trial %}
