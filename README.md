# NAME

Plagger::Plugin::Filter::Lou - Filer text to Lou Style

# SYNOPSIS

    - module: Filter::Lou
      config:
        lou_rate: 95

# DESCRIPTION

This plugin filters entry body to Lou Ohshiba Style.

# CONFIG

Same as [Acme::Lou](https://metacpan.org/pod/Acme%3A%3ALou).

- lou\_rate 

    Set percentage of translating. 100 means full translating, 
    0 means do nothing. Default is 100.

- format

    This feature is of Acme::Lou v0.03. Default is `%s`.

        - module: Filter::Lou
          config:
            format: "<ruby><rb>%s</rb><rp>(</rp><rt>%s</rt><rp>)</rp></ruby>"

    See more information at [Acme::Lou](https://metacpan.org/pod/Acme%3A%3ALou).

# AUTHOR

Naoki Tomita

# SEE ALSO

[Plagger](https://metacpan.org/pod/Plagger), [Acme::Lou](https://metacpan.org/pod/Acme%3A%3ALou)
