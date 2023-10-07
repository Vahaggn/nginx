# Nginx Module Support Matrix

This README provides an overview of module support in different versions of Nginx.

## Core Modules

| Module               | nginx-core | nginx-full | nginx-light | nginx-extras |
|----------------------|------------|------------|-------------|-------------|
| Core                 | ✔️         | ✔️         | ✔️          | ✔️          |
| Access               | ✔️         | ✔️         | ✔️          | ✔️          |
| Auth Basic           | ✔️         | ✔️         | ✔️          | ✔️          |
| Auto Index           | ✔️         | ✔️         | ✔️          | ✔️          |
| Browser              | ✔️         | ✔️         |             | ✔️          |
| Empty GIF            | ✔️         | ✔️         | ✔️          | ✔️          |
| FastCGI              | ✔️         | ✔️         | ✔️          | ✔️          |
| Geo                  | ✔️         | ✔️         |             | ✔️          |
| Limit Connections    | ✔️         | ✔️         |             | ✔️          |
| Limit Requests       | ✔️         | ✔️         |             | ✔️          |
| Map                  | ✔️         | ✔️         | ✔️          | ✔️          |
| Memcached            | ✔️         | ✔️         |             | ✔️          |
| Proxy                | ✔️         | ✔️         | ✔️          | ✔️          |
| Referer              | ✔️         | ✔️         |             | ✔️          |
| Rewrite              | ✔️         | ✔️         | ✔️          | ✔️          |
| SCGI                 | ✔️         | ✔️         | ✔️          | ✔️          |
| Split Clients        | ✔️         | ✔️         |             | ✔️          |
| UWSGI                | ✔️         | ✔️         | ✔️          | ✔️          |

## Optional Modules

| Module               | nginx-core | nginx-full | nginx-light | nginx-extras |
|----------------------|------------|------------|-------------|-------------|
| Addition             | ✔️         | ✔️         |             | ✔️          |
| Auth Request         | ✔️         | ✔️         | ✔️          | ✔️          |
| Charset              | ✔️         | ✔️         | ✔️          | ✔️          |
| WebDAV               | ✔️         | ✔️         | ✔️          | ✔️          |
| FLV                  |            |            |             | ✔️          |
| GeoIP                | ✔️         | ✔️         |             | ✔️          |
| Gunzip               | ✔️         | ✔️         |             | ✔️          |
| Gzip                 | ✔️         | ✔️         | ✔️          | ✔️          |
| Gzip Precompression  | ✔️         | ✔️         | ✔️          | ✔️          |
| Headers              | ✔️         | ✔️         | ✔️          | ✔️          |
| HTTP/2               | ✔️         | ✔️         | ✔️          | ✔️          |
| Image Filter         | ✔️         | ✔️         |             | ✔️          |
| Index                | ✔️         | ✔️         | ✔️          | ✔️          |
| Log                  | ✔️         | ✔️         | ✔️          | ✔️          |
| MP4                  |            |            |             | ✔️          |
| Embedded Perl        |            |            |             | ✔️          |
| Random Index         |            |            |             | ✔️          |
| Real IP              | ✔️         | ✔️         | ✔️          | ✔️          |
| Slice                | ✔️         | ✔️         | ✔️          | ✔️          |
| Secure Link          |            |            |             | ✔️          |
| SSI                  | ✔️         | ✔️         | ✔️          | ✔️          |
| SSL                  | ✔️         | ✔️         | ✔️          | ✔️          |
| SSL Preread          | ✔️         | ✔️         |             | ✔️          |
| Stub Status          | ✔️         | ✔️         | ✔️          | ✔️          |
| Substitution         | ✔️         | ✔️         |             | ✔️          |
| Thread Pool          | ✔️         | ✔️         | ✔️          | ✔️          |
| Upstream             | ✔️         | ✔️         | ✔️          | ✔️          |
| User ID              | ✔️         | ✔️         |             | ✔️          |
| XSLT                 | ✔️         | ✔️         |             | ✔️          |

## Mail Modules

| Module               | nginx-core | nginx-full | nginx-light | nginx-extras |
|----------------------|------------|------------|-------------|-------------|
| Mail Core            | ✔️         | ✔️         |             | ✔️          |
| Auth HTTP            | ✔️         | ✔️         |             | ✔️          |
| Proxy                | ✔️         | ✔️         |             | ✔️          |
| SSL                  | ✔️         | ✔️         |             | ✔️          |
| IMAP                 | ✔️         | ✔️         |             | ✔️          |
| POP3                 | ✔️         | ✔️         |             | ✔️          |
| SMTP                 | ✔️         | ✔️         |             | ✔️          |

## Stream Modules

| Module               | nginx-core | nginx-full | nginx-light | nginx-extras |
|----------------------|------------|------------|-------------|-------------|
| Stream Core          | ✔️         | ✔️         |             | ✔️          |
| GeoIP                | ✔️         | ✔️         |             | ✔️          |
| GeoIP2               |            | ✔️         |             | ✔️          |

## Third-party Modules

| Module               | nginx-core | nginx-full | nginx-light | nginx-extras |
|----------------------|------------|------------|-------------|-------------|
| Auth PAM             |            | ✔️         |             | ✔️          |
| Cache Purge          |            |            |             | ✔️          |
| DAV Ext              |            | ✔️         |             | ✔️          |
| Echo                 |            | ✔️         | ✔️          | ✔️          |
| Fancy Index          |            |            |             | ✔️          |
| GeoIP2               |            | ✔️         |             | ✔️          |
| Headers More         |            |            |             | ✔️          |
| Embedded Lua         |            |            |             | ✔️          |
| HTTP Substitutions   |            | ✔️         |             | ✔️          |
| Nchan                |            |            |             | ✔️          |
| Upload Progress      |            |            |             | ✔️          |
| Upstream Fair Queue  |            | ✔️         |             | ✔️          |
