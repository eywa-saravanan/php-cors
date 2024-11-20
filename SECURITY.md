# Security Policy

## Supported Versions

Use this section to tell people about which versions of your project are
currently being supported with security updates.

| Version | Supported          |
| ------- | ------------------ |
| 5.1.x   | :white_check_mark: |
| 5.0.x   | :x:                |
| 4.0.x   | :white_check_mark: |
| < 4.0   | :x:                |

## Reporting a Vulnerability

Use this section to tell people how to report a vulnerability.

Tell them where to go, how often they can expect to get an update on a
reported vulnerability, what to expect if the vulnerability is accepted or
declined, etc.

Hi,

we face security issue.. need for solution..

issue detail given below

package name : fruitcake/php-cors

Package link : https://github.com/fruitcake/php-cors

issue description : 

line numbers :
a) vendor/fruitcake/php-cors/src/CorsService.php:208

1) An attacker can exploit a permissive Access-Control-Allow-Origin setting to gain access to sensitive information by making cross-origin requests from any website. This can lead to unauthorized data exposure and potential breaches.

solution need like this : It is recommended to configure the Access-Control-Allow-Origin header to include only specific, trusted origins that need access. Avoid using a wildcard '*' and instead validate and allow origins based on a whitelist of approved domains. 


thanks
