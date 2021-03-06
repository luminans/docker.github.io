---
title: Enable layer 7 routing
description: Learn how to enable the layer 7 routing solution for UCP, that allows
  you to route traffic to swarm services.
keywords: routing, proxy
---

To enable support for layer 7 routing, also known as HTTP routing mesh,
log in to the UCP web UI as an administrator, navigate to the **Admin Settings**
page, and click the **Layer 7 Routing** option. Check the **Enable Layer 7 Routing** option.

![http routing mesh](../../images/interlock-install-3.png){: .with-border}

By default, the routing mesh service listens on port 8080 for HTTP and port
8443 for HTTPS. Change the ports if you already have services that are using
them.

Once you save, the layer 7 routing service can be used by your swarm services.
