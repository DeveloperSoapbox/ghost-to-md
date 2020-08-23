---
layout: post
author: [Developer]
draft: false
title: ${post.title}<% if (post.slug) { %>
slug: ${post.slug}<% } %>
date: ${post.publishedAt}
date_updated: ${post.updatedAt}<% if (post.tags.length) { %>
tags: [${post.tags.join(', ')}]<% }%>
---

${post.markdown}
