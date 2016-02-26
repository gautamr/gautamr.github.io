---
published: false
title: JWT token generation in Spring
layout: post
---
org.springframework.security.oauth2.provider.token.store.JwtAccessTokenConverter

String token = JwtHelper.encode(content, signer).getEncoded();