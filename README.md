# Awesome JSON Web Token (JWT) [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

A curated list of awesome libraries and resources about JSON Web Token (JWT), a standard JSON structure, compact, URL-safe means of representing properties (claims) to be transferred between two parties.

## Contents

- [JWT Libraries](#jwt-libraries)
    - [C#](#c)
    - [Golang](#golang)
    - [Java](#java)
    - [JavaScript](#javascript)
    - [PHP](#php)
    - [Python](#python)
    - [Ruby](#ruby)
- [Resources](#resources)
    - [Specifications](#specifications)
    - [Draft Specifications](#draft-specifications)
    - [Websites](#websites)
- [JWT Alternatives](#jwt-alternatives)

---

## JWT Libraries

### C#

- [jose-jwt](https://github.com/dvsekhvalnov/jose-jwt) - Minimallistic zero-dependency library for generating, decoding and encryption JSON Web Tokens.

### Golang

- [go-jose/go-jose](https://github.com/go-jose/go-jose) - An implementation of JOSE standards (JWE, JWS, JWT) in Go forked from initially developed by Square.
- [golang-jwt/jwt](https://github.com/golang-jwt/jwt) - A popular and actively maintained go implementation of JSON Web Tokens.

### Java

- [com.auth0:java-jwt](https://github.com/auth0/java-jwt) - Java implementation of JSON Web Token (JWT) developed by Auth0.

### JavaScript

- [fast-jwt](https://github.com/nearform/fast-jwt) - JSON Web Token implementation used by Fastify official JWT plugin.
- [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken) - A JavaScript implementation of JSON Web Token maintained by Auth0.

### PHP

- [firebase/php-jwt](https://github.com/firebase/php-jwt) - A simple library to encode and decode JSON Web Tokens (JWT) in PHP maintained by Firebase team.
- [LexikJWTAuthenticationBundle](https://github.com/lexik/LexikJWTAuthenticationBundle) - Symfony bundle to handle JWT authentication.

### Python

- [PyJWT](https://github.com/jpadilla/pyjwt/) - JSON Web Token implementation in Python.

### Ruby

- [jwt](https://github.com/jwt/ruby-jwt) - A Ruby implementation of the JSON Web Token (JWT) standard.

## Resources

### Specifications

- [JSON Web Token (JWT)](https://datatracker.ietf.org/doc/html/rfc7519) - JWT specifications used for different tokens.
- [JSON Web Token (JWT) Profile for OAuth 2.0 Access Tokens](https://datatracker.ietf.org/doc/html/rfc9068) - JWT format and validation specifications in the context of OAuth 2.0.
- [JSON Web Key (JWK)](https://datatracker.ietf.org/doc/html/rfc7517) - JavaScript Object Notation (JSON) data structure that represents a cryptographic key. 
- [JSON Web Encryption (JWE)](https://datatracker.ietf.org/doc/html/rfc7516) - Specifications for JWE which represents encrypted content using JSON-based data structures.
- [JSON Web Signature (JWS)](https://datatracker.ietf.org/doc/html/rfc7515) - Specifications for JWS which represents content secured with digital signatures.

### Draft Specifications

- [Selective Disclosure for JWTs (SD-JWT)](https://datatracker.ietf.org/doc/draft-ietf-oauth-selective-disclosure-jwt/) - Specification for selective disclosure of JWT elements.

### Websites

- [jwt.io](https://jwt.io/) - Reference website crafted by Auth0 (Okta).
- [IANA JSON Web Token Claims Registry](https://www.iana.org/assignments/jwt/jwt.xhtml) - Registry listing all registered claims used in JWT.
- [JWT & JWE Debugger](https://www.authgear.com/tools/jwt-jwe-debugger) - In-browser, open-source JWT/JWE debugger, with examples, encryption and decryption

## JWT Alternatives

- [Biscuit](https://www.biscuitsec.org/) - An authorization token with decentralized verification, offline attenuation and strong security policy enforcement based on a logic language.
- [PASETO](https://paseto.io/) - Platform-Agnostic Security Tokens (PASETO) is a secure alternative to JWT that focuses on simplicity and security.

## Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/cerberauth/awesome-jwt/blob/master/CONTRIBUTING.md) first.
