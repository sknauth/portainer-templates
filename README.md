# portainer-templates

This repository hosts my personal templates (**'Apps Templates'**) definitions for Portainer.

To build and run the container:

```
git clone https://github.com/sknauth/portainer-templates.git
cd portainer-templates
# Edit the file templates.json
docker build -t portainer-templates .
docker run -d -p "8080:80" portainer-templates
```

Access the template definitions at http://docker-host:8080/templates.json
