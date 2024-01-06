---
title: Interactive API documentation
permalink: /docs/openapi/
---
The interactive documentation below demonstrates the functionality of the SWC Fantasy Football API. To download the OpenAPI Specification (OAD) file, use the "openapi.json" link below.

_Note: The "Try it out" functionality is not functional at this time, but please check back soon for this feature._

<style type="text/css" rel="stylesheet">
.swagger-ui pre {
    background-color: transparent;
    border: none;
}

</style>

<div id="swagger-ui" class="intrinsic-container"></div>
<script src="https://unpkg.com/swagger-ui-dist@5.10.0/swagger-ui-bundle.js" crossorigin></script>
<script>
  window.onload = () => {
    window.ui = SwaggerUIBundle({
      url: '/sample-dev-portal/openapi2.json',
      dom_id: '#swagger-ui',
    });
  };
</script>
