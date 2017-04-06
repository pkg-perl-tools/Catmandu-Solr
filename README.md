# NAME

Catmandu::Solr - Catmandu modules for working with solr endpoints

# SYNOPSIS

    # From the command line

    # Import data into Solr
    $ catmandu import JSON to Solr  < data.json

    # Export data from ElasticSearch
    $ catmandu export Solr to JSON > data.json

    # Export only one record
    $ catmandu export Solr --id 1234

    # Export using an Solr query
    $ catmandu export Solr --query "name:Recruitment OR name:college"

    # Export using a CQL query (needs a CQL mapping)
    $ catmandu export Solr --q "name any college"

# AUTHOR

Nicolas Steenlant, `nicolas.steenlant at ugent.be`

Patrick Hochstenbach, `patrick.hochstenbach at ugent.be`

Nicolas Franck, `nicolas.franck at ugent.be`

# SYNOPSIS

For documentation on these fixes see:

[Catmandu::Store::Solr](https://metacpan.org/pod/Catmandu::Store::Solr)

[Catmandu::Importer::Solr](https://metacpan.org/pod/Catmandu::Importer::Solr)

# SEE ALSO

[Catmandu::Store](https://metacpan.org/pod/Catmandu::Store)

[Catmandu](https://metacpan.org/pod/Catmandu)

# LICENSE AND COPYRIGHT

This program is free software; you can redistribute it and/or modify it
under the terms of either: the GNU General Public License as published
by the Free Software Foundation; or the Artistic License.

See [http://dev.perl.org/licenses/](http://dev.perl.org/licenses/) for more information.
