# letsencrypt-localhost-route53-terraform

This is a Terraform module that creates a Let's Encrypt certificate for a domain that is hosted on Route53.

This module allows you to create a certbot user and policies to allow for certbot dns challenge to work with Route53.

This module also creates hosted zone records for the domain and subdomains that you specify.

It comes with a script that will create a certificate for the domain and subdomains that you specify.

All of its usage is explained in the companion blog post: [https://ilhicas.com/2023/02/17/Letsencrypt-localhost.html](https://ilhicas.com/2023/02/17/Letsencrypt-localhost.html)