# go-authcrunch

AuthCrunch provides Authentication, Authorization, and Accounting (AAA)
Security Functions (SF) in Golang.

<a href="https://github.com/tyrantlink/go-authcrunch/actions/" target="_blank"><img src="https://github.com/tyrantlink/go-authcrunch/workflows/build/badge.svg?branch=main"></a>
<a href="https://pkg.go.dev/github.com/tyrantlink/go-authcrunch" target="_blank"><img src="https://img.shields.io/badge/godoc-reference-blue.svg"></a>

This code base contains the functions implementing AAA. It is a
standalone library, i.e. it can be used with Gin, Beego, Echo,
Mux (Gorilla). Originally, the library was a part of the development
of Caddy v2 `caddy-auth-portal`, `caddy-auth-jwt`, and
`caddy-authorize` plugins.

## Documentation

Please browse to [authp.github.io](https://authp.github.io/).

## Issues

* Caddy-specific: [Open](https://github.com/greenpau/caddy-security/issues/new/choose)
* Other Go-frameworks: [Open](https://github.com/tyrantlink/go-authcrunch/issues/new/choose)

## Plugins

* Identity Stores:
  - [`go-authcrunch-ids-consul`](https://github.com/tyrantlink/go-authcrunch-ids-consul): Identity Store Plugin for Consul Key/Value (KV) Store Integration
  - [`go-authcrunch-ids-dynamodb`](https://github.com/tyrantlink/go-authcrunch-ids-dynamodb): Identity Store Plugin for Amazon DynamoDB Integration

* Credentials:
  - [`go-authcrunch-creds-aws-secrets-manager`](https://github.com/tyrantlink/go-authcrunch-creds-aws-secrets-manager): Credentials Plugin for AWS Secrets Manager Integration
  - [`go-authcrunch-creds-aws-ssm-parameter-store`](https://github.com/tyrantlink/go-authcrunch-creds-aws-ssm-parameter-store): Credentials Plugin for AWS SSM Parameter Store Integration
