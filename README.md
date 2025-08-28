# Knot, DNSTAP, Gigapipe and Grafana

Repository contains configuration files and documentation for setting up
a logging pipeline using Knot DNS, DNSTAP, Gigapipe, and Grafana.

## Setup

Clone the repository and launch logging services using _docker-compose_

```bash
docker-compose pull
docker-compose up -d
```

> [!IMPORTANT]
> At the moment I haven't built docker for **knot**, so you need to install
> **knot** locally.  **Will be fixed soon.**

### Install knot

Follow the instructions in the [Knot Installation Guide](https://www.knot-dns.cz/docs/3.4/html/installation.html#installation-from-a-package) to install **knot** on your system.

## Login to Grafana

Access the preconfigured Grafana instance as `admin/admin`

```shell
http://localhost:3000
```

## Documentation

- [Gigapipe Documentation](https://gigapipe.com/docs/oss.html)
- [Knot 3.4 Documentation](https://www.knot-dns.cz/docs/3.4/html/#)
- [DNSTAP](https://dnstap.info/)
- [DNSTAP Protocol Buffers](https://github.com/dnstap/dnstap.pb)
- [Loki Grafana Documentation](https://grafana.com/docs/loki/latest/query/)
