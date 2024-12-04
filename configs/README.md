### Home Assistant Related files

- `smtp.yaml` - this is in YAML format, but the directives inside this file should be appended to your `/homeassistant/configuration.yaml` file. There are some directives that will need to be updated. This SMTP config assumes a local SMTP server running on port 25 with no encryption.  I have a local SMTP relay at home that pipes the mail through an external relay.
