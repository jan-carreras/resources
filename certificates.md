# Certificates

## Certificate generation for local dev environment

* [mkcert](https://github.com/FiloSottile/mkcert)

## Manually creating certificates

* [Classic Guide on Certificate creation, step by step](https://www.golinuxcloud.com/openssl-create-client-server-certificate/)
* [Same as above](https://docs.apigee.com/how-to-guides/converting-certificates-to-supported-format)


## Traefik specific

* [Oficial docs on mTLS](https://doc.traefik.io/traefik/https/tls/#client-authentication-mtls)
* [mTLS check in 5 minutes](https://github.com/vahempio/PKI-Traefik-mTLS)

# Certificate extensions

### RSA Public Key

```
-----BEGIN RSA PUBLIC KEY-----
-----END RSA PUBLIC KEY-----
```

### Encrypted Private Key

```
-----BEGIN RSA PRIVATE KEY-----
Proc-Type: 4,ENCRYPTED
-----END RSA PRIVATE KEY-----
```

### CRL

```
-----BEGIN X509 CRL-----
-----END X509 CRL-----
```

### CRT

```
-----BEGIN CERTIFICATE-----
-----END CERTIFICATE-----
```


### CSR

```
-----BEGIN CERTIFICATE REQUEST-----
-----END CERTIFICATE REQUEST-----
```

### NEW CSR

```
-----BEGIN NEW CERTIFICATE REQUEST-----
-----END NEW CERTIFICATE REQUEST-----
```

### PEM

```
-----END RSA PRIVATE KEY-----
-----BEGIN RSA PRIVATE KEY-----
```

### PKCS7

```
-----BEGIN PKCS7-----
-----END PKCS7-----
```


### PRIVATE KEY

```
-----BEGIN PRIVATE KEY-----
-----END PRIVATE KEY-----
```

### DSA KEY

```
-----BEGIN DSA PRIVATE KEY-----
-----END DSA PRIVATE KEY-----
```

### Elliptic Curve

```
-----BEGIN EC PRIVATE KEY-----
-----BEGIN EC PRIVATE KEY-----
```

## PGP Private Key

-----BEGIN PGP PRIVATE KEY BLOCK-----
-----END PGP PRIVATE KEY BLOCK-----

## PGP Public Key

-----BEGIN PGP PUBLIC KEY BLOCK-----
-----END PGP PUBLIC KEY BLOCK-----
